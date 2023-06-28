# Sims 4 Toolkit - BufferFromFile Plugin

## Overview

This is a wrapper for [BufferFromFile](https://www.npmjs.com/package/bufferfromfile), so that it can optionally be included in [@s4tk/models](https://sims4toolkit.com/#/docs/models).

## Installation

Install the package as a dependency from npm with the following command:

```sh
npm i @s4tk/plugin-bufferfromfile
```

## Usage

To use this plugin, include the following at the beginning of your S4TK script. This only needed to be run once, but running it more than once will not cause any problems.

```js
// ESM / TS
import { registerPlugin } from "@s4tk/models/plugins";
import BufferFromFile from "@s4tk/plugin-bufferfromfile";
registerPlugin(BufferFromFile);

// CJS
const { registerPlugin } = require("@s4tk/models/plugins");
const BufferFromFile = require("@s4tk/plugin-bufferfromfile").default;
registerPlugin(BufferFromFile);
```

## Disclaimers

Sims 4 Toolkit (S4TK) is a collection of creator-made modding tools for [The Sims 4](https://www.ea.com/games/the-sims). "The Sims" is a registered trademark of [Electronic Arts, Inc](https://www.ea.com/). (EA). Sims 4 Toolkit is not affiliated with or endorsed by EA.

All S4TK software is currently considered to be in its pre-release stage. Use at your own risk, knowing that breaking changes are likely to happen.
