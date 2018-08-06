# à table! bug bounty program

Dear fellow developers and blockchain enthusiasts,

In preparation of the launch of our new game called “à table!”, we would like the community to help find security vulnerabilities via our bug bounty program described below.

## What you should know
* à table! is a game centered around collectible and combinable creatures represented by Ethereum tokens.
* Yummies - our  creatures - are Ethereum ERC721 non-fungible tokens
* The tokens can be transferred, auctioned and bred together

## Scope of this bug bounty program
This bounty program will run on the Ropsten network from the beginning of August 2018 until the end of August 2018.
All the contract code will be publicly available on-chain, and we would like you to help us find vulnerabilities and possible incorrect usage of contract mechanics such as :
* breaking an aspect of the game (auctioning, breeding, etc)
* steal a token from someone else
* act as a contract administrator (destroy or pause the contract, etc)
* any other sort of incorrect usage of the contract

## Rules and rewards
* Issues that have already been submitted by another user or are already known to the à table! team are not eligible for bounty rewards.
* Any website related to à table or EverdreamSoft are not part of the bug bounty program.
* We are aware that some values need tweaking, issues related only to contract efficiency will not be eligible.
* We will consider many variables when evaluating a submitted vulnerability. Determination of eligibility and rewards are at the sole discretion of EverdreamSoft

![alt text](https://i.imgur.com/SUCHcsA.png "Bug severity matrice")

The value of rewards will be determined depending on the severity of the submitted vulnerability.
* Critical: up to 1000 points
* High: up to 500 points
* Medium: up to 250 points
* Low: up to 125 points
* Note: up to 50 points

1 point corresponds to 1 USD (paid half in ETH and half in BCY)

## How to make a good vulnerability report:
* **Description** : Describe the expected result and the encountered result
* **Steps to reproduce** : Describe the sequential steps to reproduce the vulnerability with as much details as possible.
* **Impact** : The result of the vulnerability, what / who is affected.
* **Supporting material / references** : List any additional material (screenshots, logs, tx hashes, accounts used). If possible, provide a Truffle test.
* **Fix** : What would you do to fix it?

Please mail your report to bounty@everdreamsoft.com

## Important information

### Contract addresses
Core contract : 0x884a09321AC966e0a923494bEAD1D8eEabed2da0

Sale auctions contract : 0x281754efC30283b4a7244Eb258C2653142B31099

Breeding auctions contract : 0x2AAE51Df7DA23961c1b9Cb5bEA2eb1583b12D6B0

## FAQ
* **Will the code change during the bounty program ?**
  * The code will most likely change during the program. As issues are reported by the community we will update the code as soon as possible. Make sure the vulnerabilities you report are related to the latest published version of the code.
* **How are the bounties paid out?**
  * Rewards are paid half in BitCrystals (BCY) and half in ETH. Please provide both your ETH and BCY compatible (Counterparty compatible) addresses.
