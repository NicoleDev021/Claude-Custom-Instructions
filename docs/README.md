<!--
SPDX-FileCopyrightText: Copyright (c) 2026 Madison Nicole Goodwin https://github.com/NicoleDev021
SPDX-License-Identifier: CC-BY-4.0
-->
# Claude Custom Instructions

Custom instructions I actually use with Claude, plus notes on why each piece exists.

I started this repo after rebuilding my global preferences from scratch. My first attempt told Claude to be a ruthless mentor that challenges everything and never optimizes for brevity. I got exactly what I asked for: pushback on sound reasoning and essays for simple questions. The rebuild taught me more about writing instructions than any guide did, so I'm documenting the results here as I go.

---

## What's here now

- [`global-preferences.md`](global-preferences.md): The instruction set that loads into every conversation. It covers how I want Claude to engage with my reasoning, when to push back and when to concede, response length defaults, and accuracy rules. The file includes design notes explaining the reasoning behind each section.

## What's coming

This repo will grow as I build out instructions for specific projects. Global preferences and project instructions stack in Claude, so the plan is to keep the global file domain agnostic and add project files that carry the specific context. Planned additions as I write and test them:

- Project instruction sets for the areas I work in most
- Notes on what changed between versions and why, since the interesting part is usually what failed

## How I use these

Nothing here was right on the first pass. The loop that works for me: paste the instructions in, use them for a week across different kinds of conversations, note which lines get violated or misfire, then edit those specific lines instead of rewriting the whole thing. Instructions reveal what you actually wanted after you watch them fail a few times.

If you take anything from here, take the loop, not just the text.

---

## Contributor Guidance

If you contribute to this repository, **please make sure to review and follow the community standards and reference the following files**:

- [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md): Outlines the standards for behavior and participation in this community.
  _Please read and follow the Code of Conduct to help maintain a welcoming environment for all contributors._
- [`CONTRIBUTING.md`](CONTRIBUTING.md): Provides detailed guidelines on how to contribute to this project, including how to submit issues and pull requests and commit message conventions.
  _Please review these instructions before contributing to ensure your submissions align with the project's workflow and expectations._
- [`SECURITY.md`](SECURITY.md): Contains the process for reporting security vulnerabilities or concerns.
  _If you discover a security issue, please follow the instructions in this file to report it responsibly._

We appreciate your attention to these documents to help keep the project collaborative, secure, and compliant.

---

## License

All files in this repository are text documentation and are licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

Each file carries the following SPDX identifier at the top:

```
SPDX-License-Identifier: CC-BY-4.0
```

If you contribute, you agree that your contributions will be licensed under these terms.
