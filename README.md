### Demo for running Detox - E2E UI Testing for React Native app

- Install React Native CLI
- Install Detox CLI
- Open the Terminal and redirect to the app directory
- Run **npm install**
- Run **pod install** inside ios folder
- Run **detox build -c ios.sim.debug**
- Run **detox test -c ios.sim.debug**
- Run **detox build -c android.emu.debug**
- Run **detox test -c android.emu.debug**

> If you already have an existing `build` and you don't have any changes. It's not necessary to generate it again. You can just run `npm start` (it allows to start the webserver) and run `detox test -c *`
