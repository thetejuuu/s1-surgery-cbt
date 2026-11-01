# S1 Surgery CBT — starter app

Phone-first Progressive Web App for S1 surgery MCQ practice.

## Included
- Topic-based and mixed practice
- 10, 20, 50, 100, or all available questions
- Study mode with instant explanation; exam mode with marking at submission
- Incorrect-answer review and bookmarks
- Topic performance snapshot
- Local browser storage and progress export
- Installable PWA shell with offline caching after first load

## Question-bank limitation
This is a **24-question starter bank**, not a complete verbatim transcription of the four supplied past-question documents. Most items are adapted and labelled. The app shows source labels and status per question. The remaining source documents still need full transcription, deduplication, and answer-key verification before this can be called a complete past-question bank. Supplementary content is labelled as such.

## Run locally
Serve this folder over HTTP (service workers do not work from `file://`):

```bash
python -m http.server 8000
```

Open `http://localhost:8000`.

## Deploy to Vercel
1. Create a GitHub repository, e.g. `s1-surgery-cbt`.
2. Upload the contents of this folder to the repository root.
3. In Vercel, choose **Add New → Project**, import the repository, and deploy.
4. Framework preset: **Other**; build command blank; output directory `.`.
5. Open the HTTPS deployment in Android Chrome and choose **Install app** / **Add to Home screen**.

## Persistence
Attempts, bookmarks and session history are stored in localStorage on this browser/device. They do not sync between devices. Export progress before clearing browser data.

## Editing questions
Edit `questions.json`. `answer` is zero-based (A=0, B=1, C=2, D=3). Keep source metadata accurate. Increment the cache name in `sw.js` after updates.
