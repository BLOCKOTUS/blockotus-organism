<a href="https://github.com/danielfebrero">
    <img
         src="https://img.shields.io/github/followers/danielfebrero?label=danielfebrero&style=for-the-badge&logo=github"
     />
</a>
<a href="https://github.com/BLOCKOTUS/organism">
    <img
         src="https://img.shields.io/github/stars/BLOCKOTUS/blockotus-organism?logo=github&style=for-the-badge"
     />
</a>
<a href="https://github.com/BLOCKOTUS/organism">
    <img
         src="https://img.shields.io/github/license/BLOCKOTUS/blockotus-organism?style=for-the-badge"
     />
</a>

<br />

# || BLOCKOTUS || DID for Hyperledger

<br />
<br />
<br />

<p align="center">
<a href="https://nodejs.org/en/">
  <img 
      style="margin-right: 0px" 
      height="60px" 
      src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Node.js_logo_2015.svg/1200px-Node.js_logo_2015.svg.png" 
  />
</a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
  <img 
      style="margin-right: 50px" 
      height="60px" 
      src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/JavaScript-logo.png/240px-JavaScript-logo.png" 
  />
</a>
<a href="https://www.hyperledger.org/use/fabric">
  <img 
      style="margin-right: 0px" 
      height="60px" 
      src="https://www.hyperledger.org/wp-content/uploads/2018/03/Hyperledger_Fabric_Logo_Color-1-300x84.png" 
  />
</a>
<a href="https://reactjs.org">
  <img 
      style="margin-right: 50px" 
      height="60px" 
      src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1200px-React-icon.svg.png" 
  />
</a>
</p>
<br />
<br />
<br />

## Open and Decentralized Standard

[Installation](https://github.com/BLOCKOTUS/organism/blob/master/docs/installation.md)

[Usage](https://github.com/BLOCKOTUS/organism/blob/master/docs/usage.md)

<br />

<a href="https://github.com/hyperledger/fabric-sdk-node/tree/master/fabric-network">
  <img src="https://img.shields.io/badge/fabric--network-%402.3.0-green?style=for-the-badge" />
</a>
<a href="https://github.com/facebook/react">
  <img src="https://img.shields.io/badge/react-%4017.0.1-green?style=for-the-badge" />
</a>

<br />

### Abstract

Build complete decentralized applications with __Blockotus Open and Decentralized Standard__ and __Hyperledger Fabric__. 

The kit includes a Frontend (Svelte / React), a Backend (Nodejs / Express), a Network and Chaincode Contracts (Hyperledger Fabric) as specified by Blockotus Open and Decentralized Standard. Read more about design choices on [architecture](https://github.com/BLOCKOTUS/organism/blob/master/docs/architecture.md) page.

## Components 
- [Webapp - app boilerplate](https://github.com/BLOCKOTUS/webapp-react): Boilerplate React.js + TypeScript + EsLint + Router + Redux Persist
- [Nerves - API boilerplate](https://github.com/BLOCKOTUS/nerves): express
- [Network - organization boilerplate](https://github.com/BLOCKOTUS/network): hyperledger
- [Scripts](https://github.com/BLOCKOTUS/scripts): hot chaincode upgrade, auto-install, deployment
- [Organs](https://github.com/BLOCKOTUS/organism/tree/master/organs): chaincode contracts
  
### Features
#### Technical
- DID ready
- Hot-Chaincode upgrade
- Chaincode Helper
- 5 built-in contracts

#### UI
- Register network users (username, public key)
- Decentralized user verification (KYC)
  - Create encrypted identities
  - Get verified by the network
- Create and execute jobs

## Documentation

### Topics and considerations

- [Architecture - Open Standard](https://github.com/BLOCKOTUS/organism/blob/master/docs/architecture.md)
- Django vs. React + Express: case study needed
- IPFS: needs to be implemented
- Make docker containers for components: case study needed
- Organizations, Ordering Services and other technical stuffs
- Offline transaction signing not working yet

### What does it cover?
- Chaincode implementation
- Hyperledger Fabric methods

### What is not covered?
- Organizations, Ordering Services and other technical stuffs
- Offline transaction signing
