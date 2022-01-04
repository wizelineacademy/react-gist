# Mini-Challenge 5: Routing

## The Challenge

> **Note:* Apply TDD as much as you can.*

1. Implement [React Router](https://reactrouter.com/web/guides/quick-start) on your project.
2. Refactor your code to navigate across your sections.
3. Create the **Login View**
  - 3.1 It should display a form with a username and password fields.
  - 3.2 Implement the "Mocked Authentication" functionality (keep reading for more details).
  - 3.3 Update your Global Context and Provider to store and retrieve "session data".
  - 3.4 Implement the "Logout" functionality and update your Global State when the user signs out.
4. Implement the "Add to Favorites" button in the Video Details View: When a user clicks on this button, the selected video should be added to the favorites list using [`localStorage`](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage).
5. Create the **Favorite Videos View**
  - 5.1 Display the favorite videos list on a private route.
6. Create the **Favorite Video Details View**
  - 6.1 Display the selected favorite video and its information.
  - 6.2 Display the list of other favorite videos.
  - 6.3 This view should be rendered through a private route.
7. Apply styles using styled components
8. Create new test cases or modify existing ones for your components and utils if necessary.
  
## Authentication with Mocked Login
Authentication is not directly covered on this Bootcamp, that's why we are not asking you to integrate with a real authentication provider (such as Auth0, OAuth, Firebase, etc.).

Instead, we want you to explore how to configure your application to handle this kind of requirements, e.g., sharing the logged-in user state, define public and private routes, display content based on the authenticated user, etc.

You can use this mocked-login function from your **Login View**.

```js
// login.api.js

const mockedUser = {
  id: '123',
  name: 'Wizeline',
  avatarUrl: 'https://media.glassdoor.com/sqll/868055/wizeline-squarelogo-1473976610815.png',
};

export default async function loginApi(username, password) {
  return new Promise((resolve, reject) => {
    setTimeout(() => {
      if (username === 'wizeline' && password === 'Rocks!') {
        return resolve(mockedUser);
      }
      return reject(new Error('Username or password invalid'));
    }, 500);
  });
}
```
  
## Acceptance Criteria
- [ ] All the sections have their own route.
- [ ] Navigation across the sections is implemented correctly.
- [ ] The Global State is persistent across all the sections.
- [ ] The "Mocked Authentication" mechanism works correctly.
- [ ] The "session data" is stored in the Global Context correctly.
- [ ] Videos can be added to the Favorites list.
- [ ] Videos can be removed from the Favorites list.
- [ ] Navigation to **Favorite Videos View** using a private route is implemented correctly (only authenticated users should access this section).
- [ ] Navigation to the **Favorite Video Details View** using a private route is implemented correctly (only authenticated users should access this section).
- [ ] Information for the selected favorite video is displayed correctly
- [ ] The list of other favorite videos in the **Favorite Video Details View** is displayed.
- [ ] Testing coverage is above 70%. (Please include a screenshot of the code coverage report in your PR description).

## Bonus Points
- [ ] The Add/remove from favorites button should appear when the user passes the mouse over the video card in the list.
- [ ] Integrate with a real authentication provider (such as Auth0, OAuth or Firebase).
- [ ] A 404 section is shown when a route is not found.
- [ ] The **Login View** is implemented as a modal using React Portals.
