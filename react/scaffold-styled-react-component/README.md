# scaffold-styled-react-component

This is a shell script that can create a React component that is split into 2 separate files corresponding to the JSX file and a separate style.js file. This script assumes you are using styled-components to style your React application. I would recommend naming the component using kebab case for the script argument. This kebab case component name will be converted in the JSX file const export as a Pascal cased version. To use this script:

- Put the **scaffold-styled-react-component** file in your /bin directory (/usr/bin I found in WSL)
- cd into the directory you want to create the component in.
- Run the command: <code>scaffold-styled-react-component **_name-of-component_** </code>

You will then see a message output to the console and the following directory structure created:

- **_name-of-component_**
  - index.jsx (will export const NameOfComponent)
  - style.js
