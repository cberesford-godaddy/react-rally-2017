## Better UIs with Finite Automata - David Khourshid - 4:00 PM
**Speaker:** [David Khourshid](https://github.com/davidkpiano) <br>
**Topic:** Infinitely Better UIs with Finite Automata <br>
**Twitter:** [@davidkpianon](https://twitter.com/davidkpianon) <br>
**Presentation Link:** http://slides.com/davidkhourshid/finite-state-machines#/ <br>
**Local:** N/A <br>

**Notes:**
- Don't use the Bottom-up approach to React development (even though basically everyone does it)
    + Difficult to understand
    + Difficult to test
    + Will contain bugs
    + Difficult to enhance
    + Features make it worse
- User interfaces are *graphs* - things can connect to other things in a non-hierarchical fashion.
- Deterministic Finite Automata
    + Finite: Limited number of options
    + Automata: options have a specific/logical order
    + Deterministic: State + action = next state, always
- State machines provide a *common language* for designers and developers
- A machine can be represented as a mapping of states, and each of those states can be represented as a mapping to their next states
- Statecharts: hierarchical finite state machines
- `npm install xstate` - handles transitioning between hierarchical states and concurrent states. See: https://www.npmjs.com/package/xstate