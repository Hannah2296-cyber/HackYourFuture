# Reading Material React Week 2

## Agenda

These are the topics for week 2:

1. [Hooks](https://study.hackyourfuture.net/#/react/react-hooks.md)
   - **ONLY THE useEffect HOOK**
2. [API calls in React](https://study.hackyourfuture.net/#/react/api-calls.md)
   - When to load data
3. [Client-side routing](https://study.hackyourfuture.net/#/react/routing.md)
   - React-router
   - Protected routes

## Important note on React

> In the React world, there is a huge shift happening since the introduction of 'hooks' in 2018. Before hooks React was built using both class and function components. Currently it is recommended to use only function components in combination with hooks for all of the code you build from now on. When you are going to do research on your own or when you get into your internship you are going to run into class components however. This will be less and less as time goes on and hopefully we can remove this at some point in the future.

> We at HackYourFuture will only be teaching you the recommended way of building applications and have provided a section in the study book to share the most basic details on how to read class components [here](https://study.hackyourfuture.net/#/react/class-vs-function-components.md). If you encounter class components in your research, try to look for a more up to date tutorial, question, or video. If you encounter class components during your internship, then convert it to a function component. The developers will love you :).

## Week goals

Last week we learned the basic building blocks of React and how to think in components. This week we are going to introduce some more advanced techniques to give you even more power!

Firstly, it is time to work with API's again. In vanilla JavaScript we learned about the fetch mechanism, but when thinking in a component way we need to approach it a little differently. To do this we need to make use of the `useEffect` hook, so let's revisit the [hooks](https://study.hackyourfuture.net/#/react/react-hooks.md) page and read up on the `useEffect` section. With knowledge of the `useEffect` hook we can take a look at the study book [here](https://study.hackyourfuture.net/#/react/api-calls.md) to learn how you can interact with an API using React.

Next, let's look at routing. Because we build single page applications in React, the location in the address bar has no effect on what we should show. When building more advanced applications that becomes a problem, as we want to be able to define different pages. To solve this we use what is called client-side routing, have a look [here](https://study.hackyourfuture.net/#/react/routing.md).

## Finished?

Are you finished with going through the materials? High five! If you feel ready to get practical, click [here](./MAKEME.md).
