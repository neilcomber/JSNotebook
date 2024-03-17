## A standalone codepen that allows you to write and document code - with both preview and markup windows.
### Great for quickly showing conceprts ideas - capable of importing and running react.

Written with React, Redux & Typescript. 

### Some Key Technologies used:
- Transpiles & Bundles using ES Build
- Executes code in a preview window.
- Monaco open source code editor
- bulma swatch css library to do most of the styling
- react resize to have resizable code + preview windows
- react-md-editor to build the markdown editor windows
- immer to help with redux action creator updates
- Lerna to create a small CLI for startup, aswell as general file keeping

### WHAT THE BUNDLER CAN NOT DO:
- Do additional imports from CSS files
- does not perform checks the user isn't creating infinite loops.
- users will not be able to use cookies with their code
users will not be able to access local storage with their code

### To Run:
Download and npm install for dependencies
npx run start
Will automatically load in your browser, running on port 3000
