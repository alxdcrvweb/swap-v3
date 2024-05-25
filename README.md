# CoolSwap template

### Rinkeby

- Factory: 0x6Bd5A1A63ffF10De3c6B7C667040E9AE1B47fDf2
- Router: 0xA4E1f3fD10E2397f58926E215Ed331D7cDA14056
- Pair hash: 0xaf88dd15a55596feb9d67243c727bfd6144af12453963809bc91f0cfcf8241bc
    "postinstall": "rmdir /S /Q node_modules\\@uniswap\\sdk && xcopy /E /I forks\\@uniswap\\sdk node_modules\\@uniswap\\sdk && rmdir /S /Q node_modules\\@uniswap\\default-token-list && xcopy /E /I forks\\@uniswap\\default-token-list node_modules\\@uniswap\\default-token-list && npm install @types/lodash && npm install @types/react-router@5.1.14",
