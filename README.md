# Code Review Desk

A single-file, offline code review checklist tool for ABAP developments. Open `Code Review Desk.html` in Microsoft Edge or Chrome. There is nothing to install and no server.

## Workflow
1. **Developer:** enters the change details, objects, transport requests and systems, ticks the checks that apply, and self-reviews them.
2. **Reviewer:** opens the same review in the same tool, ticks off each transport, reviews each check (and can add checks the developer missed), then approves or requests changes.
3. **Rounds:** requested changes go back to the developer, who answers each finding and resubmits. Every round is kept in the history. While a review is with the reviewer, the developer's half is read-only; **Recall to edit** turns it back into a draft.
4. **Archive:** once approved, copy the document into Confluence (rich paste or wiki markup) and attach the archive `.html`, or print to PDF.

## Sharing reviews
- **Shared folder (recommended):** sync a Teams / SharePoint folder with OneDrive and connect it on the home page. Reviews, the team checklist and archives live there, and the home page shows each person's queue (set your SAP ID with the button at the top right).
- **Files:** without a shared folder, reviews are saved as `.json` files and passed on by hand.

## Team features (shared folder)
- **Team list** (`team.json`, Team page): SAP ID boxes suggest names and fill them in, and unknown IDs get a warning. **Checklist owners**: when set, only they can publish the checklist.
- **Who has it open:** while a review is open for editing or reviewing, colleagues see "Priya is reviewing" in their lists and on the review (`locks/`, expires after 3 minutes). Reviewers can **claim** an unassigned review.
- **Withdraw** (with a reason; can be restored as a draft) and **Reopen** an approved review (with a reason), both kept in the history.
- **Seen before:** earlier reviews of the same objects, and what was flagged, shown to the developer and the reviewer.
- **Insights:** checks most often not followed, self-declared exceptions, turnaround, rounds, a per-person table, approvals per month, a per-person year in review, and a CSV export of every review.
- **Per-check guidance** ("why it matters" + an example) written in Checklist setup and shown with **?** on each check.
- **Saved reviewer comments**, suggested while typing; ☆ saves one for the team.
- **Copy reminder** for reviews waiting 2 days or more.

## Checklist
Sections, checks, object types (with suggested sections) and version-backup systems are edited under **Checklist setup**. You can publish the checklist to the shared folder, or bake it into a copy of the tool with **Download tool with this checklist**.

Each review file carries its own copy of the check wording, and fingerprints of the developer and reviewer sections flag edits made outside the tool.

## Keyboard
`Ctrl K` search reviews (ticket, title, object, transport, person) and actions · `N` new review · `O` open a file · `1`–`7` Reviews / Developer / Reviewer / Document / Checklist setup / Insights / Team · `Ctrl S` save the draft or review progress.

## Look
Instrument White (Paper) and Backlit (dark) themes, following Windows by default; the sun button in the title bar cycles system → Paper → Backlit.
