# iPad 2010 — LIGHT THE SPARK WITHIN — MASTER CASE SPEC

> **Usage:** This file is the persistent source of truth for Codex.  
> Codex should read this file before editing the case. Do not compress it into a generic template.

## EXECUTION MODE

- If the case page already exists, **audit first and preserve working routes/interactions**.
- Do not rebuild a functioning case unless the current implementation blocks a required interaction or visual direction.
- Treat the confirmed reference board as **FINAL ART DIRECTION**, not as loose inspiration.
- Rebuild visual compositions as layered HTML/CSS/JS + independent assets; do not flatten a reference board into one background image.
- Missing visuals must be marked `ASSET NEEDED`; do not silently substitute stock imagery or a different visual language.
- Primary route: `/projects/ipad-2010/`

## CONFIRMED VISUAL REFERENCE LOCK

Use the confirmed four-panel reference board:
- 01 HERO: charcoal-gray field, purple/violet spark, finger-to-surface interaction.
- 02 JOURNEY MAP: translucent liquid-glass ribbon connecting six nodes.
- 03 SPARK CORRIDOR: luminous violet path activated by footsteps; dreamlike but not spaceship-like.
- 04 LIGHT THE MAP: connected sparks spreading from individual creation to a brighter world.
Final background preference is **charcoal gray rather than pure black**.
The emotional progression is ONE SPARK → A PATH → A STAGE → A NETWORK → A MAP → A WORLD.

---

我要把 **2010 初代 iPad 发布会重构方案**制作成我的 Portfolio 中 THINK 层的完整 HTML Case Study。

这不是把原来的 31 页 PPT 转成网页，而是把原方案重新剪辑成一个：

**Strategy Case Study + Interactive Journey Map + Video Evidence + Experience Prototype**

核心目标：

1. 展示我如何重新思考一场产品发布会；
2. 展示完整 Consumer Journey；
3. 强调 `Light the Spark Within` 如何贯穿 BEFORE / DURING / AFTER；
4. 突出我的个人贡献；
5. 充分利用已有视频，而不是把视频放在最后当附件；
6. 最终直接接入现有 Portfolio 的 THINK 层。

---

# 0. PROJECT LOCATION

在现有 portfolio-site 中创建：

`public/projects/ipad-2010/index.html`

素材目录：

`public/assets/ipad-2010/`

最终 URL：

`/projects/ipad-2010/`

Brain Building THINK 层中的 iPad 项目点击后进入：

`/projects/ipad-2010/`

页面固定提供：

`← BACK TO MY MIND`

返回：

`/mind`

尽量恢复用户进入项目之前的 Brain Building scroll position。

不要创建新的独立网站导航。

---

# 1. SOURCE OF TRUTH

我会提供：

1. `consumer journey map G4.pdf`
2. 最新确认的四宫格视觉参考图
3. 发布亮相视频
4. Light Up the U.S. Map 视频

规则：

- PDF = campaign logic / content source of truth
- 四宫格图 = visual direction reference
- 视频 = 原方案触点的动态展示
- 不允许根据一般 Apple 发布会知识擅自改写原方案
- 不要编造用户研究数字、KPI、转化数据或真实商业结果

这个项目是概念策划 / Experience Strategy 项目，不要包装成 Apple 实际执行过的案例。

---

# 2. PROJECT TITLE

主标题：

# LIGHT THE SPARK WITHIN

副标题：

**Reimagining the 2010 iPad Launch**

项目定位：

**Experience Strategy / Launch Journey / Integrated Communication**

核心 Thesis：

> The iPad is an extension of potential.

中文解释：

> iPad 不是创造力本身，而是唤醒一个人原本已经拥有的潜能。

---

# 3. VISUAL DIRECTION

已经确认的视觉：

## CHARCOAL × PURPLE LIQUID GLASS

不要再使用纯黑大面积背景。

主背景：

- charcoal gray
- smoky graphite
- soft warm gray-black

主色：

- violet
- lavender
- electric purple
- translucent white
- 少量 warm spark gold

风格关键词：

- liquid glass
- translucent layers
- soft glow
- refraction
- dreamy technology
- light particles
- flowing ribbons
- subtle cosmic texture
- elegant Apple-like minimalism
- cinematic launch atmosphere

IMPORTANT：

“液态玻璃”不是所有内容都做成圆角玻璃卡片。

