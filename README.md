---
title: "README"
author: "David Fredman"
date: "22 January 2016"
output: html_document
---

## Reproducible Research in Bioinformatics and Biostatistics

The scientific process in life science research, from data collection and
processing to analyses, visualization and conclusions, increasingly depend
on algorithms and computation. Collaborative projects where researchers share
written analyses, data files and computing scripts electronically are now
the norm rather than the exception. Frequently, the analysis is so complex that
it is near impossible to fully describe in a written document.

To convey findings with clarity, making it possible for a researcher to
completely follow someone else’s work, is the crux of scientific collaboration.
Thus, reproducible research, and reproducible computation in particular, has
received increasing attention in the scientific community in recent years. 

## Overview

In this practical and hands-on course, we will learn effective methods for
collaborative and reproducible research, while learning bioinformatics and
statistics methods relevant for our own research. Following a workshop that
introduces and teaches methods, each student will reproduce a chosen paper
using R + open source tools, and make the reproduction available online.

## Learning outcomes

-   You will learn good practise for how to make your own research reproducible.

-   Reproduce the figures, tables, and statistical methods of a
    [selected published paper](http://davfre.github.io/RRIB/).

-   Make the reproduction publically available (git repo + blog post, possibly
a paper in http://rescience.github.io/read/ if suiable)

-   Understand and apply methods relevant for your own research

-   Collaborate and create science.


## Modules

### Pre-workhop

- (carefully) select two papers that you would like to reproduce.
More on this below.

### Workshop (2 days)

- Collaborative science with Git [basics, branching, pull requests]

- Data management, processing, cleaning

- R and RMarkdown

- Dealing with dependencies [packaging, containers]

- Presentation of the paper you have chosen: underlying data, which portions of
the paper you will reproduce

### Capstone project (~40 hrs)

The capstone project represents the majority of the course work.
This will be done by way of online collaborative reproduction
[2 students per project] via github.com, with bi-weekly peer-review
[you provide feedback to other projects]. 


## Paper selection

We will spend substantial time and effort on each paper, so selection is very important. Please make suggestions [here](papers.md).

- Focus on papers with mostly analyses of empirical data.

- Raw data must be available.

- Reproduction should appear feasible in a weeks effort (spread over a couple of months) at most. If the paper is massive, you may reproduce a suitabily sized and interesting section of it.

## Reproduction guidelines

- Reproductions will be in R markdown, and should be generously commented.

- Data manipulations must be done programmatically in R (or other open source software, if
required). No alteration of original data files allowed.

- A reproduction will follow the sequence data download, data processing, and
finally reproduction of results/figures/tables.

## Outcome

-   A fully reproduced paper that can be generated from
    the raw datasets, available online [here](http://davfre.github.io/RRIB/).

-   An online report of our reproduction, with code.

-   Research ideas.

-   Outstanding issues.

-   Parts of the paper we decided to not reproduce and why.

## Bi-weekly meetings

Information [here](Meetings.md).

## Remote collaboration and participation

Anyone can read and contribute to a reproduction on github, see
[here](contributing.md) for detailed instructions. If you do not know what git
and Github are, please look at these [resources](Git_resources.md) to get you started).

## Communication

Please use the RRIB github repository Issues and Wiki for as much communication
as possible. There will be no email list. Any enquiries should be made as an
Issue or wiki entry here: https://github.com/davfre/RRIB 

## Gaining 1 (2?) ECTS

Norbis Students can gain 1 (2?) ECTS for attending the workshop, completing the
capstone project, and actively providing peer assessment.

You will learn how to make reproductions using R markdown.


