## Windows Monad 101环境配置



**注意** : **windows 用户建议使用 WSL(Windows for linux) 可以不必要的问题，更多内容可参考 [Unix 环境配置.md](./Unix 环境配置.md) **

---

### 1. Git 根据操作系统的不同，选择不同的系统版本，
   详⻅：[Releases · git-for-windows/git](https://github.com/git-for-windows/git/releases)

### 2. 下载node windows 版
​      [nodejs-download](https://nodejs.org/en/download/package-manager)

​	检查是否下载成功：`node -v`

### 3. 下载yarn  
   打开 `git-bash` 终端安装 ：`npm install --global yarn`  下载完成后
   终端再输入命令 `yarn –v`，若出现版本号，则安装成功。 

### 4. 下载 foundryup 包 
   1. 打开 `git-bash` 终端安装: `curl -L https://foundry.paradigm.xyz | bash`
   2. **注意: 若 step 1 执行失败或者等待时间过长可取消，然后进入 `install_foundry_for windows ` 文件夹, 执行 `bash install_foundry.sh`, 继续操作即可**
   3. 下载完成后，终端再输入如下命令进行forge等安装 : `foundryup`

   参考: https://learnblockchain.cn/docs/foundry/i18n/zh/getting-started/installation.html

### 5. 安装 scaffold-eth2
   使用`git-bash` 新建 test 文件夹

​	`npx create-eth@0.0.55`

   参考: [scaffold-eth/create-eth: Create you own Scaffold-ETH toolkit](https://github.com/scaffold-eth/create-eth)