真正应该玻璃化的是：

- Journey Path
- Spark
- iPad
- Video Window
- Interactive Nodes
- Map Points

正文区域保持克制、干净。

---

# 4. GLOBAL EXPERIENCE

整个项目必须围绕一个动作：

# LIGHT

视觉 progression：

ONE SPARK

↓

A PATH

↓

A STAGE

↓

A NETWORK

↓

A MAP

↓

A WORLD

随着用户向下滚动：

页面越来越亮。

从最开始的单个 Spark：

逐渐发展成整个世界被点亮。

---

# 5. CORE JOURNEY MAP

Journey Map 是本项目的核心信息结构，同时也是网页导航。

不要做传统 UX Journey Table。

做一条半透明的：

**LIQUID GLASS JOURNEY RIBBON**

节点：

### BEFORE
01 IGNITE

### DURING
02 ENTER  
03 REVEAL  
04 EXPERIENCE  
05 AMPLIFY

### AFTER
06 LIGHT THE MAP

用户滚动到哪个 Section：

- 对应 Journey Node 点亮；
- 当前路径变亮；
- 未到达节点保持半透明；
- 已经过的节点留下微弱残光。

桌面端可以做 sticky / fixed Journey navigation。

点击节点可直接跳转对应 section。

---

# 6. SECTION 00 — HERO

使用我确认的第一张视觉方向。

背景：

charcoal gray + soft violet atmospheric glow。

画面：

一只手指触碰 iPad / liquid glass surface。

接触点产生一个明亮 Spark。

紫色光线像液态能量一样向外扩散。

主标题：

# LIGHT THE SPARK WITHIN

小字：

> From a touch, to a brighter you.

正文：

> A new device is more than a device.
> It can become the beginning of what you create next.

可加一句：

> The iPad is an extension of potential.

Interaction：

用户鼠标靠近 Spark 时：

- light reacts
- particles drift
- liquid surface轻微波动

按钮：

`IGNITE THE JOURNEY ↓`

---

# 7. SECTION 01 — THE CHALLENGE

标题：

**Why rethink the launch?**

中文：

**为什么要重新设计这场发布？**

不要把原 PPT 五六个问题全部列成 PPT bullets。

提炼成三个核心矛盾：

### 01
**A new category without a story**

用户容易直接把 iPad 理解为：

`a larger iPhone`

### 02
**A product launch dominated by one voice**

原发布高度依赖单人演示，难以充分展示多场景使用。

### 03
**A climax without a continuing journey**

发布结束后缺乏持续参与机制。

核心 Reframe：

> Before explaining what the iPad can do,
> we wanted people to feel what it means to ignite an idea.

视觉：

三块非常轻的 translucent text layers。

不要做普通卡片。

---

# 8. SECTION 02 — BIG IDEA

中心只保留：

# LIGHT THE SPARK WITHIN

拆解：

### SPARK
curiosity / inspiration / creativity

### LIGHT
the iPad acts as the catalyst

### WITHIN
the potential was already inside the user

最后形成一句：

> The device doesn't give you creativity.
> It helps you awaken it.

这部分保持极简。

视觉以：

Spark → liquid ribbon

为主。

---

# 9. SECTION 03 — JOURNEY OVERVIEW

完整展示：

BEFORE

↓

DURING

↓

AFTER

Journey progression：

**Mystery → Curiosity → Delight → Resonance → Motivation**

这一条要作为情绪 Journey。

不要只写营销阶段。

画面使用最新确认的 `02 JOURNEY MAP` 视觉方向。

节点：

01 Ignite

02 Enter

03 Reveal

04 Experience

05 Amplify

06 Light the Map

这之后，用户开始逐节点向下探索。

---

# 10. NODE 01 — IGNITE

阶段：

BEFORE THE EVENT

目标：

不是先揭示新品。

而是让用户理解：

**Touch can become creation.**

原方案中的预热装置：

- vertical black mirror-like display
- blank canvas feeling
- interaction through touch
- Spark appears and grows

网页互动：

出现一个暗色 Liquid Glass surface。

文字：

`TOUCH TO IGNITE`

用户点击或 Pointer Down：

一个 Spark 出现。

继续拖动：

光线跟随手指移动。

最终可以演化成：

- tree
- music
- brushstroke
- formula

