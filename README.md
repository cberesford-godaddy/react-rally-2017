# React Rally 2017 Notes
Notes and Examples from React Rally 2017 in Salt Lake City, UT.<br>
http://www.reactrally.com/

## Day 1

### Unpkg - Michael Jackson - 9:00 AM
Speaker: [Michael Jackson](https://github.com/mjackson)<br>
Topic: Unpkg.com<br>
Twitter: [@unpkg](https://twitter.com/unpkg)<br>
Demos: https://github.com/unpkg/unpkg-demos<br>
Local: [unpkg-demos](unpkg-demos) <br>

**Notes**
- What is it?
    - Global CDN for everything on npm
    - Quickly and easily load any file from any package
- Module support is coming to browsers

*"Just imagine what a cool world it would be if everyone only loaded React once..."*

### D3 and React - Shirley Wu - 9:30 AM
Speaker: [Shirley Wu](https://github.com/sxywu)<br>
Topic: D3 and React<br>
Presentation Link: https://github.com/sxywu/react-d3<br>
Local: [react-d3](react-d3) <br>

**Notes**
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

### React for IOT - Devon Lindsey - 10:30 AM
Speaker: [Devon Lindsey](https://github.com/devonbl) <br>
Topic: A Hand Wave of React for All Your Internet of Thangs <br>
Presentation Link: N/A <br>
Local: N/A <br>
Twitter: [@devonbl](https://twitter.com/devonbl) <br>

**Notes**
- What the heck is NFC? Near Field Communication
    + EX: Card that is used for mass transit, work badge, etc.
- What NFC is **not**
    + A tracking device
- "I have an NFC implant in my hand, I want to wire it up to my house using IOT technology" 😳
- Random fact: Arduino != Raspberry Pi
    + Raspberry Pi entry barrier is much lower - it has an awesome community
    + See: https://github.com/raspberrypi
- Technologies Used:
    + Johnny Five: http://johnny-five.io/ - used for IOT
    + raspi-io: https://github.com/nebrius/raspi-io - Provides IO for Johnny-Five on Raspberry Pi
    + react-hardware: https://github.com/iamdustan/react-hardware

TLDR: This woman literally put an NFC chip in her hand so she can unlock her house by swiping her hand... because keys are overrated.


