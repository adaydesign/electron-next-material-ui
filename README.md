# Electron application example

This example show how you can use Next.js inside an Electron application to avoid a lot of configuration, use Next.js router as view and use server-render to speed up the initial render of the application.

For development it's going to run a HTTP server and let Next.js handle routing. In production it use `next export` to pre-generate HTML static files and use them in your app instead of running an HTTP server.

**You can find a detailed documentation about how to build Electron apps with Next.js [here](https://leo.im/2017/electron-next)!**

## How to use

Install it and run:

```bash
npm install
npm run start
# or
yarn
yarn start
```

You can create the production app using `npm run dist`.