不需要做复杂绘画系统。

做出“Touch awakens something”即可。

中文小注释：

> 在正式揭示产品之前，我们先让用户学会一种行为：触碰不是操作，而是创造的开始。

---

# 11. NODE 02 — ENTER / SPARK CORRIDOR

这是重要个人贡献之一。

标题：

# WHERE YOU WALK, YOU LIGHT.

视觉严格参考确认的 `03 SPARK CORRIDOR`：

- charcoal / violet corridor
- translucent walls
- liquid-glass floor
- purple light
- people walking
- dreamlike but not sci-fi spaceship

设计逻辑：

地面传感器检测脚步。

每个人经过：

点亮路径的一部分。

所有人的 Spark：

最终形成完整光路。

网页 Interaction：

Scroll 或 mouse move 模拟前进。

路径分段。

经过一段：

该段亮起。

文字可以出现在墙上：

CURIOSITY  
IDEAS  
IMAGINATION  
PEOPLE  
CREATE

最终：

**YOUR SPARK HAS ENTERED THE ROOM.**

这里优先嵌入已有 Spark Corridor 视频，如果有。

如果没有对应视频则使用动效模拟。

---

# 12. NODE 03 — REVEAL

标题：

# 1,000,000 SPARKS IGNITED

这是发布高潮。

使用我提供的“亮相”视频。

不要把视频放在普通播放器框里。

做成：

Full-width / cinematic video block。

进入 section 后：

视频自动播放一次。

视频播放前：

数字从：

1

→ 10

→ 100

→ …

最后：

`1,000,000`

出现：

**SPARKS IGNITED**

然后进入视频。

视频结束时：

产品 Reveal。

旁边只保留一句：

> The product wasn't simply unveiled.
> It appeared after the audience had already created the light.

增加：

`REPLAY THE REVEAL`

---

# 13. NODE 04 — EXPERIENCE

标题：

# EVERY FEATURE LIGHTS A NEW LINE

不要把这里做成 iPad Feature List。

核心机制：

一个功能

↓

点亮一条新的连接。

中心：

初代 iPad。

周围节点：

DRAW

WATCH

READ

WORK

CREATE

用户点击：

DRAW

一条 purple liquid light line 点亮。

点击：

READ

第二条亮起。

点击其他：

继续增长。

最后：

所有线路连接成一个完整发光 network。

设计逻辑：

不同功能不是孤立 demo。

它们共同构成：

**an activated creative ecosystem**

这部分可以用 CSS / SVG path / GSAP 完成。

---

# 14. NODE 05 — AMPLIFY

标题：

# ONE STAGE. MANY VOICES.

原方案将：

Jobs作为主线

+

author

photographer

professional / business user

等多角色远程连线。

目的：

把一场单人发布：

改成多个真实使用场景共同证明产品价值。

视觉：

中心一块 liquid glass screen：

Steve Jobs / main stage

周围四块轻量浮动 screen：

ARTIST

AUTHOR

PHOTOGRAPHER

PROFESSIONAL

Hover：

播放对应短视频 / placeholder。

这一 section 不需要特别长。

避免抢 Spark Corridor 和 Map 的重点。

---

# 15. NODE 06 — LIGHT THE MAP

这是另一个重要个人贡献。

标题：

# FROM MY SPARK TO OUR LIGHT

使用我提供的：

Light Up the U.S. Map 视频。

初始：

dark charcoal / violet U.S. map。

只有少量 light points。

网页互动：

点击地图任意区域：

一个 Spark 出现。

出现：

`1 CREATION`

`1 LOCATION`

`1 SPARK`

继续点击：

越来越多。

随后播放地图点亮视频。

逻辑：

用户将 iPad 创作与地点绑定。

↓

对应位置亮起。

↓

不同人的创作：

共同点亮地图。

最后地图：

zoom out / morph

从：

U.S.

到：

WORLD

结尾：

# ONE SPARK  
# A BRIGHTER WORLD.

这里可以成为整个 Case Study 的视觉终章。

---

# 16. SECTION — THE SPARK CONTINUES

AFTER阶段其它策略只做简洁补充。

不要把原PPT后半段全搬进来。

只展示：

### Conversation
专业用户 / 创作者持续讨论

### Community
官方社区与用户反馈

### Adoption
用户理解和使用产品

