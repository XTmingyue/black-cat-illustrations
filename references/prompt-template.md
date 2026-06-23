# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly thin pen lines. Lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations. Clean absurd product-sketch feeling, very close to Ian Xiaohei style. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI, no messy full-page doodle, no dirty watercolor background.

Recurring IP character required:
A small dazed black cat replaces Xiaohei as the recurring IP character. The cat is a small black hand-drawn/watercolor-like shape with subtle rough edges, triangular ears, huge white eyes, tiny black pupils, a tiny nose and mouth, a few messy whisker lines, short legs or paws, and a blank confused expression. The cat must perform the core conceptual action with paws, tail, or body, not decorate the scene. Keep the cat small: usually 8%-18% of the canvas, never more than 25% unless the user explicitly asks for a portrait. Do not make it a close-up cat head, pet sticker, realistic cat, or cute mascot.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Cat action:
{呆头黑猫的具体小动作；例如爪子扒纸卡、尾巴勾路径、叼标签、坐在关键节点上、从抽屉里探头、被少量线缠住}

Composition:
{具体画面：黑猫在哪里、动作如何参与核心结构、主要物件是什么、信息如何流动；先画结构，再放小比例黑猫}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Black for main line art, the black cat, structure, and primary text. Orange for main flow/path/arrows. Red only for key warnings/problems/results. Blue only for secondary notes or feedback/system state. Very subtle dark gray may appear only inside the cat body for slight watercolor texture.

Constraints:
One image explains only one core structure. Keep the overall subject structure around 40%-60% of the canvas. Keep the black cat small, usually 8%-18% of the canvas, and make it secondary to the structure while still doing the key action. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, dense explainer, pet portrait, cute sticker, realistic cat painting, rough watercolor poster, or chaotic doodle page. Do not copy the close-up reference portrait composition. Invent a fresh low-tech visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: cat, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

缩小黑猫占比：

```text
Regenerate this illustration with the same core meaning and layout, but make the dazed black cat smaller and less dominant. The cat should occupy only about 8%-18% of the canvas, acting inside the structure with paws or tail, while the low-tech metaphor and information flow remain the main subject. Keep the pure white background, clean thin hand-drawn line art, sparse red/orange/blue Chinese annotations, and lots of empty space.
```

增强角色参与度：

```text
Regenerate this illustration with the same core meaning and simple layout, but make the small dazed black cat more central to the conceptual action without enlarging it. The cat should explain the idea through a small physical action: pawing cards, getting lightly tangled in lines, sitting on a key node, biting a label, or pulling one main thread. Keep it clean, sparse, hand-drawn, and close to Ian Xiaohei style.
```

恢复原版清爽风：

```text
Regenerate this illustration with the same core meaning, but make the entire image cleaner and closer to Ian Xiaohei style: pure white background, minimalist black hand-drawn line art, lots of empty space, sparse red/orange/blue Chinese handwritten notes, low-tech metaphor, and a small dazed black cat as the action character. Remove messy watercolor background, heavy textures, dense scratch lines, and pet-poster feeling.
```

修正角色识别：

```text
Edit the provided image to make the small recurring character more recognizable as the dazed black cat: black body, triangular ears, oversized white eyes, tiny black pupils, tiny nose and mouth, a few messy whiskers, and a blank confused expression. Keep the cat small and preserve the original clean composition, labels, background, and conceptual action. Do not turn it into a realistic cat or a large mascot.
```
