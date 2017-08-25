## D3 and React - Shirley Wu - 9:30 AM
**Speaker:** [Shirley Wu](https://github.com/sxywu)<br>
**Topic:** D3 and React<br>
**Twitter:** [@sxywu](https://twitter.com/sxywu) <br>
**Presentation Link:** https://github.com/sxywu/react-d3<br>
**Local:** [react-d3](react-d3) <br>

**Notes:**
- Data visualization
- Who *needs* control of the DOM?
- D3 only needs the DOM in 3 places
    + transitions (x,y position, color changes, etc.)
    + axes (we tell D3 what we want, it updates for us)
    + brushes (event binding)
- D3 doesn't need the DOM for
    + layouts
    + geo
    + shape
- React renders, D3 calculates
- D3 is more than enough for hover, click, and other simple interactions. React comes in handy for more complicated UIs and interactions.
- Use React with D3 when you need to manage state in your app
- When React renders
    + if user interaction *does* mutate data
    + propagates from parent
    + calculate in `componentWillReceiveProps`