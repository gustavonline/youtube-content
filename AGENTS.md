# YouTube content

This repository contains public companion material for Gustav Anderson's videos. Read README.md and CONTRIBUTING.md before changing it.

## Make one lesson useful

- Each video companion answers one question or helps the viewer do one thing.
- Write in plain English unless Gustav asks for another language.
- README.md is the short entry point; LESSON.md is the main explanation.
- An optional SCRIPT.md adapts the lesson for spoken delivery. Optional slides live in resources/slides/. Recording and editing are outside this repository's responsibility.
- Add code/ or resources/ only when there is useful material for them.
- Use _templates/video/ as a starting point. No custom CLI or task runner is required.
- Keep video links and claims tied to actual, reviewed files and videos. Never invent URLs, test results, personal stories, or publication status.

## Keep preparation private

- Public branches, pull requests, and Git history are public too.
- Unreleased lessons, scripts, filming notes, raw footage, transcripts, editor projects, and exports belong in an explicitly selected private workspace.
- A .gitignore rule does not make tracked content private.
- Do not copy private course pages or paid Resources content into this repository.
- Add a companion only after the finished video and companion have been reviewed together and their release is authorized.
- The agent may prepare and check work locally. Publishing a video or companion needs the user's applicable release instruction.

## Check the result

- Read the lesson as someone who has not seen the video.
- Verify Markdown links and inspect the exact staged files before pushing.
- For runnable examples, document and run the setup and smallest useful verification. State any account, cost, or tool requirements.
- Keep lockfiles for reproducible runnable examples when their tooling uses them.
- Run git diff --check. Do not add a framework or CI system for prose-only material.
- Never commit credentials, private source material, local runtime data, or generated media.
