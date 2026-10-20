# Android Inventory Management App

## CS 360: Mobile Architecture and Programming

### Project Overview

For Project Three, I built an Android Inventory Management App using Java, SQLite, and Android Studio. The idea was to give users a simple way to keep track of their inventory without having to manage everything manually. The app allows users to log in, add items, view their inventory, update quantities, and remove items they no longer need. It was also designed to support optional text alerts when inventory gets low.

### User Interface and Design

I wanted the app to be easy to use without a lot of unnecessary steps. I created a login screen and an inventory screen with buttons and fields that make it clear what users need to do. I also included messages to let users know when an action was completed.

As a Product Owner, I'm used to gathering requirements and helping developers understand what users need. This time, I got to build the interface myself. It made me think more about things like where buttons should go, how someone moves between screens, and whether the layout makes sense to someone using the app for the first time. I think keeping the design simple was one of the things that worked well.

### Coding Approach

I found it easier to work on one part of the app at a time. I started with the basic functionality and worked through connecting the screens to the code and database. Java handled the actions users performed, while SQLite stored the information so it could be retrieved later.

Breaking the project into smaller pieces helped me stay organized. When something wasn't working, I could focus on that specific feature instead of trying to figure out what was wrong with the entire app. That's an approach I'll continue using in future projects.

### Testing and Troubleshooting

I tested my app using the Android Studio emulator, checking everything from logging in and managing inventory to making sure the input validation worked correctly. I also successfully tested the SMS notifications to confirm that users received text alerts when inventory levels were low.

One thing I learned is that just because the code runs doesn't mean everything works the way it should. I had to test different scenarios, make adjustments, and try again. It taught me to pay attention to the smaller details because even something simple can affect how the app works.

### Challenges and Problem-Solving

Input validation was one area where I had to do some extra work. I wanted the app to catch incorrect entries without making it frustrating for someone to use. That meant checking how the fields and buttons behaved, making changes, and testing again.

I also learned not to change too many things at once when troubleshooting. It's much easier to figure out what fixed a problem when you're working through it one step at a time.

### My Biggest Success

I'm most proud of getting the inventory features, SQLite database, and SMS notifications working together. Being able to save inventory information, update quantities, and successfully send low-stock alerts helped me understand how the different parts of an app communicate.

Before this course, I was usually on the Product Owner side, working with developers to define requirements and prioritize features. This project gave me the chance to actually build and test those features myself. Seeing everything work together was probably the most rewarding part of the project.
