# Monad 区块链上 德国心脏病游戏 的 WorkShop

Monad 是一个第 1 层区块链，每秒 10,000 笔交易，1 秒出块时间，单时隙最终确定性，硬件要求低。

这个 workshop将介绍如何在 Monad 链上构建一个简单的 dapp。我们使用内置 wagmi 和 viem 库的 Scaffold-ETH2-Open source toolkit 以及 Foundry 来构建 dapp。

**最终效果展示**

![MolliNalli Game](https://image.yaco.email/MolliNalli Game.png)

## 依赖安装

### 安装流程
在开始之前，你需要安装以下工具

1. [Node (>= v18.17)](https://nodejs.org/en/download/)

2. Yarn ([v1](https://classic.yarnpkg.com/en/docs/install/) or [v2+](https://yarnpkg.com/getting-started/install))

3. [Git](https://git-scm.com/downloads)

4. Foundry
      ```
      curl -L https://foundry.paradigm.xyz | bash
      foundryup
      ```
  - 参考： [安装 - Foundry 中文文档 | 登链社区](https://learnblockchain.cn/docs/foundry/i18n/zh/getting-started/installation.html#precompiled-binaries)

5. Scaffold-ETH2 toolkit: Type folder name you want, and choose `Foundry`
      ```
      npx create-eth@0.0.55
      ```
  - 参考：[scaffold-eth/create-eth: Create you own Scaffold-ETH toolkit](https://github.com/scaffold-eth/create-eth)

### 详情
UNIX/MAC/LINUX 安装  [Unix 环境配置.md](docs/Unix 环境配置.md)

WINDOWS 安装  [Windows 环境配置.md](docs/Windows 环境配置.md)

### 钱包配置
钱包配置 [Windows 环境配置.md](docs/钱包配置.md) 

---

## 测试依赖

1. 执行  `yarn -v`  `git --version` `node -v` 查看版本号于下周内容是否一致
2. 参考 [scaffold-eth/create-eth: Create you own Scaffold-ETH toolkit](https://github.com/scaffold-eth/create-eth) 部署一个本地测试项目，框架选择`foundry` ，开启 3 个终端，依次执行，尝试查看 `yarn start` 能否会成功运行，进入`localhost:3000`，出现以下的界面。

![Scaffold-ETH 2](https://image.yaco.email/Scaffold-ETH 2.png)

## 享受 WorkShop

如果你已经克隆的本项目，并切成功实现以上步骤。那么你恭喜你，已经准备好了开始 WorkShop，愉快的享受即将到来的 Monad 区块链之旅吧！



