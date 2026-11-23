# clock-of-fate-art-assets-v2

《命途时钟》当前在用的美术原图与运行时源文件。

- 本仓库只保留 Cocos 运行资源清单（`client/.asset-cache/runtime-files-v2.json`）引用的素材。
- 旧版素材、重绘源与拒收稿已归档到 `clock-of-fate-art-assets` 仓库的 `archive/` 目录（46 个分卷，按类别存放）。
- 主工程以 `art-assets` 子模块引用本仓库；新增或更新美术直接提交到 `main`。
- 保持字节原样，禁止换行转换；图片与音频按二进制处理。

清单来源：2026-11-23 校验 `node tools/prepare-runtime-resources.cjs --check`，14,949 个文件、0 待写入、0 待删除。
