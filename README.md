# React Router Dom v6 Catch-all Route Issue

This repository demonstrates a problem with the catch-all route (`/*`) in React Router Dom v6.  The catch-all route is incorrectly triggered even when other routes should match.

## Problem Description
The `/*` route in `Routes` component always triggers regardless of other routes defined. This behavior makes it impossible to use a catch all route for 404 pages properly.

## Solution
The issue is solved by changing the order of routes, placing the catch-all route at the end.