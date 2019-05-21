# Workflow for offboarding members from services (requires admin rights to all resources)

To offboard ,a member (or someone from their team) must:
 - Fill out the [offboarding form](https://forms.gle/Gb5H6CAYCd8iVYKG8)
 
 We track those events, as well as our progress in adding them to our resources [here](https://docs.google.com/spreadsheets/d/1bY-P5ZrIOPDrDpzlXNrDnV96XqOnV_X9z9ur7t9Qkhk/edit?usp=sharing).

## Offboarding Overview
The Offboarding form should be checked and updated at least every other business day. Offboarding each person is very quick, and all steps for a given person should be done all at once. The basic workflow is:
  
  - Remove them from our Google Group
  - Remove them from Slack
  - Remove them from GitHub
  - Add their name to the "Goodbye" list in the Weekly Announcements
  - Remove them from the upcoming MPQ form

## Offboarding Walkthrough
To offboard members, first navigate to the [Offboarding Reponses Google Sheet](https://docs.google.com/spreadsheets/d/1bY-P5ZrIOPDrDpzlXNrDnV96XqOnV_X9z9ur7t9Qkhk/edit?usp=sharing).
Individuals who have newly requested offboarding will not have data in the first four columns of the spreadsheet. Partially offboarded members will have some data.
  
Offboarding tasks should be completed (or checked up on) from left to right for each individual.

### Google Group removal

  If 'Removed from Google Group?' is unchecked:
   - Get the name of the person to be offboarded from column H
   - Find their name in the [Onboarding Responses form](https://docs.google.com/spreadsheets/d/16JcTqlkCRPqrSnykqshrVM2XLf_3HJJiPpAb7qBaOug/edit?usp=sharing)
     - You can search the form for their last name by hitting `command + f` on a Mac or `Ctrl + f` on Windows to open a search box
   - Copy their email address from column K, if they don't have one, use the email address in column J
   - Note their Title/Position from column Q and affiliation from column P
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

### Slack space removal

  If 'Removed from Slack?' is unchecked:
   - Copy their email address from column J of the [Onboarding Responses form](https://docs.google.com/spreadsheets/d/16JcTqlkCRPqrSnykqshrVM2XLf_3HJJiPpAb7qBaOug/edit?usp=sharing)
   - Navigate to the Slack Admin page: https://cfdeworkspace.slack.com/admin 
   - Paste their email address into the search bar
   - Click the ellipses on right side of the screen on the line with their name
   - Choose 'Deactivate account'
   - In the dialog box, click the `Deactivate` button
   - Check the 'Removed from Slack?' box for each person you added
   
### GitHub removal

  If 'Removed from Github?' is unchecked:
  - Copy their GitHubID from column O of the [Onboarding Responses form](https://docs.google.com/spreadsheets/d/16JcTqlkCRPqrSnykqshrVM2XLf_3HJJiPpAb7qBaOug/edit?usp=sharing)
  - Note their Title/Position from column Q and affiliation from column P of the [Onboarding Responses form](https://docs.google.com/spreadsheets/d/16JcTqlkCRPqrSnykqshrVM2XLf_3HJJiPpAb7qBaOug/edit?usp=sharing)
  - Go to https://github.com/orgs/nih-cfde/people
  - Paste thier GitHubID into the 'Find a member' box (don't put an `@` in front of it)
  - Click on the gear icon on the right side of the screen and select 'Remove from organization'
  - In the dialogue box, click the 'Remove members' button
  - Check the 'Removed from Github?' box for each person you removed

 ### Remove from MPQ
 
 If 'Removed from MQP as of?' is blank:
 - Check their Affiliation(s) in column P, of the [Onboarding Responses form](https://docs.google.com/spreadsheets/d/16JcTqlkCRPqrSnykqshrVM2XLf_3HJJiPpAb7qBaOug/edit?usp=sharing) only members of the Tech Teams (Brown, Foster, Kesselman, Ma’ayan, O'Connor, Sansone and White) need to be removed from the MPQ
 - Navigate to the MPQs folder in CFDE Admin on Google: https://drive.google.com/drive/u/0/folders/1G7omyAgRSQr-n6F4o3HWUKcRm_cvoOHJ
 - Find the MPQ that is due this month and open the form for editing. Do *NOT* delete people from previous months MPQs
 - Scroll down to the correct Tech Team
 - Click on the correct person listed in that Tech Team
 - The individuals question should switch to editing mode. You may have to click it more than once
 - At the bottom of their section, click on the trashcan icon. 
 - Click anywhere else on the screen
 - Add the correct month_year in the 'Removed from MQP as of?' column for each person you added

### Special removals for PMs, PIs and Admin contacts

If the person you are offboarding is a PI, PM or Administrative contact for *any* team, they may need to be removed from the [Points of Contact](https://github.com/nih-cfde/organization/blob/master/PointsOfContact.md) list:
  - Navigate to [Points of Contact](https://github.com/nih-cfde/organization/blob/master/PointsOfContact.md) on GitHub
  - If the person is listed, use the edit feature to remove them and issue a pull request. For help with pull requests, see the [GitHub Usage Guide](./GitHubUsage.md)


   
  

