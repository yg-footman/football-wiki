# 管线索引（Pipelines Index）

> 每条管线独立一页：输入/输出/依赖/状态/下一步/Runbook。
> 新增管线：在 `10_Pipelines/<NewPipeline>/README.md` 建页，然后在本索引加一条链接。

## 核心主线（M1：轨迹闭环）
1. 🎥 采集与机位： [Acquisition](Acquisition/README.md)
2. 📐 标定与场地映射： [Calibration](Calibration/README.md)
3. 🧍 球员检测与跟踪： [Vision → Player Tracks](Vision_PlayerTracks/README.md)
4. 🔗 轨迹合并与过滤： [Merge & Filter](Tracking_MergeFilter/README.md)
5. 📡 定位器 → 球员世界轨迹： [Tag → World Traj](Tag_PlayerWorldTraj/README.md)
6. ⚽ 球轨迹 baseline（A/B融合）： [Ball Baseline](Ball_Baseline/README.md)
7. 🧠 丢球段补全（论文创新）： [Ball Completion](Ball_Completion/README.md)

## 中长期（V3/V4，2026Q2主推）
- 🧩 动作理解与合理度评分（超图/专家背书）： [Action Scoring](Action_Scoring/README.md)

## 工程底座
- 🧱 后端/Worker/管线编排： [Backend & Worker](Backend_Worker/README.md)

## 产品侧新增管线（预留）
- 📱 手机App： [Mobile App](Mobile_App/README.md)
- 💬 微信小程序： [WeChat Mini Program](WeChat_MiniProgram/README.md)
