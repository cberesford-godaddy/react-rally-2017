## Mastering webpack from the inside out - Sean Larkin - 11:30 AM
**Speaker:** [Sean Larkin](https://github.com/TheLarkInn) <br>
**Topic:** Everything is a plugin!! Mastering webpack from the inside out <br>
**Twitter:** [@TheLarkInn](http://twitter.com/TheLarkInn) <br>
**Presentation Link:** N/A <br>
**Local:** N/A <br>

**Notes:**
- Webpack learning resource: https://webpack.academy/
- Tapable allows you to add and apply plugins to a javascript module
- 7 Tapable Instances (aka classes) - this is how Webpack works!
    + Compiler
        * Exposed via node API
    + Compilation (AKA the dependency graph)
        * Created by the compiler
        * Contains dependency graph traversal algorithm (it's like the brain)
    + The Resolver
    + Module Factories
        * Takes a successfully resolved requests and creates a module
    + Parser
        * Takes a module object and turns it into an AST to parse
        * Finds all requires and imports, then creates *Dependencies*
    + Template
        * Takes data and binds it to a view (data binding for your modules)
        * All kinds of templates
            - Main Template
            - Chunk Template
            - Module Template
            - Dependency Template

