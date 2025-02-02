# React Router v6 Nested Route Bug

This repository demonstrates a bug in React Router v6 where nested routes fail to render properly when a parent route uses dynamic parameters.  The issue occurs when a route with parameters such as `/users/:userId` is nested within other routes.  The User component, despite being correctly defined, does not render.

## Solution

The solution involves using the `useParams` hook correctly within the nested components to access the dynamic parameters.