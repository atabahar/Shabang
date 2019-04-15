# Shabang
Group Project - README Template
===

# Dating App

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
 This app will be built to make dating world more fun, enjoyable and meaningful.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category: Lifestyle
- **Mobile: Mobile first experience but would perhaps be just as viable on a computer, however mobile version could potentially have more features.
- **Story: Analyzes users friendship choices, and connects them to other users with similar choices. 
- **Market: Any individual could choose to use this app, and to keep it a safe environment, people would be organized into age groups. Ability to like, pass and superlike the other users.
- **Habit: This app could be used as often or unoften as the user wanted depending on how deep their social life is, and what exactly they're looking for. 
- **Scope: First we would start with having user sign up and make up their own profiles. Then users will be seeing other users' profile. It'll become larger as the app grows with some fun features.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can register a new account, with email and create a profile.
* User can login, logout
* User can answer questions about themselves and select their criteria
* User can view profiles
* User can like, pass or superlike a person
* User can chat with the person they've matched

**Optional Nice-to-have Stories**

* New and fun feautures will be added during construction

### 2. Screen Archetypes

* Login
* Register
   * User signs up or logs into their account
   * Upon Download/Reopening of the application, the user is prompted to log in to gain access to their profile information to be properly matched with another person.
* Onboardoing : First time user visual tutorial for how to use the App properly.
* Uploading photos and videos
* Stream: User can view feed of the other users photos, like, pass, superlike
* Messaging Screen
* Setting Screen
* VIP Screen 

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Profile
* Chat Screen
* VIP
* Main Screen

**Flow Navigation** (Screen to Screen)

* Forced log in
   * Account creation if no, Log in is available
* Main Screen to see other people
* Chat Screen 
   * To see your matches and messages
* Profile
* VIP

## Schema 
Post
Property	Type	Description
objectId	String	unique id for the user post (default field)
author	Pointer to User	image author
image	File	image that user posts
caption	String	image caption by author
commentsCount	Number	number of comments that has been posted to an image
likesCount	Number	number of likes for the post
createdAt	DateTime	date when post is created (default field)
updatedAt	DateTime	date when post is last updated (default field)

### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
