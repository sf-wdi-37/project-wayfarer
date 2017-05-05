# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> Project Wayfarer: User Stories

**Elevator Pitch:** A travel community for users to share city-specific posts about their favorite locations around the world.

---

## Sprint 3: Validations & Authorization

**A user should be able to:**

1. View city pages for "London" and "Gibraltar".
2. Verify that a new post they create is successfully published on the correct city page.

A user CANNOT save invalid data to the database, according to the following rules:

1. A user CANNOT sign up with an email (or username) that is already in use.
2. A post's title must be between 1 and 200 characters.
3. A post's content must not be empty.

A user is authorized to perform certain actions on the site, according to the following rules:

1. A user MUST be logged in to create/update/destroy resources.
2. A user may only edit their own profile and edit/delete their own posts.

#### Bonuses

**A user should be able to:**

1. View an error message when form validations fail, for the following validations:
  * Title must be between 1 and 200 characters.
  * Content must not be empty.
2. View only the 10 most recent posts on a city page (pagination), with
  * A link/button to the "Next" 10.
  * A link/button to the "Previous" 10.
3. See a list of the city pages they've contributed to, on their public profile
4. See the number of posts they've written for each city, next to the city's name in their profile.
5. View all vagabond cities as markers/pins on a map on the site's homepage.
6. Click on a pin on the homepage map and be redirected to the corresponding city page.
