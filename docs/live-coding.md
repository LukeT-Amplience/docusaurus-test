---
title: Live Coding Example 
description: How to implement live coding pages 
---

## Live coding in React with docusaurus

Explanation here 

```jsx live 
function ExampleLive(props) {
  const [counter, setCounter] = useState(0);

  return (
    <div>
      <h1>{counter}</h1>
      <button onClick = {() => setCounter(counter + 1)}>Increment</button>
      <button onClick = {() => setCounter(counter - 1)}>Decrement</button>
    </div>
  )
}
```