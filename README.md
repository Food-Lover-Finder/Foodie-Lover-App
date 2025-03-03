# Food Radar App

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
This is an app for hungry people who have little desire to do much thinking about what their next meal will be. This app will help young adults find the best restaurants/places to eat based on their food prefernces and restrictions. People can also create groups with their friends and the app will help them find the best place to eat based on the groups preferences.


### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Dining / Restaurant
- **Mobile:** This would primarily be a mobile app since it's supposed to be for people wanting to make a quick and easy decison. 

- **Story:** Primarily provides resteraunt suggestions based off of the results of a survey taken by the user. Can also just provide resteraunt suggestions based off of location without preferences. May be able to join a group with others and get the top resteraunts based of closest preferences. 

- **Market:** This app is for hungry people who have little desire to do much thinking about what their next meal will be. 

- **Habit:** This app could be used as frequently as the user decides to eat out. 

- **Scope:** First we get the location of the user to find all resteraunts near them, then the user might want to take the prefernce survey and get personalized recommendations. 

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

- [x] User sees app icon in home screen and styled launch screen
- [x] User can sign up for an account
- [x] User can log into their account 
- [x] User can choose to skip food preference survey
- [x] User can get landmarks near location
- [x] User can search for different landmarks in the location

**Optional Nice-to-have Stories**

- [ ] User can join a group of people 
- [ ] User can create a group for others to join 

### 2. Screen Archetypes

* Register
    * User can sign up for an account
* Login 
    * User can log into their account 
* Stream
    * User can get food suggestions based on their location only
    * User can get food suggestions based on food preferences as well as location
* Survey 
    * User can choose to take a food preference survey
* Profile
    * User can view profile

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Stream
   * Survey 
   * Profile

**Flow Navigation** (Screen to Screen)

* Register
   * stream 
   * survey

* Login 
   * stream

* Stream
   * survey

* Survey 
   * stream 

* Profile
   * stream
   * survey


## Wireframes
<img width="934" alt="Screen Shot 2021-10-29 at 5 36 11 PM" src="https://user-images.githubusercontent.com/87346208/139504454-cbe315bc-591f-4de9-8225-94a82be7c04b.png">

## Schema
Models

<img width="529" alt="Screen Shot 2021-11-05 at 4 35 12 PM" src="https://user-images.githubusercontent.com/87346208/140577036-9b671f6d-99df-4eeb-bc0d-69471eb29fb5.png">

## Network Requests 
Home Feed: <br />
(Read/GET) restaurant images <br />
(Read/GET) restaurant names <br />
(Read/GET) restaurant descriptions <br />
(Read/GET) restaurants’ locations <br />
(Read/GET) restaurants price range <br />
(Read/GET) restaurants rating <br />
<br />
Menu Page: <br />
(Read/GET) restaurant images <br />
(Read/GET) menu items <br />
(Update/PUT) user likes this location <br />
<br />
Login page: <br />
(Read/GET) user login information <br />
(Delete) users food restrictions & preferences <br />
(Update/PUT) users food restrictions & preferences 

Project Progress

![](https://i.imgur.com/qy3MfDH.gif) <br />

![ezgif com-gif-maker](https://user-images.githubusercontent.com/87346208/143658839-68546c1e-b6c1-49fe-88aa-f06b8da00eff.gif)


![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/87346208/144697267-ae8fe656-6a2b-482d-bc3d-dc2667db614a.gif)




