htmlhint-inline-rules-breaks-cli

### Steps to reproduce
- run `npm run test`
    - Should report error `doctype-first` for file `document.without-inline-rule.html`, but no error found.

### Files
- src
    - `document-with-inline-rule.html`
        - This file has inline rule `doctype-first:false` and not have doctype directive.
    - `document-without-inline-rule.html`
        - This file does not have doctype directive.

### License
MIT
