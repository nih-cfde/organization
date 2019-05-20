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

  If 'Slack Invite Sent?' is unchecked:
   - Copy their email address from column J
   - In your CFDE Slack window, click '+Invite people'. (It will just below your list of Direct Messages in the sidebar)
   - Paste their email address into the box. You can add more than one person at a time.
   - Check the 'Slack Invite Sent?' box for each person you added
   
### GitHub adds

  If 'GitHub Invite Sent?' is unchecked:
  - Copy their GitHubID from column O
  - Note their Title/Position from column Q and affiliation from column P
  - Go to https://github.com/orgs/nih-cfde/people
  - Click `Invite Member`
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
 - Navigate to the MPQs folder in CFDE Admin on Google: https://drive.google.com/drive/u/0/folders/1G7omyAgRSQr-n6F4o3HWUKcRm_cvoOHJ
 - Find the MPQ that is due this month and open the form for editing
 - Scroll down to the correct Tech Team
 - Click on the last person listed in that Tech Team, the one right before the 'What DCC interactions has your team had this month?' question
 - The individuals question should switch to editing mode. You may have to click it more than once
 - At the bottom of their section, click on the copy icon. It looks like two, mostly overlapping rectangles
 - You should now have two copies of that individuals questions. Copy the new team member over the name in the new copy
 - Click anywhere else on the screen
 - Add the correct month_year in the 'Added to MQP as of?' column for each person you added

### Check Slack Invite

If 'Slack Invite Accepted?' is unchecked:
  - Go to this link: https://cfdeworkspace.slack.com/admin/invites#pending (you may need to log into your Slack account)
  - If their invitation has moved to 'Accepted Invitations', click the checkbox
  - You can search for them using their email address in column J
  - Check the 'Slack Invite Accepted?' box for each person you added

### Add to Mailing lists

If you have just updated their 'Slack Invite Accepted?' checkbox, then you also need to add them to mailing lists (next section)
 - Note the mailing lists they requested to join in column R (see NOTE1 for help)
 - Go to https://cfde.groups.io/g/General/subgroupmembers (see NOTE2 for help)
 - Check the boxes next to their name for their selected lists (you can do multiple members at a time)
 - Click `Update`
 - Click `Yes` in the dialogue box that appears (Yes has a trash can for some reason)
 - Check the 'Mailing Lists Assigned?' box for each person you added
 
     NOTE1: It's basically impossible to read column R for members that choose more than one list.
     It's much easier to read their choices directly off their form. To do that:
       
      - Go to https://docs.google.com/forms/d/1sFY6y2eHB3PS0HayEyxXtZOrBJV7lfT8thJ8bL9wKqQ/edit#responses
      - Click on the 'Individual' tab
      - Click where it says 'achar@ucdavis.edu'. That will open a selection box where you can choose the email address of the member you're working on
      - Choose the right email address
      - Scroll to the bottom of their form to the 'Mailing List Options' section
       
    NOTE2: Members are automatically added to groups.io when they accept their Slack invite, 
     however the sync can take up to one hour. If someone has accepted thier Slack invite, but
     does not appear in the subgroupmembers page, you can force the sync to happen immediately by:
       
      - Go to https://cfde.groups.io/g/General/syncslackmembers
      - Click the 'Slack Members' tab
      - Check the box next to the members name
      - Click the `Add to Groups.io` button

 ### Check GitHub Invite
 
 If 'GitHub Invite Accepted?' is unchecked:
  - Go to https://github.com/orgs/nih-cfde/people
  - Click on 'X pending invitations'. It will be just below the `Invite member` button.
  - Use the dialogue box to update 'GitHub Invite Accepted?' checkmarks
  
  

   
   
  

