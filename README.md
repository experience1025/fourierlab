# Fourier Lab · 傅里叶实验室

**Live · 在线:** <https://fourierlab.pages.dev/>

> A playful, animated Fourier playground — waves that draw themselves, phasors that dance, and complex circles that can trace your own shape.
>
> 一个会转、会画、会生长的傅里叶动画游乐场：自己画出来的波形、会跳舞的相量、能描出你随手一画的复数圆链。

---

## English

### What is this?

Fourier Lab is a small, dependency-free stage for *seeing* Fourier ideas move. No derivation-first, no walls of formulas: open the page, watch the waves build themselves, drag the sliders, and draw a loop to see a chain of circles chase it.

Three scenes live on one 1600 × 900 paper-white stage, with ink-black type and a single red accent:

1. **Cabinet of Waves / 波形展柜** — fourteen curves, each with its series, its first few terms, and a live partial sum. Gibbs ears, square corners, heartbeats, staircases.
2. **Rotating Phasors / 旋转相量** — a chain of arrows placed tip to tail. The height of the tip over time is the wave; the trail is the drawing.
3. **Complex Plane / 复平面绘形** — a chain of complex circles draws a heart, a star, a wave — or whatever you draw with the mouse. The subtitle calls it *2D Fourier*.

### Why it is fun

- **It moves before it explains.** Every formula has a moving picture next to it; the picture is the point, the formula is the caption.
- **You can draw back.** In the complex-plane scene, press and drag anywhere on the whiteboard: the circles immediately try to learn your line. No button-hunting.
- **The tip leaves a trail.** The phasor scene literally writes the waveform with the tip of the chain; the wave is the memory of the motion.
- **One visual language.** Paper white, ink, red; serif formulas in little cabinet cards; no dashboard chrome.
- **Nothing to install.** No build step, no CDN, no external fonts, no images. One HTML file contains the CSS, JS, and every formula as inline SVG.

### Run

Open `index.html` directly, or serve the folder:

```bash
python -m http.server 8000
# then open http://localhost:8000/
```

### Deploy

Cloudflare Pages → **Upload assets** → upload a folder containing `index.html` at the root (or the zip). Build command: empty. Output directory: `/`.

Live: <https://fourierlab.pages.dev/>

### Files

```
fourierlab/
├─ index.html   # the whole playground
└─ README.md
```

### Credits

The page began as a chapter of **[Swell](https://swell-bep.pages.dev/)** — two little wave games and a cabinet of curves. Fourier Lab gives the animation chapter its own stage.

---

## 中文

### 这是什么？

傅里叶实验室是一个零依赖的小舞台，专门用来**看**傅里叶动起来。不是先推公式，而是先看波形自己长出来、看箭头跳舞、看圆链追着你画的线跑。

一个 1600 × 900 的纸白舞台，墨黑字，一点朱红，三幕：

1. **波形展柜** — 十四条曲线。每张卡片有级数、前几项和实时叠加；方波的尖角、心跳的脉冲、阶梯、抛物线都在里面。
2. **旋转相量** — 一串首尾相接的箭头。矢端的高度随时间走成一条波；走过的轨迹就是画。
3. **复平面绘形** — 一串复数圆链，画心形、五角星、浪花，或者你随手画的一团线。小字叫它“二维傅里叶”。

### 为什么好玩

- **先动，再解释。** 每条公式旁边都有一张会动的图；图是主角，公式是图注。
- **你可以画回去。** 复平面这一幕，直接在画板上按住拖动，圆链会立刻试着描你的线，不用先找按钮。
- **矢端会留下轨迹。** 相量那一幕，波就是链子尖端走过的记忆。
- **一套视觉语言。** 纸白、墨黑、朱红；公式像展柜里的小卡片；没有仪表盘式的边框。
- **什么都不用装。** 无构建、无 CDN、无外部字体、无图片；一个 HTML 里装着 CSS、JS 和全部内联 SVG 公式。

### 运行

直接打开 `index.html`，或者：

```bash
python -m http.server 8000
# 然后打开 http://localhost:8000/
```

### 部署

Cloudflare Pages → **Upload assets** → 上传根目录含 `index.html` 的文件夹（或 zip）。Build command 留空，输出目录 `/`。

在线：<https://fourierlab.pages.dev/>

### 目录

```
fourierlab/
├─ index.html   # 整个游乐场
└─ README.md
```

### 来历

这一页最初是 **[Swell](https://swell-bep.pages.dev/)** 的一章——两个关于波的小游戏，加一册波形展柜。现在，动画这一章有了自己的舞台。
