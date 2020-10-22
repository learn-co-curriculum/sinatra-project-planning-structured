# Bonus: Sinatra Project Planning

## Introduction

The Sinatra project is your first web application -- complete with a database!
Look Ma, I built a website! In the next lesson, you'll be presented with the project
requirements. Here is an opinionated guide for successfully
getting going with your Sinatra project.

**Use this lesson to help you plan for your Sinatra Project**

Tips on all aspects of the project are included here, so make sure to have a
look through!

> **Note:** Keep in mind that the Ask a Question is not permitted to help while
> you are building your projects. Use the internet and the resources provided in
> this document if you get stuck!

## How to Get Started On a Successful Project Build

1.  Read through the project requirements and make sure you understand them!

2.  Ideate! What do you want to build? Some considerations:

    - Choose a domain you're familiar with!
    - Choose a domain you care about
    - Choose a domain that fits the project specs

3.  User stories describe how a user would use your app, such as “A user should
    be able to…” or “As a user, I can, …” and finish the sentence. Stick with
    high-level, like, “A user can sign up or log in, create widgets, and edit and
    delete widgets they own.”

    Distinguish user stories that relate to your MVP from those that describe stretch
    goals. What’s the difference?

    - MVP = 'Minimum Viable Product': the most basic app that meets requirements and has
      core functionality
    - Stretch features: bonus features you want but don't need

    Have clear goals regarding MVP and stretch features. Once you have your MVP
    up-and-running, it’s a good idea to use feature branches from there and merge them
    in only when they’ve been thoroughly tested. This way, once you have a working
    version of your app, you always have a working version of your app. In theory,
    anyway.

4.  You don’t have to be an artist, but draw out:

    - your models
    - their attributes
    - their relationships
    - a basic flow of how your application will work

#### NOW, start coding.

5.  Start with your back-end -- build your models

    - Migrations
    - Model classes
    - Associations (& validations if you wish to use them -- you’ll at least need a
      validator to protect against duplicate login credentials across different users,
      usually username or email)

6.  Test your models and associations in the console

    - create some seed data
    - adjust migrations as needed

#### NOW, consider front-end concerns like controllers and views

7.  Start with your ApplicationController helpers - `#logged_in?` and `#current_user`

    - add your login/signup/signout routes

8.  Build out controller routes for other models (add a controller for each model)

9.  Build views and controller actions based on the flow of your app, one step at a
    time, testing as you go!

    - Use `shotgun` and `pry` (or `raise`/`inspect`) all the time!

### Handy Tools

- [draw.io][]: Not an artist? No problem! Draw.io is a free tool for, well, drawing,
  but it’s great for making model diagrams and wireframing your site. Check it out!

- [Corneal][]: Corneal is a gem used for scaffolding out a Sinatra project. You are
  welcome to use it. However, you should understand what it's doing. Remove any
  folders and files you're not using. For example, if you're not going to write any
  tests, delete the `spec` folder. Feel free to build your project out by hand if you
  like too.

- [The Sinatra Docs][]: What?! You haven’t looked through the Sinatra documentation
  yet?? Do yourself a favor and check them out. A good library should have good docs,
  and Sinatra definitely does. Official documentation is a good starting point for
  whatever tool you’re using.

- Slack: Take advantage of your cohort slack channel? Drop questions you have in there,
  work together with your fellow students!

- [Study groups][]: Look out for study groups. These could be instructor-led or
  student-led, and in particular look for support office hours,
  or topics pertaining to what you’re building.

- [Some context][]: What should we be learning here anyway?

### Demo Apps

- [RSS Reader](https://catchup-rss.herokuapp.com/)
- [Gemara Dictionary](http://www.gemaradictionary.com/)
- [Expense Tracker](https://sinatra-expense-tracker.herokuapp.com/)

### Videos

- Head to the [video library][] and search for ‘sinatra’... there is a ton of recorded material there!

[video library]: https://instruction.learn.co
[draw.io]: https://www.draw.io/
[corneal]: https://github.com/thebrianemory/corneal
[the sinatra docs]: http://sinatrarb.com/documentation.html
[study groups]: https://learn.co/study-groups
[some context]: https://github.com/AyanaZaire/sinatra-section-resources/blob/master/what-to-prioritize-in-sinatra.md
