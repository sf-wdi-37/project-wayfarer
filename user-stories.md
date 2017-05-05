# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> Project Wayfarer: User Stories

**Elevator Pitch:** A travel community for users to share city-specific posts about their favorite locations around the world.

---

## Sprint 1: CRUD

**A user should be able to:**

1. Navigate to "/" and see a basic splash page with the name of the website.
2. View the "San Francisco" page (at "/cities/1") including:
  * The site-wide header.
  * The name of the city.
  * An iconic photo of the city.
3. View a list of posts on the San Francisco page:
  * Sorted by newest first.
  * With the post titles linked to the individual post "show" views.
4. Use an "Add New Post" button on the San Francisco city page to show the new post form.
5. Create a new post for San Francisco.
6. Click "Edit" on ANY individual post, and be shown the edit form.
7. Click "delete" on ANY individual post, then:
  * see a confirmation dialogue that says "Are you sure you want to delete <title>?" with the title of the post?
  * If the user confirms, delete the post.

### Bonuses

**A user should be able to:**

1. Visit city pages via readable urls, like "/cities/san-francisco".

2. On a city's page:
  * See post content truncated to 1000 characters max, with a link to view more.
  * See a the date each post was published.  
  * Sort posts by most recent or least recent.
