# Byzantine Finance - Aggregation Layer for Restaking

This repository gathers all the code created from scratch for the **BabylonLabs Hackathon in November 2024**.

---


Welcome to Byzantine Finance, the first aggregation layer for restaking. Explore a new way to build custom restaking strategies across any collateral asset, chain, protocol, or network. Effortlessly create your vault, adjust risk, and leverage DeFi for optimal returns.


For all the details about the project, visit our page on DoraHacks: [https://dorahacks.io/buidl/19084](https://dorahacks.io/buidl/19084).

## Repository Structure

This GitHub repository is split into several submodules:

-  [babylon-evm](https://github.com/linnnnnnh/babylon-evm/tree/dd0a7fd0d07dbaf999083d076b34412ebd012a1c)  
*Ethereum contracts for the restaking of BTC on Symbiotic.*  
This module contains the smart contracts deployed on the Ethereum Virtual Machine (EVM) to facilitate the restaking of Bitcoin on the Symbiotic network.

- [spv](https://github.com/catalogfi/spv/tree/ac28c94929d250f95b170705dd13ab3b33e89c3d)  
*Simplified Payment Verification to verify Bitcoin staking transactions on Ethereum.*
This component implements SPV to allow Ethereum smart contracts to verify Bitcoin staking transactions securely.  
> Note: The SPV module is written and maintained by [Catalog Finance](https://www.catalog.fi/).

-  [babylon-byz](https://github.com/Benoitded/babylon-byz)  
*Frontend interface of the project.*  
Everything visible on [https://babylon-byz.vercel.app/](https://babylon-byz.vercel.app/) is developed in this module. It includes the user interface for interacting with Byzantine Finance's features.

## Getting Started

To get started with any of the modules, please refer to their individual README files for installation instructions and usage guides.

## Contributing

We welcome contributions from the community! Feel free to fork the repository, open issues, or submit pull requests to help improve Byzantine Finance.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

*Byzantine Finance is pioneering the future of cross-chain restaking. Join us on this exciting journey!*
