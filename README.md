# Awesome Upgradeability • <a href="https://github.com/sindresorhus/awesome"> <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"></a> <a href="http://makeapullrequest.com"> <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat"> </a>

<img align="center" src="./assets/banner.jpg" alt="awesome-upgradeability" title="awesome-foundry" />

> A curated list of awesome resources, tutorials, tools and libraries related to smartcontract upgradeability. Inspired by [awesome-foundry](https://github.com/crisgarner/awesome-foundry).

<p>Please check the <a href="CONTRIBUTING.md">contribution guidelines</a> for information on formatting and writing pull requests.</p>

## Articles:

- [Contract upgrade anti-patterns](https://blog.trailofbits.com/2018/09/05/contract-upgrade-anti-patterns/)
- [Deep dive into the Minimal Proxy contract](https://blog.openzeppelin.com/deep-dive-into-the-minimal-proxy-contract/)
- [How to create a Beacon Proxy](https://medium.com/coinmonks/how-to-create-a-beacon-proxy-3d55335f7353)
- [Perma-brick UUPS proxies with this one trick](https://iosiro.com/blog/openzeppelin-uups-proxy-vulnerability-disclosure)
- [State of Smartcontract Upgrades](https://blog.openzeppelin.com/the-state-of-smart-contract-upgrades/)
- [Storage for Upgradable Ethereum Smart Contracts](https://mixbytes.io/blog/storage-upgradable-ethereum-smart-contracts)
- [Upgradeable Proxy Contract Security Best Practices by Certik](https://www.certik.com/resources/blog/FnfYrOCsy3MG9s9gixfbJ-upgradeable-proxy-contract-security-best-practices)
- [Upgradeable Smartcontracts with OZ](https://piedao.notion.site/Upgradeable-Contracts-with-OZ-e1657f19c569475098a4ebf2a08a5d2b#0af0a20f660a45b3b72b9200d483d07a)
- [Using the UUPS Proxy pattern](https://blog.logrocket.com/using-uups-proxy-pattern-upgrade-smart-contracts/)
- [Using Foundry to Explore Upgradeable Contracts](https://runtimeverification.com/blog/using-foundry-to-explore-upgradeable-contracts-part-1)
- [Using upgradable proxies safely in Solidity.](https://medium.com/@Railgun_Project/using-upgradable-proxies-safely-in-solidity-e60d9ee31376)
- [Using UUPS proxy in foundry](https://teletype.in/@xni/ZGY6w5o9PYy)
- [Writing Upgradeable Contracts](https://docs.openzeppelin.com/upgrades-plugins/1.x/writing-upgradeable)

---

## Discussions:

- [Beware of the proxy: learn how to exploit function clashing](https://forum.openzeppelin.com/t/beware-of-the-proxy-learn-how-to-exploit-function-clashing/1070)
- [How to test upgradeable smart contracts - Foundry](https://github.com/foundry-rs/foundry/issues/2800)
- [OZ Forum UUPS Proxies: Tutorial (Solidity + JavaScript)](https://forum.openzeppelin.com/t/uups-proxies-tutorial-solidity-javascript/7786)
- [Standard Proxy Storage Slots](https://github.com/ethereum/EIPs/pull/1967#issuecomment-489276813)

---

## Misc Repos:

- [Awesome Diamonds](https://github.com/mudgen/awesome-diamonds)
- [Implementation of the various upgradeable proxy pattern [WIP] - Brownie](https://github.com/MikeSpa/proxy-pattern)
- [Moralis Tutorial - Hardhat](https://github.com/YosephKS/moralis-upgradeable-smart-contracts/tree/main)
- [OpenZeppelin Upgradeable Contracts With Foundry](https://github.com/jordaniza/OZ-Upgradeable-Foundry)
- [Solidity Proxy Playground by yAcademyDAO - Foundry](https://github.com/YAcademy-Residents/Solidity-Proxy-Playground)
- [Hardhat + Foundry template for managing contract upgrades](https://github.com/HashHaran/foundry-upgrade-hardhat)
- [Upgradeability Checks - Slither](https://github.com/crytic/slither/wiki/Upgradeability-Checks)
- [Upgradeable Contracts using the Diamond Storage pattern - Foundry](https://github.com/0xPhaze/UDS)
- [Upgradeability test for UUPS-type proxies using Foundry toolkit](https://github.com/MatinR1/UpgradeableTest)

---

## Projects:

- [AAVE V3](https://github.com/aave/aave-v3-core/tree/master/contracts/protocol/libraries/aave-upgradeability)
- [Dharma](https://github.com/dharma-eng/dharma-smart-wallet/blob/master/contracts/proxies/smart-wallet/UpgradeBeaconProxyV1.sol)
- [Maple Finance V2](https://github.com/maple-labs/maple-core-v2/tree/main)
- [Nomad](https://github.com/nomad-xyz/monorepo/tree/main/packages/contracts-core/contracts/upgrade)
- [Optimism](https://github.com/ethereum-optimism/optimism/blob/develop/packages/contracts-bedrock/contracts/universal/Proxy.sol)

---

## Publications/Research:

- [A Comprehensive Survey of Upgradeable Smart Contract Patterns](https://arxiv.org/pdf/2304.03405.pdf)
- [Ethereum Upgradeable Smart Contract R&D - Part 1](https://blog.indorse.io/ethereum-upgradeable-smart-contract-strategies-456350d0557c)
- [Ethereum Upgradeable Smart Contract R&D - Part 2](https://medium.com/coinmonks/summary-of-ethereum-upgradeable-smart-contract-r-d-part-2-2020-db141af915a0)
- [yAcademyDAO Proxies Research](https://proxies.yacademy.dev/)

---

## Security (Disclosures/Postmortems):

- [Audius Governance Takeover Post-Mortem](https://blog.audius.co/article/audius-governance-takeover-post-mortem-7-23-22)
- [Breaking Aave Upgradeability - ToB](https://blog.trailofbits.com/2020/12/16/breaking-aave-upgradeability/)
- [Harvest Finance Uninitialized Proxies Bugfix Review](https://medium.com/immunefi/harvest-finance-uninitialized-proxies-bug-fix-postmortem-ea5c0f7af96b)
- [Nomad Bridge incident analysis](https://medium.com/immunefi/hack-analysis-nomad-bridge-august-2022-5aa63d53814a)
- [UUPSUpgradeable Vulnerability Post-mortem](https://forum.openzeppelin.com/t/uupsupgradeable-vulnerability-post-mortem/15680)
- [Wormhole Uninitialized Proxy Bugfix Review](https://medium.com/immunefi/wormhole-uninitialized-proxy-bugfix-review-90250c41a43a)

---

## Tools:

- [ChungSplash](https://github.com/chugsplash/chugsplash) - A declarative and deterministic framework for deploying and upgrading smart contracts. Available for both Hardhat and Foundry.
- [Foundry Multichain](https://github.com/timurguvenkaya/foundry-multichain) - Multichain Solidity Deployment/Upgradability script pattern
- [Foundry Upgrades](https://github.com/odyslam/foundry-upgrades) - Helper smart contracts to deploy and manage upgradeable contracts
- [OpenZeppelin Defender Admin for Upgrades](https://docs.openzeppelin.com/defender/admin#upgrades) - To manage upgrades in production and automate operations.
- [OpenZeppelin Hardhat Upgrades](https://github.com/OpenZeppelin/openzeppelin-upgrades/tree/master/packages/plugin-hardhat/) - Hardhat plugin for deploying and managing upgradeable contracts.
- [Slitherin](https://github.com/pessimistic-io/slitherin) - Slither Detectors by Pessimistic.io
