## Video Streaming App Readme

## Description
This is a video streaming app that will be built in the Authoring class using the IMBb API and assets created in Level 3. The goal of this project is to build a layout, views, and components using the existing design files, and create a temporary data store for user login and permissions. Users will be able to log in/out, filter and select movies or TV shows based on their profile (adult or kids), and the UX/UI will update accordingly. Additionally, a social media API will be implemented for liking, sharing, and commenting on media selections.

## Roles
Developer - pawan pandeya
Designer - Jerome Fernandez


## Technology Used
- Node.js
- Express
- Vue.js

## Getting Started

## Prototype Link
https://xd.adobe.com/view/aa793f2a-8ebb-43de-8431-d8df68556950-ff2a/

## Running the Backend 
1. To get started with the video streaming app, follow these steps:
2. Download the project files. "https://github.com/Gitmepawan/roku_backend"
3. Import the database file located inside the "database" folder into phpMyAdmin.
4. Open the project files with VS Code.
5. Install the necessary node modules by typing npm audit fix --force in the terminal.
6. Type npm start in the terminal to start the server.
7. The database file can be accessed at localhost:5050/ums/users.
Once you've completed these steps, you should be able to see the video streaming app database.1.

## Running the Frontend
1. To run the frontend of the video streaming app, follow these steps:
2. Download the frontend files. "https://github.com/fernandezjerome/Ruko-Front"
3. Open the frontend files with VS Code.
4. Install the necessary node modules by typing npm audit fix --force in the terminal.
5. Type npm start in the terminal to start the frontend server.
6. The frontend should be accessible at localhost:3000.

Once you've completed these steps, you should be able to use the frontend of the video streaming app.


## Login
once you run your file you can see the username and password from the database file which was imported in phpmyAdmin.
you can use that username and password or you can change too. You will see the collection of movies according to permissions.

## Architecture
The app will have separate front-end and back-end projects, and a truly component-based architecture with the front-end build will be used.

## User Login System
The permissions stored in this temporary data store will dictate which components the user is able to view. For example, if a user has a "kids" permission, they will only be able to access the kids' component of the app. Similarly, if a user has an "adult" permission, they will only be able to access the adult component of the app. This will ensure that users are only able to access content that is appropriate for their age group.

## Filtering Access and User Privileges
To restrict access to some content based on age or ratings, a strategy will be developed. Users will have rights and privileges, and the UX/UI will update based on the user (children/adults). Two themes will be created and the appropriate theme/components will be rendered on login.

## Social Media API
A social media API will be researched and implemented to allow users to like, share, and comment on each media selection.

## Conclusion
We see this project as a great opportunity to work collaboratively as a team, adapt to unforeseen circumstances, and build a video streaming app using various technologies and strategies. While some aspects of the app are temporary and will be replaced with more complete implementations in the future, it's important to approach each stage of development with the same level of diligence and attention to detail. By doing so, we can ensure that the app functions smoothly and provides a great user experience, both in the short-term and long-term.

## Feedback
We hope that you enjoy using the video streaming app that we have built. Your feedback is valuable to us, and we encourage you to share your thoughts and suggestions with us as we continue to improve the app. Our goal is to provide you with the best possible user experience, and your feedback will help us to achieve that. Thank you for using our app!

## The MIT License (MIT)
Copyright © 2022 pwn jer

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.