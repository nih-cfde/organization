# GitHub Usage Guide

For help with *using* GitHub, for e.g. opening issues or making pull requests. If you need help changing GitHub notifications and other settings, please see the [GitHub section of the CFDE Communication Management Help Overview](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#github-help)


   - **[Definitions](GitHubUsage.md#definitions)**
   - **[Navigating our Organization](GitHubUsage.md#navigating-our-organization)**
   - **[Issues](GitHubUsage.md#issues)**
      - **[Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues)**
      - **[Opening New Issues](GitHubUsage.md#opening-new-issues)**
      - **[Commenting on Issues](GitHubUsage.md#commenting-on-issues)**
      - **[Referencing Issues](GitHubUsage.md#referencing-issues)**
      - **[Closing Issues](GitHubUsage.md#closing-issues)**
   - **[Pull Requests](GitHubUsage.md#pull-requests)**
      - **[Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests)**
      - **[Opening New Pull Requests](GitHubUsage.md#opening-new-pull-requests)**
      - **[Commenting on Pull Requests](GitHubUsage.md#commenting-on-pull-requests)**
      - **[Referencing Pull Requests](GitHubUsage.md#referencing-pull-requests)**
      - **[Reviewing Pull Requests](GitHubUsage.md#reviewing-pull-requests)**
      - **[Merging Pull Requests](GitHubUsage.md#merging-pull-requests)**
      - **[Closing Pull Requests](GitHubUsage.md#closing-pull-requests)**
   - **[Forking a Repository](GitHubUsage.md#forking-a-repository)**
   - **[Creating a New Repository Branch](GitHubUsage.md#creating-a-new-repository-branch)**
   - **[Searching](GitHubUsage.md#searching)**
   - **[Labels](GitHubUsage.md#labels)**

## Definitions

- Organization: Our GitHub Organization is https://github.com/nih-cfde This is the location on the web where you can access all of the CFDE github repositories. We also have an 'organization' repository, which is a folder that contains all the meta information about our Organization
- Repository: Each repository or 'repo' is a self-contained collection of documents and code. There can be any number of repositories in our Organization, and anyone in our group can make a new repository. See the [New Repository Guidelines](NewRepositoryGuide.md) for more info
- Team: Each member of our Organization will be assigned to one or more Teams. The Team(s) you are in determine what repositories you have edit access for. By default everyone has at least read access to all CFDE repositories. Teams can also be tagged into conversations and have other useful features. Anyone in our group can make new teams. 
- Pull Request: A Pull Request or 'PR' is the main way to share your own edits to documents in a repository
- Branch: Since many people might work on a document simultanously, when anyone makes an edit to a document GitHub makes that change on a different 'branch', so each person can make their own changes and then submit their version to the group for approval via a Pull Request
- Commit: Essentially saving. When you are making changes to a document in your branch, you need to commit your changes before you leave the page. If you are making a lot of changes, you can do many commits and submit all the changes on your branch as one Pull Request.
- Review Request: To ensure that errors aren't accidently introduced into important code and documents, all Pull Requests must be reviewed by at least one other person before they are merged into the official version
- Merge: Once you have submitted a Pull Request, and it has been approved via review, you can merge your changes, at which point your version of the document is the version displayed in the repository
- Issues: Issues are ways to make comments or requests in a repository

## Navigating our Organization

All Common Fund Data Ecosystem GitHub repositories are in the [nih-cfde](https://github.com/nih-cfde) GitHub organization.

## Issues

Issues can be used to keep track of bugs, enhancements, or other requests. A GitHub user can open a new Issue or view open Issues for any repository that user has access to. [More information](https://help.github.com/en/articles/about-issues)

### Accessing Repository Issues

1. Navigate to the GitHub repository which has the issues you are interested in viewing.
<img src="/images/repo-main-page.png" alt="Repo Main Page" width="400"/>

2. Sign into GitHub if not already signed in. Link in the top left.
<img src="/images/repo-main-page-sign-in.png" alt="Sign in arrow" width="400"/>

3. Select the `Issues` tab across the top of the repository page.
<img src="/images/repo-issues-tab.png" alt="Repo Issues Tab" width="400"/>

### Opening New Issues

1. See [Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues) for instructions to access issues in a GitHub repository.
2. Select the green "New Issue" button on the left side of the "Issues" page.
<img src="/images/repo-new-issue-button.png" alt="New Issue Button" width="400"/>

3. Enter Title and Comment for new issue.
<img src="/images/repo-new-issue.png" alt="New Issue" width="400"/>

4. Select green "Submit new issue" button.
<img src="/images/repo-new-issue-submit.png" alt="Submit New Issue" width="400"/>

### Commenting on Issues

1. See [Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues) for instructions to access issues in a GitHub repository.
2. Select the issue you want to comment on.
<img src="/images/repo-issue-list.png" alt="Repo Issues List" width="400"/>

3. Select the text box and type your comment.
<img src="/images/repo-issue-new-comment.png" alt="New comment" width="400"/>

4. Select the green "Comment" button at the bottom of the text box.
<img src="/images/repo-issue-comment-button.png" alt="New comment button" width="400"/>

5. You should now see your new comment in the issue with the comment box at the bottom.
<img src="/images/repo-issue-with-new-comment.png" alt="Issue with new comment" width="400"/>

### Referencing Issues

1. See [Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues) for instructions to access issues in a GitHub repository or see [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests.
2. Select the issue or pull request you want to comment on.
<img src="/images/repo-issue-list.png" alt="Repo Issues List" width="400"/>

3. Use the `#` symbol in the comment box to get a drop down of open issues in the repository. You can also type the issue number if known.
<img src="/images/repo-issue-ref_pop_up.png" alt="Reference Issue pop-up" width="400"/>
<img src="/images/repo-issue-ref_comment.png" alt="Reference Issue Comment" width="400"/>

4. Select the green "Comment" button at the bottom of the text box.
<img src="/images/repo-issue-comment-button.png" alt="New comment button" width="400"/>

5. You should now see your new comment in the issue with the comment box at the bottom.
<img src="/images/repo-issue-with-new-comment.png" alt="Issue with new comment" width="400"/>

### Closing Issues

1. See [Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues) for instructions to access issues in a GitHub repository.
2. Select the issue you want to close.
<img src="/images/repo-issue-list.png" alt="Repo Issues List" width="400"/>

3. Issues can be closed using either the `Close and comment` or `Close issue` buttons.

  * Type comment and select `Close and Comment` button.
<img src="/images/repo-issue-close-and-commit.png" alt="Close and comment issue" width="400"/>

  * Select `Close issue` button.
<img src="/images/repo-issue-close.png" alt="Close issue" width="400"/>

## Pull Requests

Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch. [More information](https://help.github.com/en/articles/about-pull-requests)

Pull Requests are used to merge Forked repositories or repository branches.

### Accessing Repository Pull Requests

1. Navigate to the GitHub repository which has the Pull Requests you are interested in viewing.
<img src="/images/repo-main-page.png" alt="Repo Main Page" width="400"/>

2. Sign into GitHub if not already signed in. Link in the top left.
<img src="/images/repo-main-page-sign-in.png" alt="Sign in arrow" width="400"/>

3. Select the `Pull Requests` tab across the top of the repository page.
<img src="/images/repo-pull-request-tab.png" alt="Pull Requests Tab" width="400"/>

### Opening New Pull Requests

1. See [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests in a GitHub repository.
2. Select green `New pull request` button on right side of screen.
<img src="/images/pull-request-new-button.png" alt="New pull request button" width="400"/>

3. Select branches to compare for the pull request. The first branch is the origional branch you are going to add your changes to. The second is the branch with your new changes.
<img src="/images/pull-request-select-branches.png" alt="pull request branches" width="400"/>

4. On the next screen, add a title and comment for the pull request you are creating.
<img src="/images/pull-request-add-info.png" alt="pull request title and comment" width="400"/>

5. Select the green `Create pull request` button on the bottom of the comment box.
<img src="/images/pull-request-create-with-comment.png" alt="pull request create" width="400"/>

6. The page will refresh with your newly created pull request.

### Commenting on Pull Requests

1. See [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests in a GitHub repository.
2. Select the pull request you want to comment on.
<img src="/images/pull-request-list.png" alt="Pull request list" width="400"/>

3. Select the text box and type your comment.
<img src="/images/pull-request-add-comment.png" alt="Pull request new comment" width="400"/>

4. Select the green "Comment" button at the bottom of the text box.
<img src="/images/pull-request-add-comment-button.png" alt="Pull request new comment button" width="400"/>

5. You should now see your new comment in the pull request with the comment box at the bottom.
<img src="/images/pull-request-with-new-comment.png" alt="Pull request with new comment" width="400"/>

### Referencing Pull Requests

1. See [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests in a GitHub repository.
2. 

### Reviewing Pull Requests

1. See [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests in a GitHub repository.
2. 

### Merging Pull Requests

1. See [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests in a GitHub repository.
2. 

### Closing Pull Requests

1. See [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests in a GitHub repository.
2. 

## Forking a Repository

A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project. [More information](https://help.github.com/en/articles/fork-a-repo)

1. Navigate to the GitHub repository and Sign into GitHub if not already signed in.
2. Select the `Fork` button on the top right of the repository page.
<img src="/images/repo-fork-button.png" alt="Fork repo button" width="400"/>

3. Select the location to Fork the repository into.
<img src="/images/repo-fork-location.png" alt="Fork repo location" width="400"/>

4. Wait while GitHub Forks the repository.
<img src="/images/repo-fork-in-progress.png" alt="Fork repo in progress" width="400"/>

5. The page will refresh to the new Forked repository.
<img src="/images/repo-new-forked.png" alt="Fork repo finished" width="400"/>

## Creating a New Repository Branch

Use a branch to isolate development work without affecting other branches in the repository. Each repository has one default branch, and can have multiple other branches. You can merge a branch into another branch using a pull request. [More information](https://help.github.com/en/articles/about-branches)

1. Navigate to the GitHub repository and Sign into GitHub if not already signed in.
2. Select list of branches using the `Branch: <name>` button.
<img src="/images/repo-select-branch-list.png" alt="Select Branches" width="400"/>

3. Type name of new branch in the text box, select `Create branch` button on pop up.
<img src="/images/repo-new-branch.png" alt="Create new branch" width="400"/>

4. The page will refresh and you are now viewing the branch you just created. You can see the branch name in the `Branch: <name>` botton.
<img src="/images/repo-name-new-branch.png" alt="View new branch" width="400"/>

## Searching
## Labels
