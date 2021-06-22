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

_**Project Title** is lorem ipsum dolor sit amet. Phasellus dapibus fermentum risus vitae bibendum. Integer vel ipsum mollis odio sollicitudin ornare eu vel ex. In quis fringilla velit, ac maximus quam. Etiam eget placerat neque. Aenean faucibus sem non nisi lobortis ullamcorper._


<br>

## MVP
Server (Back End)
    - Have a RESTful JSON API.
    - Build a Ruby on Rails server, exposing RESTful JSON endpoints.
        - Build a database with at least 3 tables:
    - There must be at least 1 association between your tables. (1:m or m:m)
    - Utilize Rails to define models for interacting with the database.
    - Implement working generic controller actions for Full CRUD (index, show, create, update,       delete) between your non-User tables

Client (Front End)
    - Have a working, interactive React app
        - Have at least 8 separate, rendered components in an organized and understandable               React file structure.
        - Utilize functional or class React components appropriately.
        - Utilize state and props in your components efficiently.
        - Use only React for DOM Manipulation.
    - Consume data from your Ruby on Rails API, and render that data in your components.
    - Utilize React Router, for client-side routing.
    - Demonstrate Full CRUD actions ( index, show, create, update, and delete ) on the front         end.

Styling
    - Be styled with CSS (or SCSS, if you'd prefer).
    - Use Flexbox or Grid in your layout design.
    - Implement 2 media queries for responsive design on 3 screen sizes (including desktop).

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

> _Why is this necessary? Time frames are key to the development cycle. You have limited time to code your app, and your estimates can then be used to evaluate possibilities of your MVP and post-MVP based on time needed. It's best you assume an additional hour for each component, as well as a few hours added to the total time, to play it safe._

<br>

### Server (Back End)

#### ERD Model

https://i.imgur.com/ORdCDDr.png

<br>

***

## Post-MVP

> Use this section to document ideas you've had that would be fun (or necessary) for your Post-MVP. This will be helpful when you return to your project after graduation!

***

## Code Showcase

> Use this section to include a brief code snippet of functionality that you are proud of and a brief description.

## Code Issues & Resolutions

> Use this section to list of all major issues encountered and their resolution.
