<p align="center">
    <img width="300" src="images/logo.png"/>
    <h1 align="center">Senior Frontend Engineer</h1>
</p>

## About the role
We are looking for a Senior Engineer to help in creating performant and large scale applications, working on features improvements and be able to define technical designs and architecture before implementations.

## Task Overview

Imagine we are assigned to mointer some user's todo lists, each user have his own todo list which is different from other user's. and we have the privilages to create, update or delete items in user's data ( as admins ).

Our task is to create a simple interface to show a dropdown of user's and a list to show user's todo items.

Behind the scences we have access to the updates history, which means we can switch the view to see this user activity and the history of this user TODOs.

## Acceptance Criteria

- View start point will be showing a dropdown with a placeholder of select user.
- On selecting user show loader in TODO container while fetching data.
- Show each user TODOs in container after the dropdown list.
- We can Create, update and delete current selected user TODOs.
- Updates should reflect to user TODO's history which means we can see the updates we just did in the history tab.
- We can navigate between user's from the dropdown.

## Wireframe

|![TODO](./images/todos.png)|![History](./images/history.png)|
|--|--|
<p align="center"><a href="/images">Better Quality</a></p>


## Technical Requirments

> We are seeking to hire someone which is skilled using React, TypeScript and can do Unit Testing.

You are not required or sticked to specific technical tools, you can use whatever you want to achieve the task functionalties.

This task is to evaluate you ability to deal with data, and managing it.

### Technical Bounses

- Dont relay on CRA for the project. and create your own biolerplate.
- Solution is following Functional paradigm
- Solution is documented, consistant.
- Solution follows TTD, have tests for UI and functionalties.
- Add CI/CD using any of free services (CircleCI, Travis).
- Beautiful UI.
- Writing Beautiful README.

## Hints
- Refer to [db.json](/db.json) for demo data you can use or visit [jsonplaceholder.typecode.com](https://jsonplaceholder.typicode.com/) for fake API.
- You can use ContextAPI for managing the state and data logic.
- You can use `useReducer` hook for actions and state updates.
- You can fake-fetching data with `Promises` and `setTimeout` to show loaders for beautiful UI.
- More strong type more error free soultion.
- More test covarage more error free solution.

Finally we wish you all of Good Luck.
