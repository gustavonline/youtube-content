# Adding video content

The public repository holds finished companion material. Prepare unreleased work in a private workspace, including any draft based on _templates/video/. Gustav's private Resources repository has a content/youtube-drafts/ area for this work.

Use one short folder name per video:

```text
videos/topic-name/
  README.md
  LESSON.md
  SCRIPT.md      # optional approved talk track
  code/          # optional runnable example
  resources/     # optional prompts, diagrams, or other useful files
```

Start with the lesson. Explain the problem, show one example, and give the reader a useful next step. The README should help someone decide whether this material is for them and where to begin.

Use SCRIPT.md when a separate spoken version helps. It should follow the lesson's meaning and be written in natural English. Production notes and unreleased scripts stay private. Slides belong in resources/slides/ when they help explain an idea.

You can ask an agent: "Prepare the companion material for a video about [topic]. Draft one clear lesson and its README. Add a script, slides, prompts, or code only where they help. Keep it private until the video and materials are ready together."

YouTube content stands on its own. Resources is the more detailed, guided learning path, with its own free and paid access choices. Link related material where it helps; do not keep two independently edited copies of the same lesson.

There is no required length. A short explanation does not need a sample application, slide deck, or empty folders.

If the lesson has runnable code, include the working directory, setup, run and verification commands, the expected result, and any costs or credentials needed. Use synthetic example data. Verify current product claims against official sources.

Before release, check the finished video and companion together. Match the explanation, examples, title, and links to what the video actually shows. Replace all template placeholders. Obtain the user's applicable publication instruction.

Then copy only the finished public files into videos/topic-name/, add one link to the root README, inspect the staged files, and run git diff --check. Do not publish the private preparation history.

Later corrections should update the affected lesson and verification notes. Keep old video links working where possible.