### Light the Map
最重要的 collective creation mechanism

用一条很短的 continuation line 表现。

---

# 17. SECTION — MY ROLE

这一段必须非常清楚。

标题：

# WHAT I SHAPED

中文：

**我在项目中负责什么？**

按照目前已确认信息：

### 01 EXPERIENCE FRAMEWORK
参与整体发布会体验框架设计。

### 02 SPARK CORRIDOR
提出并发展 Spark Corridor 核心概念。

### 03 LIGHT UP THE U.S. MAP
提出 / 发展发布后的 collective creation mechanism。

### 04 EXPERIENCE NARRATIVE
参与将 Spark 作为 BEFORE / DURING / AFTER 的统一 narrative thread。

### 05 PITCH INTEGRATION
参与最终方案结构与路演呈现整合。

IMPORTANT：

不要写：

`I created the whole campaign.`

准确使用：

proposed  
shaped  
developed  
designed  
integrated  
developed with the team

---

# 18. SECTION — WHY IT WORKS

标题：

# FROM A PRODUCT DEMO  
# TO A PARTICIPATORY JOURNEY

总结四点：

### A theme became an action.
Spark 不只是文案，用户真的去点亮它。

### The audience participated before the reveal.
产品出现前，用户已经进入这个世界。

### Features became one connected story.
每个功能不是堆叠，而是不断点亮新的 creative path。

### One person's creation became collective light.
从个人 Spark 扩展到整个地图。

---

# 19. FINAL SECTION

背景从 charcoal：

慢慢变成更亮的紫灰色。

中央：

一个小 Spark。

然后越来越多。

最后：

# LIGHT THE SPARK WITHIN

下面：

> One device.
> One spark.
> A world of possibility.

按钮：

`← BACK TO MY MIND`

---

# 20. VIDEO INTEGRATION

IMPORTANT：

不要创建独立：

VIDEO GALLERY。

视频属于 Journey。

### Reveal Video

放：

NODE 03 / REVEAL

### Map Video

放：

NODE 06 / LIGHT THE MAP

其他视频：

根据触点内容放进对应 Node。

视频窗口保持：

- liquid glass edge
- subtle glow
- no heavy browser chrome

提供：

play / pause / replay

不要强制所有视频循环。

---

# 21. TECHNICAL IMPLEMENTATION

整个 Case 优先使用：

HTML  
CSS  
Vanilla JavaScript

放在：

`public/projects/ipad-2010/index.html`

如果已有 GSAP：

可直接使用。

不要增加大型新框架。

可使用：

SVG

CSS masks

blur

backdrop-filter

mix-blend-mode

但必须注意性能。

---

# 22. RESPONSIVE

优先：

Desktop Portfolio

建议内容宽度：

1200–1440px

Journey Map：

Desktop可 sticky。

Tablet：

缩小。

Mobile：

转换为纵向 stepper。

不要为了手机牺牲 Desktop 主视觉。

---

# 23. ASSETS

创建：

`public/assets/ipad-2010/`

建议：

hero-spark.webp

liquid-glass-texture.webp

spark-particle.png

spark-corridor.webp

ipad-2010.png

journey-map-reference.png

reveal-video.mp4

light-map-video.mp4

us-map.svg

world-map.svg

jobs-stage.png

feature-draw.png

feature-read.png

feature-video.png

feature-work.png

IMPORTANT：

缺少的视觉素材：

先使用 placeholder。

标记：

`ASSET NEEDED`

不要擅自用完全不同风格的 stock image 替换。

---

# 24. INTEGRATE WITH BRAIN BUILDING

现有 THINK 层：

iPad room

Hover：

`iPad 2010`

`LIGHT THE SPARK WITHIN`

`ENTER ↗`

点击：

进入：

`/projects/ipad-2010/`

不要破坏现有：

HK7s  
EMBI  
IN STEP

等 route。

---

# 25. BUILD ORDER

不要一次全部堆完。

PHASE 1

建立完整 HTML Section skeleton。

PHASE 2

完成：

Hero  
Challenge  
Big Idea  
Journey Map

PHASE 3

完成：

Ignite  
Spark Corridor

PHASE 4

接入：

Reveal video

PHASE 5

完成：

Feature Network  
Amplify

PHASE 6

完成：

Light the Map + map video

PHASE 7

完成：

My Role  
Why It Works  
Final

