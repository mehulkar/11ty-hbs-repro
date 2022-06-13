## repro

1. Clone this
2. `npm ci`
3. `npm run build`
4. See that build fails with error

    ```
    [11ty] 1. Having trouble rendering liquid template ./does-not-work.md (via TemplateContentRenderError)
    [11ty] 2. unexpected token at "@foo \"default\"", file:./does-not-work.md, line:1, col:6 (via ParseError)
    [11ty] 3. unexpected token at "@foo \"default\"" (via AssertionError)
    ```

See it working

1. Clone this repo
2. `npm i -D @11ty/eleventy@0.12`
3. `npm run build`
