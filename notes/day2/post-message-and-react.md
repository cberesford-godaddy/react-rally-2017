## Start a conversation between browser windows - Cara Kuei - 4:30 PM
**Speaker:** [Cara Kuei](https://github.com/carakuei) <br>
**Topic:** Start a conversation between browser windows <br>
**Twitter:** [@carakuei](https://twitter.com/carakuei) <br>
**Presentation Link:** N/A <br>
**Local:** N/A <br>

**Notes:**
- PostMessage is a browser API that safely enables cross-origin communication
- http --> https (can also technically do https --> http)
- Simple example usage:

```
window.postMessage(
    "Are you ready for football", // Message to be sent
    "https://www.nfl.com" // The target origin
)
```

- https://developer.mozilla.org/en-US/docs/Web/API/Window/postMessage
- What if you miss a message? Everyone needs to be both a *listener* and a *sender*
- Takeaways:
    + PostMessage is a simple, elegant API that provides modularity
    + Well structured messages
    + Be asynchronous (set it up correctly)
    + Use in React
    + Strategic migration (smaller yet highly effective changes)
    + Simplifying UX