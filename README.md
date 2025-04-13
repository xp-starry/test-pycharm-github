# test-pycharm-github
测试pycharm推送code到github是否成功。

### pycharm连接github进行远程仓库推送
参考该链接：https://zhuanlan.zhihu.com/p/13523136490

### 问题汇总：
![image](https://github.com/user-attachments/assets/9b2fbc0b-c87d-41e0-9ec9-2cb71c9a1cb1)
![image](https://github.com/user-attachments/assets/10a5be6b-2a8a-4556-bac2-653aa55c18c0)

在定义远程时遇到如上错误，打开科学上网并配置git代理地址：git config --global http.proxy http://127.0.0.1:7890
仅设置了http代理，成功解决！
