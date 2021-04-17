## CS 495 _Journal of a Pandemic Year_ Archive Project (Group 11)

Ellen DiSilverio, Emerson Jackson, Justin Levy, Dan Seifferth


### Project Goals

Overall Project Goal:
Provide a mobile friendly website for users to interact with as a companion source and bibliography for the book, as well as a dashboard for admin to control user submitted stories and add them to the website

Group 11 Project Goals:
 1. Create a secure manner for users to submit their stories to be read and approved by admin before being added to the site
 2. Create a dashboard that allows admin to read and edit submissions before approving or rejecting them
 3. Create a way to store user submitted stories outside of Zotero that can be accessed by the companion website for display
 4. Create a way for users to view accepted stories by date that were published by the admin
 
 
### Approach

Tools:
1. Use wordpress APIs for the security advantages

User Experience:
1. User redirects to submission site, which will make them login before they can access the submission screen.
2. User can then enter in a title, story, location, and date of the submission that they would like to be displayed.
3. User clicks submit and is redirected to a page thanking them for submitting their story.
4. After their story has been published, users can go to the story viewing page and select a date and submit.
5. The page refreshes, giving all the stories that exist for that date, including the title, author, and a preview of the story. Clicking a button below the preview will allow users to read the entirety of the submission.

Admin Experience:
1. Admin accesses the bard admin menu tab from the admin page of wordpress.
2. Admin can select between tabs to see unpublished, waitlisted, and published stories.
3. Admin can select a story, which will appear in a text area that can be edited.
4. Admin can then waitlist, publish, or delete submissions, as well as email users directly with the click of a button.

Github URL:
   https://github.com/Enigmajams/495spring2021Project
