# Checklist: Adding a new repository

Any user in the CFDE can create a new repository. Before making a new repository, please check to see whether there any existing repositories with similar purposes. 

If the repository will not host much code, consider whether a mailing list or Slack channel might be effective for your goals.

**1) Decide where your repository will live.**

  - Repositories related to the Common Fund Data Ecosystem (CFDE)
    live at the [CFDE organization on Github](https://github.com/nih-cfde).
  - We encourage CFDE members to create new repositories and utilize
    teams in the [CFDE organization](https://github.com/orgs/nih-cfde/teams) on
    Github.
  - All members are welcome to create and manage their own repositories
    under the CFDE organization.
  - Repositories that are created in the CFDE organization are able to
    take advantage of Github teams in the CFDE organization.
  - All repositories that are part of the CFDE project are subject to
    the [CFDE Code of Conduct](CODE_OF_CONDUCT.md).

**2) Decide whether to make your repository public or private.**

  - In the spirit of openness and transparency, we encourage all
    participants in the CFDE to make relevant materials public.
  - However, in many circumstances repositories should be kept private
    by nature of their contents. Github is useful for managing code,
    documents, and project management tasks that should not be made
    public.
  - If you are not sure whether to make your repository public, or need a private repo, please email the [HelpDesk](mailto:autohelp+int+851+6545985337373134556@CFDE.groups.io) for help.

**3) Name the repository and add a description.**

  - Try to give your repository a name and a description that clearly
    communicate what the repository is for.
  - Please use our naming convention: lower case names, with words seperated by dashes
  - Names should be short, but informative. Consider whether new members will be able to find the repository without help.
  - Descriptions should explain the purpose and scope of the repository. 
    Consider whether new members will understand the purpose of the repository after reading the description.

**4) Decide who will have read access, write access, and admin access.**

  - We suggest read access to everyone by default.

  - Any relevant team members should be made admins on the repository, or
    given write access.

  - Anyone with write or admin access to a repository will automatically
    be subscribed to notifications about that repository by default
    (unless their Github notification settings have been modified).

  - Utilize existing teams in the CFDE Github organization to control
    access. You can find a [list of teams
    here](https://github.com/orgs/nih-cfde/teams) (click the "X teams" text
    on the right to see a list of sub-teams).

  - Please email the [HelpDesk](mailto:autohelp+int+851+6545985337373134556@CFDE.groups.io) if you need a new team created on
    Github.

**5) Decide whether branch protection is necessary.**

  - Branches can be protected in such a way that the main (master)
    branch requires (of pull requests) one human approval or requires
    passing automated tests for a pull request to be merged.
  - **IMPORTANT:** See the [Addendum](#addendum) below on branch
    protection.

**6) Add a `README.md` with at least a few sentences.**

  - Examples of good `README.md` files:
      - <https://github.com/nih-cfde/announcements>
      - <https://github.com/nih-cfde/organization>

**7) Add a `CONTRIBUTING.md` that explains how to contribute to the
repository.**

  - Sample `CONTRIBUTING.md`:
    <https://github.com/nih-cfde/organization/blob/master/CONTRIBUTING.md>


<a name="addendum"></a>

## Addendum: Branch Protection Instructions

Github offers branch protection mechanisms for any branch in a
repository.

The most common branch protection pattern is to have a "stable" or
"main" branch (usually the `master` branch) that does not allow anyone
to commit directly to the master branch. Users are required to make
changes by submitting pull requests. We also recommend a requirement
that all pull requests require at least 1 review/approval.

It is important that you **do not grant the ability to override the
branch protection mechanism, even to administrators.** If administrators
have the ability to override the branch protection mechanism, the web
interface will allow you to override this branch protection mechanism
only after warning you and requiring you to click a large red button.
However, from the command line, there is no such warning, and all
administrators will be able to commit directly to master from the
command line.

We recommend granting a **single person** with git expertise the
authority to override the branch protection mechanism, to prevent
accidental, unapproved commits to the master branch by administrators.

**Instructions:**

Go to Settings \> Branches

Check the box "Require pull request reviews before merging", and then
check the box "Include administrators"

To add individual exceptions, check the box "Restrict who can dismiss
pull request reviews" and add the individual who will be able to dismiss
pull request reviews and push directly to master.

Example:

<img width="738" alt="dcppc/internal repo screenshot"
src="https://user-images.githubusercontent.com/368075/44003884-13f7dc8a-9e0f-11e8-9574-a6d24a9ce734.png">
