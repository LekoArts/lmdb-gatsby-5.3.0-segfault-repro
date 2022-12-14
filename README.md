# LMDB Gatsby 5.3.0 Segfault

Reproduction for https://github.com/gatsbyjs/gatsby/issues/37246. Seems to only happen on Mac.

Run `npm install --legacy-peer-deps`/`yarn install` and then `yarn develop` to run into this error:

```shell
$ gatsby develop
⠋ compile gatsby files
error Command failed with signal "SIGSEGV".
```