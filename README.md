# 猫耳女仆死侍 Codex Pet

这是一个使用 Codex 及其他 AI 工具辅助生成的猫耳女仆死侍 Codex 桌宠，包含完整的动作精灵图与安装配置。

## 动作图鉴

<table>
  <tr>
    <td align="center"><img src="gif/idle.gif" width="180" alt="idle"><br><code>idle</code></td>
    <td align="center"><img src="gif/running.gif" width="180" alt="running"><br><code>running</code></td>
    <td align="center"><img src="gif/running-left.gif" width="180" alt="running-left"><br><code>running-left</code></td>
  </tr>
  <tr>
    <td align="center"><img src="gif/running-right.gif" width="180" alt="running-right"><br><code>running-right</code></td>
    <td align="center"><img src="gif/waiting.gif" width="180" alt="waiting"><br><code>waiting</code></td>
    <td align="center"><img src="gif/review.gif" width="180" alt="review"><br><code>review</code></td>
  </tr>
  <tr>
    <td align="center"><img src="gif/failed.gif" width="180" alt="failed"><br><code>failed</code></td>
    <td align="center"><img src="gif/waving.gif" width="180" alt="waving"><br><code>waving</code></td>
    <td align="center"><img src="gif/jumping.gif" width="180" alt="jumping"><br><code>jumping</code></td>
  </tr>
</table>

## 安装方法

将下面这段 prompt 直接发送给 Codex：

```text
请从 GitHub 仓库 `https://github.com/zhuqian0504/cat-maid-deadpool` 安装猫耳女仆死侍 Codex Desktop 自定义宠物。

请按以下要求直接执行：
1. 使用 `git clone https://github.com/zhuqian0504/cat-maid-deadpool.git` 克隆仓库；如果当前目录已是该仓库，直接使用当前目录。
2. 确定 Codex 配置目录：优先使用环境变量 `CODEX_HOME`；如未设置，Windows 使用 `%USERPROFILE%\.codex`，macOS/Linux 使用 `~/.codex`。
3. 创建宠物目录 `<CODEX_HOME>/pets/cat-maid-deadpool`。
4. 将仓库中的 `final/spritesheet.webp` 复制到该目录。
5. 在该目录创建 `pet.json`，内容必须为：
   {
     "id": "cat-maid-deadpool",
     "displayName": "喵仆侍",
     "description": "喵~",
     "spritesheetPath": "spritesheet.webp"
   }
6. 保留 `<CODEX_HOME>/config.toml` 中的其他配置，只在 `[desktop]` 配置段中添加或更新：
   selected-avatar-id = "custom:cat-maid-deadpool"
7. 验证 `pet.json` 和 `spritesheet.webp` 均存在，并确认 `pet.json` 是有效 JSON。
8. 完成后告诉我实际安装路径和验证结果，然后提醒我完全退出并重新打开 Codex Desktop 以加载宠物。

不要改动仓库内的原始文件，也不要覆盖 `config.toml` 中与本次安装无关的配置。
```
