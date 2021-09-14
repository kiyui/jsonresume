# jsonresume

My [jsonresume](https://jsonresume.org/), also available as a [Gist](https://gist.github.com/kiyui/fb02a6c54d922a251006a3639455b5e7) and hosted [here](https://registry.jsonresume.org/kiyui).

## usage

```sh
# setup
npm install

# previewing changes
npm run serve

# exporting pdf
PUPPETEER_EXECUTABLE_PATH=$(which chromium) npm run resume -- export resume.pdf
```

## publishing

Changes also need to be replicated on the Gist. This can be done by replicating the changes over with,

```sh
gh gist edit fb02a6c54d922a251006a3639455b5e7
```
