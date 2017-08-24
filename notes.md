# React Rally 2017

## Day 1

### Michael Jackson - 9:00 AM
Speaker: [Michael Jackson](https://github.com/mjackson)
Topic: Unpkg.com
Twitter: @unpkg
Demos: https://github.com/unpkg/unpkg-demos

See (unpkg-demos)

What is it?
- Global CDN for everything on npm
- Quickly and easily load any file from any package

- Module support is coming to browsers

"Just imagine what a cool world it would be if everyone only loaded React once..."

### Shirley Wu - 9:30 AM
Speaker: [Shirley Wu](https://github.com/sxywu)
Topic: D3 and React
Presentation Link: https://github.com/sxywu/react-d3

See (react-d3)

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


