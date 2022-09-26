# Linear notes
from initial notes guide. more: https://linear.app/method
## Features
- good clicky and kbd interfaces for creating, tagging, and changing the state of issues 
- super/ctrl k for all cmds, good for looking up commands' keybind
- connect github to link issues and PRs with **one or more repos**
  - move issues from In Progress to Done automatically so you never have to close Linear issues manually after merging a pull request or closing an issue. Opening a PR marks it as In Progress. Requires specific naming practices on issues and PRs.
- plugins for things like roadmaps, cycles, and custom views
- reusable templates

## testing github integration
- linking from github to linear isn't trivial, but is pretty straightforward. Options:
  - can put the linear issue (eg. THO-2) in the issue/pr title
  - description
  - or branch name
Developer overhead: having to look up the issue name, and/or create the linear issue in the first place, in addition to using github.

## Cycle view
Support cycles from 1-8 weeks.
Issues can be added manually, or any issues marked todo can be automoved to the current cycle, with automatic rollover to the next cycle.
## Projects - organize for larger releases
## Issue mouseover+space to peek at an issue
## Filter items with views
## todo: look at roadmap, cycle, and custom view plugins

# Github projects notes
https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects
## Features
I like the table presentation.
- an adaptable spreadsheet integrating with issues and PRs.
- metadata fields for assignees, complexity, priority, notes, iteration, n more
## TLDR:
Linear offers:
- an alternative but similar presentation for issue creation to github issues
- similar integrations to github projects wrt github PR creation
- requiring small overhead: have to put the Linear issue in a text field when creating a PR.
- better timeline representation on projects
- more flexible issue organization into projects and cycles
- excellent keyboard interface for updating issues; GH's keyboard interface is non-existant
- support for multiple repos (github also offers this)
Github offers:
- a similar, less info-dense spreadsheet format for tracking issues and pull requests
- direct tie-in with existing pull requests without linking overhead 
