- add cdn links for reactjs
- place empty div <div id="root"></div> in index.html
- create app.jsx under src directory to update the data in above mentioned div tag
- It doesn't work as expected hence we need to follow below steps
    - install nvm
        - update path for nvm from bashrc to zshrc
    - install node.js and npm via nvm
    - exectue below command in application root directory
        - npm init -y
            - this creates package.json
        - npm install babel-cli@6 babel-preset-react-app@3
            - this is required to convert next gen javascript syntax to convert into old syntax which is supported by all browsers.
- Run npx babel command
    - npx babel --watch src --out-dir . --presets react-app/prod
        - this creates app.js (converted version of app.jsx in src directory) in root directory.
- Include app.js in index.html


