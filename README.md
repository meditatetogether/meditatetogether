Original App Design Project - README Template
===

# MeditateTogether

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
A guided/group Meditation app where people can join voice channels to meditate with an instructor/with each other.

### App Evaluation

- **Category:**
Health and Fitness
- **Mobile:**
Mobile phones are the best way to ensure that users have easy-to-use and access microphone and speakers for participating in voice channels. 
- **Story:**
A key part of meditation and mindfulness is the feeling of being connected with others. A group meditation app would allow for the establishment of communities of meditators. Would bring in a sense of accountability and collaboration around meditative practices. 
- **Market:**
There is a large number of people getting into mindfulness and meditation. Group meditations can be particularly useful for making people feel connected with others. Although it is possible to do group meditations on other general purpose platforms such as Discord or Zoom, these platforms are full of other distractions and aren't designed with this specific functionality in mind. 
- **Habit:**
Most people getting into meditation want to establish a daily meditation practice. With group meditation there might be added accountability to meditate at a fixed time daily through the app. 
- **Scope:**
V1 would only have a few voice channels that are available to all users.  
V2 would allow the creation of new voice channels with restricted access.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can register on the app
* User can login to the app
* User can add a profile picture
* User can see a list of voice channels
* User can join a voice channel with other users in it

**Optional Nice-to-have Stories**

* User can create their own voice channel
* User can join meditation groups 
* User can leave text messages in a voice channel
* User can add meditation music to voice channel
* User can search for voice channels

### 2. Screen Archetypes

* Login
   * User can login to the app
* Register
   * User can register on the app
* Profile
   * User can add a profile picture
* Stream
   * User can see a list of voice channels
* Detail (Voice Channel)
   * User can join a voice channel with other users in it

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Stream
* Profile

**Flow Navigation** (Screen to Screen)

* Login
   * Stream
* Register
   * Stream
* Stream
   * Detail (Voice Channel)
* Profile 


## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="wireframe-1.png" width=600>
<img src="wireframe-2.png" width=600>


### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 


### Models

Stream Object 
   | Property      | Type     | Description |
   | ------------- | -------- | ------------|
   | objectId      | String   | unique id for the voice channel (default field) |
   | userCount | Number   | number of users in a voice channel |
   | createdAt     | DateTime | date when  is created (default field) |

[Add table of models]
### Networking
-    - Home Feed Screen
      - (Read/GET) Query all voice channels
   - Profile Screen
      - (Read/GET) Query logged in user object
      - (Update/PUT) Update user profile image

