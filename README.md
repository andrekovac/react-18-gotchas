# ⚛️🤓 React 18 gotchas

Collection of things I had to get used to after upgrading from React v17 to React v18

## React 18 features / differences

### [`React.StrictMode`](https://reactjs.org/docs/strict-mode.html)

`StrictMode` in React 18 [adds a second rendering immediately after initial mount](https://reactjs.org/blog/2022/03/08/react-18-upgrade-guide.html#updates-to-strict-mode).

When using the `useEffect` hook, you should always [add a cleanup if needed](https://beta.reactjs.org/learn/synchronizing-with-effects#step-3-add-cleanup-if-needed).

[Here](https://github.com/facebook/react/issues/24502#issuecomment-1118867879)'s what Dan Abramov has to say about it.

However, sometimes this can be a bit trickier...

*TBC*

### `useSyncExternalStore` hook

*TBC*

### `Suspense` and `startTransition`

- [What is tearing?](https://github.com/reactwg/react-18/discussions/69)


## About

This is a living document and will be continously expanded as I learn more about React 18 🤓.
