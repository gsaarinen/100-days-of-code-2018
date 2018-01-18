# 100 Days Of Code - Log

### Day 14: January 17th, 2018

**Today's Progress:**

Worked just a bit on the Rails-Spotify project with Eric and updated some iTerm settings. Not super productive today. 👎

**Time Logged:**

1

**Thoughts:**

Not much to expand on.

-----------------------------

### Day 13: January 16th, 2018

**Today's Progress:**

Spent most of my time updating my resume but also updated some README info on the micro blog as well as touch-up a few other things.

**Time Logged:**

1

**Thoughts:**

Not much to expand on.

-----------------------------

### Day 12: January 15th, 2018

**Today's Progress:**

Skipped yesterday but spent a little time today going through the RSpotify documentation and tried integrating some of it's features into my app.

**Time Logged:**

1

**Thoughts:**

Didn't get a ton done but I know where the issues are when I can't use the RSpotify methods. I need to most likely update my db so I can save certain attributes from the response I get when I use the `RSpotify::User.new` method.

-----------------------------


### Day 11: January 13th, 2018

**Today's Progress:**

Hell yeah - I got some of the basics of the Spotify authentication setup and running.

**Time Logged:**

1.5

**Thoughts:**

Finally! It's a bit far from anything useful but I am finally able to see the user info based on the spotify user data and I have the token saved in the db. Gotta hack on it more tomorrow but it's a big step forward. Next is testing and putting some of the `rspotify` gem methods to good use!


-----------------------------


### Day 10: January 12th, 2018

**Today's Progress:**

Spent a good amount of time working on the micro-blog rails app and was able to successfully deploy to Heroku again. Also, set it up to auto deploy once it get's pushed to Github.

In the afternoon I spent some time re-visiting the rails-spotify app as I found [this tutorial](https://www.sitepoint.com/rails-authentication-oauth-2-0-omniauth/) that walks through some rails + Oauth stuff.

**Time Logged:**

2.5

**Thoughts:**

It felt nice to dig back into the Spotify app. I'm really hoping that I can make some head-way this weekend and get the damn thing working so I can start pulling in user data. It seems like I was almost there but for some reason I'm getting a `NoMethodError` when I'm creating a new user in the sessions controller. I *know* there is a method on the users model that matches but I think it has something to do with the class inheritance.

-----------------------------

### Day 9: January 11th, 2018

**Today's Progress:**

Updated some of the static pages on my micro-blog rails project. Also, updated my `.bash_profile` so it now displays my git branch.

**Time Logged:**

1.25

**Thoughts:**

Not a lot of things to expand upon. I need to work more on the `README`, adjust some of the content on the footer, and update a few other static pages so the rails app is more "show-able". Also, I really need to start looking into how I push it up to Heroku again. I could just push up a whole new branch but I'm worried that with all the AWS stuff I would have to re-do all that stuff. Probably would be good to learn it again though.

-----------------------------


### Day 8: January 10th, 2018

**Today's Progress:**

Imported my Rails Micro-Blog app to my Github account from Bitbucket and did a lot of re-configure work.

**Time Logged:**

2

**Thoughts:**

I have the basics moved over but I'm still having 1 set of tests fail related to the `micropost_update` method for some for the UI integration tests. Really not sure why this is failing as the last time I ran them they all passed as I *never* `git push` with failing test 😉.

I need to spend some time on figuring out how the push to Heroku will work since it's technically a different repo. As far as I understand, it should work fine since I believe it's just setup as another remote for git as I always push via the command-line using the Heroku CLI.


-----------------------------


### Day 7: January 9th, 2018

**Today's Progress:**

Spent more time going through the Smartsheet API and ruby gem.

**Time Logged:**

1

**Thoughts:**

Didn't get to spend a lot of time working on stuff today. Mostly just played with the Smartsheet API via the command line through `pry`. Still need to find a good use for it but I know it's out there! Also, had another great MPLS Jr Dev meetup! Love that community!


-----------------------------

### Day 6: January 8th, 2018

**Today's Progress:**

Things I covered today:

- [x] Fixed the Node version issues I was having with deploying to Heroku
- [x] Started playing around with the new Smartsheet gem and the Ruby SDK
- [x] Added a bunch of fake data and counters to the aggregate components in the React app

**Time Logged:**

2.5

**Thoughts:**

Super excited about Smartsheet having a [Ruby gem](https://github.com/smartsheet-platform/smartsheet-ruby-sdk) now! This will make it a lot easier to start playing around with it at work and allow me to potentially write some code for my job.

Also, starting to get this React Spotify thing off the ground and it's nice to be learning more about React. It's really different though to have everything for a web page be in one file (styling, html, and JS).


-----------------------------

### Day 5: January 6th, 2018

**Today's Progress:**

Continued work on the DevTips Tutorial - [React JS Prototyping](https://www.youtube.com/watch?v=k3bRdvmTdwQ). Had to skip yesterday 😬

A few other things that I worked on:
- [x] Got `git` setup
- [x] Got `heroku` setup

**Time Logged:**

1.75 hrs

**Thoughts:**

Had some issues with getting the repo to build on Heroku. I found [this](https://devcenter.heroku.com/articles/troubleshooting-node-deploys) article that I need to dive into because I'm getting node version discrepancy issues.

Fun stuff! 😊

-----------------------------

### Day 4: January 4th, 2018

**Today's Progress:**

Continued work on the DevTips Tutorial - [React JS Prototyping](https://www.youtube.com/watch?v=k3bRdvmTdwQ).

**Time Logged:**

1.5 hrs

**Thoughts:**

This is fun. Kid got sick so I can't comment much.

-----------------------------

### Day 3: January 3rd, 2018

**Today's Progress:**

Started working on the DevTips Tutorial - [React JS Prototyping](https://www.youtube.com/watch?v=k3bRdvmTdwQ). It's nice to FINALLY start playing around with React!

**Time Logged:**

1.15 hrs

**Thoughts:**

I know that I'm kind of jumping around right now with things I'm working on but it feels good to just get some exposure to some different technologies. Front-end frameworks like React are a bit of a hole in my knowledge so spending some time on getting to know how they work feels like a good move.

-----------------------------

### Day 2: January 2nd, 2018

**Today's Progress:**

Building an Alexa Skill.
- learned about AWS Lambdas
- how to host and setup and Alexa Skill
- ended on [Connecting Your Voice User Interface To Your Lambda Function](https://github.com/alexa/skill-sample-nodejs-quiz-game/blob/master/instructions/3-connect-vui-to-code.md) section

Also, I'll have to install node.js and such to get this running locally.

**Time Logged:**

1.25 hrs

**Thoughts:**

Learning about Alexa skills is fun! The AWS tutorials are pretty thorough. I definitely recommend them.

-----------------------------

### Day 1: January 1st, 2018

**Today's Progress:**
- Updated repo for the Hartl tutorial
- Updated repo for #100DaysOfCode
- Updated repo for personal site
- UpdatesUpdatesUpdates

**Time Logged:**

1.5 hrs

**Thoughts:**

Let's do this 2018! Excited to be at it again with the 100 days project.

**Link to work:**

Updated the ol' [website](http://garretsaarinen.com/)
