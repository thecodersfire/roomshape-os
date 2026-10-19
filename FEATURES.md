# Built-in features for roomshape-os

Purpose: interior design

1. **prepare a creative project** — run roomshape-os-workspace. It creates ~/Documents/roomshape-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run roomshape-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/roomshape-os-session-plans/.
3. **check project and export readiness** — run roomshape-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/roomshape-os-workspace features/roomshape-os-plan features/roomshape-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for interior design:

1. **GIMP** — org.gimp.GIMP
2. **Krita** — org.kde.krita
3. **Kdenlive** — org.kde.kdenlive

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for interior design:

1. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
2. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
3. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
4. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
5. **LibreOffice** — create reports and spreadsheets (org.libreoffice.LibreOffice)
6. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
7. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
8. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
9. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
10. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
2. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
3. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
4. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
5. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
6. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
7. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
8. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
9. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
10. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
11. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
12. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
13. **FreeCAD** (org.freecadweb.FreeCAD) — design mechanical parts.
14. **OpenSCAD** (org.openscad.OpenSCAD) — model parametric 3D parts in code.
15. **KiCad** (org.kicad.KiCad) — design circuits and PCBs.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
