# scaffold-split-vue

This is a shell script that can create a Vue component that is split into 4 separate files corresponding to the Vue file, template file, style file, and script file. To use this script:

- Put the **scaffold-split-vue** file in your /bin directory (/usr/bin I found in WSL)
- cd into the directory you want to create the component in.
- Run the command: <code>scaffold-split-vue **_NameOfComponent_** </code>

You will then see a message output to the console and the following directory structure created:

- **_NameOfComponent_**
  - index.vue
  - script.js
  - style.scss
  - template.html
