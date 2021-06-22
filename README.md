# PROJECT 4 README (STILL THINKING OF NAME) <!-- omit in toc -->

- [Overview](#overview)
- [MVP](#mvp)
  - [Goals](#goals)
  - [Libraries and Dependencies](#libraries-and-dependencies)
  - [Client (Front End)](#client-front-end)
    - [Wireframes](#wireframes)
    - [Component Tree](#component-tree)
    - [Component Architecture](#component-architecture)
    - [Time Estimates](#time-estimates)
  - [Server (Back End)](#server-back-end)
    - [ERD Model](#erd-model)
- [Post-MVP](#post-mvp)
- [Code Showcase](#code-showcase)
- [Code Issues & Resolutions](#code-issues--resolutions)

<br>

## Overview

With the recent explosion in popularity, NFTs have now become hottest thing to own and create. Here at <name of app>, we believe in creating a safe space for artists and collectors alike to experience the dynamic marketplace. Maybe you're a collector bringing NFTs from a different market or an artist that wants to redefine what digital art can be. Either way, <name of app> is the most expansive collection of NFTs to date. 
  
As an artist, you can easily upload your NFTs to the market in seconds. As a collector, you can view the art and contact the artist for a direct sale.
  
Here's what you can expect from our product roadmap for the remainder of 2021:
  - Add shopping cart functionality for a quick transaction through the site rather than contacting the artist directly.
  - Create more categories and different NFT markets
  - Dynamic landing page that will show you the different markets and 

<br>

## MVP
Server (Back End)
    - Have a RESTful JSON API.
    - Build a Ruby on Rails server, exposing RESTful JSON endpoints.
        - Build a database with 3 tables: users, GIF NFTs, and comments (associations on comment table)
    - Utilize Rails to define models for interacting with the database.
    - Implement working generic controller actions for Full CRUD (index, show, create, update, delete) between your non-User tables.

Client (Front End)
    - Have a working, interactive React app
        - Have at least 8 separate, rendered components in an organized and understandable React file structure.
        - Utilize functional or class React components appropriately.
        - Utilize state and props in your components efficiently.
        - Use only React for DOM Manipulation.
    - Consume data from your Ruby on Rails API, and render that data in your components.
    - Utilize React Router, for client-side routing.
    - Demonstrate Full CRUD actions ( index, show, create, update, and delete ) on the front end.

Styling
    - Be styled with CSS Flexbox or Grid
    - Implement 2 media queries for responsive design: desktop (default), tablet, and mobile.

<br>

### Libraries and Dependencies

> Use this section to list all supporting libraries and dependencies, and their role in the project. Below is an example - this needs to be replaced!

|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|      React       | _A JavaScript library for building user interfaces_ |
|   React Router   | _A collection of navigational components that compose declaratively with your application_ |
|     Ruby on Rails      | _Lorem ipsum dolor sit amet, consectetur._ |

<br>

### Client (Front End)

#### Wireframes



#### Component Tree

https://i.imgur.com/cju9Xe7.png

#### Component Architecture

> Use this section to define your React components and the data architecture of your app. This should be a reflection of how you expect your directory/file tree to look like. 

``` structure

src
|__ assets/
      |__ fonts
      |__ graphics
      |__ images
      |__ mockups
|__ components/
      |__ Header.jsx
|__ services/

```

#### Time Estimates

> Use this section to estimate the time necessary to build out each of the components you've described above.

| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Add Contact Form    |    L     |     3 hrs      |     2 hrs     |    3 hrs    |
| Create CRUD Actions |    H     |     3 hrs      |     1 hrs     |     TBD     |
| TOTAL               |          |     6 hrs      |     3 hrs     |     TBD     |

<br>

### Server (Back End)

#### ERD Model

https://i.imgur.com/ORdCDDr.png

<br>

***

## Post-MVP

- Landing Page with carousel of images and brand
- Add a filter table so users can assign NTFs a category
  - create clickable filters for easy navigation
- Add shopping cart

***

## Code Showcase

> Use this section to include a brief code snippet of functionality that you are proud of and a brief description.

## Code Issues & Resolutions

> Use this section to list of all major issues encountered and their resolution.
