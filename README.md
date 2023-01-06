# HotKeyPad

> A fast command launcher for React

<!-- [![NPM](https://img.shields.io/npm/v/hotkeypad.svg)](https://www.npmjs.com/package/hotkeypad) -->

## Install

```bash
npm install hotkeypad
```

## Usage

```tsx
import React from "react"
import ReactDOM from "react-dom/client"
import { HotKeyPad } from "hotkeypad"
import App from "./App"
import "./index.css"

ReactDOM.createRoot(document.getElementById("root") as HTMLElement).render(
  <React.StrictMode>
    <HotKeyPad>
      <App />
    </HotKeyPad>
  </React.StrictMode>
)
```

## License

[MIT](./LICENSE) © [jesubohr](https://jesubohr-dev.vercel.app/)
