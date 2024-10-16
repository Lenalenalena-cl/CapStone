# Project Title

## Overview

AdoptMeow is a web application designed to help users find cats available for adoption within the Greater Toronto Area (GTA). The platform allows users to browse a list of available cats, search based on location and age, view detailed cat profiles, and contact shelters directly.

### Problem Space
Adopting a cat can require visiting multiple shelter websites, leading to a scattered user experience. AdoptMeow consolidates the available cats from shelters in the GTA into a single platform, making the adoption process more efficient and user-friendly.

### User Profile
Primary users: Individuals or families looking to adopt cats.

Special considerations:
Mobile-first design for easy browsing on smartphones.

### Features

As a user, I want to view a list of all cats available for adoption in the GTA.
As a user, I want to scroll back to the top of the cat list for easier navigation.
As a user, I want to search for cats by location and age, so that I can find cats that suit my preferences.
As a user, I want to view detailed profiles for each cat to learn more about them.
As a user, I want to view details about shelters and their available cats.
As a user, I want to open my default mail client by clicking on a shelter’s email to communicate with them.
As a user, I want to sign in, sign up, and log out to personalize my experience.
As a user, I want to send adoption applications or inquiries via the website.
As a user, I want to like or unlike cats to track my preferred ones.

## Implementation

### Tech Stack

Frontend: HTML5, CSS3 (with BEM and SASS for styling), JavaScript, React
Backend: Node.js (to handle server-side requests)
API: Custom-built API to manage cat profiles, shelters, user authentication, and form submissions

### APIs

Custom API: A fully custom API built with Node.js, which will handle data related to cat profiles, shelter details, user authentication, and user interactions (such as likes and application submissions).

### Sitemap

Homepage: Displays a list of cats available for adoption, with search filters for location and age.
Cat Profile: Displays detailed information about each cat, excluding health info, breed, or shelter ID.
Shelter Details: Displays shelter information, along with other available cats from that shelter.
User Account: Allows users to sign up, log in, and manage their favorite cats.
Application request: Enables users to submit adoption applications or inquiries.


### Mockups

Wireframes will be created using by sketch to illustrate the layout and design for the homepage, cat profiles, shelter details, and application form.

### Data

Cat Data: Name, age, history, description, location.
Shelter Data: Name, location, contact email.
User Data: Username, email, liked cats, submitted applications.

### Endpoints

GET /cats
GET /cats/:id
POST /cats/:id/like
DELETE /cats/:id/remove-like
GET /shelters
GET /shelters/:id
POST /shelters/:id/cats
DELETE /cats/:id/remove-like
GET /users
GET /users/:id
GET /users/:id/favorites
GET /users/:id/requests
POST /users/signup

## Roadmap

Week 1 (Oct 16-22):

Set up project environment and install dependencies.
Design wireframes for the homepage, cat profiles, and shelter details.
Develop the homepage with a list of cats and search functionality for location and age.
Implement scroll-to-top functionality for the cat list.
Week 2 (Oct 23-29):

Build detailed cat profile pages, excluding health and breed information.
Set up user authentication (sign in/sign up) and like/unlike feature.
Develop the shelter details page and email links for shelters.
Week 3 (Oct 30-31):

Create the adoption application form for sending inquiries and requests.
Conduct testing, debugging, and final refinements.
Deploy the application.
---

## Future Implementations
Add a user dashboard where users can track their liked cats and submitted applications.
Enable notifications for application status updates or shelter replies.
Implement additional search filters for more refined searches.

