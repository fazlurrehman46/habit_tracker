# Habit Tracker App – User Stories

## User Story 1: Account Registration

**Title:**
_As a user, I want to register with my name, username, age, and country so that I can create an account and access the habit tracking features._

**Acceptance Criteria:**
1. The registration page should allow users to enter their name, username, age, and country.
2. All required fields must be completed before registration.
3. The application should display a success message after successful registration.

**Priority:** High

**Story Points:** 5

**Notes:**
- User credentials are not saved in the browser cache.
- Registration credentials are removed once the user logs out.

---

## User Story 2: Account Login

**Title:**
_As a user, I want to log in using my username and password so that I can access my account and track my habits._

**Acceptance Criteria:**
1. The login page should provide username and password fields.
2. Users should be able to log in using the default username and password.
3. The application should allow successful login when valid default credentials are entered.

**Priority:** High

**Story Points:** 3

**Notes:**
- Users cannot log in using their own registered credentials because they are not retained after logout.
- Only the default username and password can be used for login.

---

## User Story 3: Error Feedback on Login

**Title:**
_As a user, I want to receive a message if I enter the wrong username or password so that I know my login attempt was unsuccessful._

**Acceptance Criteria:**
1. The application should validate the entered username and password.
2. If the username or password is incorrect, an appropriate error message should be displayed.
3. The user should be allowed to try logging in again after an unsuccessful attempt.

**Priority:** Medium

**Story Points:** 2

**Notes:**
- Error messages should be clear and understandable.
- The application should not reveal sensitive login information in error messages.

# Exercise 3: Homepage User Stories

## User Story 4: View Welcome Message

**Title:**
_As a user, I want to see a personalized welcome message with my name on the homepage, so that I feel recognized and can confirm I am logged into the correct account._

**Acceptance Criteria:**
1. The homepage should display a welcome message when the user logs in.
2. The welcome message should include the user's name.
3. The welcome message should be visible at the top of the homepage.

**Priority:** High

**Story Points:** 2

**Notes:**
- The welcome message should be personalized based on the logged-in user's name.
- The message should be displayed clearly.

---

## User Story 5: Display Weekly Progress

**Title:**
_As a user, I want to see my daily progress for each habit on the homepage, so that I can easily monitor my progress._

**Acceptance Criteria:**
1. The homepage should display the user's habits and their daily progress.
2. Users should be able to view their progress for each day of the week.
3. The progress information should be updated when users complete their habits.

**Priority:** High

**Story Points:** 5

**Notes:**
- Progress should be displayed in an easy-to-understand format.
- Each habit should have its own progress information.

---

## User Story 6: View Completed Habits

**Title:**
_As a user, I want to see a section for completed habits on the homepage, so that I can track what I have already achieved._

**Acceptance Criteria:**
1. The homepage should include a separate section for completed habits.
2. Users should be able to identify which habits have been completed.
3. Completed habits should be updated when a user marks a habit as complete.

**Priority:** Medium

**Story Points:** 3

**Notes:**
- Completed habits should be visually distinguishable from incomplete habits.
- The completed habits section should be easy to find.

# Exercise 4: Menu User Stories

## User Story 7: Access Menu Options

**Title:**
_As a user, I want to access a menu with options for configuring my habits, viewing reports, editing my profile, and signing out, so that I can easily navigate to different parts of the app._

**Acceptance Criteria:**
1. The application should display a menu with options for Habits, Reports, Profile, and Sign Out.
2. Each menu option should be clearly visible and accessible.
3. Selecting a menu option should navigate the user to the corresponding section.

**Priority:** High

**Story Points:** 3

**Notes:**
- The menu should be easy to navigate.
- All menu options should be accessible to logged-in users.

---

## User Story 8: Navigate to Profile

**Title:**
_As a user, I want to access my profile from the menu, so that I can view and edit my personal information._

**Acceptance Criteria:**
1. The menu should provide a Profile option.
2. Selecting Profile should navigate to the profile page.
3. The profile page should allow users to view and edit their personal information.

**Priority:** Medium

**Story Points:** 3

**Notes:**
- The profile page should display the user's registered information.
- Changes should be reflected in the profile.

---

## User Story 9: Navigate to Habits Page

**Title:**
_As a user, I want to access the habits page from the menu, so that I can configure and manage my habits._

**Acceptance Criteria:**
1. The menu should provide a Habits option.
2. Selecting Habits should navigate to the habits page.
3. Users should be able to configure and manage their habits from this page.

**Priority:** High

**Story Points:** 3

**Notes:**
- The habits page should be easy to access.
- Users should be able to manage their existing habits.

---

## User Story 10: Sign Out from Menu

**Title:**
_As a user, I want to sign out of my account using an option in the menu, so that I can securely log out when I'm finished using the app._

**Acceptance Criteria:**
1. The menu should provide a Sign Out option.
2. Selecting Sign Out should end the current user session.
3. After signing out, the application should redirect the user to the login page.

**Priority:** High

**Story Points:** 2

