# A create-react-app template

This template has the folowing dependencies: 
```json
{
  "dependencies": {
    "styled-components": "^4.4.1"
  },
  "devDependencies": {
    "eslint": "^6.8.0",
    "eslint-config-airbnb": "^18.0.1",
    "eslint-plugin-import": "^2.18.2",
    "eslint-plugin-import-helpers": "^1.0.2",
    "eslint-plugin-jsx-a11y": "^6.2.3",
    "eslint-plugin-react": "^7.14.3",
    "eslint-plugin-react-hooks": "^1.7.0"
  }
}
```

You can start a new react project from this template by running this command:

`create-react-app [your project name] --template blank-project`

NOTE: Since cra-template doesn't support devDependencies yet, it will be necessary to copy devDepencies list from here and paste at your package.json file and run `npm install` or `yarn` to install all the packages.