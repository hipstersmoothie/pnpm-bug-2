To get the bugs

```sh
pnpm i
```

Then look in `node_modules/.pnpm/jest-image-snapshot@6.1.0_patch_hash=dzppfzxdiywokmfxhx5kk27c2e_jest@29.5.0/node_modules/jest-image-snapshot/node_modules/chalk/package.json` and notice `1.1.3` is installed even though no dep requires that version.
