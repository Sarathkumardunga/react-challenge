# Extend React Challenge

This is bare-bones version of own of our client apps, where we ask candidates to build out a small application. The goal: give both the candidate and the Extend team a chance to interact on a realistic, but limited (shooting for just a few hours), task. We see this as a two-way evaluation, for the team and the candidate to decide if its a good fit.

### Setup
```
git clone https://github.com/helloextend/react-challenge.git
cd react-challenge
yarn
yarn start
 ```
 You should now have the app running on http://localhost:8080

## Challenge
1. Review the mock up available on [Figma](https://www.figma.com/file/GsigoCnExV2jjTBanMZwFr/Dog-Breeds) (you will need to sign up for a free figma account to be able to inspect all the elements for paddings/margins etc)
2. Review the [Dog.ceo api documentation](https://dog.ceo/dog-api/)
3. The goal of this challenge is to be able to search for a breed of dogs in a search input and then display up to 10 images of that breed of dog on screen
4. You should be able to favorite and unfavorite images of dogs, moving them into and out of the favorites section of the page
5. Add typings for any functions or Objects that are being used in the application
6. Add tests for any components you write. For testing, focus on validating any logic or functionlity that has been introduced in the component
7. If anything is unclear, please ask :)

## Extended Tasks
You want to take this further or have extra time?  Awesome, choose any of these extension tasks that interest you:
- Add a section below the search bar that keeps track of what has previously been searched
- Clicking on one of those previous searches invokes a new search of that breed
- Visually distinguish between previous searches that were successful (200) and unsuccessful (404)
- Display a running total of the number of times each search was run. ie. `Hound x 2`, `no good search x 4`
- Refactor your state management to use [Redux Sagas](https://redux-saga.js.org/) and selectors
- Add a `production` webpack config that bundles and minifies the code
- Deploy a minified version to Netlify 
