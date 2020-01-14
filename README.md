# Sinatra Project Planning

## Introduction

The Sinatra project is an excellent opportunity to show what you've learned so
far!

**Use this lesson to help you complete this [planning form][]**

Tips on all aspects of the project are included here, so make sure to have a
look through!

> **Note:** Keep in mind that the Ask a Question is not permitted to help while
> you are building your projects. Use the internet and the resources provided in
> this document if you get stuck!

## How to Get Started On a Successful Project Build

#### DO NOT WRITE CODE YET!!!!

##### Pre-Coding Work

1. Ideate! What do you want to build?
    - Choose a domain you're familiar with!
    - Choose a domain you care about

2. Wireframing & User Stories
    - Write down your models, their attributes, and their associations
    - As a user, I can .....
    - A user should be able to .....
    - What does your app _do_?

3. Design your MVP = 'Minimum Viable Product' vs. what are my 'stretch goals'
    - Stretch goals - bonus features you want but don't need

#### NOW, WE CODE! 

**Note:** NO controllers or views yet!

4. Build your models
    - Migrations
    - Model classes
    - Associations (& validations)

5. Test your models and associations in the console
    - create some seed data
    - adjust migrations as needed

#### NOW, CONSIDER CONTROLLERS AND VIEWS

6. Start with your ApplicationController helpers - `#logged_in?` and `#current_user`
    - add your login/signup/signout routes

7. Build out controller routes for other models (add a controller for each model)

8. Build views and controller actions based on the flow of your app, one step at
   a time, testing as you go!
    - Use `shotgun` and `pry` (or `raise`/`inspect`) all the time!

###### Using the Corneal Gem

You are welcome to use the [corneal gem][].  However, you should understand what
it's doing.  Remove any folders and files you're not using.  For example, if
you're not going to write any tests, delete the `spec` folder.

[corneal gem]:https://github.com/thebrianemory/corneal


[planning form]: https://docs.google.com/forms/d/18VxqGwtr4VJeTeogitVaD2gBfmQleGyPoz4N3gMURuU/edit?ts=5df96877
