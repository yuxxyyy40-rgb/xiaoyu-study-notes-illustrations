# 生图提示词模板

每张图单独生成。根据笔记内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese study-note illustration.

Visual DNA:
Pure white background. Minimalist black-and-white hand-drawn line art. Slightly wobbly thin pen lines. Lots of empty white space. Calm relaxed study-notes feeling, like a small margin sketch in a notebook. The fish-head hat may feel cute mainly through its tiny fish eyes, but the whole image should still feel like a study-note sketch. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no childish sticker style, no children's illustration, no realistic UI.

Recurring IP character required:
小鱼, a small black-and-white science-minded person wearing round glasses and a rounded fish-head hood hat. The hat wraps around the top and sides of the head like a simple soft helmet, with one side fin, a tiny top fin or bump, and 2-4 curved segmented line marks. Add two tiny fish eyes on the front forehead area of the hat: either small black dot eyes or sleepy short-arc eyes. These hat eyes should be cute and quiet, but do not add a fish mouth. The person's round glasses and calm face remain visible below the hat. The fish-head hat is a simple black-and-white line-art identity mark, not a plush toy, not a realistic fish costume, not animal-face cosplay. 小鱼 has a calm relaxed expression, loose shoulders, simple hand-drawn body, and slightly slow patient movement. 小鱼 must perform the core learning action, not decorate the scene. Make 小鱼 relaxed, reliable, lightly cute because of the hat eyes, not childish, not anxious, not motivational-poster style.

Theme:
{学习笔记配图主题}

Structure type:
{结构类型：概念边界 / 错题复盘 / 步骤台阶 / 知识抽屉 / 记忆钩子 / 前后对比 / 复习路径 / 页边小漫画}

Core memory point:
{这张图要帮人记住的核心意思}

Composition:
{具体画面：小鱼在哪里、正在做什么、主要学习物件是什么、概念如何被整理}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {可选标注词4}

Color use:
Use black and white only by default. If emphasis is necessary, use one tiny pale gray or pale blue note only. Do not use colorful main visuals.

Constraints:
One image explains only one learning concept or memory point. Keep the main subject around 35%-55% of the canvas. Preserve at least 40% blank white space. Use at most 3-6 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, dense explainer, childish sticker, or commercial illustration. It should feel relaxed and clear, like a helpful hand-drawn note in the margin.
```

## 图像编辑提示

去掉多余标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank page. Preserve everything else exactly: character, labels, objects, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强小鱼参与感：

```text
Regenerate this illustration with the same core memory point and simple layout, but make 小鱼 more central to the learning action. 小鱼 should be the relaxed glasses-wearing little person with a fish hat who sorts, folds, marks, sits beside, or holds the concept together, not standing beside the drawing. Keep it black-and-white, sparse, relaxed, and clear.
```
