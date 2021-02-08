# Blockchain-and-smart-contracts-for-the-optimization-of-energy-exchange-in-Microgrid

The implementation of the blockchain and smart contract will solve several problems in
managing produced and consumed electricity flows that we often experience in traditional grids.
Creating energy market on blockchain can contribute to adapt the produced energy to the use of
each customer, it will help find the balance between production and consumption in Microgrid.
More concretely, the project aims to ensure the autonomy of the microgrid’s use of energy, then,
apply the property of decentralization of the blockchain in order to carry out the payments and
the exchanges between consumers and producers, and finally resolving the problem of energy
optimization with Smart contracts.


#Three smart contracts have been created to demonstrate the use case of energy trading on Ethereum.
(See Solidity code in Appendix)
- Contract MicrogridEnergyMarket.sol creates purchase / sale orders and records them.
- Contract registerMeter.sol registers a smart meter using its address
wallet on the blockchain to participate in microgrid energy trading.
- Contract Migrations.sol. since the deployment needs will change over time, as and when
As the project evolves, new migration scripts need to be implemented to
continue this evolution on the blockchain. A history of previous migrations
executed is recorded in chain via the Migrations.sol migration contract
