# QiPhone Trial

QiPhone Trial is a phone mod for the "Run For Money" Minecraft video series, created by 柒风Captain. It retains the core features of the phone mod and removes series-exclusive integration, available for free to players.

QiPhone Trial 是由 柒风Captain 为《全员逃走中》系列作品制作的手机模组体验版。它保留了手机模组的核心功能，移除了系列联动的专属内容，供玩家免费体验。

This mod is still in the development stage. If you have any features you want to add, you can leave a comment here or contact me!

这个模组还处于开发阶段。如果你有任何想添加的功能，可以在这里留言或联系我！

---

## 主要功能 / Main Features

### 消息 / Messages

Send and receive text and image messages. Multi-conversation support with unread badges.

玩家可以使用 QiPhone 发送与接收文字消息、图片消息，支持多会话管理，未读消息角标。

### 通话 / Calls

Integrated with Simple Voice Chat. Each player gets a random phone number. Supports call, answer, reject, hang up, with call timer and call history.

与 Simple Voice Chat 联动，每位玩家都会获得一个随机电话号码。玩家可以通过电话功能远程交流，支持拨打、接听、拒绝、挂断，通话计时与通话记录。

### 相机与相册 / Camera & Album

Take photos, save them locally, or send to other players.

可以拍摄照片，保存到本地相册，或发送给其他玩家。

### 指南针 / Compass

A compass displayed for 10 seconds on screen, showing your facing direction in real time.

在屏幕显示10秒的指南针，可以在屏幕上实时显示你的朝向。

### 步数 / Steps

Records your movement steps in-game, with a leaderboard that resets every 3 in-game days.

记录你在游戏中的移动步数，步数会生成步数排行榜，排行榜每 3 个游戏日重置。

### 小游戏 / Mini-games

Mini-games (Snake, Qi Block) with score leaderboards.

一些小游戏（贪吃蛇、柒块），以及得分排行榜。

### 设置 / Settings

Customize your nickname and phone wallpaper.

可以自定义昵称和手机壁纸。

Server admins can place a PNG image in the `<world>/QiPhone/wallpaper/` folder, with the filename matching the player's game ID (e.g. `Steve.png`).

服务器管理员可以将 PNG 图片放到 `<世界目录>/QiPhone/wallpaper/` 目录，文件名与玩家游戏 ID 一致（如 `Steve.png`）。

Players can go to Phone → Settings → Wallpaper Settings and click "Refresh Wallpaper" to see it.

玩家进入手机 → 设置 → 壁纸设置，点击「刷新壁纸」即可看到新壁纸。

Recommended resolution: `172x294` (keep the 172:294 ratio; the client will center-crop without stretching).

推荐分辨率：`172x294`（保持 172:294 比例，客户端会自动居中裁切，不会拉伸）。

If the wallpaper does not show, check:
- Filename matches the player's game ID exactly (case-sensitive)
- File format is PNG
- "Refresh Wallpaper" was clicked, or the player rejoined the server

如果壁纸没有显示，请检查：
- 文件名是否与玩家游戏 ID 完全一致（区分大小写）
- 图片格式是否为 PNG
- 是否点击了「刷新壁纸」或重新进入服务器

---

## 环境要求 / Requirements

| 项 / Item | 版本 / Version |
|---|---|
| Minecraft | 1.20.1 |
| Forge | 47.4.x |
| Simple Voice Chat | 2.6.x (optional, needed for calls) |
| Java | 17 |

Must be installed on both client and server.

必须同时安装在客户端和服务端。

---

## 反馈 / Feedback

遇到 Bug 或有功能建议，欢迎提交到 GitHub Issues，或通过 B 站私信联系我：

If you find a bug or have a feature suggestion, feel free to open a GitHub Issue, or contact me via Bilibili DM:

- GitHub Issues: [提交反馈](https://github.com/QFCaptain/qiphone-trial/issues)
- B 站私信 / Bilibili DM: [柒风Captain](https://space.bilibili.com/472268218)

反馈时请尽量附上：
- 游戏版本与 Forge 版本
- QiPhone Trial 版本号
- 崩溃日志（`crash-reports/` 目录下的文件）或截图
- 复现步骤

When reporting, please include:
- Game version and Forge version
- QiPhone Trial version
- Crash log (from `crash-reports/`) or screenshots
- Steps to reproduce

---

## 致谢 / Credits

| 类型 / Type | 成员 / Member | 相关链接 / Links |
|---|---|---|
| 作者 / Author | 柒风Captain | [Bilibili](https://space.bilibili.com/472268218) |
| 语音通话 API / Voice chat API | Simple Voice Chat | [Modrinth](https://modrinth.com/plugin/simple-voice-chat) |

---
© 2026 柒风Captain. All Rights Reserved.

Copyright © 2026 柒风Captain. All Rights Reserved.
