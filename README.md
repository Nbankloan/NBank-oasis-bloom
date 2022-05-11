![image](https://raw.githubusercontent.com/Nbanksolo/Nbank/main/images/NBank.jpg)
## Overview

NBank is an ERC20 token bank that produces NFTs in batch while providing composable deposit certificates.

## How to use it?

1.Use the ERC20 token factory to create an token, and set basic information such as the token name, issuance quantity, token logo, and decimal places.  

2.Create a NFT bank: NFT bank name, the address of the staked governance token, the staking duration, and the generated NFT name;  

3.The NFT token mainly contains the following information: NFT number, NFT initial minter, NFT current holder, NFT lock-up time, NFT governance token name, NFT governance token quantity, lock-up start time, lock-up time End time, remaining days of lock-up, withdrawal button;  

4.Stake governance tokens to create NFT tokens: select the deposit amount and time to generate NFT tokens;  

5.In order to obtain liquidity during the staking period, NFT tokens can be mortgaged in the loan market, and then a certain amount of funds can be borrowed;  

6.The loan order contains the following information: loan tokens, loan amount, loan period, loan start time, estimated repayment time, remaining repayment days, loan interest rate, loan actual interest, repayment operation;  

7.In order to obtain liquidity during the mortgage period, NFT tokens can be transferred in the transfer market, and existing tokens can be directly sold;  

8.The transfer market order mainly includes the following information: order number, NFT number, NFT initial creator, NFT current holder, NFT creation time, NFT expiration time, unlocking reputation time, NFT transfer price, including the number of tokens, transfer procedures fee.  

9.Anyone can purchase the NFT in circulation through the transfer market, and obtain the token contained in the NFT. After the bank lock-up expires, the token can be withdrawn from the bank through the NFT lock-up token.

## Oasis contract address
- ERC20FACTORY 0x465A46D9D8CA6b1defAB8d7E9599A2499Be2EDc6
- NBANKFACTORY 0xdd057e4A4b23eD0a98ED4FAE19B1B23011354898
- LOANMARKET 0xEC45605f01C5437e4120386FfB667e668049Bd3A
- NBANK 0x3675bb23bB50E283Cc07933cCF4F8FE9f49C92Ad
- NBT 0xE93A356Ee83a81661bee947b4c7032Fa78c27161
- NDEPOSIT 0xBD0B452DD4c47A33001253c215A8Bc42650c72DE