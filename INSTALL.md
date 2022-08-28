### [Sandpack by CodeSandbox](https://sandpack.codesandbox.io) 

#### Install

After the [Sandpack installation and proper configuration](https://sandpack.codesandbox.io/docs/getting-started/install), you can configure Dracula Theme through _theme support_.

To use Dracula Theme, install the `@codesandbox/sandpack-themes` package; this official open source package contains all the Sandpack compatible themes.

```bash
npm install @codesandbox/sandpack-themes
```

or

```bash
yarn add @codesandbox/sandpack-themes
```

#### Activating theme

1. Now let's import the package.

```js
import { dracula } from "@codesandbox/sandpack-themes";
```

2. And in the Sandpack instance let's reference it.

```js
<Sandpack theme={dracula} />
```

3. Boom! It's working! 🦇

You can also read the [official Sandpack doc](https://sandpack.codesandbox.io/docs/getting-started/themes) on how to do this installation.

There is also [this repository](https://github.com/luxonauta/dracula-themed-sandpack-example) with an example with NextJs.
