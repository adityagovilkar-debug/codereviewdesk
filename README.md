# Code Review Desk

A single-file, offline code review checklist tool for ABAP developments. Open `Code Review Desk.html` in Microsoft Edge or Chrome. There is nothing to install and no server.

## Workflow
1. **Developer:** enters the change details, objects, transport requests and systems, ticks the checks that apply, and self-reviews them.
2. **Reviewer:** opens the same review in the same tool, reviews each check and transport (and can add checks the developer missed), then approves or requests changes.
3. **Rounds:** requested changes go back to the developer. Every round is kept in the history.
4. **Archive:** once approved, copy the document into Confluence (rich paste or wiki markup) and attach the archive `.html`, or print to PDF.

## Sharing reviews
- **Shared folder (recommended):** sync a Teams / SharePoint folder with OneDrive and connect it on the home page. Reviews, the team checklist and archives live there, and the home page shows each person's queue.
- **Files:** without a shared folder, reviews are saved as `.json` files and passed on by hand.

## Checklist
Sections, checks, object types (with suggested sections) and version-backup systems are edited under **Checklist setup**. You can publish the checklist to the shared folder, or bake it into a copy of the tool with **Download tool with this checklist**.

Each review file carries its own copy of the check wording, and fingerprints of the developer and reviewer sections flag edits made outside the tool.
