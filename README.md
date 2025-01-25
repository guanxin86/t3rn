# t3rn
## 官方教程
[https://docs.t3rn.io/executor/become-an-executor/binary-setup]
## 参数设定
```
export NODE_ENV=testnet
export LOG_LEVEL=debug
export LOG_PRETTY=false
export EXECUTOR_PROCESS_ORDERS=true
export EXECUTOR_PROCESS_CLAIMS=true
export PRIVATE_KEY_LOCAL=<>
export ENABLED_NETWORKS='arbitrum-sepolia,base-sepolia,optimism-sepolia,l1rn'
```
## 执行
```
cd /root/executor/executor/bin/
./executor
```
## 设置base链RPC
```
export RPC_ENDPOINTS_BSSP=https://base-sepolia-rpc.publicnode.com
```
## 删除旧版本
```
cd $h
rm -rf ~/executor
```
## 安装新版本
```
wget -O executor.tar.gz
```
```
tar -zxvf executor.tar.gz
cd ~/executor/executor/bin
./executor
```
## releases文件
[releases](https://github.com/t3rn/executor-release/releases/)
