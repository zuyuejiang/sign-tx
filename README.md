# Send a Signed JSON-RPC Request using the Alchemy SDK
🚀 Update: Mitigated from Göerli to Sepolia
</br> My work: https://sepolia.etherscan.io/tx/0x2d4f849cccc93f9b4b719e07911697ec382888986ea7636a4cd76aabfa44e776

### 🔄 Workflow
- `npm install`
- `touch .env`
    - `TEST_API_KEY`: get it from Alchemy Dashboard (create app)
    - `TEST_PRIVATE_KEY`: your private key
    - `TARGET_ADDRESS`: the recipient address
- `node index.js`
- open https://sepolia.etherscan.io/ to check your transaction!