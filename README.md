# 星际弹幕 Neon Arc

竖屏太空弹幕射击游戏。同一套 HTML5 引擎，Electron 壳出 Windows exe，WKWebView 壳出 iOS ipa。

## 玩法
- 战役：固定关卡推进，末尾 BOSS
- 无尽：难度随时间爬升，刷分
- BOSS 连战：连续 BOSS，无杂兵间歇
- 联机合作：双人确定性锁步，服务器只转发输入帧

## 结构
- app/ HTML5 游戏本体
- shell/ Electron 主进程
- server/ WebSocket 中继
- ios/ XcodeGen 工程描述 + Swift 壳
