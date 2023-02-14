# Three.js

## Setup
Download [Node.js](https://nodejs.org/en/download/).

## To be sure of the compatibility (only the first time) 
Uninstall and reinstall react-scripts
``` bash
# Open the terminal and run 
npm uninstall react-scripts
# Then run
npm install react-scripts
```
Manually change the react script version
- Go to your package.json and change the react-script version to 5.0.1
- Delete the node_modules folder
- Delete the package.lock.json
- Install dependencies (node modules)
  ``` bash
  npm install
  ```

## Run the project
``` bash
# Run the local server at localhost:8080
npm run dev

# Build for production in the dist/ directory
npm run build
```
