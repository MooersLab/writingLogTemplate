![Version](https://img.shields.io/static/v1?label=writingLogTemplate&message=0.5.5&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# An Advanced Writing Tool for Metacognition about Research Papers

## Introduction
This writing log contains a diary about a writing project, but it also contains the metadata (plans, decisions, correspondence, and progress made) about the writing project that is often stored in comments or at the bottom of manuscript documents.
These metadata are vulnerable to being accidentally deleted and clutter the main manuscript document.
These metadata are actually very valuable and deserve to be stored properly.
We think that storing them with the diary about the progress being made on the writing project enhances the use of the diary for metacognition about the writing project.

## Background
This document is a tool for narrowing your focus and sustaining momentum on one specific writing project.
We know others who have suggested keeping a writing diary, but these diaries are not project-specific.
We think keeping the document specific to one project is essential to narrow one's focus.

Busy academics often have to work on several writing projects in a given week because they do not have the luxury of working on one writing project at a time.
The one project-at-a-time approach has a lower cognition load, but it also gives the subconscious less time to develop ideas in the background of one's mind. 
Working on several projects in parallel leads to juggling dozens to hundreds of thoughts about several writing projects.
Keeping all these thoughts across multiple projects in one document leads to a tangled mess that is very laborious and time-consuming to parse.
This is why we use one document per writing project; this document is a key part of how we progress on 2-5 writing projects in a given week.

The writing diaries of others also have little to no support for metadata and metacognition about the writing project.
We think an external document for storing metadata about a writing project and thinking about that metadata enhances the focus on the paper's content.
We have found that the more time we spend on metacognition about the writing project outside of the manuscript, the more effective our time is when working inside that manuscript because our efforts are more focused and directed.
We have been struck by the diversity and extent of metacognitive activities associated with a specific writing project.
The writing log is a place for documenting these vital activities.
This record is a valuable resource for documenting decisions made about the current paper and for stimulating ideas for new manuscripts.

This enhanced writing log is also a tool that eases re-engagement in an interrupted writing project.
It is like a master thinking document or a second brain for a writing project.
It is a safe storage site for your thoughts about a writing project that could otherwise clutter your mind and get in the way of your next generative writing session for a particular project.

This writing log is for research papers.
The contents of our writing log for a grant application, book, platform talk, lecture, and seminar would be similar in nature but differ slightly in content.
We have not developed writing logs for these particular kinds of writing projects yet.
We plan to do it when time permits.
In the meantime, you can use this writing log as a template to develop writing logs for these other writing projects.

We do most of our writing in LaTeX.
The most advanced version of this writing log document is being developed in LaTeX.
At the moment, it is undergoing a spurt in development as we add new features.
We will update the other formats listed below when it reaches the next stable state.
If you are anxious to use the latest version in a different format, you can convert it to other formats using  pandoc.
You may have to do some subsequent editing because pandoc is not perfect.


- [Writing log template in Org-mode](https://github.com/MooersLab/writingLogTemplateInOrg) a superset of markdown for Emacs. Can be edited in VS Code.
- [Writing log template in reStructuredText](https://github.com/MooersLab/writing-log-rst) reStructuredText is used by programmers for documentation.
- [Writing log template in Markdown](https://github.com/MooersLab/writing-log-md) Markdown variant. Read and rendered to PDF by most good text editors.
- [Writing log template in ODT](https://github.com/MooersLab/writing-log-odt) ODT can be read by Open Office, LibreOffice, and MS Word.
- [Writing log template in DOCX for MS Word](https://github.com/MooersLab/writing-log-docx) MS Word variant. This is probably the least suitable format for this task.
- Planned: a version for typist.

The LaTeX version will have the most features.
The `logXXXhiddenCommentsVer0.5.5.tex` file is easy to edit in a free account on [Overleaf](https://www.overleaf.com/).
You can view it in the rich text format if you cannot tolerate LaTeX.
Overleaf is accessible to anyone with access to the World Wide Web.
As a result, this format best follows the FAIR principles because not everyone has access to MS Word.

When using LaTeX, use this writing log in parallel to the main writing project document to track your progress and record your plans.
This template can be used in any text editor that supports LaTeX, including online servers like Overleaf.
Other compatible text editors include Visual Studio Code, Vim, NeoVim, Emacs, TextMate, Sublime Text, etc.
Visit [here](https://mooerslab.github.io/pymolsnips/#editors) for an informal review and install instructions for 18 leading text editors.

If you start the name of the writing log with the word `log,` this will make navigating to the current file easier when using a terminal supported by tab completion.
I use `log` followed by the project number and name in the Camel or Pascal case.
This helps distinguish the log file from the `main*.tex` file that contains the manuscript.


## Features

- Protocol for planning a manuscript.
- A table of contents that is automatically generated and hyperlinked.
- An automatically generated index that is hyperlinked.
- Support for generating a references cited section from a Bibtex library.
- Section for lists required for most manuscripts like keywords, alternate titles, and potential reviewers.
- Includes inventories of the private and public data locations.
- A checklist to monitor manuscript completion.
- A timeline with milestones. A plan without deadlines is just a wish list.
- A list of questions to ask during assessments of the project's current state.
- Generation of a list of barriers to project completion.
- A pre-writing protocol to warm up for the day's generative writing.
- A writing log section for recording notes on each day's accomplishments.
- A section for the next action item to ease starting the next day.
- A section for to-dos.
- A section for future project ideas, related tangents, and rabbit holes.
- Plot of wordcount by writing session to track your progress.
- A section for protocols, guidelines, and checklists.

## Instructions

Instructions for using the writing log are found in the annotations in the template.
You can use [logXXXXhiddenCommentsVer0.5.5.tex](https://github.com/MooersLab/writingLogTemplate/blob/main/logXXXhiddenCommentsVer0.5.5.tex), which hides the comments in commented-out lines to spare you the trouble of deleting them while retaining them for future reference.
Replace XXXX with the project number or number-name.

Version 0.5 of the writing log was divided into five sections: 

- Project initiation
- Project management and assessment
- Daily entries
- Future additions and tangents
- Guidelines, checklists, protocols, and helpful tips

The subsections of these five sections are shown below.

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
  + Funding sources and account information (e.g., chart field spreads).
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

## Plan for timely completion of this project

  - A checklist for the completion of the manuscript.
  - A timeline with milestones.
  - Snapshots of the project's current state.
  - Current list of barriers to project completion.


## Protocol for pre-writing exercises


## Daily entries

- Daily Protocol.
- Daily Log.
- Next action.
- To be done.
- Timeline or Benchmarks.
- Word Count.
- Update writing progress notebook.
- Update personal knowledge base.



### Future additions and tangents

- New branches on the above mind map for this project and research program.
- Mind map for the research program (the big picture that includes related manuscripts, talks, posters, funded grants, grant applications). This is a super metacognition tool.
- Ideas to consider adding to the manuscript.
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
- Guideline for writing a cover letter.
- Guideline for responding to reviewers.


## Sorting of lists

Some of the above lists must be sorted and duplicates must be removed when augmenting a list with new items.
Most text editors will support the sorting of lines.
Some text editors support the removal of duplicates in a list.
Most text editors ignore blank lines.

The function below for Emacs combines the above 3 functionalities into the key board short cut `Control-c s`.
The keys linked by a dash are pressed down in unison.

```elisp
(defun clean-sort-list-in-region (beg end)
  "Clean and sort the lines in the selected region.
   Removes duplicate lines, blank lines, and sorts alphabetically."
  (interactive "r")
  (let ((lines (split-string (buffer-substring-no-properties beg end) "\n" t))
        (cleaned-lines nil))
    ;; Remove duplicates and blank lines
    (dolist (line lines)
      (when (and (not (string-blank-p line))
                 (not (member line cleaned-lines)))
        (push line cleaned-lines)))
    ;; Sort alphabetically
    (setq cleaned-lines (sort cleaned-lines #'string<))
    ;; Replace the region with the cleaned and sorted lines
    (delete-region beg end)
    (insert (mapconcat #'identity cleaned-lines "\n"))))
(global-set-key (kbd "C-c s") 'clean-sort-list-in-region)
```

This function removes the blank lines in a selected region, and it removes the duplicated lines. 
Then this function sorts the remaining lines in alphabetical order.
To select the list by creating a region, move the cursor to the first line, enter `Control-space` (or `C-space` in Emacs shorthand), and use the down arrow to select the list.
Enter `Control-c s` (i.e., C-c s) to apply the function to the list.
This function is useful for updating keywords and other lists in the writing log.


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

|Version           | Changes                                                                   | Date            |
|:----------------:|:-------------------------------------------------------------------------:|:---------------:|
| Version 0.3      | First posted.                                                             | 2024 January 22 |
| Version 0.4.0    | Added subsections on data and code inventories.                           | 2024 April 5    |
| Version 0.4.1    | Added subsections on lists of videos and blogs.                           | 2024 April 7    |
| Version 0.4.2    | Added version with hidden comments to spare the trouble of deleting them. | 2024 May 17     |
| Version 0.4.2    | Edited the README.md for improving readabiity.                            | 2024 May 30     |
| Version 0.5.0    | Added subsubsection for mindmap.                                          | 2024 June 11    |
| Version 0.5.1    | Added subsubsection for GitHub repos.                                     | 2024 June 12    |
| Version 0.5.2    | Added subsubsection for Plans.                                            | 2024 June 12    |
| Version 0.5.3    | Expanded lists to include nuts and bolts.                                 | 2024 June 15    |
| Version 0.5.4    | Added subsection on rewriting protocol.                                   | 2024 June 18    |
| Version 0.5.5    | Added section on planning for project completion.                         | 2024 June 19    |
| Version 0.5.5    | Added six paragraphs to REAME.md to explain the advanced features.        | 2024 June 20    |

## Sources of Funding

- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH P20GM103640 and P30GM145423 (PI: A. West)

