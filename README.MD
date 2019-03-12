[![pagepro_logo](https://raw.githubusercontent.com/Pagepro/frontend-recruitment-task-landing-page/master/logo.svg?sanitize=true)](https://pagepro.co/)

# React Developer Recruitment Task 

## The task
Your job is to code an app with posts of users with ability to manage posts and comments. Application must be SPA and use multiple routes (listed below). 

## Tech stack:
* API: [API DOCS](https://jsonplaceholder.typicode.com/)
* Starter: [Create react app starter](https://github.com/facebook/create-react-app)
* State Managment: [Redux](https://github.com/reduxjs/react-redux)
* Routing: [React-router](https://github.com/ReactTraining/react-router)
* Middleware: [redux-thunk](https://github.com/reduxjs/redux-thunk)

## Screens:
* `Homepage` 
    ![Homepage](img/HomePage.png)
    * List of users. 
    * For each user you must display his details (you can omit the address). 
    * On user click you will redirect to `User Details` page
* `User Details`
    ![User Details](img/UserDetails.png)
    * This page contains the user name at the top of the page.
    * List of user posts (just titles trimmed to one line).
    * On click on the post item you will redirect to `Post Details` page
    * Button that on click will open the  `Add post modal`. 
    * Back button that will go back to `Homepage`
* `Post Details`
    ![User Details](img/PostDetails.png)
    ![User Details comments](img/PostDetailsComments.png)
    * On top of the page you still have the username
    * Post full details 
    * Button to remove post. 
    * On remove you will have to go back to `User Details` page and remove current post from the list and API.
    * Button/link for comments 'show/hide comments' that will toggle the comments list visibility.
    * Button to add comment.
    * Adding comments should be similar to `Add Post Modal` but contain different fields and action.
    * Back button that will go back to `Posts list
*  `Add Post/Comment Modal`
    ![Add Post Modal](img/AddPostModal.png)
    ![Add Comment Modal](img/AddCommentModal.png)
    *   Title
    *   Form fields
    *   Two buttons `Cancel`, `Save`
    *   Cancel will just close the modal and ignore changes
    *   Save will connect with API and add Comment/Post to the list

## Must-have:
1. React &amp; Redux
2. Connection with API
3. Usage of react-router for multiple pages
4. Loaders when you wait for the data
5. Validation on forms
6. Usage of modern js functionality (ES6+)

## Good to have:
1. Typescript
2. Clean code (linters, prettier)
3. UI kit for styles (or styled-components)
4. Tests
5. App deployed to [Netlify](https://www.netlify.com/)

## What will we be paying attention to:
1. How you split code for components
2. How your store looks like and how you communicate with redux.
3. Reusability of the components.
4. Code repetitions and reusability (keep your code [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) and simple [KISS](https://en.wikipedia.org/wiki/KISS_principle)).
5. How and where you put your business logic.
6. Code optimization and the solution&#39;s performance.
7. Working in accordance with good practices in general.
8. How you communicate with API.
9. Handling unexpected errors or potential exceptions.
