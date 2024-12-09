mkdir my-electron-app && cd my-electron-app
npm init
npm install --save-dev electron
npm start
npm install --save-dev @electron-forge/cli
npx electron-forge import
npm run make

name and description in package.json is required for electron-forge