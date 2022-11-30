# Poseidon
[https://www.poseidon-hash.info](https://www.poseidon-hash.info)

## Important
Please enable solidity compilers optimize
```js
{
    compilers: [
      {
        settings: {
          optimizer: {
            enabled: true,
            runs: 200,
          },
          evmVersion: "istanbul",
        },
      },
    ],
    overrides: {
      "contracts/optimized/PoseidonT3.sol": {
        version: "0.8.16",
      },
      "contracts/optimized/PoseidonT4.sol": {
        version: "0.8.16",
      },
    },
  },
```

## Reference
[circomlibjs](https://github.com/iden3/circomlibjs)
- [poseidon_opt.js](https://github.com/iden3/circomlibjs/blob/main/src/poseidon_opt.js)
- [poseidon_gencontract.js](https://github.com/iden3/circomlibjs/blob/main/src/poseidon_gencontract.js)

## LICENSE
The [MIT License](LICENSE).
