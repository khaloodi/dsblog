---
layout: post
title: React Notes
---
### 📅 Schedule A Meeting:
- [Consultation & Project Scoping](https://calendly.com/kadad1312/1-on-1?back=1&month=2024-01)
## Handling Form Input React (steps)

- initialize state for the value of the input

- listen for changes on the input to detect when value is updated

- create an event handler that updates the value state

## Component Lifecycle

- every component instance follows a cycle: it’s mounted onto the DOM, it’s updated with changes in data, and it’s unmounted from the DOM 

## React Lifecycle Methods:

- built-in methods that get called at each point in the life cycle

- hooks that run code at key times in a component’s life cycle

- give the ability to control what happens when a component mounts, updates, and unmounts

## React Component Patterns

- destructure props

- validate props

- access DOM nodes with refs

- practice creating React components

- use PureComponent

(Shift + Cmd + L) -keyboard shortcut to select all of same item

## Updating State

- Without a function (use if state doesn’t depend on previous state)

`
this.setState({
	username: ‘Tyler’
})
`
- With a functions (use if state does depend on previous state)

`
this.setState( (prevState)=>({
	count: prevState.count + 1
}))
`
## Controlled Components Recap
Controlled components refer to components that render a form, but the "source of truth" for that form state lives inside of the component state rather than inside of the DOM. The benefits of Controlled Components are:

- instant input validation
- conditionally disable/enable buttons
- enforce input formats
In ListContacts component (reactnd-contacts-app), not only does the component render a form, but it also controls what happens in that form based on user input. In this case, event handlers update the component's state with the user's search query. And as we've learned: any changes to React state will cause a re-render on the page, effectively displaying our live search results.

### Make 💰 By Learning Programming:
- [Tesla](https://ts.la/khaled835973)
- [Liquid I.V. Hydration Multiplier 30 Stick, 16.93 Ounce](https://amzn.to/3ZFDjDq)
- [Xeela Pre workout](https://amzn.to/3NXWwMD)
- [Sour Strips](https://amzn.to/3EDWUM7)
- [Impractical Python Projects](https://amzn.to/3JpCpWH)
- [Designing Data-Intensive Applications](https://amzn.to/3Hgh5Sj)
- [Python for Data Analysis](https://amzn.to/3D0C8pl)
- [Python for Data Science Handbook](https://amzn.to/3XnZ1ez)
- [Hands-On Machine Learning w/Scikit-Learn & Tensorflow](https://amzn.to/3QTWoyt)

<br>