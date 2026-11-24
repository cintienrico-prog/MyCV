# Data shared by the CV and the website

The CV (`main.tex`) and the website (enricocinti.com, which reads this folder from
this repo when it is built) take these from here, so an entry is added once:

- `publications.bib`: books, articles and chapters, and work not yet published
  (`status = {…}` instead of a year). See the comment at its top for the fields.
  The CV prints books and articles from it (cv-data.tex); unpublished entries
  appear only on the website.
- `teaching.csv`: courses, newest first. `hours` and `note` may be empty.
- `supervision.csv`: thesis and project supervision, newest first. The website
  leaves out `title`; `role` (e.g. co-supervisor) is optional.

The CSV files are plain comma-separated values: put a field in double quotes when
it contains a comma. Overleaf edits them like any other file.
