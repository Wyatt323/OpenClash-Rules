# 带ChatGPT分流的clash规则
本规则基于
ACL4SSR_Online_Full 全分组重度用户使用(与Github同步)[传送门](https://github.com/ACL4SSR/ACL4SSR/blob/master/Clash/config/ACL4SSR_Online_Full.ini)  
wgetnz/chattgpt-openclash的chatgpt.list[传送门](https://github.com/wgetnz/chatgpt-openclash/blob/main/chatgpt.list)  
整合而成  

## 使用方法：  
方法一：  
直接替换订阅链接到下面的链接中(本人没试过，不知是否可行)  
```shell
https://api.dler.io/sub?target=Clash&url=%E4%BD%A0%E7%9A%84%E8%AE%A2%E9%98%85%E9%93%BE%E6%8E%A5%EF%BC%88URL%E7%BC%96%E7%A0%81%EF%BC%89&config=https%3A%2F%2Fraw.githubusercontent.com%2FWyatt323%2Fopenclash-rules%2Fmain%2FACL4SSR_Online_Full.ini
```  
方法二：  
订阅转换站(可自行搭建引用我的配置文件，也可以使用下方转换站)  
```shell
晚点专门做一个站给你们用
```  
## 免责声明：
后端地址均为网上收集，如出现订阅地址泄漏等问题，与本项目无关，概不负责。  

## 目前已知存在的问题
1、openclash在使用此规则时只在tun模式下生效，但是tun模式会影响游戏。  
使用环境：smartdns+openclash(控制面板的连接中只显示ip不显示域名)  
原因：根据openclash作者vernesong大佬的描述，是因为DNS劫持有问题。  
解决办法：开始meta内核的嗅探  

### 致谢：(列表不分先后)  
[ACL4SSR](https://github.com/ACL4SSR)  
[wgetnz](https://github.com/wgetnz)  
[vernesong](https://github.com/vernesong)  
