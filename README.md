# DePay's Claimable NFT Airdrops

Smart contract allowing to airdrop NFTs without sending them to the receivers
but instead having receivers withdrawal them through the airdrop contract.

Airdrop distributors reate off-chain signatures that can be used by the
airdrop receiver to redeem them for the NFT.

## Deployments

#### Mainnet

[DePayNFTAirdropV1 XXX](XXX)

#### Ropsten

[DePayNFTAirdropV1 0x1ceadd57e477901499c08aec5d2044cc3430d7fc](https://ropsten.etherscan.io/address/0x1ceadd57e477901499c08aec5d2044cc3430d7fc)

[ERC721 0xe7f982e9f25471bc1dd6a84a5433274834d7853f9b49357ece40538ce2c5d7af](https://ropsten.etherscan.io/tx/0xe7f982e9f25471bc1dd6a84a5433274834d7853f9b49357ece40538ce2c5d7af)

[ERC1155 0xb6bb75ae8af249891b1cdcb92a6cb74c6c1b30f8](https://ropsten.etherscan.io/address/0xb6bb75ae8af249891b1cdcb92a6cb74c6c1b30f8)

## Functionalities

### `claim` Claim NFT

The main function allowing people to redeem off-chain airdrop signatures for NFTs.

Arguments:

`address tokenAddress`: The address of the NFT to be claimed.

`address[] receivers`: An array of all receivers, required to validate off-chain signatures.

`bool isERC1155`: Boolean indicating if the airdrop token is a ERC1155 (otherwise falling back to ERC721).

`uint256[] tokenIds`: Ids of all airdroped NFT tokens, required to validate off-chain signatures.

`uint256 index`: Position/index of the current receiver within `receivers` and `tokenIds`.

`uint8 v`: `v` of the off-chain signature.

`bytes32 r`: `r` of the off-chain signature.

`bytes32 s`: `s` of the off-chain signature.

### Deploy

1. `yarn flatten`

2. Deploy flatten contract via https://remix.ethereum.org/
Contribution: 2021-07-04 20:00

Contribution: 2021-07-04 20:01

Contribution: 2021-07-04 20:02

Contribution: 2021-07-04 20:03

Contribution: 2021-07-04 20:04

Contribution: 2021-07-04 20:05

Contribution: 2021-07-04 20:06

Contribution: 2021-07-04 20:07

Contribution: 2021-07-06 20:00

Contribution: 2021-07-06 20:01

Contribution: 2021-07-06 20:02

Contribution: 2021-07-06 20:03

Contribution: 2021-07-06 20:04

Contribution: 2021-07-06 20:05

Contribution: 2021-07-06 20:06

Contribution: 2021-07-06 20:07

Contribution: 2021-07-06 20:08

Contribution: 2021-07-06 20:09

Contribution: 2021-07-07 20:00

Contribution: 2021-07-07 20:01

Contribution: 2021-07-07 20:02

Contribution: 2021-07-07 20:03

Contribution: 2021-07-07 20:04

Contribution: 2021-07-07 20:05

Contribution: 2021-07-07 20:06

Contribution: 2021-07-18 20:00

Contribution: 2021-07-25 20:00

Contribution: 2021-07-25 20:01

Contribution: 2021-07-25 20:02

Contribution: 2021-07-25 20:03

Contribution: 2021-07-25 20:04

Contribution: 2021-07-25 20:05

Contribution: 2021-07-25 20:06

Contribution: 2021-07-25 20:07

Contribution: 2021-07-25 20:08

Contribution: 2021-07-26 20:00

Contribution: 2021-07-26 20:01

Contribution: 2021-07-26 20:02

Contribution: 2021-07-26 20:03

Contribution: 2021-07-26 20:04

Contribution: 2021-07-26 20:05

Contribution: 2021-07-30 20:00

Contribution: 2021-08-03 20:00

Contribution: 2021-08-03 20:01

Contribution: 2021-08-03 20:02

Contribution: 2021-08-03 20:03

Contribution: 2021-08-03 20:04

Contribution: 2021-08-03 20:05

Contribution: 2021-08-03 20:06

Contribution: 2021-08-03 20:07

Contribution: 2021-08-03 20:08

Contribution: 2021-08-03 20:09

Contribution: 2021-08-05 20:00

Contribution: 2021-08-05 20:01

Contribution: 2021-08-05 20:02

Contribution: 2021-08-05 20:03

Contribution: 2021-08-05 20:04

Contribution: 2021-08-05 20:05

Contribution: 2021-08-06 20:00

Contribution: 2021-08-06 20:01

Contribution: 2021-08-06 20:02

Contribution: 2021-08-06 20:03

Contribution: 2021-08-06 20:04

Contribution: 2021-08-06 20:05

Contribution: 2021-08-06 20:06

Contribution: 2021-08-08 20:00

Contribution: 2021-08-08 20:01

Contribution: 2021-08-08 20:02

Contribution: 2021-08-08 20:03

Contribution: 2021-08-08 20:04

Contribution: 2021-08-08 20:05

Contribution: 2021-08-08 20:06

Contribution: 2021-08-10 20:00

Contribution: 2021-08-10 20:01

Contribution: 2021-08-10 20:02

Contribution: 2021-08-11 20:00

Contribution: 2021-08-11 20:01

Contribution: 2021-08-11 20:02

Contribution: 2021-08-11 20:03

Contribution: 2021-08-11 20:04

Contribution: 2021-08-11 20:05

Contribution: 2021-08-11 20:06

Contribution: 2021-08-11 20:07

Contribution: 2021-08-11 20:08

Contribution: 2021-08-11 20:09

Contribution: 2021-08-16 20:00

Contribution: 2021-08-16 20:01

Contribution: 2021-08-17 20:00

Contribution: 2021-08-17 20:01

Contribution: 2021-08-17 20:02

Contribution: 2021-08-17 20:03

Contribution: 2021-08-17 20:04

Contribution: 2021-08-25 20:00

Contribution: 2021-08-25 20:01

Contribution: 2021-08-25 20:02

Contribution: 2021-08-25 20:03

Contribution: 2021-08-25 20:04

Contribution: 2021-08-25 20:05

Contribution: 2021-08-25 20:06

Contribution: 2021-08-25 20:07

Contribution: 2021-08-25 20:08

Contribution: 2021-08-25 20:09

Contribution: 2021-08-27 20:00

Contribution: 2021-08-27 20:01

Contribution: 2021-08-27 20:02

Contribution: 2021-08-27 20:03

Contribution: 2021-08-27 20:04

Contribution: 2021-08-27 20:05

Contribution: 2021-08-27 20:06

Contribution: 2021-08-27 20:07

Contribution: 2021-08-27 20:08

Contribution: 2021-08-27 20:09

Contribution: 2021-08-28 20:00

Contribution: 2021-08-28 20:01

Contribution: 2021-08-28 20:02

Contribution: 2021-09-07 20:00

Contribution: 2021-09-07 20:01

Contribution: 2021-09-07 20:02

Contribution: 2021-09-07 20:03

Contribution: 2021-09-07 20:04

Contribution: 2021-09-07 20:05

Contribution: 2021-09-07 20:06

Contribution: 2021-09-07 20:07

Contribution: 2021-09-10 20:00

Contribution: 2021-09-10 20:01

Contribution: 2021-09-10 20:02

Contribution: 2021-09-10 20:03

Contribution: 2021-09-12 20:00

Contribution: 2021-09-13 20:00

Contribution: 2021-09-13 20:01

Contribution: 2021-09-21 20:00

Contribution: 2021-09-21 20:01

Contribution: 2021-09-21 20:02

Contribution: 2021-09-21 20:03

Contribution: 2021-09-21 20:04

Contribution: 2021-09-22 20:00

Contribution: 2021-09-22 20:01

Contribution: 2021-09-22 20:02

Contribution: 2021-09-22 20:03

Contribution: 2021-09-22 20:04

Contribution: 2021-09-22 20:05

Contribution: 2021-09-22 20:06

Contribution: 2021-09-22 20:07

Contribution: 2021-09-22 20:08

Contribution: 2021-09-22 20:09

Contribution: 2021-09-23 20:00

Contribution: 2021-09-24 20:00

Contribution: 2021-09-24 20:01

Contribution: 2021-09-24 20:02

Contribution: 2021-09-24 20:03

Contribution: 2021-09-24 20:04

Contribution: 2021-09-24 20:05

Contribution: 2021-09-24 20:06

Contribution: 2021-09-25 20:00

Contribution: 2021-09-25 20:01

Contribution: 2021-09-25 20:02

Contribution: 2021-09-25 20:03

Contribution: 2021-09-25 20:04

Contribution: 2021-09-25 20:05

Contribution: 2021-09-28 20:00

Contribution: 2021-09-28 20:01

Contribution: 2021-09-28 20:02

Contribution: 2021-10-01 20:00

Contribution: 2021-10-01 20:01

Contribution: 2021-10-01 20:02

Contribution: 2021-07-16 20:00

Contribution: 2021-07-20 20:00

Contribution: 2021-07-20 20:01

Contribution: 2021-07-20 20:02

Contribution: 2021-07-20 20:03

Contribution: 2021-07-20 20:04

Contribution: 2021-07-20 20:05

Contribution: 2021-07-20 20:06

Contribution: 2021-07-20 20:07

Contribution: 2021-07-21 20:00

Contribution: 2021-07-21 20:01

Contribution: 2021-07-21 20:02

Contribution: 2021-07-21 20:03

Contribution: 2021-07-21 20:04

Contribution: 2021-07-21 20:05

Contribution: 2021-07-21 20:06

Contribution: 2021-07-23 20:00

Contribution: 2021-07-23 20:01

Contribution: 2021-07-23 20:02

Contribution: 2021-07-23 20:03

Contribution: 2021-07-23 20:04

Contribution: 2021-07-23 20:05

Contribution: 2021-07-23 20:06

Contribution: 2021-07-23 20:07

Contribution: 2021-07-23 20:08

Contribution: 2021-08-04 20:00

Contribution: 2021-08-04 20:01

Contribution: 2021-08-04 20:02

Contribution: 2021-08-08 20:00

Contribution: 2021-08-08 20:01

Contribution: 2021-08-08 20:02

Contribution: 2021-08-08 20:03

Contribution: 2021-08-12 20:00

Contribution: 2021-08-12 20:01

Contribution: 2021-08-12 20:02

Contribution: 2021-08-12 20:03

Contribution: 2021-08-12 20:04

Contribution: 2021-08-12 20:05

Contribution: 2021-08-12 20:06

Contribution: 2021-08-12 20:07

Contribution: 2021-08-15 20:00

Contribution: 2021-08-15 20:01

Contribution: 2021-08-15 20:02

Contribution: 2021-08-15 20:03

Contribution: 2021-08-15 20:04

Contribution: 2021-08-15 20:05

Contribution: 2021-08-15 20:06

Contribution: 2021-08-27 20:00

Contribution: 2021-08-28 20:00

Contribution: 2021-08-28 20:01

Contribution: 2021-08-28 20:02

Contribution: 2021-08-28 20:03

Contribution: 2021-08-28 20:04

Contribution: 2021-08-28 20:05

Contribution: 2021-08-30 20:00

Contribution: 2021-08-30 20:01

Contribution: 2021-08-30 20:02

Contribution: 2021-08-30 20:03

Contribution: 2021-09-01 20:00

Contribution: 2021-09-01 20:01

Contribution: 2021-09-01 20:02

Contribution: 2021-09-01 20:03

Contribution: 2021-09-01 20:04

Contribution: 2021-09-01 20:05

Contribution: 2021-09-01 20:06

Contribution: 2021-09-08 20:00

Contribution: 2021-09-08 20:01

Contribution: 2021-09-08 20:02

Contribution: 2021-09-08 20:03

Contribution: 2021-09-08 20:04

Contribution: 2021-09-08 20:05

Contribution: 2021-09-08 20:06

Contribution: 2021-09-08 20:07

Contribution: 2021-09-08 20:08

Contribution: 2021-09-12 20:00

Contribution: 2021-09-12 20:01

Contribution: 2021-09-12 20:02

Contribution: 2021-09-12 20:03

Contribution: 2021-09-12 20:04

Contribution: 2021-09-12 20:05

Contribution: 2021-09-12 20:06

Contribution: 2021-09-12 20:07

Contribution: 2021-09-12 20:08

Contribution: 2021-09-12 20:09

Contribution: 2021-09-15 20:00

Contribution: 2021-09-15 20:01

Contribution: 2021-09-15 20:02

Contribution: 2021-09-15 20:03

