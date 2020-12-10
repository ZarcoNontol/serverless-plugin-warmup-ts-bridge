# serverless-plugin-warmup-ts-bridge

The library resolves [a warmup and typescript issue](https://github.com/prisma/serverless-plugin-typescript/issues/125).


And also resolves: 

- [suguru03/serverless-plugin-warmup-ts-bridge/issues/5](https://github.com/suguru03/serverless-plugin-warmup-ts-bridge/issues/5)
- [suguru03/serverless-plugin-warmup-ts-bridge/issues/6](https://github.com/suguru03/serverless-plugin-warmup-ts-bridge/issues/6)


Credits to: [jkachhia](https://github.com/jkachhia)

Repo with the fix: [pmcretail/serverless-plugin-warmup-ts-bridge](https://github.com/pmcretail/serverless-plugin-warmup-ts-bridge)


## Install

```sh
$ npm install -D @zarconontol/serverless-plugin-warmup-ts-bridge
```


```yaml
// serverless.yaml
plugins:
  - serverless-plugin-warmup-ts-bridge
  - serverless-plugin-warmup
  - serverless-plugin-typescript
```
