# Workflow for onboarding new members to services (requires admin rights to all resources)

To fully onboard, a new member must:
 - Fill out the onboarding form
 - Accept our GitHub invite
 - Accept our Slack invite
 
 We track those events, as well as our progress in adding them to our resources [here](https://docs.google.com/spreadsheets/d/16JcTqlkCRPqrSnykqshrVM2XLf_3HJJiPpAb7qBaOug/edit?usp=sharing).

## Onboarding Overview
The Onboarding form should be checked and updated at least every other business day. Onboarding each person is a typically a multi-day process, because you have to wait for them to accept your invitations. The basic workflow is:
  
  - Add them to our Google Group, and send them an invitation GitHub
  - Add their name to the "Welcome" list in the Weekly Announcements
  - Add them to the MPQ form
  - Add them to the correct mailing lists
  - Wait for them to accept the invitations

## Onboarding Walkthrough
To onboard new members, or to continue boarding partially onboarded members, first navigate to the [Onboarding Reponses Google Sheet](https://docs.google.com/spreadsheets/d/16JcTqlkCRPqrSnykqshrVM2XLf_3HJJiPpAb7qBaOug/edit?usp=sharing).
  Individuals who have newly requested onboarding will not have checks in the first six columns of the spreadsheet. Partially onboarded members will have some boxes checked.
  
  Onboarding tasks should be completed (or checked up on) from left to right for each individual.

### Google Group adds

  If 'Added to Google Group?' is unchecked:
   - Copy their email address from column K, if they don't have one, use the email address in column J
   - Note their Title/Position from column Q and affiliation from column P
   - Decide what Google Permissions group to add them to:
      - For members of Teams Brown or White who are working on infrastructure or data access management, choose [CFDE_Admin](https://groups.google.com/forum/#!managemembers/cfde_admin/add)
      - For everyone else, choose [CFDE_Everyone](https://groups.google.com/forum/#!managemembers/cfde_everyone/add)
   - (You can also reach those pages by going to [Google Groups](https://groups.google.com/forum/#!myforums), choosing 'Manage members' for the appropriate group, and then clicking 'Direct add members' on the left side of the screen.)
   - Enter the email address of the person you want to onboard. If you have more than one to add to a given group, you can add multiple, comma-seperated, email addresses
   - Ensure that the welcome message box is filled correctly (see below), then click `Add` at the top of the screen
   - As soon as you've added them to the Google Group, you should add them to the Welcome list on the Announcements list. Go to [the issues for the announcements repo](https://github.com/nih-cfde/announcements/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+Announcements)
   - Click on the issue called "Weekly Announcements"
   - Scroll to the bottom of the page to the text box.
   - Make the first line say `# Welcome`
   - List the name and group affiliation of each person you added to Google Groups as in: `Brown: Amanda Charbonneau, Titus Brown`
   - Click the `Comment` button
   - Check the 'Added to Google Group?' box for each person you added

#### Google Group Welcome Messages

Google groups should cache the correct welcome messages, however you can copy/paste in one from below if they get erased:

##### Admin
```
Welcome to the CFDE working group. 

You have been added to Admin. You will have: 

- Edit access to CFDE_Everyone- day to day documents for the CFDE 
- Edit access to CFDE_Admin- documents for administration of CFDE infrastructure 

You can access these groups in your google drive under Team Drives 

If you have any problems, please email our help desk mailto:autohelp+int+851+6545985337373134556@CFDE.groups.io 

- CFDE Onboarding Team
```
##### Everyone

```
Welcome to the CFDE working group. 

You have been added to Everyone. You will have: 

- Edit access to CFDE_Everyone- day to day documents for the CFDE 
- View access to CFDE_Admin- documents for administration of CFDE infrastructure 

You can access these groups in your google drive under Team Drives 

If you have any problems, please email our help desk mailto:autohelp+int+851+6545985337373134556@CFDE.groups.io 

- CFDE Onboarding Team
```

### Slack space adds

As of 7/15/2019 new members are automatically sent a Slack invitation by Groups.io

### Add to Mailing lists

If 'Mailing Lists Assigned??' is unchecked:

 - Copy their email address from column K, if they don't have one, use the email address in column J
 - Copy their name from column L
 - Note the mailing lists they requested to join in column Q (see NOTE1 for help)
 - Got to [direct add for the general mailing list](https://cfde.groups.io/g/General/directadd)
 - Paste the following text in the 'Customize Message' box:
 
 ```
 To complete your access, you'll need to accept the invitation to join our GitHub repository nih-cfde

If you do not receive your invitation or have are having trouble with our resources, visit our Onboarding Help
or email the HelpDesk 

For help using all of our communication resources visit our Communication Management Help page

Please remember that all interactions in the CFDE Google Drive spaces, Github repositories, Slack, groups.io and any other CFDE managed spaces are bound by the [CFDE Code of Conduct](./CODEOFCONDUCT.md). By participating in any of these community spaces you are agreeing to abide by these rules.

All documents in the CFDE Google Drives and GitHub repositories are assumed to be under the [CFDE License](./LICENSE.md) unless another license is specified in the document.

- CFDE Onboarding Team
```

 - Check the boxes for their selected lists (you can do multiple members at a time)
 - Add their name and address to the 'Emails' box in this format: `Name <email@example.com>`
 - Click `+ Add Members`
 - Check the 'Mailing Lists Assigned??' box for each person you added
 
     NOTE1: It's basically impossible to read column R for members that choose more than one list.
     It's much easier to read their choices directly off their form. To do that:
       
      - Go to [the form view for onboarding](https://docs.google.com/forms/d/1sFY6y2eHB3PS0HayEyxXtZOrBJV7lfT8thJ8bL9wKqQ/edit#responses)
      - Click on the 'Individual' tab
      - Click where it says 'achar@ucdavis.edu'. That will open a selection box where you can choose the email address of the member you're working on
      - Choose the right email address
      - Scroll to the bottom of their form to the 'Mailing List Options' section      
   
### GitHub adds

  If 'GitHub Invite Sent?' is unchecked:
  - Copy their GitHubID from column O
  - Note their Title/Position from column Q and affiliation from column P
  - Go to [the people list on GitHub](https://github.com/orgs/nih-cfde/people)
  - Click `Invite Member` or `Buy more` (it will only show one or the other)
    
  If you clicked `Buy more`:
  - Type in the number of seats (users) you want to add today
  - Click 'Add seats'
  - Click `Invite Member` and follow the instructions below
  
  If you clicked `Invite Member`:
  - Paste thier GitHubID into the box (don't put an `@` in front of it)
  - Click on the rendered version of their GitHubID that pops up. Be sure it's the right person!
  - Click `Invite`
  - Scroll down and click 'Show all XX teams'
  - Based on their Title/Position and affiliation, add them to as many teams as is appropriate
  - Click `Send Invite`
  - Check the 'GitHub Invite Sent?' box for each person you added

 ### Add to MPQ
 
 If 'Added to MQP as of?' is blank:
 - Check their Affiliation(s) in column P, only members of the Tech Teams (Brown, Foster, Kesselman, Ma’ayan, O'Connor, Sansone and White) need to be added to the MPQ
 - Note the name and affilitation for each person you need to add (columns L and P)
 - Navigate to [the MPQs folder in CFDE Admin on Google](https://drive.google.com/drive/u/0/folders/1G7omyAgRSQr-n6F4o3HWUKcRm_cvoOHJ)
 - Find the MPQ that is due this month and open the form for editing
 - Scroll down to the correct Tech Team
 - Click on the last person listed in that Tech Team, the one right before the 'What DCC interactions has your team had this month?' question
 - The individuals question should switch to editing mode. You may have to click it more than once
 - At the bottom of their section, click on the copy icon. It looks like two, mostly overlapping rectangles
 - You should now have two copies of that individuals questions. Copy the new team member over the name in the new copy
 - Click anywhere else on the screen
 - Add the correct month_year in the 'Added to MQP as of?' column for each person you added

### Special additions for PMs, PIs and Admin contacts

If the person you are onboarding is a PI, PM or Administrative contact for *any* team, they should be added to the [Points of Contact](https://github.com/nih-cfde/organization/blob/master/PointsOfContact.md) list:
  - Navigate to [Points of Contact](https://github.com/nih-cfde/organization/blob/master/PointsOfContact.md) on GitHub
  - Use the edit feature to add them and issue a pull request. For help with pull requests, see the [GitHub Usage Guide](./GitHubUsage.md)


### Check Slack Invite

If 'Slack Invite Accepted?' is unchecked:
  - Go to [the admin page for slack](https://cfdeworkspace.slack.com/admin/invites#pending) (you may need to log into your Slack account)
  - If their invitation has moved to 'Accepted Invitations', click the checkbox
  - You can search for them using their email address in column J
  - Check the 'Slack Invite Accepted?' box for each person you added

 ### Check GitHub Invite
 
 If 'GitHub Invite Accepted?' is unchecked:
  - Go to [the people list on GitHub](https://github.com/orgs/nih-cfde/people)
  - Click on 'X pending invitations'. It will be just below the `Invite member` button.
  - Use the dialogue box to update 'GitHub Invite Accepted?' checkmarks
  
  

   
   
  
