# Forum Single Page Web Application (SPA)

![Home Page](https://res.cloudinary.com/dqnbdaara/image/upload/v1685912859/Forum/Screenshot_2023-06-04_202334_t1usbv.png)

## Description

The Forum Single Page Web Application (SPA) is a dedicated platform designed to facilitate seamless communication, knowledge sharing, and student connectedness within the Solent University community. It provides a user-friendly interface that allows students to ask questions, help each other, and engage in meaningful discussions beyond the confines of the physical campus. The SPA offers features such as creating communities, adding posts, commenting, upvoting/downvoting, and personalized profile pages. It promotes teamwork, encourages social interactions, and saves students time by eliminating the need for lengthy emails or waiting for responses. The Forum SPA enhances student engagement and fosters a collaborative learning environment.

[Forum Web Application] The link to the hosted web application

> See it live on [ovidiuborze22.github.io/forum-master](https://ovidiuborze22.github.io/forum-master/)
> Or clone repo, cd into repo, then run "npm run start"

## Purpose

Creating a full-stack webapp with React.js and Firebase, with multiple routes. Using Typescript and Redux.

Beyond that, other learning outcomes were:

- Design reusable components
- Creating and deleting data inside of a Firebase Firestore database
- Allowing the user to authenticate to interact with the web application
- Creating custom hooks
- Using Redux for state management
- Typescript for types
- Using moment.js for Date utilities

## Features

1. Allows users to authenticate
2. Allows users to create subforum
3. Allows users to create posts
4. Allows users to filter through posts
5. Allows users to upvote/downvote posts and comments
6. Allows users to reply to comments
7. Allows users to search for subforum
8. Responsive
9. Subforum moderators
10. Subforum editing
11. Image upload
12. User can join subforum and more

## Development

### Javascript Framework

- [React](https://github.com/facebook/create-react-app)

### Technologies used

- [Firebase](https://firebase.google.com/) - Cloud services (database, authentication)
- [Redux](https://redux.js.org) - State management library
- [ESLint](https://eslint.org/) - A linter tool to standardize code
- [Github Pages](https://pages.github.com/) - Hosting
- [Prettier](https://prettier.io/) - Code formatter
- [React Router](https://reactrouter.com/web/guides/quick-start) - Router tool for React applications
- [Jest](https://github.com/facebook/jest) - Assertion and test running library
- [Testing Library](https://github.com/testing-library/dom-testing-library) - Testing library for queries
- [React CSS Modules](https://github.com/gajus/react-css-modules) - CSS with local scoping
- [React](https://github.com/facebook/react/) - Javascript library
- [Typescript](https://www.typescriptlang.org/) - Static typing in JavaScript

<p align="left"> 
<a href="https://www.typescriptlang.org/" target="_blank"> 
  <img src="https://www.manejandodatos.es/wp-content/uploads/2015/03/typescript.png" alt="typescript" width="40" height="40"/> </a>
<a href="https://jestjs.io" target="_blank"> 
  <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" width="40" height="40"/> 
</a>
<a href="https://github.com/gajus/react-css-modules"> 
  <img src="https://raw.githubusercontent.com/gajus/react-css-modules/master/.README/react-css-modules.png" width="40" height="40"/> 
</a> 
<a href="https://redux.js.org/"> 
  <img src="https://raw.githubusercontent.com/reactjs/redux/master/logo/logo.png" width="40" height="40"/> 
</a> 
<a href="https://firebase.google.com/"> 
  <img src="https://res.cloudinary.com/startup-grind/image/upload/c_fill,dpr_2.0,f_auto,g_center,h_1080,q_100,w_1080/v1/gcs/platform-data-goog/events/firebase%20icon.jpg" width="40" height="40"/> 
<a href="https://testing-library.com/"> <img src="https://testing-library.com/img/octopus-64x64.png" width="40" height="40"/> </a> 
</p>

## Areas for Improvement

1. Questions
2. Allow users to change profile pictures
3. Give the user back their time in seconds with demicals instead of seconds
4. Trending posts
5. Awards
6. Coins
7. Pagination and lazy loading
8. Allow users to filter their content inside their profile
9. Allow users to search for posts within subforum
10. Pinning posts in a subforum
11. Light theme a bit too bright
12. "Back" button for easier navigation to previous page
13. More options for customizing the community's appearance
14. Notification system to alert users when someone replies
15. More customization options for unique profile page
16. All Communities page search bar for quick community search

## How to run Forum (SPA)

1. Download zip and unzip folder in Local Machine from GitHub
   <br>
2. Git Clone using the link - `git clone https://github.com/ovidiuborze22/forum-master.git`
   
    ![Download Folder](https://res.cloudinary.com/dqnbdaara/image/upload/v1685913510/Forum/Screenshot_2023-06-04_221714_wn8ufr.png)

3. Open folder in IDE([VS Code](https://code.visualstudio.com/download) preferable)
<br> 

4. Open Terminal in the root directory and run command: 
   `npm install`-installing all required libraries 
   <br>

5. To start the code use the command:
   `npm run start`- react-scripts start

## Create and connect Firebase Forum (SPA)

For Forum web application, Firebase is already set up and connected.

To create your own firebase project you need to follow next steps:

1. **Step 1**
     - Open [Firebase](https://firebase.google.com/) an create an account it's free
    ![Create Project Firebase](https://res.cloudinary.com/dqnbdaara/image/upload/v1685915028/Forum/Screenshot_2023-06-04_224229_xwz2cm.png)

    - Give a project name
    ![Project Name](https://res.cloudinary.com/dqnbdaara/image/upload/v1685915299/Forum/Screenshot_2023-06-04_224615_joygcx.png)

    - Select Default Account for Firebase
    ![Default Account](https://res.cloudinary.com/dqnbdaara/image/upload/v1685915502/Forum/Screenshot_2023-06-04_225107_sszxr8.png)

    - After creating a project successfully 
      - Configure Authentication for Email and Google
      - Configure Firestore Database
      - Configure Storage
    ![Configure Project](https://res.cloudinary.com/dqnbdaara/image/upload/v1685916055/Forum/Screenshot_2023-06-04_225819_nacusw.png)
    
      - Register App 
      - Go to Terminal `npm install firebase` 
    ![Register App](https://res.cloudinary.com/dqnbdaara/image/upload/v1685916647/Forum/Screenshot_2023-06-04_230825_erocpm.png) 

<br>

1. **Step 2**
   - In Firestore are two options: 
     - production mode
     - test mode (development mode)
    ![Production/Development mode](https://res.cloudinary.com/dqnbdaara/image/upload/v1685917613/Forum/Screenshot_2023-06-04_232550_umsjjh.png)

<br>

3. **Step 3** 
  
  - Change `.env` file by replacing the values in `firebaseConfig()` with the generated once from your firebase project
  - Make sure to use command `firebase login` in Terminal to connect to Firebase

## How to Deploy Forum (SPA) - GitHub

1. Create a [GitHub](https://github.com/) Repository and commit all code to Github
   - How to add repository more info [here](https://docs.github.com/en/github-ae@latest/get-started/quickstart/create-a-repo) 
<br>

2. In GitHub go to settings and configure the following:
   
   - Settings->Pages->Branch->Root->Save
  ![GitHub Settings](https://res.cloudinary.com/dqnbdaara/image/upload/v1685918784/Forum/Screenshot_2023-06-04_234431_ata9zl.png)

<br>

3. In Terminal you have to run the following commands:
   - `npm run build`
   - and `npm run deploy`
<br>

4. In GitHub go to:
   - Actions to check the deploying process
   - If successful will show the generated Link for the hosted app
  ![GitHub Actions](https://res.cloudinary.com/dqnbdaara/image/upload/v1685919374/Forum/Screenshot_2023-06-04_235429_xp4lgp.png)

