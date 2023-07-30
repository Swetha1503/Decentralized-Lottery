# Decentralized-Lottery
A decentralized lottery system built upon Ethereum blockchain using Solidity. This has been integrated with Metamask wallet and is deployed on Sepolia Testnet.

This smart contract provides a secured lottery system.
The contract works with a manager and participants. 
Each participant from the dynamic array of participants is enabled to transfer 1 ether to the manager.
The balance of the manager's account will be the total number of participants as only 1 ether is transferred from each participant.
A random function is coded which selects one random participant as the winner from the dynamic array of participants.
The total balance in the manager's account is transferred to the selected winner.
