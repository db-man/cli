## Debug

```
node bin/cli.mjs __test_dir__ split
node bin/cli.mjs __test_dir__ merge
```

## Publish npm

```
npm version patch
git push && git push origin v0.1.2
npm publish --access=public
```
