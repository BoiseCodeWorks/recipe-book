# RecipeBook

![recipe](./recipe.jpg)
We all remember grandmas book full of all her recipes organized into a box full of 3x5 cards, hand written and covered in flour, bits of chocolate and vegetable oil. We are ready to bring grandma into the digital age with this new RecipeBook!

## Goals

In this checkpoint students will demonstrate a working knowledge of building full-stack applications. They will utilize a Vanilla Javascript frontend implementing the MVC design pattern. On the server side students will use Express with Node.js, as well as implementing Auth0 for User Credentials, mongoose as an ORM and MongoDB as their database.

## The Setup

### Step 1

It will probably be helpful to start on the backend of this application first. Utilize a tool like postman and start creating and editing your Recipes.

On the server you will utilize a node-express server setup with mongoose-mongoDB for your database. The server side code needs to be setup similar to your previous projects. You will need to create a new free database on atlas for this assignment.

The active user is always stored on the server side via a JWT so you should be able to enforce some of the security concerns using something like `req.user` and `auth0Provider.getAuthorizedUserInfo`

All Recipes should be public, however we want each user to be able to keep track of their favorites. This relationship involves `many` users being able to add `many` recipes

### Step 2

The Web client will be an MVC application. The project has already been initialized but requires you to configure it with your own auth0 credentials and some of the services and controllers established. Login/Register should all work for example, however it is up to you figure out what to do from there.

## Requirements

- [ ] Recipes must be rendered in a card like format
- [ ] Recipes have a favorite icon that changes color if it is already favorited
- [ ] A user should not have to re-login everytime they refresh the page
- [ ] The main page shows all recipes regardless of whether you are logged in or not
- [ ] When not logged in do not show a favorite icon
- [ ] Users have an option to view only the recipes they have created
- [ ] Users have an option to view only the recipes they have favorited
- [ ] Users can only edit their own recipes
- [ ] Users can only delete their own recipes
- [ ] Recipes use a soft delete (never destroy grandma's recipes)
- [ ] Users can add comments to recipes
- [ ] Recipes show the creators name and image
- [ ] Comments show the creators name and image
- [ ] Recipes have a like count

## Legal Overview

The content under the CodeWorks®, LLC Organization and all of the individual repos are soley intended for use by CodeWorks Instruction to deliver Educational content to CodeWorks Students.

---

## Copyright

© CodeWorks® LLC, 2021. Unauthorized use and/or duplication of this material without express and written permission from CodeWorks, LLC is strictly prohibited.


<img src="https://bcw.blob.core.windows.net/public/img/7815839041305055" width="125">
