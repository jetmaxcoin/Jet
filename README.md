# JETMAX (JET)

JETMAX (ticker: **JET**) is the primary utility token of the **JETMAX ecosystem**, deployed on **BNB Chain (BEP-20 standard)**.  
It serves as the foundation for liquidity, governance, and future ecosystem applications focused on logistics and decentralized finance (DeFi).

---

## Contract Information
- **Token Name:** JETMAX  
- **Symbol:** JET  
- **Standard:** BEP-20  
- **Decimals:** 18  
- **Contract Address:** `0x7847bffd0eb96c53a96af526643e2546efec0828`  
- **Network:** BNB Chain  

🔗 [View on BscScan](https://bscscan.com/token/0x7847bffd0eb96c53a96af526643e2546efec0828)

---

## Liquidity Pools
- **JET / BNB:** `0x573a67c44dfd23c5abc035e86054a9a1dce19f73`  
- **JET / JETMAX ecosystem pool:** `0x3b2a94b53cfc7afd97538673f6c38f7caf0075d7`  

---

## Key Features
- **Utility Token:** Core asset of the JETMAX ecosystem.  
- **Ecosystem Support:** Designed to back future tokens and applications.  
- **Liquidity Integration:** Active pools on BNB Chain to enable trading and stability.  
- **Scalability:** Built on BNB Chain for fast and secure transactions.  

---

## Usage
You can interact with the JETMAX token contract using any Web3-compatible wallet or library.  
Example with **Web3.js**:  

```javascript
const Web3 = require('web3');
const web3 = new Web3('https://bsc-dataseed.binance.org/');
const tokenAddress = "0x7847bffd0eb96c53a96af526643e2546efec0828";
const abi = [ /* JETMAX ABI here */ ];
const contract = new web3.eth.Contract(abi, tokenAddress);

async function getTotalSupply() {
  const supply = await contract.methods.totalSupply().call();
  console.log("Total Supply:", web3.utils.fromWei(supply, 'ether'));
}
getTotalSupply();
