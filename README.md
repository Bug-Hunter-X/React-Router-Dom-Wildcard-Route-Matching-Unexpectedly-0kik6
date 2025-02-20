# React Router Dom Wildcard Route Issue

This repository demonstrates a problem with React Router Dom's wildcard route ('*') unexpectedly matching before more specific routes, resulting in a 404 error.

## Description

The issue is observed when using nested routes in conjunction with a wildcard route. The wildcard route seems to take precedence over nested routes, even if a more specific path exists.

## Setup

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.

## How to Reproduce

Navigate to the application and observe the behavior of nested routes and the wildcard routes. You'll notice the wildcard route will be displayed instead of the intended nested route. 

## Solution

The solution involves reordering the routes, ensuring the more specific routes are defined before the wildcard route.