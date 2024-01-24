# Provably Random Raffle Contracts

## About

This code is to create a provably random smart contract lottery.

## What we need it to do?

1. Users can enter by paying for a ticket
   1. The ticket fees are going to the winner during a draw
2. After X period of time, the lottery will automatically draw a winner and this will be done programatically
3. Using Chainlink VRF & Chainlink Automation
   1. Chainlink VRF -> Randomness
   2. Chainlink Automation -> Time based trigger

## Tests

1. Write some deploy scripts
2. Write our tests
   1. Work on local chain
   2. Forked testnet
   3. Forked mainnet
