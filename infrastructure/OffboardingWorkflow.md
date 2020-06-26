# Workflow for offboarding members from services (requires admin rights to all resources)

To offboard ,a member (or someone from their team) must:
 - Fill out the [offboarding form](https://forms.gle/Gb5H6CAYCd8iVYKG8)
 
 We track those events, as well as our progress in adding them to our resources [here](https://docs.google.com/spreadsheets/d/1bY-P5ZrIOPDrDpzlXNrDnV96XqOnV_X9z9ur7t9Qkhk/edit?usp=sharing).

## Offboarding Overview
The Offboarding form will send notifications to coordination@CFDE.groups.io whenever the form is filled out. To request being added to coordination mailing list and receive notifications, send your request to the [helpdesk](mailto:coordination+int+1482+3914664481228082529@CFDE.groups.io).

A member of the coordination mailing list should begin the onboarding process for new forms *within 2 business days*. Full onboarding for each person is a typically a multi-day process, and can be done by multiple memebers of the coordination team, because we have to wait for each new onboardee to accept the invitations. The basic workflow is:

  - Remove them from our Google Group
  - Remove them from Slack
  - Remove them from GitHub
  - Add their name to the "Goodbye" list in the Weekly Announcements

## Offboarding Walkthrough
To offboard members, first navigate to the [Offboarding Reponses Google Sheet](https://docs.google.com/spreadsheets/d/1bY-P5ZrIOPDrDpzlXNrDnV96XqOnV_X9z9ur7t9Qkhk/edit?usp=sharing).
Individuals who have newly requested offboarding will not have data in the first four columns of the spreadsheet. Partially offboarded members will have some data.
  
Offboarding tasks should be completed (or checked up on) from left to right for each individual.

### Google Group removal

  If 'Removed from Google Group?' is unchecked:
   - Get the name of the person to be offboarded from column G
   - Find their name in the [Onboarding Responses form](https://docs.google.com/spreadsheets/d/16JcTqlkCRPqrSnykqshrVM2XLf_3HJJiPpAb7qBaOug/edit?usp=sharing)
     - You can search the form for their last name by hitting `command + f` on a Mac or `Ctrl + f` on Windows to open a search box
   - Copy their email address from column J, if they don't have one, use the email address in column I
   - Note their Title/Position from column P and affiliation from column O
   - Go to the correct Google Group management page: Most CFDE members are in [CFDE_Everyone](https://groups.google.com/forum/#!managemembers/cfde_everyone/members/active), however some members of Teams Brown or White will be in [CFDE_Admin](https://groups.google.com/forum/#!managemembers/cfde_admin/members/active)
     - (You can also reach those pages by going to [Google Groups](https://groups.google.com/forum/#!myforums), and choosing 'Manage members' for the appropriate group)
   - Find the email address of the person you want to offboard and click the box at the begining of their row. If you have more than one to remove from a given group, you can check multiple boxes
   - Click the `Actions` button near the top, center of the screen and choose 'Remove from group'
   - As soon as you've removed them from the Google Group, you should add them to the Goodbye list on the Announcements list. Go to https://github.com/nih-cfde/announcements/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+Announcements
   - Click on the issue called "Weekly Announcements"
   - Scroll to the bottom of the page to the text box.
   - Make the first line say `# Goodbye`
   - List the name and group affiliation of each person you added to Google Groups as in: `Brown: Amanda Charbonneau, Titus Brown`
   - Click the `Comment` button
   - Check the 'Removed from Google Group?' box for each person you removed

### Groups.io space removal

 If 'Removed from Groups.io?' is unchecked:
  - Copy their email from column I of the [Onboarding Responses form](https://docs.google.com/spreadsheets/d/16JcTqlkCRPqrSnykqshrVM2XLf_3HJJiPpAb7qBaOug/edit?usp=sharing)
   - Go to https://cfde.groups.io/g/General/members
  - Paste thier email into the 'search' box
  - Check the box on the left side of their name and click the 'Actions' button
  - In the drop down menu, choose 'Remove' 
  - In the dialogue box, choose 'Yes'
  - Check the 'Removed from Groups.io?' box for each person you removed (Groups.io will automatically remove them from Slack)
   
### GitHub removal

  If 'Removed from Github?' is unchecked:
  - Copy their GitHubID from column N of the [Onboarding Responses form](https://docs.google.com/spreadsheets/d/16JcTqlkCRPqrSnykqshrVM2XLf_3HJJiPpAb7qBaOug/edit?usp=sharing)
  - Note their Title/Position from column P and affiliation from column O of the [Onboarding Responses form](https://docs.google.com/spreadsheets/d/16JcTqlkCRPqrSnykqshrVM2XLf_3HJJiPpAb7qBaOug/edit?usp=sharing)
  - Go to https://github.com/orgs/nih-cfde/people
  - Paste their GitHubID into the 'Find a member' box (don't put an `@` in front of it)
  - Click on the gear icon on the right side of the screen and select 'Remove from organization'
  - Check the 'Removed from Github?' box for each person you removed on the [CFDE Offboarding form](https://docs.google.com/spreadsheets/d/1bY-P5ZrIOPDrDpzlXNrDnV96XqOnV_X9z9ur7t9Qkhk/edit#gid=1873329009). 

### Slack removal 
  - Admins can access Slack and change accounts [here](https://cfdeworkspace.slack.com/admin) to remove a user or change their e-mail. 
 
### Special removals for PMs, PIs and Admin contacts

If the person you are offboarding is a PI, PM or Administrative contact for *any* team, they may need to be removed from the [Points of Contact](https://github.com/nih-cfde/organization/blob/master/PointsOfContact.md) list:
  - Navigate to [Points of Contact](https://github.com/nih-cfde/organization/blob/master/PointsOfContact.md) on GitHub
  - If the person is listed, use the edit feature to remove them and issue a pull request. For help with pull requests, see the [GitHub Usage Guide](./GitHubUsage.md)


   
  

