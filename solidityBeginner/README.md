
# GreenCoin

support green energy by investing in the greenCoin economy

## Description

greencoin is a eco-friendly crypto project based in Ghana
Anyone can create or destroy greencoins
the number of greencoins a user owns represents their contribution to the greencoin economy

## Getting Started

the greencoin contract found in greenCoin.sol is  a basic crypto token contract with mint and burn capability
you need to compile the contract using a solidity compiler
you can use the remix ide for compiling deploying and testing

### Installing

  go to the remix ide website
  copy and paste the greencoin token contract into a solidity (.sol) file in remix
  compile the contract

  now you can deploy to a blockchain mainnet or testnet
  and you can debug the contract using the remix virtual machine
  
### Executing program

provide a user address and an amount to mint the amount in greenCoins to that user
this is using the mint function

provide a user address and an amount to destroy greencoin. the greencoins destroyed will match the amount specified.
this is using the burn function

you can provide any user address to check it's balance. if the user has not recieved greencoins before, balance defaults to zero

users cannot transfer greenCoins

## Help

currently anyone can mint greenCoins even if they did not contribute to the greenCoin economy, that needs to be fixed
also anyone can destroy (burn) greenCoins even if they don't own them. it's like someone burning your money. it needs to be fixed

## Authors

EVERGREEN

## License

This project is licensed under the MIT licence
