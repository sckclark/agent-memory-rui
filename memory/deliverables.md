---
name: deliverables
description: Every 蕊元 document: source template, current version, history
metadata:
  type: reference
---

Deliverables live in `~/deliverables/蕊元书院_营销评估/`, and sources in `~/work/ruiyuan/`.

| Document | Source | Current | Notes |
|---|---|---|---|
| 《AI可见度与市场营销评估》 | report.tpl.html | v5 汇报反馈版, 16 pp (11-22) | 零 feedback table 13 rows; §九 ops, §十 客源, §十二 incentives, §十三 小红书, §十四 → 文创 PDF, §十五 needs; v1–v4 + v5_1119 in 旧版 |
| 《落地物料文案》 | kit.tpl.html | v3, 3 pp | room cards, 节气卡, 3 breakfasts, staff scripts, 抖音 titles, group-buy, fact sheet; yellow = fill-ins |
| 《定位与对外宣传说辞》 | position.tpl.html | v1, 5 pp | see [[positioning]] |
| 《文创小店方案》 | shop.tpl.html + merch/gen.py | v2 蕊元雅集 文创主线 (11-23), 3 pp; v1 template shop.v1a.tpl.html, v1 PDF in 旧版 as _v1_1122 | 文创设计稿_初稿.png preview (v1 drafts) |
| 《小红书账号诊断》 | xhs.tpl.html | v1, 2 pp | duplicates report §十三; offered to shrink §十三 to a pointer (no answer yet) |
| 小瑞狮形象草图 | merch/lion.py → lion.svg/png | v1 (11-23): 标准形象抱绣球 + 礼/书/冬至 variants, palette | deliverables/小瑞狮_形象草图_v1.png; sent to 郑宗梅 |
| 小瑞狮形象草图 v2 | merch/lion2.py → lion2.svg/png (ref_lobby_lion.png crop) | v2 (11-23): closer to the lobby 瑞狮 (gold on 朱红, 海棠 frame, 绣球, pedestal) | deliverables/小瑞狮_形象草图_v2.png; sent to 郑宗梅 |
- 客房清扫SOP_v1.pdf (11-23, for 郑宗梅; source `work/ruiyuan/hk.tpl.html`): 9-step housekeeping SOP "按五星级标准" (internal only; 书院 not star-rated). Draft; 房务负责人 to check against real 房型/布草/用品.
- 客房清扫九步法_培训视频_v1.mp4 (11-23): ~5 min vertical, 14 slides + 火山 TTS narration. Source `work/ruiyuan/video/make.py` (slides s*.png, narration s*.txt, ffmpeg concat).
- 客房清扫九步法_小瑞狮动画版_v1.mp4 (11-23): ~4.5 min vertical cartoon (chibi housekeeper in 朱红 uniform + 小瑞狮 v1 narrator, sparkles, timed subtitles, fades). Same narration audio as v1 video. Source `work/ruiyuan/video2/` (art.py drawings, scenes.py layers → Chrome PNGs, render.py ffmpeg overlays). Sent to 郑董 for OK before posting to group.
- 客房清扫配套表格_v1.pdf (11-23, source `work/ruiyuan/hkforms.tpl.html`): 3 pages. Checklist (22 items), monthly 100-point staff scoring, training sign-in sheet. Posted to group 蕊元书院 at 郑董's request.
- 总值班检查表_模板_v2.xlsx (11-24; source `work/ruiyuan/duty/make.py`, run with ~/work/.venv/bin/python, which has openpyxl and pillow). Adds 沽清登记, a complaint-handling outcome, specifics/follow-up columns, a 节能 check, handover owners and deadlines, and signatures. Posted to 总值班沟通群 at 郑董's request.
- 2026-11-24 蕊元书院_电子查房表_v1.xlsx（源 ~/work/ruiyuan/eform/make.py，venv python）：使用说明、查房记录（1000 行，22 项 ✓/✗ 下拉，自动算用时和不合格数）、统计（总体、分项、清扫员、检查人，可按月）、名单、检查标准。给段立军（房务）。未在钉钉在线表格里测试。
