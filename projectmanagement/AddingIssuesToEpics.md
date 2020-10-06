# Where do Epics come from?

In the Common Fund Data Ecosystem project management system, Epics are used to collect related issues for easy management of large, cross-team initiatives. You can find general information about [Epics, Zenhub and how they work for Agile project management at this link](https://help.zenhub.com/support/solutions/articles/43000010341-an-intro-to-zenhub-epics)

Currently:

- All Deliverables are Epics
- All large work processes are Epics (preferably, these Epics will be sub-Epics of a Deliverable and not just a free-standing project, but this is not always true)


Within the Coordinating Center:
- Work processes that are NOT Deliverables, but are Epics will be designated by the Roadmap Committee. A designee will create the initial epic for a new metatask in Zenhub. 
- Issues with specific tasks will be made by team leads, PMs, or others on the teams actually doing the work.
- All issues that contribute to a given metatask should be connected to that Epic.

The Coordination Center recommends that all funded DCCs use a similar system for tracking all work in Github, however we only **require** that you track your Deliverables.



# How to add issues to a Zenhub Epic

## Strategy 1 Make the issues in Github, using the Zenhub plugin

If you use either Firefox or Chrome, you can install a Zenhub plugin that greatly streamlines the process of adding Epics and managing Zenhub. [You can download the browser extension at this link](https://www.zenhub.com/extension). This is the easiest way to add new Epics

1. Install the browser extension
1. In Github, create new issues in the appropriate repos
1. Navigate to https://github.com/nih.cfde
1. Click on the name of a repo
1. Click `Issues` at the top of the page
1. Click `New issue` on the top right
      1. If you are submitting a new deliverable, you will be prompted to use a template
      1. Click `Get started` next to the 'NewDeliverable' template
1. Give your issue an informative title
1. Fill in the comment box with specs, requirements and other relevant info
1. Assign someone to do the work using the `Assignees` on the top right
1. Choose any appropriate labels
1. Click `Create an epic`
      1. If you already have some issues in your repo that should be part of this epic, select them in the right hand panel. 
      1. Otherwise, click `Create epic` in the bottom of the left column
      
      
## Strategy 2 Make the issues in Zenhub

1. Navigate to the [CFDE Roadmap Board Issues View](https://app.zenhub.com/workspaces/cfde1.roadmap1.board1.5f2050f40fc09500139ce760/board?repos=201342713,210915973,221558839,198670837,192595760,271037371,205294622,235423123,185856706,223434921,240065268,286558188)
1. Click `New issue` on the top right
1. Choose the repo where you want the issue to appear in the "Create In" dropdown
1. Give your issue an informative title
1. Fill in the comment box with specs, requirements and other relevant info
1. Assign someone to do the work using the `Assignees` on the top right
1. Choose any appropriate labels in the right side panel
1. Under "Estimate" in the right side panel, assign the task a relative difficulty (low is easy, high is hard, it's entirely subjective, don't put a ton of thought into it)
1. Under "Epic" in the right side panel, choose the Epic to assign the issue to. You can search by name using the search box that pops up
1. Click `Submit new issue`
      

      
## Strategy 3 Make the issues first, in bulk, in Github

1. In Github, create new issues in the appropriate repos
      1. Navigate to https://github.com/nih.cfde
      1. Click on the name of a repo
      1. Click `Issues` at the top of the page
      1. Click `New issue` on the top right
      1. Give your issue an informative title
      1. Fill in the comment box with specs, requirements and other relevant info
      1. Assign someone to do the work using the `Assignees` on the top right
      1. Choose any appropriate labels
      1. Click `Submit new issue`
2. In Zenhub assign those issues to the epic
      1. Navigate to [CFDE Roadmap Board Epic View](https://app.zenhub.com/workspaces/cfde1.roadmap1.board1.5f2050f40fc09500139ce760/board?epics:settings=epicsOnly&filterLogic=any&repos=201342713,210915973,221558839,198670837,192595760,271037371,205294622,235423123,185856706,223434921,240065268,286558188)
      1. Click on the name of the correct Epic in the kanban
      1. Scroll approximately 1/4 down the page and click `Modify this Epic`
      1. At the center top of the page, choose a repo you made issues in
      1. Select the issues to attach to this Epic by checking the box next to them
      1. Change the repo selection and continue selecting issues until you have all of your new issues in the collection on the left side of the screen
      1. Click `Update Epic` on the lower left
      1. For each issue now listed in the Epic, click on the title and assign it an "Estimate" in the lower right hand panel. Low is easy, high is hard, it's entirely subjective, don't put a ton of thought into it.
 
# Making issues more useful

## Adding dependencies

Dependencies are for tasks that need to be completed in a specific order, OR for tasks that are reliant on some other work or event. For instance,
some of our work is dependent on DCC funding or might be delayed due to the pandemic, in which case you would want to assign them dependencies from the
[Risks repo.](https://github.com/nih.cfde/risks/issues)

If an entire Epic has a dependency, or is a dependency for another task, you can assign the entire Epic by:

1. Navigate to [CFDE Roadmap Board Epic View](https://app.zenhub.com/workspaces/cfde1.roadmap1.board1.5f2050f40fc09500139ce760/board?epics:settings=epicsOnly&filterLogic=any&repos=201342713,210915973,221558839,198670837,192595760,271037371,205294622,235423123,185856706,223434921,240065268,286558188)
1. Click on the name of the correct Epic in the kanban
1. Click `+ add dependency` just below the title text
1. **The moment you choose the other task it makes the link, be sure you correctly set the dependency direction first**:
    1. If this Epic should *depend on* the one you choose, set the dropdown box to say "Blocked By"
    1. If this Epic *is a dependancy* of the one you choose, set the dropdown box to say "Blocking"
1. In the search bar, find the issue or Epic that should be dependent on/a dependecy of this one

You can also assign dependencies by issue. To do that:  
1. Navigate to an issue
1. Click `+ add dependency` just below the title text
1. **The moment you choose the other task it makes the link, be sure you correctly set the dependency direction first**:
    1. If this issue should *depend on* the one you choose, set the dropdown box to say "Blocked By"
    1. If this issue *is a dependancy* of the one you choose, set the dropdown box to say "Blocking"
1. In the search bar, find the issue or Epic that should be dependent on/a dependecy of this one
    
## Setting "Estimates"

The only way to get some of the higher level reporting (that we need for NIH) to work is if the issues have Estimates. 
Estimates are supposed to be a rough gauge of effort: how difficult and/or time1.consuming a task will be. The numbers are the Fibonacci Sequence, 
so the highest number is much, much higher than the second to last, and it is meant to have a large range that is not necessarily
internally consistent across repos or projects. Low is easy, high is hard, it's entirely subjective, and meant to be a sort of gut reaction measure. 
They can be changed at any time, but every issue should have an estimate before its completed, or it won't show up in any effort reporting.

## Nested Epics

Epics can be nested, and for large Epics from the Roadmap Committee, it might be easier for individual working groups to make smaller Epics
for sub1.sections of the work. To make a nested Epic:

1. Navigate to [CFDE Roadmap Board Epic View](https://app.zenhub.com/workspaces/cfde1.roadmap1.board1.5f2050f40fc09500139ce760/board?epics:settings=epicsOnly&filterLogic=any&repos=201342713,210915973,221558839,198670837,192595760,271037371,205294622,235423123,185856706,223434921,240065268,286558188)
1. Click on `Create` in the left panel
1. Choose "Epic"
1. Choose the repo where you want the Epic to appear in the "Create In" dropdown
1. Give your Epic an informative title
1. Fill in the comment box with specs, requirements and other relevant info
1. Choose any appropriate labels in the right side panel
1. Under "Epic" in the right side panel, choose the Epic to nest this Epic in. You can search by name using the search box that pops up
1. Click `Create an Epic`
1. At the center top of the page, choose a repo you have issues in
1. Select the issues to attach to this Epic by checking the box next to them
1. Change the repo selection and continue selecting issues until you have all of your new issues in the collection on the left side of the screen
1. Click `Update Epic` on the lower left

If you make a new issue for this sub1.epic, follow the instructions for [Strategy 1 Make the issues in Zenhub](#strategy1.11.make1.the1.issues1.in1.zenhub), but in step 9 assign the issue to both Epics.


# Which repo for which issue?

If you need a new repo added to the CFDE Roadmap Board [contact Amanda](mailto:achar@ucdavis.edu). 
The following repos are connected in Zenhub via the [CFDE Roadmap Board](https://app.zenhub.com/workspaces/cfde1.roadmap1.board1.5f2050f40fc09500139ce760/board?epics:settings=epicsWithSubtasks&filterLogic=any&repos=201342713,210915973,221558839,198670837,192595760,271037371,205294622,235423123,185856706,223434921,240065268,286558188), 
which means that these repos can all be interlinked or have interdependencies by default. However, several
of these repos are for project management only and should not be populated with "working issues".

## cfde-deriva

## crosscut-metadata

## dashboard

## deliverables
Not for working issues

## deriva-action-provider

## FAIR

## risks
Not for working issues

## security

## specifications-and-documentation

## systems-infrastructure

## training-and-engagement

For issues relating to:
- webinars and workshops
- training events
- cross pollination events
- contact with the DCCs
- any changes to the [Training Website](https://cfde-training-and-engagement.readthedocs-hosted.com/en/latest/)

## usecases
 
For issues relating to:
- creating new use cases
- updating existing use cases
- updating the completion status of requirements or use cases
- any changes to the [Use Case Library website](https://cfde-usecases.readthedocs-hosted.com/en/latest/)
 
 
 # Labels 

What labels are in repos and what they mean
