## CFDE Communication Management Help Overview

We are using a number of services to communicate and share files:
  - [Github](https://github.com/nih-cfde/organization/new/master#github): Code sharing, organization and deliverables tracking
  - [groups.io](https://github.com/nih-cfde/organization/new/master#groupsio): mailing lists
  - [Google Drive Teams](https://github.com/nih-cfde/organization/new/master#google-drive): file sharing
  - [Slack](https://github.com/nih-cfde/organization/new/master#slack): Group chat, forum and instant private messaging

Depending on your role and needs, you may find that the default settings for these services
give you too many, or too few, notifications. On this page you will find instructions for 
altering common settings as well as links out to more detailed information. 

If you are having problems *accessing* these services, please see the [Onboarding Help](https://github.com/nih-cfde/organization/blob/master/OnboardingHelp.md)

## Table of Contents

- **[GitHub](https://github.com/nih-cfde/organization/new/master#github)**
   - **[Definitions](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#definitions)**
   - **[Changing Notifications](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#changing-notifications)**
       - **[Watching Settings](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#watching-settings)**
       - **[Notifications Settings](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#notification-settings)**
       - **[Subscriptions](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#subscriptions)**
       - **[Watching Repos and Teams](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#watching-repos-and-teams)**
- **[groups.io](https://github.com/nih-cfde/organization/new/master#groupsio)**
   - **[Getting Mail](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#getting-mail)**
   - **[Managing Subscriptions](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#managing-subscriptions)**
      - **[Join a Mailing List](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#join-a-mailing-list)**
      - **[Leave a Mailing List](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#leave-a-mailing-list)**
      - **[Change email frequency](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#altering-your-email-frequency)**
      - **[Create a new mailing list](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#creating-a-new-mailing-list)**
- **[Google Drive Teams](https://github.com/nih-cfde/organization/new/master#google-drive)**
- **[Slack](https://github.com/nih-cfde/organization/new/master#slack)**

### GitHub Help

#### Definitions

- Organization: Our GitHub Organization is https://github.com/nih-cfde This is the location on the web where you can access all of the CFDE github repositories. We also have an 'organization' repository, which is a folder that contains all the meta information about our Organization
- Repository: Each repository or 'repo' is a self-contained collection of documents and code. There can be any number of repositories in our Organization, and anyone in our group can make a new repository. See the [New Repository Guidelines](NewRepositoryGuide.md) for more info
- Team: Each member of our Organization will be assigned to one or more Teams. The Team(s) you are in determine what repositories you have edit access for. By default everyone has at least read access to all CFDE repositories. Teams can also be tagged into conversations and have other useful features. Anyone in our group can make new teams. 
- Pull Request: A Pull Request or 'PR' is the main way to share your own edits to documents in a repository
- Branch: Since many people might work on a document simultanously, when anyone makes an edit to a document GitHub makes that change on a different 'branch', so each person can make their own changes and then submit their version to the group for approval via a Pull Request
- Commit: Essentially saving. When you are making changes to a document in your branch, you need to commit your changes before you leave the page. If you are making a lot of changes, you can do many commits and submit all the changes on your branch as one Pull Request.
- Review Request: To ensure that errors aren't accidently introduced into important code and documents, all Pull Requests must be reviewed by at least one other person before they are merged into the official version
- Merge: Once you have submitted a Pull Request, and it has been approved via review, you can merge your changes, at which point your version of the document is the version displayed in the repository
- Issues: Issues are ways to make comments or requests in a repository

#### Changing Notifications

By default, your Github account will automatically 'watch' repositories and teams that you are added to, and by default it will
email you notifications each time there is a PR, Commit, Review Request, Issue or Comment on any of those repositories, and also
whenever a new repository is made in our Organization. 

However, unless you are actively working in a repository, you probably don't need to be notified of every change. 
There are two places where you will need to change your settings to reduce the number of times GitHub contacts you.

##### Watching Settings

First, make sure you are only watching repos that you are actively interested in tracking. Since everyone in our Organization has at least read access to all our repos, you'll be watching all of them, regardless of how they relate to your role. You can see all the repos you are watching at this link: https://github.com/watching
You should get something like this:

<img src="/images/watching.png" alt="Watch List" width="600"/>

For each repository in the list, decide how often you want to hear about it. There are four options: 'Not Watching', 'Releases Only', 'Watching' and 'Ignoring'
<img src="/images/watchingoptions.png" alt="Watching Options" width="600"/>

For repositories that you actively work in, and would like to be notified of things like PRs and conversations, choose 'Watching'. You can set what types of actions send you notifications using the [Notification Settings](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#notification-settings) instructions below.

For most other repositories, you will likely want to set them to 'Not Watching' or 'Releases Only'. Both of these options will
only send you notifications if someone specifically invokes you or your team in a PR, comment, etc.

If you are sure you will never be interested in a repository, you can set it to 'Ignoring'. This will stop all notifications, even if people specifically mention you. As this is a collaborative project and your colleagues might request your input in places you didn't expect, we do not advise setting CFDE repos to 'Ignoring'. 

##### Notification Settings

Once you have determined which repos you want to watch, you can change what triggers watching notifications, as well as
edit the default behavior of watching everything. You edit these settings at: https://github.com/settings/notifications 

Your current notification settings will look like this:

<img src="/images/toomanynotifications.png" alt="Notification Options" width="400"/>

**Automatic watching section**
To stop GitHub from automatically watching repos in the future, you should uncheck the 'Automatically watch repositories' box. 
You can also stop GitHub from automatically watching any new Teams.

Note that if you uncheck these boxes you will have to specifically turn on 'watching' for specific repos and teams you become interested in later ([See Watching Repos and Teams](https://github.com/nih-cfde/organization/blob/master/CommunicationManagementHelp.md#watching-repos-and-teams) below). 

**Participating section**
Here you can choose where you receive notifications for discussions you are *actively participating in*. This includes things like PRs or Issues you made, PRs or Issues your have reviewed or commented on, and other conversations where your name is mentioned.
You can get them either only by email, only at your GitHub notifications page (https://github.com/notifications) or get them in both places.

**Watching section**
Here you can choose where you receive notifications for discussions you are *watching*. This includes things like PRs or Issues on repositories you are watching.
You can get them either only by email, only at your GitHub notifications page (https://github.com/notifications) or get them in both places.

Settings to try: Have 'Participating' notifications only emailed to you so you always see them right away, but have 'Watching' notifications only visible on the web, so you can look through them all once a week.

**Vulnerability alerts section**
We suggest checking only the 'Web' option. Most of our repositories don't contain running code, and so won't have security alerts anyway.

**Email notification preferences section**
Here, you can further customize what types of events trigger your alerts. 

- Comments on Issues and Pull Requests: Unchecking this box will stop general notifications about comments on Issues and PRs in your watched repos
- Pull Request reviews: Unchecking this box will stop general notifications about new Review Requests on repos your watched repos
- Pull Request pushes: Unchecking this box will stop general notifications about Merges in your watched repos
- Include your own updates: Checking this box will cause GitHub to email you notifications about things you did. Unchecking this box will stop notifications about your own actions.

Unchecking all of these boxes would cause you to only get email alerts for conversations where you are specifically mentioned or actively participating. 

For more information about notifications see the [GitHub Notification About page](https://help.github.com/en/articles/about-notifications) or the [GitHub Getting Started with Notifications page](https://help.github.com/en/articles/getting-started-with-notifications)

##### Subscriptions
You can make more fine-grained changes to your notifications by subscribing, or unsubscribing, from specific conversations, PRs, issues, etc; regardless of whether you are watching the repo they happen in. For more information, see the [Subscriptions help page](https://help.github.com/en/articles/subscribing-to-and-unsubscribing-from-notifications) from Github.

##### Watching Repos and Teams

If you have turned off auto-watching, you will need to manually start watching new repos that you would like to follow.

To watch a new repository:
- Go to the main page of that repository (for our project management repo that would be: https://github.com/nih-cfde/project-management)
- In the upper right corner click the `Watch` button and select 'Watching'

See [the GitHub help](https://help.github.com/en/articles/watching-and-unwatching-repositories#watching-a-single-repository) for more info

To watch a new team:
- Navigate to the nih-cfde Teams page: https://github.com/orgs/nih-cfde/teams
- Click the name of the Team you are interested in (you may have to use the arrows on the right to uncollapse the team lists)
- On the left side of the screen, click the `Watch` button and select 'Watching'

See [the GitHub help](https://help.github.com/en/articles/watching-and-unwatching-team-discussions#watching-a-single-teams-discussions)

If you did not find the solution to your problem on this page, please email the [HelpDesk](mailto:autohelp+int+851+6545985337373134556@CFDE.groups.io)

### groups.io Help

We are using groups.io to manage our mailing lists. Our overall groups.io account is restricted access and can only be joined 
by filling out the [onboarding form](https://forms.gle/wsBAYevSQNVfG5eF9), however most mailing lists are unrestricted to members, and you can edit your subscriptions at any time. See the list of [available mailing lists here](./MailingLists.md).

#### Getting Mail
If you are not receiving or intermittedly receiving, mail, you may need to add CFDE@groups.io to your safe sender list in your email client’s contacts.

You should also check your subscription settings by:
- Navigating to https://cfde.groups.io/g/General
- Clicking on `Your Groups` at the top of the page and selecting the specific list you are having problems with
- Clicking on `Subscription` near the top left of the screen
- Ensuring that your 'Email Delivery' option is correct. Most users will want 'Individual Messages', 'Full Featured Digest', or 'Daily Summary', which will email you every message, messages in groups of 12, or a summary of all the days messages, respectively. 

#### Managing Subscriptions

##### Join a mailing list
You can add yourself to a mailing list by:
- Navigating to https://cfde.groups.io/g/General
- Clicking on `Subgroups` on the left side of the screen
- Scrolling down to Subgroups You Can Join'
- Clicking the name of the mailing list you'd like to join
- Clicking the `Join This Group` or `Apply For Membership In This Group` button near the bottom of the page. Groups with a `Join This Group` button will add you instantly. `Apply For Membership In This Group` groups are restricted and your request must be approved by a moderator.

##### Leave a mailing list
You can leave a mailing list by:
- Navigating to https://cfde.groups.io/g/General
- Clicking on `Subgroups` on the left side of the screen
- Finding the list in 'Subgroups You Belong To'
- Clicking the name of the mailing list you'd like to leave
- Clicking on `Subscription` near the top right of the screen
- Clicking on the `Unsubscribe` button at the bottom of the page

##### Changing your email frequency
You can alter your subscription to a mailing list you already receive by:
- Navigating to https://cfde.groups.io/g/General
- Clicking on `Your Groups` at the top of the page and selecting the specific list you are having problems with
- Clicking on `Subscription` near the top right of the screen
- Ensuring that your 'Email Delivery' option is correct. Most users will want 'Individual Messages', 'Full Featured Digest', or 'Daily Summary', which will email you every message, messages in groups of 12, or a summary of all the days messages, respectively. 

##### Creating a new mailing list
To create a new mailing list:
- Navigate to https://cfde.groups.io/g/General
- Click on `Subgroups` on the left side of the screen
- Click on the `+ Create Subgroup`
- For your 'Subgroup Email Address', choose something short but descriptive
- Add a description to help other users decide whether they want to join your list
- For 'Visibility', we recommend choosing 'Subgroup listed in parent group, messages viewable by parent group members'. This will keep your archive private to the CFDE, but allow members to search your archives without joining
- Accept the warning about making messages private
- Click on `+ Create Subgroup`
- Make an issue or PR to update https://github.com/nih-cfde/organization/blob/master/MailingLists.md
- Consider advertising your new list by posting it in General on Slack or submitting it the 'Announcements' mailing list

If you did not find the solution to your problem on this page, please email the [HelpDesk](mailto:autohelp+int+851+6545985337373134556@CFDE.groups.io)

### Google Drive Help
If you did not find the solution to your problem on this page, please email the [HelpDesk](mailto:autohelp+int+851+6545985337373134556@CFDE.groups.io)



### Slack Help

If you did not find the solution to your problem on this page, please email the [HelpDesk](mailto:autohelp+int+851+6545985337373134556@CFDE.groups.io)
