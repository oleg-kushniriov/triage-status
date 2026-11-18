# Triage Desk status pages

These pages are written by Triage Desk. Each one says how many issues and pull requests of a
repository are overdue, aging or awaiting a reply, so that a link to it shows those counts as
its preview. Whoever opens it sees the counts, with a button that opens the same place in
the dashboard.

Addresses, under the address of the site:

- `/`: every repository.
- `/<owner>/<name>/`: one repository; `/<owner>/<name>/issues/` and `/<owner>/<name>/prs/`
  for one of its lists. These are the addresses to share: their preview is about that
  repository.
- `/?repo=<owner>/<name>` opens the page of that repository as well. The name alone is
  enough when only one repository has it, and upper and lower case do not matter.

Do not edit anything here: every file is replaced the next time the counts change.
