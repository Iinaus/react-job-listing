# React Job Listing Project

## Table of contents
- [About](#about)
- [Features](#features)
- [Getting started](#getting-started)
  - [Dev setup step-by-step](#dev-setup-step-by-step)
  - [Production version](#production-version)

## About

This code is from the [React Crash Course 2024](https://www.youtube.com/watch?v=LDB4uaJ87e0) tutorial on YouTube.

The project uses [Vite](https://vitejs.dev/) as the build tool and JSON-Server for a mock backend.

With this exercise, we practiced:
- Using components and props
- Using React Hooks (useState, useEffect)
- Using React Router and its hooks (useParams, useNavigate)
- Using data loader
- Setting up JSON-Server and making API calls from the frontend

## Features

The project offers the following features:

- Pages with consistent layout (header, navbar)
- Main Page with different components
  - Hero
  - Home Cards
  - Recent jobs
    - Showing 3 jobs with More/Less description toggle
- Jobs Page
    - Showing all jobs with More/Less description toggle
- Add Job Page
    - Form for adding job and sending POST request with toast (if successful) and navigating back to job listing
- Single Job Page
    - Button to delete job sending DELETE request with comfirm and toast (if successful) and navigating back to job listing
    - Button to edit job
- Edit Job Page
    - Form showing information to edit and sending PUT request with toast (if successful) and navigating back to edited job

## Getting started

Instructions on how to set up and run the project. Make sure you have [Node.js](https://nodejs.org/) installed.

### Dev setup step-by-step

1. Install dependencies with command `npm install`
2. Run JSON Server on http://localhost:8000 with command `npm run server`
2. Run the frontend on http://localhost:3000 with command `npm run dev`

### Build production version

1. Use command `npm run build` to deploy production version
2. Preview production version with command `npm run preview`

Remember to create API server and update requests instead of using local server when deploying production version.
