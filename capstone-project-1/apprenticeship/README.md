# Wizeline Academy - 2022 React Apprenticeship Program Capstone Project 1
## Introduction
Thank you for participating in the 2022 React Apprenticeship Program! Here you will find the instructions to complete your project.

The purpose of this assignment is for you to demonstrate your React skills. This is your chance to show off everything you've learned during our apprenticeship program and earn your diploma.

The idea is to build and deliver an *entire* React application on your own. We don't want to limit you by providing some fill-in-the-blanks exercises but ask you to build it from scratch. We hope you find this project challenging and engaging.

## The Challenge

Consider the following:
- **Goal:** To create a YouTube client app.
- **Demo application**: https://react-certification-2020.netlify.app/
- **Credentials**:
  - Username: `wizeline`
  - Password: `Rocks!`

### Main Functionalities
These are the main features required for the project:

- **Home View**
  - Search and display a list of videos using YouTube API.
- **Video Details View**
  - Display the selected video and its information.
  - Display a list of related videos.
  - Allow users to mark videos as favorites.
- **Login**
  - Implement a mocked login and store the logged-in user data in a browser; it should be persistent and globally accessible from a Context.
- **Favorite Videos List**
  - Display the favorite videos on a private route.
- **Favorite Video Details View**
  - Display the selected favorite video and its information.
  - Display the list of other favorite videos.

> **Tip**: You should use the [demo application](https://react-certification-2020.netlify.app/) just as a guide and as a trigger for your ideas. It's not mandatory to reproduce the same styling or to stick only to the main features listed above. Feel free to extend the functionalities if you want some bonus points ;)! This is YOUR project and you can be as creative as you like.*

> **Note**: We won't share the project's source code until the apprenticeship program is completed and all the participants deliver their implementations (we don't want to bias your solution).

### General Requirements
The following are the main requirements we will evaluate from your deliverables:
- Apply everything you've learned during our apprenticeship program:
  - Functional Components
    - React Hooks
    - Custom Hooks
  - Styled Components
  - State Management with React Context
  - React Router
    - Public and private routes
  - Fetch results from YouTube API
    - Search videos by name
    - Get related videos
  - User Authentication
  - Testing Coverage (~70%)
  
> **Tip**: Try to keep the use of third-party libraries to the minimum, especially those related to the topics covered in our apprenticeship program. For example, you can use a CSS framework (such as Bootstrap) if that makes you feel comfortable and move faster, but we still want you to develop and deliver meaningful styled-components.

### Deliverables
The project is divided into five mini-challenges. You will have to solve each one at the end of each module so we can evaluate what you've learned. 

> **Important**: Each deliverable must be reported in the same PR. For example, you should send the first and second in the same pull request.

- **First Deliverable**
  - [**Mini-Challenge 1:** Core Concepts + Styling](https://github.com/wizelineacademy/react-gist/blob/main/capstone-project-1/mini-challenges/mini-challenge-1.md)
  - [**Mini-Challenge 2:** Intro to Testing](https://github.com/wizelineacademy/react-gist/blob/main/capstone-project-1/mini-challenges/mini-challenge-2.md)
- **Second Deliverable**
  - [**Mini-Challenge 3:** Hooks](https://github.com/wizelineacademy/react-gist/blob/main/capstone-project-1/mini-challenges/mini-challenge-3.md)
- **Third Deliverable**
  - [**Mini-Challenge 4:** State Management](https://github.com/wizelineacademy/react-gist/blob/main/capstone-project-1/mini-challenges/mini-challenge-4.md)
- **Fourth Deliverable**
  - [**Mini-Challenge 5:** Routing](https://github.com/wizelineacademy/react-gist/blob/main/capstone-project-1/mini-challenges/mini-challenge-5.md)
- **Final Deliverable**

> **Important**: Beware that all mini-challenges must be solved in order and incrementally.

#### Submitting the deliverables
For submitting your work, you should follow these steps:
1. Fill [the form](https://forms.gle/7Jz2uXMFYXfcU2428) to submit your project.
2. Fork projects from the [baseline repo](https://github.com/wizelineacademy/react-apprenticeship-capstone1).
3. Make sure that your forked repo is public.
4. Submit your deliverables as a **Pull Request (PR)** in a new branch derived from master/main on your own GitHub account.
5. Add your mentor as a reviewer of your PR.
6. Remember to submit your deliverables on time to be successfully evaluated.

Remember to always use your creativity!

## Demo App

### Set up
To set up the app and install dependencies, follow the next steps:
1. Run the following command: `npm install` or `npm i`.
2. Run: `npm run prepare` to initialize husky.
3. Run `npm install -g @commitlint/cli @commitlint/config-conventional` to install commitlint.

To find out more documentation about commitlint and conventional commits visit this [wiki](https://github.com/wizelineacademy/react-apprenticeship-capstone1/wiki/Creating-commits)
<br>
> **Note**: The demo app has a private route; use `wizeline` as the username and `Rocks!` as the password to log in.

## Questions or difficulties?

If you have any questions about this challenge, please ask on the Slack channel ASAP. 
If you encounter any trouble with the base repo, feel free to give feedback on the Slack channel, and if possible open an issue on the project.
