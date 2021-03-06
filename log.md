# 100 Days Of Code - Log

### Day 25: February 8th, 2018

**Today's Progress:**

Worked again on the React Spotify app. Got all the final design work done and deployed it.

**Time Logged:**

1.15

**Thoughts:**

Oooof.

It's been a solid week since I've been able to get back into coding. I feel bad but with stress, flu, and so many other things going on it was pretty important to take a break.

It was nice to finish the React project and it taught some very basics of how components work in a React app. 

-----------------------------


### Day 24: February 1st, 2018

**Today's Progress:**

Worked on the React Spotify playlist app. Updated to include the top 3 songs of each playlist and updated the filter so it works on the songs as well.

**Time Logged:**

1.25

**Thoughts:**

Yup - pretty much summed it up in the progress section.

-----------------------------


### Day 23: January 31st, 2018

**Today's Progress:**

Wrote some tests for the CSV portion of the Ruby todo app and started working more on the React Spotify Playlist app.

**Time Logged:**

1

**Thoughts:**

Got really tripped up during some of the more advanced data wrangling portions of the playlists tracks piece of the tutorial. Stuff is getting kind of confusing. Plus - now it seems my backend server isn't working for local development.

Oy vey!

-----------------------------

### Day 22: January 30th, 2018

**Today's Progress:**

Worked through my Ruby CL todo app. Restructured the app, and added a `Rakefile` to run all the tests at once.

**Time Logged:**

1.75

**Thoughts:**

Decided to fire up the todo app again and dove into added the ability to read a CSV file. I also spent a lot of time restructuring the into a lib folder and the tests in a test folder. This made my tests not work but then I got dive into how to setup a `Rakefile` and how they work. Super cool!

Also, I added the ability for you to load in a csv file using a custom method:

```ruby
def parse_csv_list
  CSV.foreach('test_todo.csv', headers: true) do |row|
    @list << TodoItem.new(row[0], row[1])
  end
end
```
...and it worked on the first try!

-----------------------------


### Day 21: January 27th, 2018

**Today's Progress:**

Fully got the Photon device setup and walked through a couple of their sample apps.

**Time Logged:**

1

**Thoughts:**

This hardware stuff is pretty cool! It reminds me a lot of some of my engineering classes at IPR and walking through signal flow. I got the web IDE setup as well as installed the command line tools so hopefully I can keep playing around with them more.

-----------------------------


### Day 20: January 26th, 2018

**Today's Progress:**

Started setting up the [Photon](https://www.particle.io/products/hardware/photon-wifi-dev-kit) I got from Matt and also walked through the Spotify Better Playlists react app.

**Time Logged:**

.75

**Thoughts:**

Not much to expand on.

-----------------------------

### Day 19: January 24th, 2018

**Today's Progress:**

Updated the React Spotify Playlist app with actual Spotify account data via authorization.

**Time Logged:**

2.5

**Thoughts:**

It's working awwwwww yeah! Had some issues with commits at the end and fixing a lot of typos and production snafus but she is [up and working](https://gs-spotify-better-playlists.herokuapp.com/)!
-----------------------------


### Day 18: January 23rd, 2018

**Today's Progress:**

Spent some time going through ASCII animation stuff in the command line.

**Time Logged:**

2

**Thoughts:**

Was feeling very uninspired today so I decided to do something fun and dive a little more into how ASCII animation stuff works in command line apps. It was a lot of fun. Long story short - `\r` is your friend :)

-----------------------------


### Day 17: January 21st, 2018

**Today's Progress:**

Tried working directly with ruby and the rpsotify gem / Spotify API.

**Time Logged:**

1.5

**Thoughts:**

Kind of a frustrating day. Nothing seemed to click and for some reason concepts seem harder to understand than they were before. Maybe I'm just getting dumber 😢

-----------------------------


### Day 16: January 19th, 2018

**Today's Progress:**

Played around more with the Rails Spotify app.

**Time Logged:**

2

**Thoughts:**

Super late getting this log in so not sure how much I can elaborate. I need to figure out how to either bring in the rspotify app or just work with the API natively.

-----------------------------


### Day 15: January 18th, 2018

**Today's Progress:**

Focused on the [React Spotify Playlist](https://github.com/gsaarinen/spotify-better-playlists) application today.

**Time Logged:**

3

**Thoughts:**

Awwwww yeah! I was able to really get some stuff done today. Felt good to get such a large chunk of work done and deployed on top of it as well. I'm kind of starting to come around on this React thing. It's nice that everything (at least for this app) is all pretty centrally located file-wise. I'm definitely going to keep learning more about React after this basic app and who knows - maybe I'll convert my [Rails Spotify](https://github.com/gsaarinen/rails-spotify-demo) app to a React app. It's seems to be what all the cool kids are doing.

-----------------------------

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
