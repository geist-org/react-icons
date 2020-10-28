# React Icons

React icon components for Geist UI.

[![npm Version](https://img.shields.io/npm/v/@geist-ui/react-icons)](https://www.npmjs.com/package/@geist-ui/react-icons)
[![Build](https://img.shields.io/github/workflow/status/geist-org/react-icons/Build)](https://github.com/geist-org/react-icons/actions?query=workflow%3ABuild)

## Install

```
$ yarn add @geist-ui/react-icons
OR
$ npm install @geist-ui/react-icons
```

## Usage

```tsx
import React from 'react'
import { Code } from '@geist-ui/react-icons'

const App = () => {
  return <Code />
}

export default App
```

Icons can be configured with `color`, `size` and any SVG props:

```ts
<Code color="red" size={36} />
<Code color="blue" strokeWidth={2} />
```

## Other ways

1. You can include the whole icon pack:

```tsx
import * as Icons from '@geist-ui/react-icons'

const App = () => {
  return <Icons.Code />
}
```

2. You can include single icon:

```tsx
import Code from '@geist-ui/react-icons/code'

const App = () => {
  return <Code />
}
```

<br/>

## LICENSE

[MIT](https://raw.githubusercontent.com/geist-org/react-icons/master/LICENSE)
