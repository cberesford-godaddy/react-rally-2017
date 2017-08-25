### Layperson's guide to React Fiber - Ben Ilegbodu - 2:00 PM
**Speaker:** [Ben Ilegbodu](https://github.com/benmvp) <br>
**Topic:** Layperson's guide to React Fiber <br>
**Twitter:** [@benmvp](https://twitter.com/benmvp) <br>
**Presentation Link:** N/A <br>
**Local:** N/A <br>

**Notes:**
- What is React Fiber?
    + Rewrite of reconciler
    + Prioritizes UI updates
    + Enables async rendering
    + Improves perceived performance
    + Will be released in next major React version (v16)
- React@16 is 20% smaller than React@15
- React@15.5 deprecations --> React@16 errors
- Adjacent JSX elements is *still* an error in React 16, but arrays are valid component return values in React 16!

```
const pageBody = () => ([
    (<aside key="aside"> LEFT NAV </aside>),
    (<section key="section"> MAIN BODY </section>)
]);
```

- Strings are also valid return values in React 16
- Uncaught errors now unmount your app --> blank page
- New `componentDidCatch` lifecycle method!
    +  Can be used to create error boundary components
    +  Wrap top-level route components in error boundary components
    +  This basically allows us to simulate server-side errors on the client
- No more `data-reactid` attributes from server - it's normal HTML
- Use new `ReactDOM.hydrate()` on client
- Fiber makes React renderers easier to build

`npm install --save react@next react-dom@next`