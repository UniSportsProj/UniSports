# **UniSports**
# Table of Contents
Overview
Product Spec
Wireframes
Schema

# Overview
Description
[Provide a brief description of your app, its purpose, and functionality.]
UniSports is an app where students who want to play pickup sports can post or find games happening now or near in the future. Students will sign up and will have access to a network of other students who are looking to play quick pick up games or fun tournaments.

# App Evaluation
[Evaluation of your app across the following attributes]

Category: [e.g., Social, Entertainment, Education] 
Sports Social Network
Mobile: [Is it a mobile application only?]
Yes
Story: [What story does your app tell?]
Students are willing to play sports but finding people to play with or where to play can pose a problem. This app serves as a central hub for students to easily express their need to play and connect with others who want to play sports with them
Market: [Target audience for the app] 
University Students in relatively similar geographic area.
Habit: [Is it a daily use app or occasional use?]
Depending on the sports habits of our users, the use will vary. Very active students may want to play daily and hence use the product daily, but more casual sports players will use this on a less frequent basis.
Scope: [Is it a broad or narrow app in terms of features?]
UniSports has a relatively narrow scope. The app will have thefunctionality that allows users to post, find and comment on current and upcoming events.

# Product Spec
# 1. User Stories (Required and Optional)
**Required Must-have Stories**

[User can [specific action, e.g., register an account]]
...
- User must be able to create an account
- User must be able to log in/out of that account
- User must be able to scroll through feed of other user posts
- User must be able to post their own event

**Optional Nice-to-have Stories**

[User can [specific action, e.g., persist user information across working sessions]]
...
- User can comment on other user posts
- User can enter location of event
- User can like other user posts
- 
# 2. Screen Archetypes
[Screen Name, e.g., Login Screen]
[Required User Feature: User can log in.]
- SignUp Screen
    - User creates a username and password that is remembered for login
- LogIn Screen
    - User inputs existing username and password to login
- Feed
    - User can view and interact with other user posts
    - User can scroll through posts
    - User can post their own event
- Create
    - User can Input a picture and caption (time, location, etc.) of their own event
    
# 3. Navigation
[First Tab, e.g., Home Feed]
[Second Tab, e.g., Profile] ... ... ...
Tab Navigation (Tab to Screen)
First Tab: SignUp/Login Screen
Second Tab: Feed Screen
Third Tab: Create

Flow Navigation (Screen to Screen)

[Screen Name]
Leads to [Next Screen]
[Another Screen Name]
Leads to [Another Screen]

[Add picture of your hand sketched wireframes in this section]
SignUp Leads to LogIn
Login Leads to Feed
Feed leads to Create
# Wireframes
[BONUS] Digital Wireframes & Mockups
[BONUS] Interactive Prototype
## Schema
## Models
[Model Name, e.g., User]

Property	Type	Description
username	String	unique id for the user post (default field)
password	String	user's password for login authentication
...	...	...
Networking
[List of network requests by screen]
[Example: [GET] /users - to retrieve user data]
...
[Add list of network requests by screen ]
[Create basic snippets for each Parse network request]
[OPTIONAL: List endpoints if using existing API such as Yelp]
