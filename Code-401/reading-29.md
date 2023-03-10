# Component Lifecycle & the useEffect() Hook

[Effects Hook](https://reactjs.org/docs/hooks-effect.html)

**What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?**

- It lets us access any props from the effect. Since useEffect is in a component, effects will happen after rendering. With using its counterparts in class components, there are times where you'll need to duplicate code to ascribe to lifecycle methods.

When using the useEffect Hook:

  **What does useEffect do?**

    - useEffect does a thing after [every] render.

    - lets us express different side effects after a component renders.

  **Why is useEffect called inside a component?**

    - It's called inside a component so it can have access to any props right from the effect. Aka it's within the fn scope.

**Explain the importance of properly implementing effects with Cleanup:**

- Implementing effects w/ cleanup is important as to not introduce a memory leak.

- Returning a function from our effect is the optional cleanup mechanism for effects. 

- React will cleanup when the component unmounts-- will cleanup from the previous render before running the effects next time.