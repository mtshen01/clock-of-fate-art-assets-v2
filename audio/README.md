# 音频资源

`bgm/bgm_room.mp3` 对应《渡口候席》，`bgm/bgm_battle.mp3` 对应《石阶交锋》。交互拟音位于 `sfx/`，药水按完整数据 ID 命名，位于 `sfx/potions/`。精英、首领、普通怪与水晶球专属声库沿用各自子目录。

背景音乐为立体声，交互与药水音效为单声道，均为 44.1 kHz MP3。保留同名 `.meta`，以便 Creator 按原有 UUID 导入。主项目运行 `npm run assets:prepare` 后，播放器即可通过 `audio/bgm/<key>` 或 `audio/sfx/<key>` 读取。

主项目中的 `tools/audio/render_room_battle.py` 和 `tools/audio/interaction-sfx.py` 保留原创谱面和拟音配方。工作目录、技术验证、试听与缺口清单见主项目的 `docs/26-audio-design.md` 与 `docs/128-interaction-audio-audit.md`。
