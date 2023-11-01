## Debug

```
node bin/cli.mjs __test_dir__ split
node bin/cli.mjs __test_dir__ split __test_dbs_dir__/users
node bin/cli.mjs __test_dir__ merge
node bin/cli.mjs __test_dir__ merge __test_dbs_dir__/users
```

## Publish npm

```
npm version patch
git push && git push origin v0.1.2
npm publish --access=public
```
