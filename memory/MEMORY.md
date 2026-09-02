# 活记忆（Hermes 式）· 孙承泽数字人

> **规则**：每次对话结束前，把新学到的偏好/进展/语言风格/决策追加到下方日志（带日期，追加式）。新会话开局必读本文件。
> **建立**：2026-09-01（随 v1.1）。目前尚无对话记录——第一条由首次实测对话写入。

## 开局速查 · 已固化偏好（摘要自 SKILL.md v1.1）

- 全程中文；语音输入常有口误，纠错后回应；
- 给默认值、不阻塞交付；问题可分批答、可跳过；
- 反 AI 套话；结论先行 + 数字锚点；说人话；
- 决策风格：选"让我变强"的选项（哪怕更累）；重大决策先 AI 多轮校对 + 深度调研，确认万无一失再执行；"给我虚假的东西我是会揍它的"；
- 作息锚点：7:00 起（双闹钟放远处）— 24:00 前睡，午休 30 分钟；周末全天图书馆；周跑约 4×2 km；
- 风险警报 4 类默认开启：情绪冲动 / 完美主义 / 大局观丢失 / 刷手机；
- 话题边界：政治回避、宗教不主动聊、家庭可聊；
- 当前主线：大二进组（郭振东方向：叶轮机械智能设计优化/智能流场预测/UQ）；103 页综述《Machine learning in aerodynamic shape optimization》精读中；Obsidian「SCZ Lab」待建体系。

## 对话日志（追加式）

- **2026-09-02 · 全账号跨分支重扫**：首轮只扫 main 不完整，用户指正后**重新扫描全部 13 仓库的 `arena/*` 工作分支**。关键发现（已写入对外档案）：① 多数仓库 main 只是壳/README，**真货在 `arena/<会话>` 分支**（Arena 一个会话一个分支）；② `ai` 仓库其实是「attic」归档仓，把 **21 个一次性单页项目**收敛一仓（`MANIFEST.md` 总账，2026-09-02 快照，真货在 arena 01a06017/01a060a9）——全是备考(physics/dawu/gaoshu/cet6/IELTS/tushupdf)、生日礼物祝福(ryh戴森球/rzyz高考/孙鸣泽生日/霍格沃茨)、科普科幻(-0517脑机/20260524黑洞/planck/liangji两机/claude-cpt/COSMOS)等单页；③ `yiming` main 只是星际指令生日页，真货在 arena=**Yiming Lab/Council 百人圆桌多Agent决策** + minillm + `lab/OPENCLAUDE_GUIDE.md`（证实 **OpenClaude = @gitlawb/openclaude**，Claude Code 风格、接 OpenAI 兼容/DeepSeek 等后端）；④ `notEBooklm-scz`（今日新建，arena 有真货）= NotebookLM 桌面版封装(notebooklm-py)；⑤ turbine 平台 HANDOFF 已到 v8/Day44，含 **GHG「大师观后感」内阁评审**（Tufte/Munger/Karpathy/vonKármán/Garry Tan/Betz/Brunton/da Vinci/Jameson/Goldberg/李博杰 等 9–11 位大师逐页找茬打分）+ 四级证据链 E0→E4 诚实披露；⑥ `wode`=狗头军师(fork goutoujunshi，恋爱军师 v1)；⑦ `123` 真货在 arena=wind wake-steering 取证 + 叶轮机械 MDO 证据审计，结论暂不投稿；⑧ `sucheng` 已全分支整合进 main。对外档案已按「真货所在分支」重写，README 更新。
- **2026-09-02 · 技术环境 + 账号全景扫描**：用户委托「做对外信息仓库 + 全面扫描账号」。新录入事实：本地装 **Anaconda + Python + GitHub CLI（gh）**，下载了 GitHub 上的 **OpenClaude**（`〔推断〕`最可能=开源 claude-code 兼容版，接 OpenAI 兼容后端的 shim），**主力用 Claude Code 原生 harness 接 DeepSeek API** 跑 agent 工程。账号扫描：`sunccchengze` 建于 2025-12-14，扫描时 13 个公开仓库，无 bio/关注；仓库地图新增既有档案未收录项——`123`(321456789)、`wode`(恋爱军师 v1，2025-12-15 最早项目)、`ai`(nextjs-postgresql-template 脚手架，2026-07)、`yiming`(「星际指令」科幻单页，2026-06)、`notEBooklm-scz`(2026-09-02 今日新建空库，`〔推断〕`NotebookLM 个人版)；近期关注 minimind/scientific-agent-skills/OpenMAIC/awesome-ppt（`〔推断〕`mini-LLM 训练+科研 Agent 兴趣）。产出：根目录新增 `对外信息仓库-孙承泽账号档案.md`（对外扫描入口，推断带标注），README 加指向与状态行。
- **2026-09-01 · 迁库**：数字人主本由 `sunccchengze/-SKILL-`（`skills/community/nuwa-distilled/sun-chengze-perspective/`）整体迁至独立仓库 `sunccchengze/sunchengze-distilled`（即本仓库，唯一活的主本；`-SKILL-` 那份冻结为公开存档快照）；开局指令已改为连接本仓库、三个文件路径改为根目录相对路径（`SKILL.md`、`memory/MEMORY.md`、`references/acquisition/INTAKE_2026-08-31.md`）；新增根目录 `AGENTS.md`（全仓库铁律 8 条：活记忆只追加、有改动就 commit + 回复前 push 当前会话分支且失败必如实报告、全程中文、口误先纠正、诚实优先标「待确认」、不冒充本人对外发言、4 类风险警报默认开启、政治回避）。
