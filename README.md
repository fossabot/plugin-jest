# Jest Plugin for [Automated](https://github.com/automated-tools/automated)

[![Greenkeeper badge](https://badges.greenkeeper.io/automated-tools/plugin-jest.svg)](https://greenkeeper.io/)

Adds Jest snapshots

# Setup

Add the following to your `.gitignore`

```
*/.automated/jest/__index.js
```

Install automated

```bash
yarn add automated
```

Run automated

```bash
yarn automated
```

Add [Jest CLI options](https://facebook.github.io/jest/docs/en/cli.html) like
this

```bash
yarn automated jest\[--updateSnapshot --watch\]
```