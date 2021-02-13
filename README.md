### Frontend for a blogging platform, with mock APIs using React.js

## Contents:
The source folder contains following:
1. api/httpcalls.js: centralized files to make all the API calls using axios.
2. components: Contains the following components
  -- Users: Renders a list of users with columns as Username, company name, blog posts.
  -- Posts: Renders a list of posts for a particular user.
  -- FullPost: Renders detailed view of every post, contains title and body for each post.
  -- Comments: Renders comments assosiated for a particular post.
  -- Error: Page for handling invalid URLs
  -- Navbar: For creating Navbar which is rendered at the top of all the components.
3. constants: URL to fetch the data (can be populated with other constants)
4. App.js -- Container to wrap other components.

NOTE: All the components have their JS files and required CSS files in the same folder.

## Pre-requisites:
1. node
2. npm

## How to run :
1. Run npm install in the root folder.
npm install installs all the required dependencies. These can be found in package.json
2. Run npm start to see the project in the browser at localhost:3000