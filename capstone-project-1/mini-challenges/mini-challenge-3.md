 # Mini-Challenge 3: Hooks

## Before you start
1. In order to fetch videos from YouTube you need to create a new project using the Google console, and then create an API key for consuming the API.

  - **Step 1:** Follow the [YouTube API v3 getting-started guide](https://developers.google.com/youtube/v3/getting-started) to get your API credentials.
  > **Note:* You only need to complete the steps 1, 2 and 3 in the guide to get your API_KEY.*
  - **Step 2:** After configuring the API key, you can read the [YouTube JavaScript client getting-started documentation](https://github.com/google/google-api-javascript-client/blob/master/docs/start.md) to get examples about how to consume the API.

2. Identify the API calls that you need in order to get all the information for each section in your app.
3. Identify which hooks will allow you to fetch information from the API.

> **Pro Tip:* Use environment variables to store sensitive data like your API credentials.*

## The Challenge

> **Note:* Apply TDD as much as you can.*

1. Fetch videos using the YouTube API and display them in the **Home View**
 > **Note:* now you can remove the logic that you implemented in the first mini-challenge to display videos from the mock file.*
2. Implement the logic to search videos using the YouTube API (it's time to enable the search field functionality).
3. Create the **Video Details View** (this section will be displayed when the user clicks on a specific video in the list). 
    - 3.1 Display the video player.
    - 3.2 Display the information for the selected video.
    - 3.3 Display a list of related videos.
 > **Hint:* You can use conditional rendering to display or hide the Video Details View according to user interactions.*

4. Apply styles to the new components you create.
5. Create test cases for your API calls.
6. Create new test cases or modify existing ones for your components if necessary.
7. If you're duplicating code for your API calls inside your components, try creating a custom hook to reuse this logic more easily.

## Acceptance Criteria
- [ ] Videos in the Home View are fetched from the YouTube API and displayed correctly.
- [ ] Users can search for YouTube videos using the search field on the header.
- [ ] A video can be played from the **Video Details View** after clicking on it.
- [ ] The video information and related videos list are displayed correctly on the **Video Details View**.
- [ ] When a user clicks on a related video the video player, information and related videos list are updated.

### Bonus Points
- [ ] Custom Hooks for API calls are implemented and tested correctly.
- [ ] Testing coverage is above 60%. (Please include a screenshot of the code coverage report in your PR description).
