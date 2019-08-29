# Product Owner Test

Welcome to the QuickSeries SCRUM Product Owner take home test. In order to test your writing skills and your ability to translate complexe technical language into language that can be consumed by non-technical individuals, we would like to do the follow two things:

* Write 3 to 5 users stories along with the acceptance criteria
* Write release notes

## Instructions

Submit your answers in Text, Word or Apple Pages format by email to your recruiter or directly to the hiring manager you have spoken to. Allow a minimum of 1 to 2 business days for us to review the results and give you feedback. Good luck!

### Write user stories

In order to complete this exercise, you will need to download the QuickSeries app from the Apple App store or Google Play store:

* iOS: https://apps.apple.com/ca/app/quickseries/id1424521895
* Android: https://play.google.com/store/apps/details?id=com.quickseries.rca.quickseries

Launch the app, and using the top left Hamburger menu, navigate to the Feedback module. Create user stories for any or all of the following screens:

* Categories screen
* Having a technical problem screen
* Report a bug screen

### Release notes

Below you will find a list of users stories, improvements and bug fixes that are part of a release. In order to communicate these changes to the end-users, you must write a release note than can be understood by non technical individuals.

We understand that you have limited information to work with, so don't worry about being vague or even inventing something around a bug, improvement or feature.

| Description    | Acceptance criteria                                                                 | Screenshots |
|----------------|-------------------------------------------------------------------------------------|-------------|
|**Bugs**        | A pop-up should be displayed when the user tries to mark a private module as public |             |
|                | Unable to navigate to the promo module when we access a promo notifications         |             |
|                | When we update any field in the configuration of the assessment form module, new changes are appearing only when after we manually refresh the page                                                                | |
|**Improvements**| Users should not receive a push notification if the respective module               | |
|                | (news/promo/alert) is locked by access code                                         | |
|                | Applied filters should be preserved until the user removes them explicitly from the | |
|                | map view of the Resources module                                                    | |
|**Stories**     | As an admin, I want to view the aggregate results of an assessment|**Part A:**<br/>- From the list of assessment, click on one assessment item<br/> - From the dashboard, click on the "Details" Button from the top left corner of the page, on the right of "X total of responses" lable.<br/><br/>**Part B:**<br/>- This should open the results page.<br/>- This page contains a top bar with the following items:<br/>-- Back button<br/>-- 3 tabs<br/>--- Aggregate<br/>---Individual<br/>--- Data trends<br/>-- Values toggle (% or #)<br/>-- Options buttons (3 vertical dots)<br/>--- Export<br/>---Print<br/>- Click on the "Aggregate" tab to load the aggregate results of this assessment.<br/>- This page contains:<br/>-- A summary<br/>--- Title of the Assessment<br/>--- Number of responses<br/>--- First response date and time<br/>--- Last response date and time<br/>--- Average score  X out of Y (z%)<br/>-- List of sections and questions<br/>- Each questions should display:<br/>-- The question number<br/>-- The question<br/>-- The right color of the right answer should be different.<br/>--The percentage of people who answered each choices<br/>--- If it's a Scored Assessment, it should display the value of the question beside each answer (score points)||
||As an admin, I want to view the individual results of an assessment|**Part A:**<br/>- From the list of assessment, click on one assessment item<br/>- From the dashboard, click on the "Details" Button from the top left corner of the page, on the right of "X total of responses" lable.<br/><br/>**Part B:**<br/>- This should open the results page.<br/>- This page contains a top bar with the following items:<br/>-- Back button<br/>-- 3 tabs<br/>--- Aggregate<br/>--- Individual<br/>--- Data trends<br/>-- Values toggle (% or #)<br/>-- Options buttons (3 vertical dots)<br/>--- Export<br/>--- Print<br/>- Click on the "Individual" tab to load the aggregate results of this assessment.<br/>- This page contains:<br/>-- A summary<br/>-- View by (dropdown list of collected meta data)<br/>-- When configuring an assessment, you can collect certain types of information, such as name, email, phone number, etc... That dropdown list should contain the keys that were collected.<br/>-- Selecting something will load the proper list in the "Respondents" dropdown. For example, if you pick email, the Respondents dropdown list will display emails.<br/>-- If the assessment is NOT configure to collect personal data, this dropdown should not be visible.<br/>-- Respondents (dropdown list of respondents)<br/>--- Selecting something in the respondents dropdown will load the results of that person.<br/>--- If the assessment is NOT configured to collect personal data, the list should contain "Respondent #"<br/>---- Respondent #1<br/>---- Respondent #2<br/>---- Respondent #3<br/>---- etc...<br/>-- Next/Previous buttons to view the next or previous results<br/>-- <meta data item>: <value><br/>--- Example:<br/>---- Name: XXXX<br/>---- Email: XXXX<br/>-- Number of responses<br/>-- Started time<br/>-- Submitted time<br/>-- Score:  X out of Y (z%)<br/>-- List of sections and questions<br/>-- Each questions should display:<br/>--- The question number<br/>--- The question<br/>--- The list of answers<br/>---- If it's Quiz<br/>----- If the answer is right, it should be green with a checkmark<br/>----- If the answer is wrong, it should be red with an X<br/>----- The other answer should be greyed out (except the text)<br/>---- If it's a Scored Assessment<br/>----- There are no right or wrong answer, so there should only be a checkmark on the selected answer<br/>----- We should see the value (number of points) the question is worth||
||As an admin, I want to view the data trends of an assessment|||
