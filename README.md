# TutorialToken Truffle Box

This box has all you need to get started with our [Open Zeppelin (TutorialToken) tutorial](http://truffleframework.com/tutorials/robust-smart-contracts-with-openzeppelin).

## Installation

1. Install truffle and an ethereum client. For local development, try EthereumJS TestRPC.
    ```javascript
    npm install -g truffle // Version 3.0.5+ required.
    npm install -g ethereumjs-testrpc
    ```

2. Download box.
    ```javascript
    truffle unbox tutorialtoken
    ```

3. Compile and migrate the contracts.
    ```javascript
    truffle compile
    truffle migrate
    ```

4. Run the `liteserver` development server for front-end hot reloading. For now, smart contract changes must be manually recompiled and migrated.
    ```javascript
    npm run dev
    ```

**NOTE**: This box is not a complete dapp, but the starting point for the [Open Zeppelin (TutorialToken) tutorial](http://truffleframework.com/tutorials/robust-smart-contracts-with-openzeppelin). You'll need to complete that for this to function.
