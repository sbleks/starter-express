# Remix Starter for Express

Welcome to Remix!

This is a starter repo for using [Remix](https://remix.run) with [Express](http://expressjs.com/).

## Development

After cloning the repo, rename `.npmrc.example` to `.npmrc` and insert the license key you get from [logging in to your dashboard at remix.run](https://remix.run). 

> Note: if this is a public repo, you'll probably want to move the line with your key into `~/.npmrc` to keep it private.

Then, install all dependencies using `npm`:

```sh
$ npm install
```

Your `@remix-run/*` dependencies will come from the Remix package registry.

Once everything is installed, start the app in development mode with the following command:

```sh
$ npm run dev
```

This will run a few processes concurrently that will dynamically rebuild as your source files change. To see your changes, refresh the browser.

> Note: Hot module reloading is coming soon, which will allow you to see your changes without refreshing.

## Production

To run the app in production mode, you'll need to build it first.

```sh
$ npm run build
$ npm start
```

This will start a single HTTP server process that will serve the app from the files generated in the build step.

## Documentation

Detailed documentation for Remix [is available at remix.run](https://remix.run/dashboard/docs).

## Prefer TypeScript?

The [default branch of this repo](https://github.com/remix-run/starter-express) does the same thing, but using TypeScript.
