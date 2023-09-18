# Venture-Miner-Academy-Web3-Workshop

09/17/2023 Web3 Workshop

# Mission

To create a marketplace type of platform where each "post" or "engagement" has an escrow contract associated to it

- Each "engagement" smart contract will have different inputs based off a template
- Parent contract serves as a factory/interface

Goals:

- Acceptance criteria:
  - Smart contract holds certain information (requester, job completer wallets), price of engagement
  - Requesting user interacts with smart contract
  - Smart contract pulls out the cash and holds it safely
  - Once the requester signs an additional signature, it triggers the smart contract to send to the job completer address

Possible approaches

- Factory contract with sub-smart contracts
- master smart contract that acts like Binance LP, it keeps all funds in one place
  - could be built with structs that track which address contributed what amount
