# Human Writing Skill

A work-in-progress writing skill for Claude, Cursor, and other AI assistants that support SKILL.md-style instruction files.

The goal is to make generated text sound more human, more natural, and less like generic AI output.

## Status

This repository is currently:
- In progress.
- Not fully tested.
- Still being refined.

The current version should be treated as an experimental foundation, not as a finished production-ready skill.

## What this skill is for

Use this skill when you want AI-generated text to:

- Sound more human.
- Avoid obvious AI tells.
- Reduce emojis unless explicitly requested.
- Avoid em dashes.
- Use less fluff and fewer empty adjectives.
- Adapt better to tone, audience, and language.
- Support English and German output.

## Current focus

The current implementation is designed as a shared core for multiple tools.

Claude support is the primary target.
Cursor support is also planned, but Cursor-specific behavior and integration details are still being worked out.

## Planned Cursor-specific work

Future updates may include:
- Cursor-optimized usage notes.
- Tool-specific setup guidance.
- A cleaner split between shared skill logic and Cursor-specific rules.
- Better recommendations for how Cursor should load and apply the skill.

## Structure

- `README.md` explains the repository.
- `.github/skills/human-writing/SKILL.md` contains the main skill instructions.

## Contributing

This repository is public and contributions are welcome.

If you want to help:
- Fork the repository.
- Create a feature branch.
- Make your changes.
- Open a pull request.

Please keep changes focused, readable, and consistent with the writing goals of the skill.

## Notes

This repository is still under active development.
If something looks incomplete or inconsistent, that is expected for now.
