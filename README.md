# NFT Market Reference Implementation

## TODO / DONE:
- [x] basic purchase of NFT with FT
- [x] demo pay out royalties (FTs and NEAR)
- [x] test and determine standards for markets (best practice?) to buy/sell NFTs (finish standard) with FTs (already standard)
- [x] demo some basic auction types, secondary markets and 
- [x] frontend example
- [ ] connect with bridged tokens e.g. buy and sell with wETH/nDAI (or whatever we call these)

## Notes:

High level diagram of NFT sale on Market using Fungible Token:
![image](https://user-images.githubusercontent.com/321340/113903355-bea71e80-9785-11eb-8ab3-9c2f0d23466f.png)

Differences from `nft-simple` NFT standard reference implementation:
- anyone can mint an NFT
- Optional token_type
- capped supply by token_type
- lock transfers by token_token
- enumerable.rs

#### If you don't have Rust
	Install Rust https://rustup.rs/

#### If you have never used near-cli
1. Install near-cli: `npm i -g near-cli`
2. Create testnet account: [Wallet](https://wallet.testnet.near.org)
3. Login: `near login`


## Installation

Beyond having npm and node (latest versions), you should have Rust installed. I recommend nightly because living on the edge is fun.

https://rustup.rs/

Also recommend installing near-cli globally

`npm i -g near-cli`

Everything else can be installed via:
`yarn`
`cd server && yarn`


## Test Utils

1. creating a near connection and establishing a keystore for the dev account
2. creating test accounts each time a test is run
3. establishing a contract instance so you can call methods


