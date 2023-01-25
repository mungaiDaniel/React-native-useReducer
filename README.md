# React-native-useReducer

useReducer is a React Hook that lets you add a reducer to your component.
example
```
const [state, dispatch] = useReducer(reducer, initialArg, init?)

```

**reducer**: The reducer function that specifies how the state gets updated.
**initialArg**: The value from which the initial state is calculated.

The **dispatch** function returned by useReducer lets you update the state to a different value and trigger a re-render.

