# PetPix

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

A media-sharing social media app focused around pets. From dogs and cats, to monkeys and lizards. All sorts of furry and non-furry friends are welcome.

### App Evaluation

- **Category:** Social, Lifestyle, Pets & Animals
- **Mobile:** Mobile only (currently)
- **Story:** Shows the inside world of pet-owners and their friends. The good, bad, and ugly parts of the responsibility of owning a pet.
- **Market:** Pet owners & animal lovers
- **Habit:** Daily use
- **Scope:** Narrow

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can create an account
* User can sign into an account
* User can dictate what their feed will look like by answering a few introductory questions when they first create an account
* ...

**Optional Nice-to-have Stories**

* [User can [specific action, e.g., persist user information across working sessions]]
* ...

### 2. Screen Archetypes

- [ ] [**Login Screen**]
* [Required User Feature: User can log in / create an account.]
- [ ] [**Introductory Questions Screen**]
* [Required User Feature: User can determine their timeline.]
...
...
...

### 3. Navigation

**Tab Navigation** (Tab to Screen)


- [ ] [Home Feed]
- [ ] [Profile]
- [ ] [Post/Create/Upload]
- [ ] [Search & Explore]
...
...
...

**Flow Navigation** (Screen to Screen)

- [ ] [**Home Screen**]
  * Leads to [**Private messaging**]
  * Leads to [**User profile**]
  * Leads to [**User on timeline**]
  * Leads to [**Post/Create/Upload**]
  * Leads to [**User on timeline**]
  * Leads to [**Search & Explore**] 
- [ ] [**Profile**]
  * Leads to [**Edit profile picture**]
  * Leads to [**Settings**]
  * Leads to [**Privacy**]
- [ ] [**Create**]
  * Leads to [**Camera**]
  * Leads to [**Photo Gallery**]


## Wireframes

![PetPix-Wireframe](https://github.com/MurtajizMehdi/COP4655-Project/assets/90480945/b166be3a-d94b-4665-9881-8e4d29d0639e)

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 


### Models

[User]
| Property | Type   | Description                                  |
|----------|--------|----------------------------------------------|
| username | String | unique id for the user post (default field)   |
| password | String | user's password for login authentication      |
| Name     | String | User's name that's displayed on their account |
| email    | String | user's email where they'll get account info   |


### Networking

- [List of network requests by screen]
- [Example: `[GET] /users` - to retrieve user data]
- ...
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
