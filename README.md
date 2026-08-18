# M+ Visual Identity Research Hub / M+ 视觉识别研究面板

一个关于香港 **M+ 博物馆视觉识别系统（Visual Identity）** 的研究型可视化面板与品牌视觉套件。识别系统由阿姆斯特丹设计工作室 **thonik** 设计（标志由英国 **North** 工作室设计）。

**在线浏览**：启用 GitHub Pages 后访问 `https://<用户名>.github.io/<仓库名>/`

## 内容

- **项目概览** — M+ 博物馆简介、项目时间线、设计团队与协作方、所获奖项（DFA 2022 大奖、Dezeen Awards 2022 入围、欧洲设计奖铜奖、Tokyo TDC 2023 提名）
- **识别系统解读** — 标志逻辑（North）、50% 黑等明度色彩科学、香港城市叙事（霓虹 × 高楼灰）、中英双语排版规则
- **品牌视觉套件**（`brand-kit/`）— 研究性重建的 SVG 资产：
  - `mplus-palette.svg` — 中调色板卡（15 主色 + 3 中性色，色值采样自官方图片）
  - `mplus-colour-wheel.svg` — M+ 色轮重建（12 中调色段 + 50% 灰轮心）
  - `mplus-pattern-1~4.svg` — 「+」加号满版图案 × 4 组官方配色
- **图片档案馆**（`images/`，43 张）— 4 个官方/权威来源的全部项目图片，逐图附画面描述与 VI 应用方式解读：
  - `dezeen/` — Dezeen 报道（13 张）
  - `thonik-open/` — thonik「Open: M+ in Hong Kong」（8 张）
  - `thonik-chromatic/` — thonik「A chromatic visual identity for M+ Hong Kong」（9 张）
  - `thonik-annual/` — thonik「M+ Annual Review」（13 张）

## 本地运行

纯静态站点，无需构建：

```bash
cd mplus-vi-hub
python3 -m http.server 8000
# 打开 http://localhost:8000
```

或直接双击打开 `index.html`。

## 资料来源

- Dezeen — [Thonik creates colourful visual identity for Hong Kong's M+ museum](https://www.dezeen.com/2022/10/18/thonik-visual-identity-m-museum/) (2022-10-18)
- thonik — [Open: M+ in Hong Kong](https://thonik.nl/stories/open-m-hong-kong)
- thonik — [A chromatic visual identity for M+ Hong Kong](https://thonik.nl/stories/a-chromatic-visual-identity-for-m-hong-kong)
- thonik — [M+ Annual Review](https://thonik.nl/stories/m-annual-review)
- M+ 官网 — [mplus.org.hk](https://www.mplus.org.hk/)

## 版权说明

- M+ 标志与品牌资产的版权归 **M+ 博物馆（西九文化区管理局）** 与设计方（标志：North；VI：thonik）所有
- 图片摄影：SWKIT、Kimberley Zondag 等，版权归原方所有
- thonik 未公布官方 hex 色值；套件色板为从官方图片采样的**研究性重建**
- 本项目仅供研究与学习用途，不用于商业目的
