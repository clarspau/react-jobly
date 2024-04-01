# React Jobly

This repository contains the frontend implementation for the Jobly application, built using React. Jobly is a job board platform where users can browse companies and available job listings, apply for jobs, and manage their profiles.

## Setup

1. **Backend Setup** : The backend for this project is provided as a solution to the express-jobly exercise. You can find the starter code [here](http://curric.rithmschool.com/springboard/exercises/react-jobly.zip). Make sure to recreate the jobly database using the provided `jobly.sql` file.
2. **Create React Project** : Create a new React project for the frontend.
3. **Start Backend** : Start the backend server on port 3001.

## Step One: Design Component Hierarchy

Take time to design the component hierarchy for the application. Sketch out the components you think you'll need and determine the most critical parts of state and where they should live.

## Step Two: API Helper

Create a `JoblyAPI` class to centralize API calls to the backend. This class will have helper methods for interacting with the backend endpoints.

## Step Three: Make Your Routes File

Define the routes for the application, including:

* Homepage
* Companies list
* Company details
* Jobs list
* Authentication routes: login, signup, logout
* Profile editing page

Create placeholder components for each feature area and a navigation component to navigate between different sections.

## Step Four: Companies & Company Detail

Implement components for displaying company details, listing all companies, and showing simple info about a company. Implement a search box for filtering companies, with backend filtering.

## Step Five: Jobs

Develop components for listing all jobs and displaying job details. Implement the "job card" component to show information about a single job.

## Step Six: Current User

Implement user authentication features including login, signup, and logout. Manage user authentication state centrally and update components accordingly.

## Step Seven: Using localStorage and Protecting Routes

Utilize localStorage to store user tokens and ensure persistence across page refreshes. Protect certain routes to require user authentication.

## Step Eight: Profile Page

Allow users to edit their profiles. Ensure changes reflect throughout the application.

## Step Nine: Job Applications

Enable users to apply for jobs. Implement functionality to differentiate between applied and unapplied jobs.

## Step Ten: Deploy your Application

Deploy both the frontend and backend using Render. Ensure proper setup of environment variables and configurations for both services.

## Deployment Instructions

Follow the provided deployment instructions to deploy both the backend and frontend applications on Render. Make sure to set up environment variables and configurations correctly for seamless deployment.
