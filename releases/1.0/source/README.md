# 灵犀输入法 1.0 对应词库源码

`RimeSharedData/` 是灵犀输入法 1.0 构建时使用的可编辑数据源快照。

- `cn_dicts/`、`cn_dicts_cell/`、`opencc/` 及相关 schema 主要派生自 [iDvel/rime-ice](https://github.com/iDvel/rime-ice)，并由本项目修改，按 GNU GPL v3 分发。
- `english_dict.txt` 由本项目独立维护，不源自 Rime Ice。
- 本目录刻意不包含 librime 生成的预编译文件；使用随 App 相同版本的 librime 部署这些 YAML、文本和 JSON 文件即可重新生成运行时数据。

完整许可见 `LICENSE-GPL-3.0.txt`。
