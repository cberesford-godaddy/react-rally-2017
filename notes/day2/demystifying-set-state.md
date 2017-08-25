## Demystifying setState() - Justice Mba - 2:30 PM
**Speaker:** [Justice Mba](https://github.com/Dajust) <br>
**Topic:** Demystifying setState() <br>
**Twitter:** [@daajust](https://twitter.com/daajust) <br>
**Presentation Link:** N/A <br>
**Local:** N/A <br>

**Notes:**
- "The core premise for React is that UIs are simply a *projection of data into a different form of data*..."
- "A component describes a UI"
- `setState()` - used to tell the UI it needs to update (and what parts need to be updated)

```
this.state = { value: 0 };

function increaseValue() {
    this.setState({ value: 1 });
    console.log(this.state.value); // 0
}
```

- As you can see from above, `setState()` needs to be *asynchronous* 
- The power of async `setState`:
    + Delay off-sscreen rendering
    + Split updates
    + Prioritze updates
    + Pause updates
    + Abort updates