**Notes:**
- User session information should be cleared after logout.
- The user should need to log in again to access the application.

  # Exercise 5: Profile Page User Stories

## User Story 11: View Personal Information

**Title:**
_As a user, I want to view my saved name, username, age, and country on my profile page, so that I can see the details I provided during registration._

**Acceptance Criteria:**
1. The profile page should display the user's name.
2. The profile page should display the user's username, age, and country.
3. The displayed information should match the details provided during registration.

**Priority:** High

**Story Points:** 3

**Notes:**
- Personal information should be displayed clearly.
- Only the logged-in user's information should be displayed.

---

## User Story 12: Edit Personal Information

**Title:**
_As a user, I want to update my name, username, age, and country on my profile page, so that I can keep my information up to date._

**Acceptance Criteria:**
1. The profile page should allow users to edit their name, username, age, and country.
2. Users should be able to modify their existing information.
3. The application should validate the updated information before accepting changes.

**Priority:** High

**Story Points:** 5

**Notes:**
- Required fields should not be left empty.
- Updated information should follow the application's validation rules.

---

## User Story 13: Save Updated Information

**Title:**
_As a user, I want the changes I make to my profile to be saved, so that my updated details are stored and reflected throughout the app._

**Acceptance Criteria:**
1. The profile page should provide a Save option.
2. Selecting Save should store the updated profile information.
3. The application should display a success message after saving the changes.

**Priority:** High

**Story Points:** 3

**Notes:**
- Users should receive appropriate feedback if saving fails.
- Updated details should remain available according to the application's data storage and session rules.

---

## User Story 14: Update Name in Header

**Title:**
_As a user, I want my updated name to be displayed in the app's header after I change it in the profile, so that my changes are immediately visible._

**Acceptance Criteria:**
1. The application should retrieve the updated name after the profile is saved.
2. The app header should display the updated name.
3. The updated name should appear without requiring the user to log out and log in again.

**Priority:** Medium

**Story Points:** 2

**Notes:**
- The header should reflect the latest saved profile name.
- The updated name should be displayed consistently throughout the app.

# Exercise 6: Habits Page User Stories

## User Story 15: Add a New Habit

**Title:**
_As a user, I want to add new habits on the details configuration page so that I can manage and update my habits as needed._

**Acceptance Criteria:**
1. The habits configuration page should provide an option to add a new habit.
2. Users should be able to enter the required details for a new habit.
3. The newly added habit should appear in the user's habits list.

**Priority:** High

**Story Points:** 5

**Notes:**
- Users should receive confirmation when a habit is successfully added.
- Required habit details should be validated.

---

## User Story 16: Delete a Habit

**Title:**
_As a user, I want to delete existing habits so that I can keep my habits up to date._

**Acceptance Criteria:**
1. Each existing habit should have a Delete option.
2. The application should ask for confirmation before deleting a habit.
3. Once deleted, the habit should no longer appear in the active habits list.

**Priority:** Medium

**Story Points:** 3

**Notes:**
- Users should not accidentally delete habits.
- Deleted habits should not appear as active habits.

---

## User Story 17: Personalize a Habit with Color

**Title:**
_As a user, I want to assign a specific color to each habit to make it personal to me._

**Acceptance Criteria:**
1. Users should be able to select a color when creating a habit.
2. Users should be able to change the color of an existing habit.
3. The selected color should be displayed consistently for that habit throughout the app.

**Priority:** Medium

**Story Points:** 3

**Notes:**
- Provide multiple color options.
- The selected color should make each habit easy to identify.

# Exercise 7: Reports Page User Stories

## User Story 18: View Weekly Reports

**Title:**
_As a user, I want to see a report of my weekly habit progress so that I can understand how well I am maintaining my habits._

**Acceptance Criteria:**
1. The reports page should display a weekly summary of habit progress.
2. Users should be able to view their progress for each day of the week.
3. The report should reflect the user's recorded habit activity.

**Priority:** High

**Story Points:** 5

**Notes:**
- Weekly reports should be easy to understand.
- Progress should be displayed in an organized format.

---

## User Story 19: Visualize Completed Habits

**Title:**
_As a user, I want to see a chart of my completed habits for each day of the week so that I can quickly identify trends in my progress._

**Acceptance Criteria:**
1. The reports page should display a chart showing completed habits for each day.
2. The chart should clearly identify the days of the week.
3. The chart should update when new habit completion data is recorded.

**Priority:** Medium

**Story Points:** 5

**Notes:**
- The chart should be visually clear and easy to understand.
- Users should be able to identify daily progress trends.

---

## User Story 20: View All Habits

**Title:**
_As a user, I want to see both completed and incomplete habits in my report so that I have a comprehensive view of my habit tracking performance._

**Acceptance Criteria:**
1. The report should display both completed and incomplete habits.
2. Users should be able to distinguish completed habits from incomplete habits.
3. The report should provide an overall view of the user's habit tracking performance.

**Priority:** High

**Story Points:** 3

**Notes:**
- Completed and incomplete habits should be visually distinguishable.
- Both categories should be included in the weekly report.
