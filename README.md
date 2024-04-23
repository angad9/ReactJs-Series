# Introduction to React.js 👋

Welcome to the React.js folder! 🎉

This folder contains various subfolders covering different topics related to React.js development. React.js, commonly referred to as React, is an open-source JavaScript library used for building user interfaces.

## What is React? 🤔

React is all about building interactive and dynamic user interfaces for web applications. It allows you to break down your UI into reusable components, making it easier to manage and maintain your code.

**React's main features:**

- **Component-Based**: Build UIs using small, reusable components.
- **Virtual DOM**: Efficiently update and render components for better performance.
- **Declarative**: Describe how your UI should look, and React handles updates.
- **React Native**: Extend your skills to build mobile apps with React Native.

## Explore the Subfolders 📂

Within these subfolders, you'll find various React topics. However, it won't cover the basics like "what's a state" or "what are props" since I'm already familiar with them. Instead, you'll discover topics that might be new or less familiar, such as performance or other advanced concepts.

Feel free to explore these subfolders to deepen your knowledge of React. Enjoy! 💻🚀

# React Performance Workshop 🚀

📚 I've enrolled in the React Performance workshop by Steve Kinney! These notes summarize the key takeaways.

## What's Covered?

- 🧐 Dive into React's inner workings.
- 🛠 Build a toolkit to diagnose performance issues.
- 🚀 Learn best practices for a high-performing React app.

### High-Level Topics

Let's focus on:

- ⚡ Caching and memoizing components.
- 🏗 Effective component and state structuring.
- 🎯 Leveraging React 18's concurrency features.

## Inspect Performance with Dev Tools 🕵️‍♀️

If React acts up during development, grab the [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) for troubleshooting!

## Golden Rules for Success 🌟

1. **Less is More:** Before complexity, consider restructuring your components or state.
2. **Skip Unnecessary Work:** Sometimes, doing less is better. Try memoization and API suspense.
3. **Prioritize Urgent Tasks:** Handle critical tasks first, like API transitions.

## The React Rendering Cycle 🔄

React operates in three phases:

1. **Render Phase:** Identifies changes and updates the DOM smartly.
2. **Commit Phase:** Applies changes to the DOM.
3. **Clean Up:** Handles tasks like `useEffect` cleanup.

CSS animations usually run off the main thread, but changes to DOM nodes can be synchronous.

Memoization helps if it saves more time than it costs.

### Handling State Changes

React checks if a parent component changes to decide if a child should render. If props stay constant, the child won't re-render.

## Fiber & Rendering 🌐

- Fiber is React's magic structure for tracking components and optimizing rendering.

- Keys help React differentiate between components.

- Remember, React's focus is UI and state, not semantic HTML. Still, use semantic elements for accessibility and SEO.

## Reducing Rerenders 🔄

Minimize rerenders by placing components close to changed state.

## Suspense ⏳

Render pages as users need them, reducing the initial bundle size. Use the suspense API for gradual loading.

## Transitioning 🚀

React 18 brings more capabilities for deferring tasks. Exciting times ahead!
