![Version](https://img.shields.io/static/v1?label=writingLogTemplate&message=0.5.3&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# Writing log for Research Papers in LaTeX

This writing log is for research papers.
The contents of our writing log for a grand application, book, platform talk, lecture, and seminar would be similar in nature but differ slightly in content.
We have not developed writing logs for these particular kinds of writing projects yet.
We plan to do that someday when time permits.
In the meantime, you can use this writing log as a template to develop writing logs for these other kinds of writing projects.

When using LaTeX, use this writing log in parallel to the main writing project document to track your progress and record your plans.
This template can be used in any text editor that supports LaTeX, including online servers like Overleaf.
Other compatible text editors include Visual Studio Code, Vim, NeoVim, Emacs, TextMate, Sublime Text, etc.
Visit [here](https://mooerslab.github.io/pymolsnips/#editors) for an informal review and install instructions for 18 leading text editors.

The writing log is a document that is external to the manuscript.
It stores the plans, decisions, correspondence, and progress made on a specific manuscript.
It is a tool for narrowing your focus and sustaining momentum on the writing project.
It is also a tool that eases re-engagement in an interrupted writing project.
It is like a master thinking document or a second brain for a writing project.

If you start the name of the writing log with the word `log,` this will make navigating to the current file easier when using a terminal supported by tab completion.
I use `log` followed by the project number and name in the Camel or Pascal case.
This helps distinguish the log file from the `main*.tex` file that contains the manuscript.


## Features

- Protocol for planning a manuscript.
- A table of contents that is automatically generated and hyperlinked.
- An automatically generated index that is hyperlinked.
- Support for generating a references cited section from a Bibtex library.
- Section for lists required for most manuscripts like keywords.
- Includes inventories of the private and public data locations.
- A writing log section for recording notes on each day's accomplishments.
- A timeline with benchmarks. A plan without deadlines is just a wish list.
- Plot of wordcount by writing session to track your progress.

## Instructions

Instructions for using the writing log are found in the annotations in the template.
You can use [logXXXXhiddenCommentsVer0.5.1.tex](https://github.com/MooersLab/writingLogTemplate/blob/main/logXXXhiddenCommentsVer0.5.1.tex), which hides the comments to spare you the trouble of deleting them while retaining them for future reference.
Replace XXX with the project number.

Version 0.3 of the writing log was divided into four sections: 

- project initiation
- daily entries
- future additions and tangents
- Guidelines, checklists, protocols, and helpful tips

The subsections of these four sections are shown below.

## Project initiation

- Rationale
- Elevator pitch
- Audience
- Target journals
- Related projects
- Research program mind map
- Potential Introduction
- Potential Results
 + Potential figures
 + Potential tables
- Potential Discussion points
- Published discussion points
- Results and Discussion mind map
- Potential titles
- Potential keywords
- Potential abstract
- Abbreviations
- Acronyms
- Required plasmids
- Required cells
- Required lab supplies
- Required software
- Required safety training
- Potential collaborators
- Potential competitors
- Potential reviewers
- Draft cover letter
- Inventory of data on hand and where is located
- List of associated GitHub repositories
- List of relevant blog posts
- List of relevant videos
- List of relevant literature to search and read
- List of relevant collections of papers in literature management software (e.g., collections in research rabbit)
- List of relevant RSS feeds
- Acknowledgments
- Funding sources
- Project summary for grant report.
- Project summary for annual report.
- List of plans (likely stored elsewhere).
  + Timeline to do the required experiments to test the hypothesis. 
  + User proposals for national laboratory resources.
  + User proposals for HPC resources.
  + Gather the appropriate information from the literature.
  + Related current grant(s) and specific aim(s)
  + Funding sources and account information (e.g., chartfield spreads).
  + Recruit collaborators.
  + Recruit lab members to do the work.
  + Career development plans for each lab member, including you.
  + Biosafety.
  + Authentication of key biological and chemical resources.
  + Statistical sampling and power analysis.
  + data analysis.
  + Data management (backups, archives).
  + Data sharing.
  + The NIH PEDP.


### Daily entries

- Daily Protocol
- Daily Log
- Next action
- To be done
- Timeline or Benchmarks
- Word Count
- Update writing progress notebook
- Update personal knowledge base



### Future additions and tangents

- New branches on the above mind map for this project and research program
- Mind map for the research program (the big picture that includes related manuscripts, talks, posters, funded grants, grant applications)
- Ideas to consider adding to the manuscript
  + Introduction
  + Results
  + Discussion
- Graphical abstract
- To be done someday
- Spin-off writing projects
  + manuscripts
  + grant applications
  + books
  + talks
  + posters


### Guidelines, checklists, protocols, helpful hints
 
- Tips for using Overleaf
- Protocol for running Grammarly in Overleaf
- Guidelines for debugging the annotated bibliography
- Graphical Abstract
- Guidelines for benchmarks
- Guidelines for using the Writing Progress Notebook
- Guidelines for using a personal knowledge base


## Usage on Overleaf

- Upload the files into your current writing project.
- Open the writing log file to edit and compile it on the fly.
- Compile times are lightning fast.
- You can configure Overleaf to use its default, Vim, or Emacs key bindings.


## Usage in Emacs

Emacs has the `latex-mode` built into the main distribution.
You can install the `AUCTeX` package on top of it.
Compile times are several seconds on a 2018 MacBook Pro with 32 GB of RAM.

- `git clone https://github.com/MooersLab/writingLogTemplate` into your current writing project folder.
- Start Emacs, perhaps using the [latex-emacs](https://github.com/MooersLab/latex-emacs) profile.
- Load the writingLogTemplate.tex file into Emacs via the pull-down menu or the keybinding `C-x C-f`. 
- Essential keybindings for editing this file include (note that most of these operations are available via the pull-down menus):
  + `C-g` to abort the current command.
  + `C-x C-c` to quit Emacs
  + `C-x C-s` to save the current document.
  + `C-x C-w` to write the current document to a new file name.
  + `C-x u` to undo the last change.
  + `M-UP` or `M-DOWN` to shift lines up and down. UP and Down are the arrow keys.
  + `C-c =` to create a navigable table of contents at the top of the `tex` file.
  + `C-c C-a` to export to pdflatex, bibtex, make index, and open the resulting PDF in the default PDF viewer.

For more keybindings, see the README.md file of the repository for the [latex-emacs](https://github.com/MooersLab/latex-emacs) profile.

## Related projects of possible interest

- [Writing log template in Org-mode](https://github.com/MooersLab/writingLogTemplateInOrg)
- [Writing log template in reStructuredText](https://github.com/MooersLab/writing-log-rst) reStructuredText is used by programmers for documentation.
- [Writing log template in Markdown](https://github.com/MooersLab/writing-log-md) Markdown variant. Read and rendered to PDF by most good text editors.
- [Writing log template in ODT](https://github.com/MooersLab/writing-log-odt) ODT can be read by Open Office, LibreOffice, and MS Word.
- [Writing log template in DOCX for MS Word](https://github.com/MooersLab/writing-log-docx) MS Word variant. This is probably the least suitable format for this task.
- [Voice computing-related repos](https://github.com/MooersLab#voice-computing)
- [LaTeX manuscript template](https://github.com/MooersLab/manuscriptInLaTeX/edit/main/README.md)
- [Org-mode manuscript template](https://github.com/MooersLab/manuscriptInOrg/edit/main/README.md)
- [Slideshow template in LaTeX](https://github.com/MooersLab/slideshowTemplateLaTeX)
- [Annotated bibliography Template in LaTeX](https://github.com/MooersLab/annotatedBibliography)
- [Diary for 2024 in LaTeX](https://github.com/MooersLab/diary2024inLaTeX)- [latex-emacs profile](https://github.com/MooersLab/latex-emacs)
- [default Emacs profile](https://github.com/MooersLab/configorg)
- [snippets for latex-mode in Emacs](https://github.com/MooersLab/snippet-latex-mode)
- [Quizzes about Emacs to improve recall of keybindings](https://github.com/MooersLab/qemacs)
- [Slides from talk about GhostText, Data Science Workshop, July 2022](https://github.com/MooersLab/DSW22ghosttext)
- [Video link to talk about GhostText, Data Science Workshop, July 2022](https://mediasite.ouhsc.edu/Mediasite/Channel/python/watch/4da0872f028c4255ae12935655e911321d)
- [Slideshow about using LaTeX in Emacs, Berlin Emacs Meetup, 31 August 2022](https://github.com/MooersLab/BerlinEmacsAugust2022)
- [The writer's crede](https://github.com/MooersLab/thewriterslaw)


## Version History

|Version           | Changes                                               | Date            |
|:----------------:|:-----------------------------------------------------:|:---------------:|
| Version 0.3      | First posted.                                         | 2024 January 22 |
| Version 0.4.0    | Added subsections on data and code inventories.       | 2024 April 5    |
| Version 0.4.1    | Added subsections on lists of videos and blogs.       | 2024 April 7    |
| Version 0.4.2    | Added version with hidden comments to spare the trouble of deleting them. | 2024 May 17    |
| Version 0.4.2    | Edited the README.md for improving readabiity.        | 2024 May 30    |
| Version 0.5.0      | Added subsubsection for mindmap.                      | 2024 June 11    |
| Version 0.5.1      | Added subsubsection for GitHub repos                      | 2024 June 12    |
| Version 0.5.2      | Added subsubsection for Plans                     | 2024 June 12    |
| Version 0.5.3      | Expanded lists to include nuts and bolts.                     | 2024 June 15    |
| Version 0.5.3      | Added subsection on rewriting protocol.                     | 2024 June 18    |

## Sources of Funding

- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH P20GM103640 and P30GM145423 (PI: A. West)

