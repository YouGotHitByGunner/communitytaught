# CommunityTaught.org

A comprehensive tracker for 100Devs classes and homework.

**Live website:** [CommunityTaught.org](https://communitytaught.org/)

![Preview of CommunityTaught.org](https://communitytaught.org/img/resources/communitytaught-preview.png)

## How It's Made:

**Tech used:** Node.js, Express, MongoDB, Pug, Tailwind CSS

This app was built from scratch using my [authentication boilerplate](https://github.com/labrocadabro/node-mongo-boilerplate/) as the base for the code, and [my previous homework tracker](https://labrocadabro.github.io/100devs-hw-tracker/) as the base for the application design.

## How to Contribute:

I build the website without really taking collaboration into account and the project needs some work in terms of both documentation and processes. I am in the process of getting that built out, but in the meantime, here are the basic steps to get the project up and running locally:

- fork the repository
- create a MongoDB database on your account to store the data
- import the class and homework data into your database
- rename example.env to .env and add your credentials (.gitignore will ignore the .env so your credentials won't get pushed to Github)
- Set up mailhog if you are using email and password login

## Optimizations and Improvements:

- Tests & refactoring to make unit tests easier.
- Possibly switching the front end to React + Typescript.
- Progress bars to show how much of the course has been completed.
- API integrations to automatically check if certain tasks (like Twitter check-in) have been completed.
- Video timestamps.
- Note-taking alongside the videos.

## Lessons Learned:

- This is the largest project I've built so far, and certain parts of it were new to me. First, second, and even third attempts sometimes felt wrong - too complex, difficult to read, or slow to execute. I learned that this gut feeling is usually right, but it's also ok to move on temporarily rather than dwelling on a single problem.
