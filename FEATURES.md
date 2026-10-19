# Built-in features for gallery-desk-os

Purpose: museum collections research

1. **prepare study and research files** — run gallery-desk-os-workspace. It creates ~/Documents/gallery-desk-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run gallery-desk-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/gallery-desk-os-session-plans/.
3. **check study and source readiness** — run gallery-desk-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/gallery-desk-os-workspace features/gallery-desk-os-plan features/gallery-desk-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for museum collections research:

1. **Anki** — net.ankiweb.Anki
2. **Foliate** — com.github.johnfactotum.Foliate
3. **LibreOffice** — org.libreoffice.LibreOffice

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
