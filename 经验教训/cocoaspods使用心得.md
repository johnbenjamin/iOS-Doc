# cocoapods

### 众所周知，翻墙翻墙翻墙



## 如何快速pod仓库

### 源：source 'https://cdn.cocoapods.org/'



### 查询终端IP：curl cip.cc



### 终端翻墙：

1. ```
   vim ~/.bash_profile
   ```

2. ```
   function proxy_on(){
       export http_proxy=http://127.0.0.1:1087
       export https_proxy=http://127.0.0.1:1087
       echo -e "已开启代理"
   }
   function proxy_off(){
       unset http_proxy
       unset https_proxy
       echo -e "已关闭代理"
   }
   ```

3. ```
   source ~/.bash_profile
   ```

4. ```
   proxy_on
   ```

