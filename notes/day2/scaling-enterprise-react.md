### Scaling My First Enterprise React App! 🐙 - Jennifer Van - 11:00 AM
**Speaker:** [Jennifer Van](https://github.com/sugargreenbean) <br>
**Topic:** Scaling My First Enterprise React App! 🐙 <br>
**Twitter:** [@sugargreenbean](https://twitter.com/sugargreenbean) <br>
**Presentation Link:** N/A <br>
**Local:** N/A <br>

**Notes:**
- As your product grows, how do you keep React fast?
    + Define presentaiton vs. container components
        * Review: Presentation components are only concerned with how things **look**, container components are concerned with how things **work**
    + Utilize performance timeline to determine bottlenecks
        * Append ?react_perf
        * Open chrome devTools and click "Performance Tab" --> Record
        * Interact with app
        * Stop recording
        * View results
    + Remove unnecessary renders
        * Use `shouldComponentUpdate`
    + Prioritize network calls
        * Priority of rendering elements:
            - Highest: HTML
            - Highest: Styles
            - High: Ajax/XHR/fetch
            - Depends: Images
            - Depends: Scripts
            - Low: Font
        * How to prioritize network calls
            - Open dev tools --> Network tab --> Right click to show "Priority" column
    + Code splitting
