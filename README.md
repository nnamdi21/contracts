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

### Example2 - Car Rental Service

* Contract first checks if car is available. If yes, user can rent car.
* A minimum rent fee is set for the first hour; then a fixed rate for subsequent hours.
* The amunt of hours spent can be viewed at anytime.
* Payment is made when trip is ended. 
* Daily interest is paid on money owed for defaulting users.
* Defaulting users can not use service unless all outstanding debt paid.


