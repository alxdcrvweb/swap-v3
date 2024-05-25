# CoolSwap template

### Rinkeby

- Factory: 0x08c4f9FB1f7De09e87128e8dc3B769b7A02979F2
- Router: 0xA4E1f3fD10E2397f58926E215Ed331D7cDA14056
- Pair hash: 0x5b297b2db2b8aa0d3bddf1edfc64700e181be57f7b31aa184b7ba7f981692909
    "postinstall": "rmdir /S /Q node_modules\\@uniswap\\sdk && xcopy /E /I forks\\@uniswap\\sdk node_modules\\@uniswap\\sdk && rmdir /S /Q node_modules\\@uniswap\\default-token-list && xcopy /E /I forks\\@uniswap\\default-token-list node_modules\\@uniswap\\default-token-list && npm install @types/lodash && npm install @types/react-router@5.1.14",
