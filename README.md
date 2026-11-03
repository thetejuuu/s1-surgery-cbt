# S1 Surgery CBT — Full source archive edition

## Contents
- **125 playable MCQs** in `questions.json` (answerable questions with keyed options and explanations).
- **17 theory/essay prompts** in `theory.json`.
- **Full PQ archive** in `source-archive.json`: extracted text from all four uploaded compilations, including incomplete, repeated, unclear and OCR-affected entries. The app's **Full PQ archive** tab lets you search the extracted source text and filter by compilation.
- `source-compilation-transcription.md`: longer audit/transcription record.
- `question-bank-review.md`: notes on source quality, duplicates and exclusions.

## Important distinction
The 125 MCQs are the playable, keyed subset; they are not a claim that every fragment in the source documents can be fairly scored. Incomplete recollections, missing options and corrupted PDF layouts are preserved in the archive rather than silently converted into invented questions or answers. PDF text extraction may not preserve original two-column reading order. Compare with the original PDF page when exact layout or wording matters.

## Deploy
Upload all files in this folder to the root of the existing `s1-surgery-cbt` GitHub repository, replacing files with the same names. Add `source-archive.json`. Commit the changes; Vercel should redeploy if the repository integration is active.

Progress is stored in browser local storage. Keep the same deployed origin to retain existing progress. Export progress from the app before moving to a different hostname.
