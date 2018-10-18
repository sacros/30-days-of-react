- **Components**
    - heart of all react apps: 
    - self-contained module that renders some output.

- **DOM**
    - React doesn't work on browser's DOM immediately, but on a virtual DOM.
    - Rather than manipulating document in a browser after changes, it resolves changes on a DOM, built and run entirely in memory.
    - After the virtual DOM has been updated, React intelligently determines what changes to make to the actual browser's DOM.
    - The React Virtual DOM exists entirely in-memory and is a representation of the web browser's DOM.
