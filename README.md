# S1 Surgery CBT — Full bank + immediate seniors' paper

## What's in this update
- **206 MCQ records** in `questions.json`: 125 from the previous bank plus 81 individually extracted from `S1 R2 2025.pdf`.
- **163 keyed MCQs** and **43 unkeyed source questions**. Unkeyed questions remain visible but are excluded from scoring.
- **17 theory prompts** in `theory.json`, including all six theory questions from the immediate seniors' paper.
- **Full PQ archive** in `source-archive.json`, preserving extracted text from all four source compilations.
- The original immediate seniors' PDF is included at `source-pdfs/S1 R2 2025.pdf`.
- `S1-R2-2025-extraction-notes.md` documents exactly what was extracted and what cannot be scored reliably.

## Practise the immediate seniors' paper only
Open Practice → Question type → **Immediate seniors’ R2 2025 — 81 extracted MCQs**. Choose **All available** to attempt the entire extracted set, or 10/20/50/100 for shorter sessions. Unkeyed questions can be answered for self-practice, but they are not graded because the source does not support a reliable answer key.

## Source fidelity and answer keys
The original paper does not provide an answer key. Any key or explanation added for practice is labelled in the question record as independently added. Missing options and unclear wording are not silently reconstructed. Repeated questions are retained as separate source entries. Consult the included PDF when the extracted text is uncertain.

## Deploy to your existing GitHub/Vercel app
1. Unzip this package.
2. Upload **all files and folders inside the ZIP** to the root of your existing `s1-surgery-cbt` GitHub repository, replacing files with the same names. Do not upload only `questions.json`; the app code and service worker are updated too.
3. Commit the changes. If GitHub is connected to the existing Vercel project, it should redeploy automatically.
4. Open the same deployed URL. The service-worker cache is versioned `s1-cbt-v6`.

Keep the same deployed origin to preserve local progress. Export progress from the app before clearing browser/site data.
