# Igniting the App

## What is NPM ?

- It is a package manager available for javascript applications. The default package manager for Node.js
- Before the NPM, In order to run the project, developer has to download project libraries manully. The developer has to check each package's version number and look for the correct dependency. Above process is a very time-consuming activity.
- So, NPM is the tool to overcome the above issues. The developer does not need to manage thrid-party packages for their project manually. Dependenices easily managed by tool like NPM

## What is npx ?

- Stands for Node packge execute.
- Npm package runner that can excute any package without intalling that package.

## What is difference between Dependencies vs devDependencies ?

- Dependencies - A dependencies required to run project effectively. - included into the final code bundle. - must need dependencies to run code. - can be added into the project : npm install < packageName >

- devDependencies - A dependency that are required while developing the app . - These dependencies are not required while executing. - can be added into the project : npm install < packageName > --save-dev

## What is .gitignore file? What should we add and not add into it ?

- .gitignore is the text file that tells the git which files or folders to ignore in the project.
- The files/ folders can be easily reproducible at a server or other machine-end, such files or folders added into a .gitignore file. Eg, dist, node_modules folder.

## What is Parcel/ Webpack? Why do we need it ?

- webpack, parcel, etc are the bundlers, use to minify the source code before shipping the code into prod.
- ### Bundler :
  - A bundler is a tool that bundles all source code files like js, css, images, and their dependencies into the new javascript output file.
  - Webpack, Parcel, Rollup, Browserify, etc are the different bundlers.
  ***
- ### In our project, a parcel is used as default bundler.

  - ### how to install parcel in the project :
    npm install --save-dev parcel

- Super powers of the parcle.js
  - #### Developemnt :
    - Dev server
    - Hot reloading
    - lazy mode
    - caching
    - https
  - #### Production :
    - Size Optimization
      - Minification of the code
      - Tree shaking
      - Development branch removal
      - Image optimazation
      - Compression
    - Cache optimazation
