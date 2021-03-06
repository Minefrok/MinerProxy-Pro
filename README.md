<h1 align="center">
  <br>
  <img src="https://github.com/Minefrok/MinerProxy-Pro/blob/8af2437313573c2a8dd6b254755103d454ab8737/images/logo.png" width="350"/>
</h1>

<h4 align="center">基于GoLang的高性能多线程ETH/ETC矿池转发中继代理工具.</h4>

<p align="center">
  <a>
    <img src="https://img.shields.io/badge/Release-3.0.0_ETHASH-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Last_Update-2022_03_15-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Language-GoLang-green.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/License-Apache-green.svg" alt="travis">
  </a>
</p>

<p align="center">
  • <a href="https://t.me/minerproxypro">Telegram 讨论群组</a>
</p>

![Screenshot](https://github.com/Minefrok/MinerProxy-Pro/raw/main/images/1.png)
![Screenshot](https://github.com/Minefrok/MinerProxy-Pro/raw/main/images/2.png)

## :sparkles: 特性

* :cloud: 矿池转发：支持ETH/ETC的中继代理，支持Stratum/NiceHash/Stratum2所有协议，方便统一管理(其他币种即将更新)
* :zap: 超高性能：採用高效率的GoLang语言编写，并对多线程进行优化
* 💻 自定义抽水：支持中继平台自定义抽水比例进行抽水，并支持在不关闭代理池的情况下进行动态修改
* 📚 多种抽水算法：用户可自选各种抽水算法，防止算力出现週期函数或心跳图的情况
* 💾 安全稳定：支持TCP、SSL等方式，并对CC攻击编写一定的策略进行防护
* :gear: 独家前置代理模式：支持中转服务器到矿池端的加密与混淆，可内网部署
* :outbox_tray: 批量转发：一个软件即可开启对多个矿池的转发，无需开启多个进程
* :card_file_box: 热修改：配置均可网页后台上热修改，无需再修改繁琐配置文件再重启
* :art: 精美后台：后台网页功能全面、折线图、统计丰富、黑暗模式、多语言支持
* :eye_speech_bubble: 完善社区支持：Telegram 群组内可帮助处理解决遇到的各类问题，欢迎提出反馈建议
* :rocket: 开箱即用：All-In-One 打包，一键搭建运行，一键配置
* :family_woman_girl_boy: 多系统支持：Windows Linux MacOS均可支持使用，无需额外环境等
* :gear: 专业团队：拥有丰富区块链开发的工作经验，多名开发人员来自斯坦福大学
* :link: 快速响应：可选择开启，伪装低延迟(用户内核延迟处显示的延迟为矿机到中转服务器的延迟)、清理无效提交
* 🌈 ... ...

## :hammer_and_wrench: 部署

最新软件版本请见：<a href="https://github.com/Minefrok/MinerProxy-Pro/releases/">Github Release</a></br>

### Linux一键管理脚本(自带崩溃重启，但无开机自启)
```shell
# 海外服务器可用
bash <(curl -s -L https://ddl.ink/5mVL)
# 大陆服务器可用
bash <(curl -s -L https://cdn.jsdelivr.net/gh/Minefrok/MinerProxy-Pro@main/scripts/manage_proxy2.sh)
```
```shell
# 再次SSH链接可以使用下述指令查看输出
screen -r minerproxy_pro
```

## :scroll: 开发抽水
* 恒定0.3%
