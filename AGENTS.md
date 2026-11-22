# Repository notes

This repository contains companion material for Gustav Anderson's YouTube videos.

## Where content lives

- Lessons are written in the Notion [YouTube lessons](https://www.notion.so/4206d2e17f5681fcb39de978b54b8752) database (data source `4206d2e1-7f56-81af-ab85-000b1d1c37ff`). It has one row per video: Title, Slug, Status (Idea, Script, Recording, Editing, Published), Video URL, Related resource, Production, Publish date, Tags, and Summary. The page body holds the script and notes.
- Write and change lesson text in Notion, not here. Scripts, production notes, and drafts stay in Notion.
- After a video is published and its materials have been reviewed together with it, copy only the selected viewer files to `videos/<slug>/`, using the row's Slug. Then set the row's Repo folder to that folder's URL and add the video to the list in README.md.

## Writing the viewer files

- Write for the person watching or reading. Keep explanations clear and useful without requiring the video.
- Keep each video's README short and put the main explanation in LESSON.md.
- Include slides, prompts or code only where they help the reader.
- Preserve working video links and verify claims and runnable examples.
- Keep changes focused. Check Markdown links and run `git diff --check`.
