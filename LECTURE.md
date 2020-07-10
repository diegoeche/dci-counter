* React-Redux

** Motivation

*** React

Change things in the DOM faster

*** Redux

UI and State can interact in weird ways.

Redux is just a way to make UI and State play nice to each other.

**** How does Redux does that?

Using some rules

- Single Source of Truth
- State is Read Only
- Changes are made with pure functions


* Getting Started Template

Code is based on the official React-Redux Template. But I changed things to make it
simpler.

You can find the code here: <add-url>

## Let's just run the code:

```
npm start
```

LIVE CODING


** Single Source of Truth

There's ONE and only ONE Store.

But since is super big, let's split the store into "Slices"


** State is Read-Only

Let's use a function to read the state, so we don't change it by accident



** Changing Data from the State

Don't change the State, use pure functions (Reducers)

* Implementing a Counter using Redux Principles

* What is the Store?

- Where state lives
- Where we define how the state can be changed
