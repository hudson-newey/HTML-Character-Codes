# HTML Character Codes

This is no where near an exhaustive list and I am still working on the most obscure character codes

## How to use

```js
import { enDash } from "@hudson-newey/html-character-codes.js";

function htmlCode() {
    return `2019 ${enDash} 2020`;
}
```

## Why are all the character codes not consolidated into one big object

Because I want the HTML character codes to be tree shakeable
