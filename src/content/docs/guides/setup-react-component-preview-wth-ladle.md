---
title: Add local component previews with ladle
description: Cli commands to set up a lightweight react component preview environment used during development of individual components.
---

This dev server can also be used to run e2e tests on.

```sh

mkdir my-ladle
cd my-ladle
yarn init --yes
yarn add @ladle/react react react-dom
mkdir src
echo "export const World = () => <p>Hey</p>;" > src/hello.stories.tsx
yarn ladle serve

```
## Further reading

- Read more [about ladle in their docs](https://ladle.dev/docs/setup).
