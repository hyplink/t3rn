# t3rn
t3rn binary running

- 下载最新binary程序：
    
    ```bash
    wget https://github.com/t3rn/executor-release/releases/download/v0.26.0/executor-linux-v0.27.0.tar.gz
    ```
    
    输入 `ls` 查看文件夹内文件
    
- 解压该程序:
    
    ```bash
    tar -xzf executor-linux-v0.27.0.tar.gz
    ```
    
- 查看文件夹后
    
    ```
    cd executor/executor/bin
    ```
    
    ```bash
    export NODE_ENV=testnet
    export LOG_LEVEL=debug
    export LOG_PRETTY=false
    export EXECUTOR_PROCESS_ORDERS=true
    export EXECUTOR_PROCESS_CLAIMS=true
    ```


