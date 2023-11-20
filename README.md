# Steps to replicate the ts6059 error

1. yarn
2. Go check the file `packages/package-c/DogBus.vue` (no error when opening)
3. Ctrl + S -> error showing up on line 8

```
File 'monorepo-ts-vue-test/node_modules/@test/package-b/Bus.vue.ts' is not under 'rootDir' 'monorepo-ts-vue-test/packages/package-c'. 'rootDir' is expected to contain all source files.
  The file is in the program because:ts(6059)
```
