<h1 align="center">React Electron with Typescript </h1>

<div align="center">

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

## Table of Contents

- [About](#about)
- [How to use](#usage)
- [Deploy to Desktop](#deploy)

## <div id="about">About</div>

Easy-to-understand-and-use boilerplate code for creating an Electron desktop app simply using Reactjs. Includes React Router

## <div id="usage">How to use</div>

1. Clone this repository.
```
git clone https://github.com/david-fernando/react-electron-ts.git
```
2. If you havent already, install Yarn globally.
```
npm install -g yarn
```
3. Navigate into project root and install dependencies.
```
cd <your-project-name> && npm install
```
4. Run dev server.
```
npm run start
```

## <div id="deploy">Deploy to Desktop</div>
1. Run the build process
```
npm run build
```
2. Go into your project folder using your file explorer. Navigate to the `dist` folder and open it. Then double-click `<your-project-name>` Setup 0.1.0. Your app should open and there should now be an icon on your desktop for this app.

**Use a Custom Icon**

Add a 256 x 256 .png or .ico image in your public folder. It should be either `icon.ico` or `icon.png`. Update the `icon` property in your `package.json` if necessary. Currently, it uses an image called `icon.png`, which is a graphic of a coffee cup. You'll only see this in production. For more info, see the [electron-builder documentation](https://www.electron.build/icons)