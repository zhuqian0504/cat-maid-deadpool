# Cat-Maid Deadpool Codex Pet

[中文](README.md) | **English**

This is a Cat-Maid Deadpool desktop pet for Codex, created with assistance from Codex and other AI tools. It includes a complete animation spritesheet and installation configuration.

## Animation Gallery

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

## Installation

Send the following prompt directly to Codex:

```text
Install the Cat-Maid Deadpool custom desktop pet for Codex Desktop from this GitHub repository: `https://github.com/zhuqian0504/cat-maid-deadpool`.

Perform these steps directly:
1. Clone the repository. If the current directory is already this repository, use it directly.
2. Copy the entire `final` folder to `<CODEX_HOME>/pets/cat-maid-deadpool`. If `CODEX_HOME` is not set, use `%USERPROFILE%\.codex` on Windows or `~/.codex` on macOS/Linux.
3. Preserve all other content in `<CODEX_HOME>/config.toml`. Under `[desktop]`, add or update `selected-avatar-id = "custom:cat-maid-deadpool"`.
4. Verify that `pet.json` and `spritesheet.webp` exist in the installation directory, then report the installation path and verification result.
5. Remind me to fully quit and reopen Codex Desktop.

Do not modify the original repository files or overwrite unrelated settings in `config.toml`.
```
