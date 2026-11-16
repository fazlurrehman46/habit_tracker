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
