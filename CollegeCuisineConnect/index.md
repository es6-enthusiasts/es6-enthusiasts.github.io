# College Cuisine Connect

Welcome to College Cuisine Connect, a project dedicated to helping students with limited cooking skills and resources find quality and healthy recipes.


## Table of Contents

- [Team Members](#team-members)
- [Overview](#overview)
- [User Guide](#user-guide)
- [Community Feedback](#community-feedback)
- [Developer Guide](#developer-guide)
- [Deployment](#deployment)
- [Continuous Integration](#continuous-integration)
- [Development History](#development-history)

## Team Members

|                                                                                                                        | Name             | Role                   | GitHub Handle    |
|------------------------------------------------------------------------------------------------------------------------|------------------|------------------------|------------------|
| <img src="https://github.com/julietteraubolt.png" alt="Juliette" width="100" height="100" style="border-radius: 50%;"> | Juliette Raubolt | Solutions Architect    | @julietteraubolt |
| <img src="https://github.com/loellelam.png" alt="Loelle" width="100" height="100" style="border-radius: 50%;">         | Loelle Lam       | UX Dev and Design Lead | @loellelam       |
| <img src="https://github.com/janeljo.png" alt="Janel" width="100" height="100" style="border-radius: 50%;">            | Janel Joson      | Development-Lead       | @janeljo         |
| <img src="https://github.com/kyla8.png" alt="Kyla" width="100" height="100" style="border-radius: 50%;">               | Kyla Lee         | Database Architect     | @kyla8           |
| <img src="https://github.com/willjsimmons.png" alt="William" width="100" height="100" style="border-radius: 50%;">     | William Simmons  | Scrum-Master           | @willjsimmons    |
 
All members of this team have agreed to abide by the following [contract](https://docs.google.com/document/d/1o7tGRP024l86Usm7qH7RX9-gTofHFc-ff8x5b5ZbVPA/edit?usp=sharing).

Feel free to contact us through our GitHub!

## Overview

College Cuisine Connect is a project dedicated to helping students with limited cooking skills and resources find quality and healthy recipes. It aims to foster a sense of community by allowing students to share their own culinary experiences and support each other in their culinary journeys.

The system provides a centralized platform that curates a diverse range of recipes tailored to the specific needs and constraints of college life. Recognizing that many students may have limited access to a fully equipped kitchen or face time constraints, College Cuisine Connect emphasizes recipes that are not only nutritious but also quick, budget-friendly, and easy to execute.

Through a user-friendly interface, students can explore a variety of recipes, ranging from simple microwave-based meals to those requiring minimal cooking equipment. The platform also takes into consideration dietary preferences, allergies, and restrictions to ensure inclusivity and accommodate diverse needs within the UH community.

### Purpose

College Cuisine Connect aims to accomplish the following goals:

- Provide a curated collection of simple and healthy toaster oven capable recipes suitable for students.
- Encourage students to adopt nutritious eating habits.
- Create a supportive community for sharing recipes and cooking experiences.

### Problem Statement:

Many college students struggle to maintain a healthy diet due to time constraints, limited cooking facilities, and a lack of easy-to-follow recipes tailored to their specific needs. The absence of a dedicated platform catering to students with toaster ovens exacerbates the issue, as conventional cooking resources often overlook this common dormitory appliance. Consequently, students find it challenging to adopt nutritious eating habits, leading to a higher prevalence of unhealthy dietary choices and potential long-term health issues.

### Solution:

In response to these challenges, we propose "College Cuisine Connect," a comprehensive platform designed to address the unique culinary needs of college students. Our solution involves providing a carefully curated collection of simple and healthy toaster oven-capable recipes specifically tailored for students, taking into account their time constraints and limited cooking resources. By doing so, we aim to empower students to make healthier food choices without compromising on convenience. Moreover, our platform will foster a supportive community where students can share their favorite recipes and cooking experiences, creating a collaborative environment that encourages the adoption of nutritious eating habits. Through College Cuisine Connect, we envision a positive shift in the dietary choices and overall well-being of college students, promoting a healthier lifestyle during their academic journey.

## User Guide

Learn how to start using College Cuisine Connect now! [Follow our tutorial here](https://es6-enthusiasts.github.io/CollegeCuisineConnect/tutorial).

## Community Feedback

We sought feedback from the community, and here are some reflections and thoughts shared with us.

- "I liked how the single recipe would pop up when viewing instead of taking me to another page."
- "The aesthetics were really pleasing, but what I really liked about it was how easy it was to navigate through the site without getting lost or confused."
- "I feel like a search bar would make the website easier to browse through."
- "The navigational bar at the top could have some aesthetic improvements "

Overall, the design and functionality were well-received, with most participants expressing positive sentiments. The application was unanimously considered easy to understand and navigate.

## Developer Guide

This section is intended for developers seeking guidance on downloading, installing, executing, and customizing the system.

1. Install [Meteor](https://www.meteor.com/install).
2. Clone the [College Cuisine Connect repository](https://github.com/es6-enthusiasts/ToasterOvenLovin) from GitHub to your local machine.
3. cd into the ToasterOvenLovin/app directory and install libraries with:
```$ meteor npm install```
4. Run the system with:
```$ meteor npm run start```
5. The application will appear at http://localhost:3000.

## Deployment
Our [College Cuisine Connect application](https://collegecuisineconnect.site/) is running on Digital Ocean.

## Continuous Integration
![ci-badge](https://github.com/es6-enthusiasts/ToasterOvenLovin/workflows/college-cuisine-connect/badge.svg)

College Cuisine Connect uses GitHub Actions to automatically run ESLint and TestCafe each time a commit is made to the default branch. You can see the results of all recent “workflows” [here](https://github.com/es6-enthusiasts/ToasterOvenLovin/actions).

The workflow definition file is located at .github/workflows/ci.yml.

## Development History

The development process for College Cuisine Connect conformed to [Issue Driven Project Management](http://courses.ics.hawaii.edu/ics314f19/modules/project-management/) practices. In a nutshell:

- Development consists of a sequence of Milestones.
- Each Milestone is specified as a set of tasks.
- Each task is described using a GitHub Issue, and is assigned to a single developer to complete.
- Tasks should typically consist of work that can be completed in 2-4 days.
- The work for each task is accomplished with a git branch named “issue-XX”, where XX is replaced by the issue number.
- When a task is complete, its corresponding issue is closed and its corresponding git branch is merged into master.
- The state (todo, in progress, complete) of each task for a milestone is managed using a GitHub Project Board.

The following sections document the development history of College Cuisine Connect.

### Project Mockups

The following images are mockups of pages we want to add to our application.

**Landing Page** <br>
<img src="/images/MockupCrop.png" alt="Landing Page" width="500">

**View Vendors** <br>
<img src="/images/ViewVendors.png" alt="View Vendors" width="500">

**View Recipes** <br>
<img src="/images/ViewRecipes.jpeg" alt="View Recipes" width="500">>

**Add Recipe** <br>
<img src="/images/AddRecipe.jpeg" alt="Add Recipe" width="500">>

**Edit Recipe** <br>
<img src="/images/EditRecipe.jpeg" alt="Edit Recipe" width="500">

Usage:
1. Browse the recipe categories and select a recipe that piques your interest.
2. Follow the step-by-step instructions, and don't forget to check the nutritional information.
3. If you have a unique and more importantly simple recipe to share, click on the "Contribute" button and submit your own creation.
4. Engage with the community by sharing your recipes, and seeking cooking advice from fellow students.

### Milestone 1
Objectives:
- [x] Deploy to Digital Ocean
- [x] Functional landing page
- [x] At least 4 mockup pages

Milestone 1 was managed using [GitHub Project Board M1](https://github.com/orgs/es6-enthusiasts/projects/1).

Sample of some implemented pages:

**Landing** <br>
<img src="/images/m1_landing.png" alt="Landing" width="500">

**Recipes** <br>
<img src="/images/m1_recipes.png" alt="View Recipes" width="500">

**Vendors** <br>
<img src="/images/m1_vendors.png" alt="View Vendors" width="500">

**Edit Recipes** <br> 
<img src="/images/m1_edit.png" alt="Edit Recipes" width="500">

### Milestone 2
Objectives:
- [x] Four pages in addition to the Landing page
- [x] At least one page in the deployment should read data from the database
- [x] At least one page in the deployment should write data to the database

Milestone 2 was managed using [GitHub Project Board M2](https://github.com/orgs/es6-enthusiasts/projects/4).

Sample of some implemented pages:

**Add Recipes** <br>
<img src="/images/add_recipe.png" alt="View Recipes" width="500">

**Edit Recipes** <br>
<img src="/images/edit_recipe.png" alt="View Recipes" width="500">

**Vendors** <br>
<img src="/images/m2_vendors.png" alt="View Recipes" width="500">

**My Cookbook** <br>
<img src="/images/m2_cookbook.png" alt="View Recipes" width="500">

### Milestone 3
Objectives:
- [x] Significantly improve the functionality of your system from Milestone M2.
- [x] Incorporate a significant amount of “real” data into your system.
- [x] Find at least five UH community members (not from ICS 314) to try out your system and provide feedback.
- [x] Implement acceptance testing.

Milestone 3 was managed using [GitHub Project Board M3](https://github.com/orgs/es6-enthusiasts/projects/5).

Sample of some implemented pages:

**Landing** <br>
<img src="/images/tutorial/home.png" alt="Home" width="500">

**My Cookbook** <br>
<img src="/images/tutorial/cookbook.png" alt="Cookbook" width="500">

**Vendors** <br>
<img src="/images/tutorial/myStores.png" alt="My Stores" width="500">

**Edit Recipe** <br>
<img src="/images/tutorial/editRecipe.png" alt="Edit Recipe" width="500"><br>

---

We're excited to help students embrace the simplicity and deliciousness of dorm room cooking. If you have any questions, suggestions, or feedback, please feel free to reach out.
