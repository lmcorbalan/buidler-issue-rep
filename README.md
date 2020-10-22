This is meant to be used to reproduce an issue in Buidler.

Steps:

```bash
npm i
```

```bash
npm run start:ganache
```

```bash
npm test
```

- I would expect to get: `The address of Greeter in Ganache is:  0xe78A0F7E598Cc8b0Bb87894B0F60dD2a88d6a8Ab`

- Instead I get the error: `Error BDLR402: File SOME-PATH/buidler-issue-rep/node_modules/buidler-issue-contracts/contracts/Greeter.sol belongs to a library but was treated as a local one.`
