## 第一章：走进 Web3 世界

1. 简单描述一下本地开发、部署合约的流程             
首先，开发者需要在本地环境中编写智能合约代码，通常使用 Solidity 语言。
使用工具如 Truffle 或 Hardhat 进行合约的编译和测试。
在本地测试网络（如 Ganache）上进行部署，以确保合约的功能正常。
最后，将合约部署到以太坊主网或其他区块链网络。                                                 

2. 简单描述一下用户在使用一个 DApp 时与合约交互的流程              
用户通过 DApp 的前端界面进行操作，通常是通过浏览器插件（如 MetaMask）连接钱包。
用户在界面上发起交易请求，DApp 将请求发送到区块链网络。
智能合约接收请求并执行相应的逻辑，结果返回给用户。
用户可以在区块链浏览器上查看交易状态和结果。                                  
 
3. 通读[「区块链黑暗森林自救手册」](https://github.com/slowmist/Blockchain-dark-forest-selfguard-handbook/blob/main/README_CN.md)，列出你觉得最重要的三个安全技巧 
使用多重签名钱包来提高资金安全性。
定期更新和审计智能合约代码，以防止已知漏洞。
谨慎处理私钥和助记词，避免在不安全的环境中暴露。
