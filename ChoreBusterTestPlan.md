Chore Buster App


App Description: This is an app designed to help divorced parents stay consistent with their children’s chores between households. It helps create a way for parents to keep consistency between homes, and for children to learn how to contribute to the family in a fun and positive way. It provides an incentivized approach for kids to have age-appropriate responsibilities with the freedom to manage their tasks while still creating a sense of accountability to the family as a unit.


The app will enable multiple family users to access the same platform to create and check off chores. Each family member can set up a profile with an illustrated avatar, bio, and reward they’re working toward. The app will have a chore tab, calendar tab, and rewards tab. 


Parents will create daily chore lists and assign them to each child. The chores can be viewed within the chore tab in list format with the child’s avatar next to it, or in calendar format within the calendar tab. Parents will have the option to set a point amount for each chore which correlates with the rewards the children can earn. The children can check off completed chores and watch as their points accrue towards a reward. The app will allow parents and children to customize the rewards. For rewards claimed, they can be archived within each child’s profile. Each archived reward will have the option to upload a photo and journal entry about the experience. 


Chore Buster App Test Plan

Introduction
Test Plan Objective: Ensure the user experience is easy and intuitive as a wide range of ages will be interacting with the app. Also, focus on the functionality of the app throughout a chore’s “lifecycle” from creation to the claiming of a reward.

Scope of Testing: Testing will center around chore and reward creation, ease of completing chores for children, profile creation and customization, claiming and archiving rewards, updating archived reward journal entries, and overall ease of navigating app. 

Test Items
Testing will ensure buttons function accurately in chore and reward creation, chores being marked as complete, and in claiming and archiving rewards.
Testing will ensure points tally correctly for a reward as chores are completed. List the specific features or functionalities of the web application that will be subjected to testing.
Testing will ensure photos upload and format correctly to archived rewards and journal entries are easy to save.
Overall ease moving from one tab to the next as well as moving through the chore lifecycle will be accessed.
Testing will ensure multiple users in one family can access the same account easily.

Test Criteria
Entry Criteria: App has been built; bug tracking in place; environments used for testing are available and ready; major defects are fixed due to completion of coding; requirements are clearly outlined
Exit Criteria: Multiple users must be able to use the app concurrently without the app crashing or preventing others from updating their chores. The user experience needs to be seamless and without frustration for the expected youngest and oldest users.

Resources
Human Resources: QA team, stakeholders
Software and Hardware: 
Software: Jira, Selenium
Hardware: Android, iOS devices, tablets

Schedule
Week 1: Test planning
Review requirements, user stories, test cases and comparisons
Create test plan
Procure testing tools (hardware, software), environments factors
Week 2: Manual and Functional Testing
Perform basic manual testing for user experience - app should be easy to navigate and perform all basic commands without bugs
Perform functional tests - ensure all functions are working properly
White Box testing - ensure photos are uploading and formatting correctly, points are tallying, chores are created without error.
Week 3: Regression Testing
Perform regression/automation tests on improvements based on previous tests
App navigation and controls are performing properly without error or crashing.
Week 4: Final Testing
UAT testing by stakeholders for user exerience
Final testing

Test Environment
Test Andriod, iOS on mobile devices and tablets (app not being created for desktop use)
Test while connected to high-speed internet connections, without internet connection, and on low-bandwidth connections 

Roles and Responsibilities
QA team - Functional and Non-functional testing including: performance, load, reliability, and compliance testing
Stakeholders - usability, visibility, and accessibility testing

Test Cases
Test Case: Chore Creation for Multiple Children
Test Objective: Parent A creates identical chore for multiple children: app needs to create and place chore in correct area (i.e. chore list or calendar)
Test type: Functional
Priority: High
Existing conditions: Logged into app; app accessible via download
Test Steps: 
Parent logs in
Parent clicks “+” and selects “Create Chore”
Chore creation screen pulls up
Parent enters chore details (i.e. name, points value, task) and selects “Next”
Parent selects more than one child’s name to assign chore to
Parent selects “Next” button which moves them to “Select Calendar”
Parent enters date from dropdown menu
Parents select “Save Chore”
Expected Result: Chore populates in calendar for the date selected and under each child’s chore list.
Actual Results: TBD based on testing
Defect Tracking via Jira throughout testing

Test Case: Chore completion (manual test): 
Test Objective: Upon the completion of a chore, the assigned points need to be applied to the reward and updated correctly. 
Test type: Functional via Manual
Priority: High
Existing conditions: Logged into app; app accessible via download
Test Steps: 
Select chore from list (repeat test by selecting from calendar)
Select “Done!” and mark chore as completed
Associated reward should pop up with a new points total displaying
Expected Result: Point value from chore should be added to reward points total
Actual Results: TBD based on testing
Defect Tracking via Jira throughout testing

Risks and Mitigations
Compatibility: test across different browsers and devices
Deadline: Prioritize critical testing to ensure the main functions of app work appropriately
Last Minute Requirement Changes/Adjustments: address via agile testing approach to adapt, improve, and alter with regression testing
Miscommunication and Collaboration Mistakes: implement agile approach to ensure frequent alignment on requirements, adjustments, and results across teams

Tools and Techniques
Jira - test and bug tracking
Selenium - functional testing, regression testing as changes are made over sprints
Black Box Testing - manual testing for user experience

Reporting and Communication
Testing will be documented through continuous updates via Github and Jira. Sprint reviews will discuss results and improvements in process for next sprint. Updates will be provided to stakeholders via QA team lead.
