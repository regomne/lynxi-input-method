# 灵犀输入法：词库与配置对应源码

本分支提供灵犀输入法 App Store 发布版本随包分发的 Rime 词库、Emoji 数据与输入方案配置源文件，用于履行 GNU GPL v3 的对应源码提供义务。

## 发布版本

| App 版本 | 源码目录 | 下载包 | SHA-256 |
| --- | --- | --- | --- |
| 1.0 | [`releases/1.0/source`](releases/1.0/source) | [`lynxi-rime-source-1.0.zip`](releases/1.0/lynxi-rime-source-1.0.zip) | [`SHA256SUMS`](releases/1.0/SHA256SUMS) |

## 来源与许可

- 上游项目：[iDvel/rime-ice](https://github.com/iDvel/rime-ice)，作者 iDvel 及贡献者，采用 GNU GPL v3。
- 本项目最初导入词库的日期为 2026-03-31；该日期对应的上游历史参照提交为 `48789c26d9dd809329d57065baabc0053009f540`。
- 灵犀输入法对词库文件名、拆分方式、词条、权重、Emoji 数据和 Rime schema 做过修改。发布目录保存的是 App 1.0 实际采用的完整、可修改源文件，而不是仅指向持续变化的上游分支。
- `english_dict.txt` 为灵犀输入法项目独立维护的数据，不源自 Rime Ice；为便于复现随包数据，一并收录在对应源码中。

GNU GPL v3 全文见 [`LICENSE-GPL-3.0.txt`](LICENSE-GPL-3.0.txt)，版本目录内也附有一份副本。

## 范围

源码包只包含可编辑的词库、OpenCC 文本/JSON 数据和 Rime YAML 配置。它不包含用户词典、用户输入数据、日志、安装标识或 librime 生成的 `.bin`、`.prism`、`.reverse` 预编译产物。

