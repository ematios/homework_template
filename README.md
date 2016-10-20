# homework_template
Latex template for assignments.

**Usage:**

Add this repo as a submodule to your exercise repo.

**Assumptions:**

This package makes a few assumptions about your directory structure.

. -> "root" git repo
├── assignment_01 -> all assignments have individual folders
│   ├── assignment.tex -> Contains the assignment number. E.g "Assignment 01". This is included when building the pdf.
│   └── exercises -> Folder containing the individual answers.
│       └── problem1.tex -> Answers to individual questsions. Best to use *\section{}*
├── homework_template -> submodule, you don't need to edit this
│   ├── exercise.tex
│   ├── LICENSE
│   └── README.md
├── names.tex -> Names of all group participants. Dividied by "\\"
└── unihei_logo_4c.pdf -> Logo to include in the title page
