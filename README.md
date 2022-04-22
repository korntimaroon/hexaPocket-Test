//3333aaaa - mishaiphone
# DEXCANARY HEXAPOCKET MEGAPROGECT

HEXA POCKET CRYPTOCURRENCY WALLET

## Install Dependency


> Main Dependencies for Hexa Pocket


| Dependency | Version | Owner | Note |
|------------|---------|-------|------|
| Hexa Pocket Secret Phrase Generator | 1.1.0 | Dexcanary | Generating Secret Phrase For User |
| Hexa Pocket Cryptocurrency | 1.0.0 | Dexcanary | Generating and Checking Cryptocurrency Address  |
| Dexcanary Number and Text | 1.0.0 | Dexcanary | Text and Number Package |
| Dexcanary Hexa Pocket Package | 1.1.0 | Dexcanary | Others Package for Hexa Pocket Features |
| Next Router | - | Next | Changing file |
| Next Link | - | Next | Direct to file |
| Next Script | - | Next | JS Compiler in NextJS |
| ethereum-blockies-base64 | - | - | Generating Ethereum Addrress Profile |
| reactjs-popup | - | - | Modal and Popup for Dexcanary |
| Web3js | - | web3 | All cryptocurrency Package |
| Axios | - | Axios | Fetch website or link |

> Other Dependencies for Hexa Pocket

- useState
- useEffect Hooks
- Component
- useRef

## File Arranging System Catagories in Hexa Pocket

Dexcanary Hexa Pocket file store are devide into five (5) catagories

### UI (User Interface) - CSS

**File**
- Home.module.css

### UX (User Experience) - JS, TS

**Wallet File**

| File | Note | 
|------|------|
| /account/wallet.js | Show wallet balance with transaction service and history |
| /account_management.js | Show your store wallet address with professional activity and calculation |
| /setting.js | Hexa Pocket Wallet Setting |
| /lockPage.js | Hexa Pocket lock page |

**Privacy File**

| File | Note | 
|------|------|
| /account_service/createAccount.js | create account file |
| /account_service/importAccount.js | import account file |


### Component File - JS, TS

Most of the Component File Store is about 'tip, comment, announcement and a small structure'


**Component File**

| File | Note |
|------|------|
| /components/

### Transaction - JS, TS

Transaction Catagories is using [```Window.open()``` method](https://developer.mozilla.org/en-US/docs/Web/API/Window/open) to verified the trasaction or to confirmed the transaction

The Transaction Feature will read the condition of the blockchain and will display the UI.

Hexa Pocket Standard transaction fee is 0.9% of all transaction

**File**

| File | Note |
|------|------|
| /transaction.js | Transaction |

### Database System [IPFS](https://ipfs.io/) Cluster - JS, TS

Hexa Pocket will use [OrbitDB IPFS Database](https://orbitdb.org/). It will store in a DocumentDB form

Each Person will have a key (Primary Key - Secret Phrase Key) when the user key the password the program will automaticly request the key from OrbitDB Store Database to check the password.


**Store Format (Not a real addrress public and a private key)** 

```json
[{"hexaID":"123456789012","secretPhrase":"fly end mouth majority bill natural tree nothing safe election meeting expert","password":"1234567890","walletStore":[{"walletAddress": "31f3be31bb29b2e7ac0225b2d46a071ca2c5737884ca6441baedac9b7b150b34","walletPrivateKey":"739483ad1f634086c04b0273da3825d291aa54adf8d76537dbe5698fc89baa0a"}]}]
```

- hexaID - Store UserID in form of SHA-256




## Blockchain Smart Contract (Hexa Pocket Router - UNISWAP API) Method

### Swap Token

- Swap Crypto currency Token

**Parameter**

- Token[from, to]

- Address[number]

- Amount[number]

- GasLimit[number]

### Sent Back Money

- Sent Money Back to Hexa Pocket Main Wallet

**Parameter**

- Token[addrress]

- Amount[number]

### Sent Money

- Sent Money to the address you given

**Parameter**

- Token[addrress]

- Amount[number]

- Addrress[from, to]

- GasLimit[number]
