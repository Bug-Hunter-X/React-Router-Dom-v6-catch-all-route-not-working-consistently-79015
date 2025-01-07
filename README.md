# React Router Dom v6 Catch-All Route Issue

This repository demonstrates a problem with the catch-all route (`path="*"`) in React Router Dom v6.  The catch-all route is intended to handle any unmatched routes and display a 404 page. However, under certain conditions, this route does not always work as expected, leading to unexpected 404 errors.  This repo provides the buggy code and a working solution.

## Problem Description
The issue arises when combining specific route configurations, causing certain routes to be incorrectly handled by the application, despite having the catch-all route in place. The provided code example illustrates this issue.  The bug is described in detail in the `App.js` file.

## Solution
The solution, in `AppSolution.js`, shows how the problem can be resolved by ensuring that the catch-all route is placed correctly within the routing configuration, so it functions as intended and catches any remaining routes that were not explicitly matched.