# Tokenomics
UNCC Online FinTech Bootcamp Module 21 Challenge due by 11:59pm 5/1/2022

<img src="Images/21-4-application-image.png"/>

Image from [bootcampspot.com](https://courses.bootcampspot.com/courses/980/assignments/20398?module_item_id=378225)

---

## Background

After waiting for years and passing several tests, we were selected by the Martian Aerospace Agency to be part of the first human colony on Mars. As prominent fintech professionals, we were chosen to lead a project to develop a monetary system for the new Mars colony. We have decided to base this new monetary system on blockchain technology, and to define a new cryptocurrency called KaseiCoin. (“Kasei” means “Mars” in Japanese.)

KaseiCoin will be a fungible token that is ERC-20 compliant. We will launch a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin.

---

## What's Being Created

We will create a fungible token that is ERC-20 compliant and that will be minted by using a Crowdsale contract from the OpenZeppelin Solidity library.

The crowdsale contract that we create will manage the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI, or KaseiCoin tokens. Our contract will mint the tokens automatically and distribute them to buyers in one transaction.

---

## Technologies

This application is written in Solidity with [Remix 0.22.2 IDE](https://remix-ide.readthedocs.io/en/latest/index.html)

Other dependencies:

 - [ERC20](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20.sol) - *a standard for Fungible Tokens.*
 - [ERC20Detailed](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Detailed.sol) - *sets values for `name`, `symbol` and `decimals`.*
 - [ERC20Mintable](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Mintable.sol) - *Extension of {ERC20} that adds a set of accounts with the {MinterRole}, which have permission to mint (create) new tokens as they see fit.*
 - [Crowdsale](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/Crowdsale.sol) - *Crowdsale is a base contract for managing a token crowdsale, allowing investors to purchase tokens with ether.*
 - [MintedCrowdsale](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/emission/MintedCrowdsale.sol) - *Extension of Crowdsale contract whose tokens are minted in each purchase.*
 - [CappedCrowdsale](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/validation/CappedCrowdsale.sol) - *Crowdsale with a limit for total contributions.*
 - [TimedCrowdsale](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/validation/TimedCrowdsale.sol) - *Crowdsale accepting contributions only within a time frame.*
 - [RefundablePostDeliveryCrowdsale](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/distribution/RefundablePostDeliveryCrowdsale.sol) - *Extension of RefundableCrowdsale contract that only delivers the tokens once the crowdsale has closed and the goal met, preventing refunds to be issued to token holders.*
 - [SafeMath](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/utils/math/SafeMath.sol) - *a library to help you check for overflows in case of addition, underflow in case of substraction as well as when performing multiplication and division.*
  
---

## Usage

---

## Contributors
Geoff Tarleton - jobeycat@protonmail.com

adapted from Starter Code supplied by UNCC FinTech Online Bootcamp by Trilogy Educational Services, a 2U, Inc. brand.

---

## License

[MIT](LICENSE)
