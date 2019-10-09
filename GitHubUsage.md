# GitHub User Guide

This guide provides instructions for *using* GitHub, such as opening issues or making pull requests. If you need help changing GitHub notifications and other settings, please see the [GitHub Help section of the CFDE Communication Management Help Overview.](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#github-help)


   - **[Definitions](GitHubUsage.md#definitions)**
   - **[Navigating our Organization](GitHubUsage.md#navigating-our-organization)**
   - **[Issues](GitHubUsage.md#issues)**
      - **[Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues)**
      - **[Opening New Issues](GitHubUsage.md#opening-new-issues)**
      - **[Commenting on Issues](GitHubUsage.md#commenting-on-issues)**
      - **[Referencing Issues](GitHubUsage.md#referencing-issues)**
      - **[Closing Issues](GitHubUsage.md#closing-issues)**
   - **[Forking a Repository](GitHubUsage.md#forking-a-repository)**
   - **[Creating a New Repository Branch](GitHubUsage.md#creating-a-new-repository-branch)**
   - **[Pull Requests](GitHubUsage.md#pull-requests)**
      - **[Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests)**
      - **[Opening New Pull Requests](GitHubUsage.md#opening-new-pull-requests)**
      - **[Commenting on Pull Requests](GitHubUsage.md#commenting-on-pull-requests)**
      - **[Referencing Pull Requests](GitHubUsage.md#referencing-pull-requests)**
      - **[Reviewing Pull Requests](GitHubUsage.md#reviewing-pull-requests)**
      - **[Merging Pull Requests](GitHubUsage.md#merging-pull-requests)**
      - **[Closing Pull Requests](GitHubUsage.md#closing-pull-requests)**
   - **[Searching](GitHubUsage.md#searching)**
   - **[Labels](GitHubUsage.md#labels)**
      - **[Adding Labels to an Issue or Pull Request](GitHubUsage.md#adding-labels-to-an-issue-or-pull-request)**

## Definitions

| Term | Definition |
| ------------- |:-------------|
| Branch | Since many people can work on a document simultaneously, when anyone edits a document, GitHub makes that change on a different "branch" so each person can make their own changes and then submit their version to the group for approval via a Pull Request. |
| Commit | Essentially, this is synonymous with saving. When you are making changes to a document in your branch, you need to commit your changes before you leave the page. If you are making a lot of changes, you can do many commits and submit all the changes on your branch as one Pull Request. |
| Issues | Issues are ways to make comments or requests in a repository. |
| Merge | Once you have submitted a Pull Request and it has been approved via review, you can merge your changes, at which point your version of the document is the version displayed in the repository. |
| Organization | Our GitHub organization is https://github.com/nih-cfde. This is the location on the web where you can access all of the CFDE GitHub repositories. We also have a repository called "organization", which is a folder that contains all the meta information about our organization. |
| Pull Request | A Pull Request or "PR" is the main way to share your own edits to documents in a repository. |
| Repository | Each repository or "repo" is a self-contained collection of documents and code. There can be any number of repositories in our organization, and anyone in our group can make a new repository. See the [Checklist for Adding a New Repository](NewRepositoryGuide.md) for more information. |
| Review Request | To ensure that errors are not accidently introduced into important code and documents, all Pull Requests must be reviewed by at least one other person before they are merged into the official version. |
| Team | Each member of our organization will be assigned to one or more teams. The team(s) you are in determines what repositories you have edit access for. By default, everyone has at least read access to all CFDE repositories. Teams can also be tagged into conversations. Anyone in our group can make new teams. |

## Navigating our Organization

All Common Fund Data Ecosystem GitHub repositories are in the [nih-cfde](https://github.com/nih-cfde) GitHub organization.

## Issues

Issues can be used to keep track of bugs, enhancements, or other requests. A GitHub user can open a new issue or view open issues for any repository that the user has access to. See the [About Issues](https://help.github.com/en/articles/about-issues) help page for more information.

### Accessing Repository Issues

1. Navigate to the GitHub repository that has the issues you are interested in viewing.

<img src="images/repo-main-page.png" alt="Repo Main Page" width="400"/>

2. Sign in to GitHub using the link in the top right.

<img src="images/repo-main-page-sign-in.png" alt="Sign in arrow" width="400"/>

3. Select the Issues tab at the top of the repository page.

<img src="images/repo-issues-tab.png" alt="Repo Issues Tab" width="400"/>

### Opening New Issues

1. See [Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues) for instructions to access issues in a GitHub repository.
2. Click the green "New Issue" button on the right side of the Issues page.

<img src="images/repo-new-issue-button.png" alt="New Issue Button" width="400"/>

3. Enter the Title and Comment for the new issue.

<img src="images/repo-new-issue.png" alt="New Issue" width="400"/>

4. Click the green "Submit new issue" button.

<img src="images/repo-new-issue-submit.png" alt="Submit New Issue" width="400"/>

### Commenting on Issues

1. See [Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues) for instructions to access issues in a GitHub repository.
2. Select the issue you want to comment on.

<img src="images/repo-issue-list.png" alt="Repo Issues List" width="400"/>

3. Select the text box and type your comment.

<img src="images/repo-issue-new-comment.png" alt="New comment" width="400"/>

4. Click the green "Comment" button at the bottom of the text box.

<img src="images/repo-issue-comment-button.png" alt="New comment button" width="400"/>

5. You should now see your new comment in the issue with the comment box at the bottom.

<img src="images/repo-issue-with-new-comment.png" alt="Issue with new comment" width="400"/>

### Referencing Issues

1. See [Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues) for instructions to access issues in a GitHub repository or see [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests.
2. Select the issue or pull request you want to comment on.

<img src="images/repo-issue-list.png" alt="Repo Issues List" width="400"/>

3. Use the # symbol in the comment box to view a drop-down of open issues in the repository. You can also type the issue number, if known.

<img src="images/repo-issue-ref_pop_up.png" alt="Reference Issue pop-up" width="400"/>

<img src="images/repo-issue-ref_comment.png" alt="Reference Issue Comment" width="400"/>

4. Click the green "Comment" button at the bottom of the text box.

<img src="images/repo-issue-comment-button.png" alt="New comment button" width="400"/>

5. You should now see your new comment in the issue with the comment box at the bottom.

<img src="images/repo-issue-with-new-comment.png" alt="Issue with new comment" width="400"/>

### Closing Issues

1. See [Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues) for instructions to access issues in a GitHub repository.
2. Select the issue you want to close.

<img src="images/repo-issue-list.png" alt="Repo Issues List" width="400"/>

3. Issues can be closed using either the "Close and comment" or "Close issue" buttons.

  a. Type your comment and click the "Close and Comment" button.

<img src="images/repo-issue-close-and-commit.png" alt="Close and comment issue" width="400"/>

  b. Click the "Close issue" button.

<img src="images/repo-issue-close.png" alt="Close issue" width="400"/>

## Forking a Repository

A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project. See the [Fork a Repo](https://help.github.com/en/articles/fork-a-repo) help page for more information.

1. Navigate to the GitHub repository and sign in to GitHub.
2. Click the "Fork" button on the top right of the repository page.

<img src="images/repo-fork-button.png" alt="Fork repo button" width="400"/>

3. Select the location to fork the repository into.

<img src="images/repo-fork-location.png" alt="Fork repo location" width="400"/>

4. Wait while GitHub forks the repository.

<img src="images/repo-fork-in-progress.png" alt="Fork repo in progress" width="400"/>

5. The page will refresh to the new forked repository.

<img src="images/repo-new-forked.png" alt="Fork repo finished" width="400"/>

## Creating a New Repository Branch

Use a branch to isolate development work without affecting other branches in the repository. Each repository has one default branch and can have multiple other branches. You can merge a branch into another branch using a Pull Request. See the [About Branches](https://help.github.com/en/articles/about-branches) help page for more information.

1. Navigate to the GitHub repository and sign in to GitHub.
2. Select the list of branches using the "Branch: <name>" button.

<img src="images/repo-select-branch-list.png" alt="Select Branches" width="400"/>

3. Type the name of the new branch in the text box and click the "Create branch: < new branch name >" highlighted block.

<img src="images/repo-name-new-branch.png" alt="Create new branch" width="400"/>


4. The page will refresh and the branch you just created displays. You can see the branch name in the "Branch: < name >" button.

<img src="images/repo-new-branch.png" alt="View new branch" width="400"/>

## Pull Requests

Pull Requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a Pull Request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch. See the [About Pull Requests](https://help.github.com/en/articles/about-pull-requests) help page for more information.

Pull Requests are used to merge forked repositories or repository branches.

### Accessing Repository Pull Requests

1. Navigate to the GitHub repository that has the Pull Requests you are interested in viewing.

<img src="images/repo-main-page.png" alt="Repo Main Page" width="400"/>

2. Sign in to GitHub using the link in the top right.

<img src="images/repo-main-page-sign-in.png" alt="Sign in arrow" width="400"/>

3. Select the "Pull Requests" tab at the top of the repository page.

<img src="images/repo-pull-request-tab.png" alt="Pull Requests Tab" width="400"/>

### Opening New Pull Requests

1. See [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests in a GitHub repository.
2. Click the green "New pull request" button on right side of page.

<img src="images/pull-request-new-button.png" alt="New pull request button" width="400"/>

3. Select the branches to compare for the Pull Request. The first branch is the original branch to which you are going to add your changes. The second branch is the branch with your new changes.

<img src="images/pull-request-select-branches.png" alt="pull request branches" width="400"/>

4. Enter the Title and Comment for the Pull Request you are creating.

<img src="images/pull-request-add-info.png" alt="pull request title and comment" width="400"/>

5. Click the green "Create pull request" button on the bottom of the comment box.

<img src="images/pull-request-create-with-comment.png" alt="pull request create" width="400"/>

6. The page will refresh with your newly created Pull Request.

### Commenting on Pull Requests

1. See [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests in a GitHub repository.
2. Select the Pull Request on which you want to comment.

<img src="images/pull-request-list.png" alt="Pull request list" width="400"/>

3. Select the text box and type your comment.

<img src="images/pull-request-add-comment.png" alt="Pull request new comment" width="400"/>

4. Click the green "Comment" button at the bottom of the text box.

<img src="images/pull-request-add-comment-button.png" alt="Pull request new comment button" width="400"/>

5. You should now see your new comment in the Pull Request with the comment box at the bottom.

<img src="images/pull-request-with-new-comment.png" alt="Pull request with new comment" width="400"/>

### Referencing Pull Requests

1. See [Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues) for instructions to access issues in a GitHub repository or see [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests.
2. Select the issue or Pull Request on which you want to comment.

<p float="left">
   <img src="images/pull-request-list.png" alt="Pull request list" width="300"/>
   <img src="images/repo-issue-list.png" alt="Repo Issues List" width="300"/>
</p>

3. Use the # symbol in the comment box to view a drop-down of open issues and open pull requests in the repository. You can also type the issue or pull request number, if known.

<p float="left">
   <img src="images/pull-request-ref-in-pr.png" alt="Reference in PR" width="300" />
   <img src="images/pull-request-ref-in-issue.png" alt="Reference PR in issue" width="300" />
</p>

4. Click the green "Comment" button at the bottom of the text box.

<img src="images/pull-request-ref-in-pr-comment.png" alt="New comment button" width="400"/>

5. You should now see your new comment in the issue or pull request with the comment box at the bottom.

<p float="left">
   <img src="images/pull-request-ref-in-pr-hover.png" alt="Reference PR in PR" width="300">
   <img src="images/pull-request-ref-issue-comment.png" alt="Reference PR Issue" width="300"/>
</p>

### Reviewing Pull Requests

1. See [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests in a GitHub repository.
2. GitHub users added to review a Pull Request will be listed on the right side of the page and in the center of the page as you scroll down.

<p float="left">
   <img src="images/pull-request-reviewers.png" alt="PR Reviewrs list" width="300">
   <img src="images/pull-request-review-in-line.png" alt="PR reviewer in-line" width="300"/>
</p>

3. If you are listed as a reviewer, click the "Add your review" button at the top of the Pull Request page.

<img src="images/pull-request-add-your-review-button.png" alt="PR add review button" width="400">

4. Enter comments in the text box, select the correct radio button, and click the "Submit review" button at the bottom of the box.

<img src="images/pull-request-review-text.png" alt="PR review text box" width="400">

5. Your review will display on the Pull Request page.

<img src="images/pull-request-with-review.png" alt="PR with review" width="400">

### Merging Pull Requests

1. See [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests in a GitHub repository.
2. Click the "Merge pull request" button on the Pull Request page.

<img src="images/pull-request-merge-button.png" alt="PR merge button" width="400"/>

3. Enter a comment and/or title.

<img src="images/pull-request-confirm-merge.png" alt="PR confirm merge" width="400"/>

4. Click the "Confirm merge" button.

<img src="images/pull-request-confirm-merge-button.png" alt="PR confirm merge button" width="400"/>

5. Delete the branch the changes were on with the "Delete branch" button. This keeps the list of branches in your repository tidy.

<img src="images/pull-request-delete-branch-button.png" alt="PR delete branch button" width="400"/>

6. A confirmation message will display in the Conversation tab when the branch is successfully deleted.

<img src="images/pull-request-deleted-branch.png" alt="PR deleted branch" width="400"/>


### Closing Pull Requests

You may choose to close a pull request without merging it into the upstream branch. This can be handy if the changes proposed in the branch are no longer needed, or if another solution has been proposed in another branch. [More Information](https://help.github.com/en/articles/closing-a-pull-request)

When closing a Pull Request without merging, both branches will still exist in the repository. However, your changes will only exist on the origional branch.

1. See [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests in a GitHub repository.
2. Click the "Close pull request" button under the text box at the bottom of the Pull Request page.

<img src="images/pull-request-close.png" alt="Closed pullr request" width="400"/>

## Searching

Many different powerful ways of searching GitHub exist. See the [About Searching on GitHub](https://help.github.com/en/articles/about-searching-on-github) help page for more information.

Use the GitHub search box to:

<img src="images/search-box.png" alt="GitHub search box" width="400"/>

* Search within a repository:

<img src="images/search-repo.png" alt="Search within a repo" width="400"/>

* Search within an organization:

<img src="images/search-in-org.png" alt="Search within an organization" width="400"/>

* Search results:

<img src="images/search-results.png" alt="Search results" width="400"/>

## Labels

Labels on GitHub help you organize and prioritize your work. You can apply labels to issues and Pull Requests to signify priority, category, or any other information you find useful. See the [About Labels](https://help.github.com/en/articles/about-labels) help page for more information.

### Adding Labels to an Issue or Pull Request

1. See [Accessing Repository Issues](GitHubUsage.md#accessing-repository-issues) for instructions to access issues in a GitHub repository or see [Accessing Repository Pull Requests](GitHubUsage.md#accessing-repository-pull-requests) for instructions to access Pull Requests.
2. Select the gear icon next to the "Labels" title on the right side of the screen.

<img src="images/labels-available.png" alt="Available labels" width="400"/>

3. Click on the labels to apply them to the Issue or Pull Request.

<img src="images/labels-selected.png" alt="Selected labels" width="400"/>

4. Click somewhere else on the page for the labels to be applied.

<img src="images/labels-applied.png" alt="Applied labels" width="400"/>
