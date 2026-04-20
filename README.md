# 9micedevs

Lua scripting repository for Roblox/Luau experiments, UI work, and utility logic.

## Overview

The project currently keeps the main implementation in a single Lua entry file. The repository is useful as a place to iterate on scripting patterns before extracting stable pieces into smaller modules.

## Repository Contents

- `main.lua` - primary Lua/Luau source file.
- `.gitignore` - common Lua and build-output ignore rules.
- `LICENSE` - Apache 2.0 license.

## Development Notes

- Keep reusable logic separated into small local functions before moving it into modules.
- Avoid committing generated files, local executor configuration, tokens, cookies, or account-specific data.
- Prefer small focused commits so future changes are easier to review.
- Document any required runtime assumptions near the relevant code.

## Safety

Use this code only in environments where you have permission to test it. Do not use repository code for unauthorized access, abuse, cheating, or disruption of other users' experiences.

## Future Cleanup Ideas

- Split large UI and configuration sections into modules.
- Add a short changelog for major script behavior changes.
- Add examples for safe local testing.
