<p align="center">
  <h1 align="center">🎯 IELTS Speaking Lab</h1>
  <p align="center"><strong>雅思口语 Part 2 实战练习实验室</strong></p>
  <p align="center">2026年5-8月题库 · 55道题卡 · 44个7分素材 · AI润色</p>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/题库-2026年5~8月-blue" alt="Question Bank">
  <img src="https://img.shields.io/badge/题卡-55道-orange" alt="Cue Cards">
  <img src="https://img.shields.io/badge/素材-44个-purple" alt="Stories">
  <img src="https://img.shields.io/badge/依赖-零-brightgreen" alt="Zero Dependencies">
</p>

---

## 这是什么

一个**浏览器直接打开就能用**的雅思口语 Part 2 练习工具。专为 2026 年 5-8 月题库打造。

核心理念：**一个故事，多题复用** — 用有限的个人素材应对海量题卡，配合 AI 润色帮你打磨出 7 分水平的回答。

## 预览

**主界面：左侧目录 + 题卡 + 考官 + 计时 + AI润色**

<img src="images/screenshot-overview.png" alt="主界面概览" width="80%">

**44 个素材学习区：完整口语模板 + 好词好句 + 词汇表 + 四维评分**

<img src="images/screenshot-stories.png" alt="素材学习区" width="80%">

**自定义素材 + AI 润色：输入中文 → Gemini/DeepSeek → 7分英文故事**

<img src="images/screenshot-ai-polish.png" alt="AI润色演示" width="50%">

## 为什么用它

- 📋 **题库全**：55 道题卡完整覆盖人物/事物/事件/地点，标注新旧题，左侧目录一键跳转
- ⏱️ **真实模拟**：1 分钟准备 + 2 分钟作答计时，带进度条提示
- 📚 **44 个高质量素材**：每个素材含 ~170 词口语模板、好词好句、重点词汇、**IELTS 四项评分维度解析**
- ✨ **AI 润色**：输入中文思路，自动生成 7 分英文故事，支持 Gemini / DeepSeek
- 🔒 **隐私安全**：API Key 仅存本地浏览器，不写入文件，不上传第三方
- 📦 **零依赖**：单个 HTML 文件 + 4 张图片，下载即用

## 快速开始

```bash
git clone https://github.com/tutuhua/ielts-speaking-lab.git
cd ielts-speaking-lab
open index.html   # 或用浏览器直接打开
```

或者直接[下载 ZIP](https://github.com/tutuhua/ielts-speaking-lab/archive/refs/heads/main.zip)，解压后打开 `index.html`。

## 功能一览

| 模块 | 说明 |
|------|------|
| 🗂️ 左侧目录 | 55 题可折叠侧边栏，按分类筛选，点击跳转 |
| 🎲 随机抽题 | 支持全局抽/按分类抽，键盘 `D` 键快速抽题 |
| ⏱️ 计时训练 | 1 分钟准备（`1` 键）+ 2 分钟作答（`2` 键），`S` 键停止 |
| 📝 准备笔记 | 准备阶段记关键词，自动保存到练习记录 |
| 👩‍🏫 AI 考官 | 4 位 AI 生成考官照片，随机切換 |
| ✨ AI 润色 | 中文输入 → 7 分英文故事，支持 Gemini / DeepSeek |
| 📖 素材库 | 44 个内置素材 + 自定义增删改，分类浏览 |
| 📊 素材学习区 | 每个素材完整展示模板、好词好句、词汇表、评分 |
| 📋 练习记录 | 自动保存，可回顾、删除、升级为自定义素材 |

## 评分标准

所有素材均按 IELTS 口语四项评分维度标注：

- **FC** — Fluency & Coherence（流利度与连贯性）
- **LR** — Lexical Resource（词汇资源）
- **GRA** — Grammatical Range & Accuracy（语法范围与准确性）
- **P** — Pronunciation（发音建议）

## 隐私安全

- 🔑 API Key 存储在浏览器 `localStorage`，**不会写入项目文件**
- 🚫 **不会被 git 提交**，不会上传到任何第三方服务器
- 💻 所有练习数据保存在本地，不会离开你的设备
- 🗑️ 清除 Key：点击页面右上角 ⚙️ → 清空 Key 输入框

## AI 考官说明

页面中的考官头像均由 AI 生成，非真实人物，不涉及肖像权或利益冲突。

## License

MIT © 2026
