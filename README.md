# myToken Smart Contract Using Solidity

## Overview
This Solidity smart contract implements a basic ERC-20 token called "ETHEREUM" with the symbol "ETH". It includes functionality to mint and burn tokens while keeping track of total supply and individual balances.

## Features

Public Variables:

tokenName: Name of the token.

tokenAbbr: Abbreviation of the token.

totalSupply: Total supply of the token.

## Mapping

balances: Maps addresses to their respective token balances.

## Mint Function:
1. Takes an address and a value.
2. Increases the total supply by the given value.
3. Increases the balance of the given address by the same value.
   
## Burn Function:
1. Takes an address and a value.
2. Decreases the total supply by the given value, provided the address has enough balance.
3. Decreases the balance of the given address by the same value, provided the address has enough balance.
