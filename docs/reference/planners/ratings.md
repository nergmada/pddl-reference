---
layout: default
title: Planners by rating
has_children: true
parent: Planners
grand_parent: Reference
permalink: /ref/planners/rating
nav_order: 2
---

# Planners by Rating

Contributors: {% git_author %}

For user convenience we rank planners according to a Quality Assurance metric detailed below. This metric, scores planners between 0 and 100, not based solely on their competitive performance, but rather by a number of factors, with a strong emphasis focused on end user experience.

Such a metric [was highly controversial](https://github.com/nergmada/planning-wiki/issues/59) when first proposed, and so this metric comes with a caveat, that planning researchers have not agreed to or support this metric. Over time we aim to fine tune this metric to better capture the elements end users of planning value. 

We welcome debate and further input on this system, so if you have any feedback or wish to voice an opinion, a dedicated issue has been opened to discuss this [here](https://github.com/nergmada/planning-wiki/issues/59)

## Score system

- **25 points** for coverage
    - **5 points** for classical coverage
    - **5 points** for classical optimal coverage
    - **10 points** for temporal-numeric coverage
    - **5 points** for expressive features coverage (TILs, Action Costs, Processes, Events)
- **50 points** for end user usability 
    - **25 points** for published and maintained code including:
        - **10 points** for a code publication on a popular public source control system (GitHub, BitBucket, Mercurial etc.)
        - **5 points** for including a readme in text/markdown format on how to compile the code for a defined system (e.g. here's how to compile in on Ubuntu/Fedora/MacOS/Windows etc)
        - **5 points** for including an automated script that is guaranteed to work on a developer defined base system with no pre-requisites installed
        - **5 points** for clear updates and bug reporting and patching processes 
    - **25 points** for documentation of planner including
        - **5 points** for a readme detailing the major contribution of the planner, and how to use it (e.g. command line/UI instructions)
        - **10 points** for an extended readme detailing supported PDDL features, as defined in this wiki or on the eviscerator testing tool - or equivalent table of support attached clearly to the planner or the software repo
        - **10 points** for code documentation that outlines structure and implementation of the code
- **25 points** for IPC competitve ranking
    - If `n` planners participate, and rank in position `p` the score is `25 * (p/n)`

## Planners by score

| Planner | Links | Score |
|---------|-------|-------|
| Alien | [Guide Page](/ref/planners/alien) \| Home Page [Not Found] \| [Paper](https://ipc2018-classical.bitbucket.io/planner-abstracts/team33.pdf) | 38.1 |
| AllPACA | [Guide Page](/ref/planners/allpaca) \| Home Page [Not Found] \| [Paper](https://helios.hud.ac.uk/scommv/IPC-14/repository/booklet2014.pdf) | 31.2 |
| Arvandherd | [Guide Page](/ref/planners/arvandherd) \| Home Page [Not Found] \| [Paper](https://webdocs.cs.ualberta.ca/~mmueller/ps/2011/2011-arvandherd-IPC-booklet.pdf) | 30 |
| Arvand | [Guide Page](/ref/planners/arvand) \| Home Page [Not Found] \| [Paper](https://webdocs.cs.ualberta.ca/~mmueller/ps/arvand-art-of-random-walks.pdf) | 22.6 |
| ACOPlan & ACOPlan 2 | [Guide Page](/ref/planners/acoplan) \| Home Page [Not Found] \| [Paper](https://www.aaai.org/ocs/index.php/FLAIRS/2009/paper/download/116/276) | 15.9 |