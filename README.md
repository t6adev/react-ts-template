# React with TypeScript Template
This project is to know how do we set up react with typescript project to start as minimal.

## How to Start
After run `$ npm run start`, you can access provided url to see results.

## Settings
### tsconfig.json
```
{
  "compilerOptions": {
    "lib": [
      "dom", // To use react-dom lib
      "es2015" // To write code by es2015
    ],
    "jsx": "react" // To use JSX. `react` mode is to emit React.createElement
  }
}
```
