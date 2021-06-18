# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## What is the issue
When including a single material ui icon in my component the render time goes from instant to around 8 secs.
If I copy the icon and create my own version it renders almost instantly again.

When running the code outside of storybook there is no issue.

## How to see the issue

In the project directory, you can run:
### `npx start-storybook`
Observe the app renders in the browser almost instantly after you see the Storybook 6.2.9 Started message in the command line

### `Edit the file Button.tsx to uncomment line 51 and repeat`
Observe the app renders in the browser but now takes several seconds after you see the Storybook 6.2.9 Started message in the command line

### `Edit the file Button.tsx to comment line 51 then uncomment line 52 and repeat`
Observe the app renders in the browser almost instantly after you see the Storybook 6.2.9 Started message in the command line

