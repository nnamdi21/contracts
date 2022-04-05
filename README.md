# Contracts

## Description

Examples of smart contracts.

### Example1 - Buy a house

This contract allows multiple EOAs to bid for a house based on certain rules:
* Bids are made at a certain cost requirement.
* The cost requirement increases as new bids are made
* To make a new bid, you must out-bid the highest bidder
* After 24hrs the highest bidder can choose to pay for the house.
* If payment for the house fails due to insufficient funds after three attempts, the EOA defaults and can no longer buy the house.
