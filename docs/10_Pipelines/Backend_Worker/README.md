# 🧱 后端 / Worker / 管线编排（Backend & Worker）

## 目标 / 范围
把各管线输出工件入库、可追溯、可回放、可对外服务（matches/teams/pipeline）。

## 输入
- 标定结果、轨迹结果、球轨迹、评分结果、视频索引
- 元数据：team/match 信息

## 输出（关键工件）
- API/任务编排：backend/worker
- 工件组织规范：match_id 对应一套标准路径/版本信息
- 版本绑定：commit hash / 数据版本 / 参数版本

## 当前进度 & 已知问题
- ✅ 已做过 backend + worker 的 snapshot/tag（工程化关键节点）
- ⚠️ 需要把关键命令固化为一键入口（减少人为差异）

## 下一步（可执行）
- 用 make/just 固化：calibrate / track / ball / eval
- 每次跑完自动落盘实验记录到 notes/04_Experiments
