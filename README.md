# Electron-React-Typescript-starter files

A minimal secure boilerplate for writing Desktop Applications using [Electron](https://www.electronjs.org/), [React](https://reactjs.org/), [Webpack](https://webpack.js.org/) & [TypeScript](https://www.typescriptlang.org/) with Custom Titlebar.


<br>
<img src="assets/images/app_screen.png" />

<br>

# Custom Electron Window Titlebar & Menus etc.

**Following are the list of features it provides :**

- Custom Titlebar for Electron Window.
- Easily changable platform specific controls for max/min/close buttons using `windows` or `mac` value for `platform` property with `<WindowFrame>` in renderer.
- Titlebar menus can show/hide by pressing `alt` or `option` key.
- Window frame `title` prop displays in titlebar center when menus are toggeled off.
- Menu entries can be customized in `misc/window/titlebarMenus.ts` file.
- Menu items and windows controls layout or colors can be customized easily by modifying the `misc/window` modules.

<br><br>

# Core Features

- 🌟 Electron
- 🌀 TypeScript
- ⚛️ React
- 🥗 SASS/SCSS Loader
- 🛶 LESS Loader (optional)
- 🎨 CSS Loader
- 📸 Image Loader
- 🆎 Font Loader
- 🧹 ESLint
- 📦 Electron Forge
- 📐 Custom Window Frame
- 📐 Custom Window Titlebar
- 📐 Custom Window Menubar
- 🔱 Webpack & Configuration
- 🧩 Aliases for Project Paths
- 🔥 React Fast Refresh + Webpack HMR
- 🌞 Dark Mode + Light Mode (Theme)
- 🎁 Package Bundling (Distribution / Release)

<br>

## Custom Aliases for Paths

We can use predefined aliases for `import` paths already used in this project. Following are the details:

| Alias         | Target Path                |
| ------------- | -------------------------- |
| `@assets`     | `/assets`                  |
| `@main`       | `/src/main`                |
| `@renderer`   | `/src/renderer`            |
| `@common`     | `/src/common`              |
| `@misc`       | `/misc`                    |
| `@src`        | `/src`                     |
| `@components` | `/src/renderer/components` |

<br><br>

# Installation

<br>

Install dependencies using [pnpm](https://pnpm.io/) or [yarn](https://www.npmjs.com/package/yarn) or [npm](https://www.npmjs.com/) :

```bash
# using pnpm
pnpm install

# or using yarn
yarn install

# or using npm
npm install
```

<br />

## Start : Development

To develop and run your application, you need to run following command.
<br />
Start electron application for development :

```bash
yarn start
```

<br />

## Lint : Development

To lint application source code using ESLint via this command :

```bash
yarn lint
```

<br />

## Package : Production

Customize and package your Electron app with OS-specific bundles (.app, .exe etc)

```bash
yarn package
```

<br />

## Make : Production

Making is a way of taking your packaged application and making platform specific distributables like DMG, EXE, or Flatpak files (amongst others).

```bash
yarn make
```

<br />

## Publish : Production

Publishing is a way of taking the artifacts generated by the `make` command and sending them to a service somewhere for you to distribute or use as updates. (This could be your update server or an S3 bucket)

```bash
yarn publish
```

<br />

## Packager & Makers Configuration

This provides an easy way of configuring your packaged application and making platform specific distributables like DMG, EXE, or Flatpak files.

This configurations file is available in :

```bash
tools/forge/forge.config.js
```

For further information, you can visit [Electron Forge Configuration](https://www.electronforge.io/configuration)
