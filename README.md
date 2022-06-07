
## Accessing the site
Access the app here: https://ux-colab.web.app/

Both responsive on desktop and mobile.

## Features

Space Origin is a full stack application that allows users to subscribe to newsletters and edit their preferences.

The features include:

Subscription to Newsletter Functionality
Edit Subscription Functionality
A database is used to store user information and subscription preferences.

Users have the ability to do the following:
Sign Up to the newsletter
Select and edit their newsletter preferences
View a dashboard with user sign up statistics.

## Technologies used

Front end
Reactjs
Axios

Back end
Firebase

## Approach taken

Planning
Given the short timeframe for the project sprint (2 days) we wanted to maximise functionality whilst minimise work with the backend. Firebase seemed like an appropriate choice given its easy use and setup.

The designs were created by the UX team using figma (designs below) with mobile and desktop view in mind.

Given the short timeframe we did not feel it was necessary to implement a full User Authetication login system with firebase so we opted to save user login data in local storage to allow them to edit their preferences.

![designs](https://user-images.githubusercontent.com/99111357/171306627-aa328390-5dca-4375-9b01-857a831102bc.png](https://github.com/Josephhu706/Space-Colab-Project/blob/1cd3470d46d903bdb077dd7110631a927f259ea7/src/images/FigmaDesign.jpg)


## Lessons learnt
To plan and revist the plan frequently to make sure you are on track or if things need to be revised

There is a lot that goes into a full stack application and that it can be a lot to do in 7 days

A lot of learning is done when you are working on a project
I learnt more about Vue, how to use styling libraries like Tailwindcss, learned how to implement simple animations and transitions.

## Future improvements

As there were time constraints with the project, I was not able to deliver everything I would have liked to with my app.

In the future, I would like to add/improve the following:

The styling falls apart a little bit on medium screens, i'll need to configure the tailwind config file more.

I accidentally used multiple fonts, will need to consolidate fonts.

On the achievments page, the workout gifs shrink a little bit too much on small screens.

I did not have time to filter out all the data from the fitness api i used by equipment. The exercises are properly sorted by body part but some exercises might not require a weight field but it is there by default.

The Calendar content could be a bit more interactive. At the moment there is just the modal but it would be more interesting if i could add stuff like creating a workout from the calendar etc.
