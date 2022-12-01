# Poseidon
[https://www.poseidon-hash.info](https://www.poseidon-hash.info)

## Important
Please enable solidity compilers optimize
```js
{
  compilers: [
    {
      version: "0.8.16",
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
    "contracts/helper/PoseidonT3.sol": {
      version: "0.8.16",
      settings: {
        optimizer: {
          enabled: true,
          runs: 9999,
        },
        evmVersion: "istanbul",
      },
    },
    "contracts/helper/PoseidonT4.sol": {
      version: "0.8.16",
      settings: {
        optimizer: {
          enabled: true,
          runs: 9999,
        },
        evmVersion: "istanbul",
      },
    },
  },
}
```

## Reference
[circomlibjs](https://github.com/iden3/circomlibjs)
- [poseidon_opt.js](https://github.com/iden3/circomlibjs/blob/main/src/poseidon_opt.js)
- [poseidon_gencontract.js](https://github.com/iden3/circomlibjs/blob/main/src/poseidon_gencontract.js)

## LICENSE
The [MIT License](LICENSE).