### What WebAssembly Means for React - Lin Clark - 11:30 AM
Speaker: [Lin Clark](https://github.com/linclark) <br>
Topic: What WebAssembly Means for React <br>
Twitter: [@linclark](https://twitter.com/linclark) <br>
Presentation Link: N/A <br>
Local: N/A <br>

**Notes:**
- What is WebAssembly?
    + From [webassembly.org](http://webassembly.org/): "WebAssembly or wasm is a new portable, size- and load-time-efficient format suitable for compilation to the web."
    + It's possible/will be possible to update the DOM in the browser in programming languages other than JavaScript (such as C/C++)
- Possible benefits
    + Reuse code
    + Run faster in the browser
- WebAssembly can currently only understand `integers` and `floats`
- Decoding WebAssembly is faster than parsing JavaScript
- WebAssembly Flow
    + parse
    + compile + optimize
    + re-optimize
    + execute
    + garbage collection