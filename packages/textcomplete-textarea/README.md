# @textcomplete/textarea

> Textcomplete editor implementation for Textarea elements.

## Install

```bash
npm install --save @textcomplete/core @texttcomplete/textarea
```

## Synopsis

```js
const { Textcomplete } = require("@textcomplete/core")
const { Textarea } = require("@textcomplete/textarea")

const editor = new Textarea(textareaElement)
const textcomplete = new Textcomplete(editor, strategies, option)
```