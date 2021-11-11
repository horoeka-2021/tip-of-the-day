## Visual Studio Code tips

| Shortcut                  | Description                                                                     |
| ------------------------- | ------------------------------------------------------------------------------- |
| `ALT/Option` + `Up/Down`  | Move an entire line up and down                                                 |
| F12/Right Click Symbol    | Go to Definition                                                                |
| CTRL/COMMAND + TAB        | Switch between opened tabs                                                      | 
| `ALT/Option` + Left Arrow | Go back to previous location                                                    |
| `log` snippet             | In vscode type `log` and hit tab. Vscode will automatically write `console.log` |
| `ALT/Option` + Click      | Multi-cursor edit                                                               |
| `CTRL/COMMAND` + P        | Search by file name.<br>Very handy when working with large codebase.            |

## Animations using Framer Motion

```
npm i framer-motion
```

```js
import React, { useState } from 'react'
import { motion } from 'framer-motion'

function App () {
  return (
    <div>
      <motion.h1
        transition={{
          ease: 'easeIn',
          duration: 0.7
        }}
        initial={{
          opacity: 0
        }}
        animate={{
          opacity: 1
        }}
      >Some animatable animation</motion.h1>

    </div>
  )
}

export default App
```

## Developer Tools

[Flexbox debugger](https://daily-dev-tips.com/posts/chrome-devtools-flex-debugger/)

## Dicord

To share a block a of code use, surrond your code with triple ` (back ticks)
```
function myFunction() {
  console.log('hello')
}
```
