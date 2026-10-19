# Built-in features for roomshape-os

Purpose: interior design

1. **prepare a creative project** — run roomshape-os-workspace. It creates ~/Documents/roomshape-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run roomshape-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/roomshape-os-session-plans/.
3. **check project and export readiness** — run roomshape-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/roomshape-os-workspace features/roomshape-os-plan features/roomshape-os-check "$HOME/.local/bin/"
