# React with TypeScript Template (Snowpack)
This project is to know how do we set up react with typescript project to start as minimal.
When you build an app by react with typescript, it's needed to use bundler for compiled code.
But if your app is assumed to run on modern browsers, You can write javascript code as esmodule type.
This shows the proof how you can set up an environment by [Snowpack](https://github.com/pikapkg/snowpack) and Babel.

## How to Start
After run `$ npm run start`, you can access provided url to see results.

## Settings
- Install unofficial react and react-dom. The reason is [here](https://www.snowpack.dev/#react).
- Prepare web_modules to access esmodules from released js/html files.
- To compile ts code by babel, Install babel libs and write its settings.
- If you want to check ts type correctly by `tsc --noEmit`, You have to fill up tsconfig.json properties. But it has no problem to just compile code if tsconfig.json was blank.

## Note
- Assumed `public/index.html` is copied to dist directory at build phase
