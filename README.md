<h1 align="center">
  <br>
  <img src="https://github.com/Minefrok/MinerProxy-Pro/blob/8af2437313573c2a8dd6b254755103d454ab8737/images/logo.png" width="350"/>
</h1>

<h4 align="center">基於GoLang的高性能多線程ETH/ETC礦池轉發中繼代理工具.</h4>

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
  • <a href="https://t.me/minerproxypro">Telegram 討論群组</a>
</p>

## :sparkles: 特性

* :cloud: 礦池轉發：支持ETH/ETC的中繼代理，支持Stratum/NiceHash/Stratum2所有協議，方便統一管理(其他幣種即将更新)
* :zap: 超高性能：採用高效率的GoLang語言編寫，並對多線程進行優化
* 💻 自定義抽水：支持中繼平台自定義抽水比例進行抽水，並支持在不關閉代理池的情況下進行動態修改
* 📚 多種抽水算法：用戶可自選各種抽水算法，防止算力出現週期函數或心跳圖的情況
* 💾 安全穩定：支持TCP、SSL等方式，並對CC攻擊編寫一定的策略進行防護
* :gear: 獨家前置代理模式：支持中轉伺服器到礦池端的加密與混淆，可內網部署
* :outbox_tray: 批量轉發：一個軟件即可開啟對多個礦池的轉發，無需開啟多個進程
* :card_file_box: 熱修改：配置均可網頁後台上熱修改，無需再修改繁瑣配置文件再重啟
* :art: 精美後台：後台網頁功能全面、折線圖、統計豐富、黑暗模式、多語言支持
* :eye_speech_bubble: 完善社區支持：Telegram 群組內可幫助處理解決遇到的各類問題，歡迎提出反饋建議
* :rocket: 開箱即用：All-In-One 打包，一鍵搭建運行，一鍵配置
* :family_woman_girl_boy: 多系統支持：Windows Linux MacOS均可支持使用，無需額外環境等
* :gear: 專業團隊：擁有豐富區塊鏈開發的工作經驗，多名開發人員來自香港科技大學名校
* :link: 快速響應：可選擇開啟，偽裝低延遲(用戶內核延遲處顯示的延遲為礦機到中轉服務器的延遲)、清理無效提交
* 🌈 ... ...

## :hammer_and_wrench: 部署

最新軟件版本請見：<a href="https://github.com/Minefrok/MinerProxy-Pro/releases/">Github Release</a></br>

### Linux一鍵管理脚本(自帶崩潰重啟，但無開機自啟)
```shell
# 海外伺服器可用
bash <(curl -s -L https://ddl.ink/5mVL)
# 大陆伺服器可用
bash <(curl -s -L https://cdn.jsdelivr.net/gh/Minefrok/MinerProxy-Pro@main/scripts/manage_proxy2.sh)
```
```shell
# 再次SSH链接可以使用下述指令查看输出
screen -r minerproxy_pro
```

## :scroll: 開發抽水
* 恆定0.3%
