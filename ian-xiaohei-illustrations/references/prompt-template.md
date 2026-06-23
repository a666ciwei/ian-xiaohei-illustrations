# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Clean white or very light warm off-white background. Minimalist brown-black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations. Warm clean hand-drawn notebook / gentle children-book character illustration feeling, but not childish. Soft pencil or ink outlines, light watercolor or colored-pencil wash, muted earthy palette. No gradients, no heavy shadows, no dirty paper texture, no complex background, no commercial vector style, no PPT infographic look, no sticker mascot poster, no realistic UI.

Recurring IP character required:
刺猬, a warm anthropomorphic hedgehog character: round chubby body, cream face and belly, brown soft spiky hedgehog quills, tiny black bead eyes, small black round nose, subtle smile, peach blush cheeks, round ears, oversized cream knit sweater, burnt-orange scarf with fringes, olive green loose pants, olive green crossbody satchel with a button. Optional small ukulele or handmade tool prop. 刺猬 must perform the core conceptual action, not decorate the scene. Make 刺猬 gentle, focused, handmade, slightly clumsy, and calm; not a generic cute mascot.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：刺猬在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Brown/black pencil lines for main line art. Cream, brown, burnt orange, and olive green for 刺猬. Orange for main flow/path/arrows. Red only for key warnings/problems/results. Blue only for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank clean space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not draw the old solid-black 小黑 creature. Do not make 刺猬 look like a realistic animal, 3D toy, Disney-style big-eyed mascot, or overly childish cartoon. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, warm but not childish, imaginative but clean.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强角色参与感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make 刺猬 more central to the conceptual action. 刺猬 should be doing the warm handmade work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, warm, and not childish.
```