PHASE 8

接入 Brain Building route。

PHASE 9

检查：

- Desktop
- Scroll
- Journey highlight
- Videos
- Hover
- Spark interaction
- Map interaction
- Back to My Mind
- Console errors
- Broken assets

先检查现有 portfolio-site 项目结构。

输出 Implementation Plan。

然后直接开始 PHASE 1。

不要重新设计已经确认的视觉方向。
不要改变 `Light the Spark Within`。
不要把31页PPT逐页搬上网页。
不要把视频全部放进独立 Gallery。
不要编造研究数据或商业效果。

---

# APPENDIX A — DO NOT LOSE

- [ ] Touch / finger interaction becomes the Spark metaphor.
- [ ] `LIGHT THE SPARK WITHIN` remains the core idea and title.
- [ ] The six-node Journey remains: Ignite → Enter → Reveal → Experience → Amplify → Light the Map.
- [ ] The page grows brighter as the user moves through the case.
- [ ] Spark Corridor remains a major personal-contribution section.
- [ ] The Reveal uses the existing reveal video in the REVEAL node.
- [ ] Light the Map uses the existing U.S./map video in the LIGHT THE MAP node.
- [ ] Existing videos live inside their journey touchpoints; no separate video gallery.
- [ ] Feature presentation is a connected light network, not a feature-list grid.
- [ ] The visual system stays charcoal + violet liquid glass, not generic Apple minimalism.
- [ ] My Role remains explicit and does not claim sole ownership of the team project.

# APPENDIX B — PRODUCTION ASSET MANIFEST

## P0 — VISUAL IDENTITY
- `hero-spark.webp — hero visual / tactile spark focal point`
- `ipad-2010.png — clean device cutout or high-quality device render`
- `spark-corridor.webp or layered corridor assets — core ENTER environment`
- `liquid-glass-texture.webp — subtle material texture used selectively`
- `journey-map-reference.png — reference-only guide, not a flat webpage background`

## P1 — CORE INTERACTION
- `reveal-video.mp4 — NODE 03 cinematic reveal`
- `light-map-video.mp4 — NODE 06 map illumination`
- `us-map.svg — interactive U.S. spark map`
- `world-map.svg — final zoom-out / world state`
- `spark-particle.png / light-ribbon.svg — reusable interactive light elements`
- `jobs-stage.png or verified project stage visual — AMPLIFY node if needed`

## P2 — POLISH / OPTIONAL
- `feature-draw.png`
- `feature-read.png`
- `feature-video.png`
- `feature-work.png`
- `subtle grain / cosmic texture overlays`

### Asset Rules

- Keep important text as HTML, not baked into imagery.
- Use SVG for simple paths/icons/lines when practical.
- Use PNG/WebP alpha for complex transparent collage elements.
- Use WebP for photographic or non-transparent raster assets.
- Use project-supplied videos in their intended narrative nodes, not in a separate gallery.
- If an asset is missing, use a restrained placeholder and annotate `ASSET NEEDED`.
- Do not replace missing assets with unrelated stock, emojis, generic icons, or a new AI style.

# APPENDIX C — ACCEPTANCE CHECKLIST

- [ ] Hero visually matches the confirmed charcoal + purple reference direction.
- [ ] Journey Map visibly communicates BEFORE / DURING / AFTER and all six nodes.
- [ ] Current node highlights as the user scrolls; passed nodes retain a soft residual glow.
- [ ] Spark Corridor reacts to scroll/pointer and visually lights the path.
- [ ] Reveal video plays in-context and offers replay without heavy browser chrome.
- [ ] Experience node lights multiple feature paths into one connected network.
- [ ] Light the Map interaction grows from individual sparks to collective illumination.
- [ ] Page brightness and spatial openness increase across the narrative.
- [ ] My Role is clear, accurate, and uses collaborative verbs where required.
- [ ] No fabricated KPIs, user-research numbers, or claims of real Apple execution.
- [ ] Back to My Mind works and existing portfolio routes remain intact.
- [ ] Desktop is primary; tablet/mobile degrade gracefully without sacrificing the core visual story.

# FINAL IMPLEMENTATION PRINCIPLE

> Preserve this project's unique logic and visual personality. Shared portfolio components may standardize navigation and accessibility, but **must not flatten the case into the same template as the other THINK projects**.
