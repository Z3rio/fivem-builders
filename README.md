# FiveM Builders

This repo aims to be a more maintained version of the [yarn/webpack builders](https://github.com/citizenfx/cfx-server-data/tree/master/resources/%5Bsystem%5D/%5Bbuilders%5D) for FiveM.

## Main Changes

FiveM's official version of these resources hasn't been touched in nearly a year for yarn, and 4 years for webpack.
So its obvious that some things oughta be outdated.

### Let packages be ignored by yarn

Simply add `"fivemIgnore": true,` to the resource's `package.json` file, and it
shall be completely ignored by yarn.
