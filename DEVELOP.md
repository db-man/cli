## Debug

```
node bin/cli.mjs __test_dir__ split
node bin/cli.mjs __test_dir__ split __test_db__/users
node bin/cli.mjs __test_dir__ merge
node bin/cli.mjs __test_dir__ merge __test_db__/users
```

## Publish npm

```
npm version patch
git push && git push origin v0.1.2
npm publish --access=public
```
