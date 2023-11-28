---
layout: page
title: "Rate My Facilities"
---

### Table of Contents
- <a href="overview">Overview</a>
- <a href="team">Team</a>
- <a href="deployment">Deployment</a>

<h2 id="overview">
Overview</h2>

Many people on campus struggle with finding facilities they are satisfied with. Well-known restrooms tend to become crowded and will sometimes run out of resources like toilet paper and soap. Water fountain filters are sometimes left unchanged for too long and will become contaminated. Popular study spaces can also become overcrowded and loud, while many "secret" spots are not utilized. Our project, Rate My Facilities, will be a resource that students can use to find facilities near them, rate their quality, and post comments about them.

<h2 id="team">
Team</h2>

<a href="https://docs.google.com/document/d/1ddkkbSHYJAy0VHQvVl842vhn9q4RlY688vB10F-lX9o/edit?usp=sharing">Team Contract</a>

- <a href="https://silviadebenedictis.github.io/">Silvia De Benedictis</a> - Silvia is a Computer Science student expecting to graduate in Fall 2024. Her interests are in Programming, Web Design, Artificial Intelligence, and Graphic Design.
- <a href="https://jgaleria.github.io/">Joshua Galeria</a> - Joshua is a Computer Engineering student expecting to graduate in Spring 2024. His interests are in Software Engineering, Robotics, Computer Vision, and Machine Learning.
- <a href="https://uhalpern.github.io/">Urban Halpern</a> - Urban is a Computer Science student expecting to graduate in Fall 2024. His interests are in Data Science, Machine Learning, Programming, and Game Development.
- <a href="https://kimsyd.github.io/">Sydney Kim</a> - Sydney is a Computer Science student expecting to graduate in Fall 2024. Her interests are in STEM Education, Sustainability Technologies, User Experience Design, and Graphic Design.
- <a href="https://tranw8.github.io/">Wilson Tran</a> - Wilson is a Computer Science student expecting to graduate in Fall 2024. His interests are in Cybersecurity, Linux Kernel Development, and Language Learning.

<h2 id="deployment">
Deployment</h2>
<a href="https://ratemyfacilities.me/">Deployed application running on Digital Ocean</a>

## Installation

First, [install Meteor](https://www.meteor.com/install).

Second, go to [https://github.com/d-facilitators/rate-my-facilities](https://github.com/d-facilitators/rate-my-facilities), and click the "Use this template" button. Complete the dialog box to create a new repository that you own that is initialized with this template's files.

Third, go to your newly created repository, and click the "Clone or download" button to download your new GitHub repo to your local file system.  Using [GitHub Desktop](https://desktop.github.com/) is a great choice if you use MacOS or Windows.

Fourth, cd into the app/ directory of your local copy of the repo, and install third party libraries with:

```
$ meteor npm install
```

## Running the system

Once the libraries are installed, you can run the application by invoking the "start" script in the [package.json file](https://github.com/ics-software-engineering/meteor-application-template-react/blob/master/app/package.json):

```
$ meteor npm run start
```

### Viewing the running app

If all goes well, the template application will appear at [http://localhost:3000](http://localhost:3000).  You can login using the credentials in [settings.development.json](https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/config/settings.development.json), or else register a new account.

### ESLint

You can verify that the code obeys our coding standards by running ESLint over the code in the imports/ directory with:

```
meteor npm run lint
```

### Landing Page

<img src="assets/images/rmf_landing1.png">
This landing page is displayed upon running the site before the user logs in.

### Sign Up Page
<img src="assets/images/Onboarding-Mockup.png">

The sign up page allows a new user to create an account so that they have access to other pages.

### User Homepage
<img src="assets/images/rmf_homepage.png">

The home page contains access to other pages like the Campus Map and Ranking page.

### Facility Ranking
<img src="assets/images/facility-rankings.png">
Once the user is logged in, they are able to access all ratings and view the top rated facilities. 

### Individual Facilities

<img src="assets/images/sample-facility.png">

This page displays individual facilities, where the user is able to rate them. Users can also view and upload images and comments as well as report any issues. 

### Building List
<img src="assets/images/rmf_buildings.png">
Logged users can view a list of UH Manoa buildings with information on how many facilities they have, such as number of restrooms and water filters.

### Project Pages

[**Milestone 1**](m1.md)

[**Milestone 2**](m2.md)

[**Milestone 3**](m3.md)

<a href="https://github.com/d-facilitators">Check us out on Github!</a>
