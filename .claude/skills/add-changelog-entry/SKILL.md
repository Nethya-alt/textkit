---
name: add-changelog-entry
description: Append a formatted entry to CHANGELOG.md under the Unreleased heading.
disable-model-invocation: true
---

Add a changelog entry for: $ARGUMENTS

1. If CHANGELOG.md doesn't exist, create it with a "# Changelog" title and a "## [Unreleased]" section.
2. Under "## [Unreleased]", add a bullet at the top: `- <YYYY-MM-DD>: $ARGUMENTS` (use today's date).
3. Keep entries newest-first within the section.
4. Show me the diff. Do NOT commit.
