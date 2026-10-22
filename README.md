# Text / Image-to-3D 图文思维导图

面向入门学习的三维生成技术地图：29 个细分类、53 篇代表论文、51 幅高清论文配图。

在线版本：[打开图文思维导图](https://text-image-3d-research-map.decentseal10.chatgpt.site/)。Sites 版本目前按站点权限访问；本仓库可独立下载并在本地运行。

## 内容

- 物体、场景、人体、动态 4D 与文字/图像联合控制。
- 各方法的输入输出、机制简介、教学流程图、局限和原论文链接。
- 包含 Dream Fields 原论文的框架图与结果图。
- SDS 分支包含 DreamGaussian、GaussianDreamer、GSGEN，区分优化机制与 3D Gaussian 表示。
- “场景生成 → 语言与程序组合”包含 LEGO-Anything，介绍 Image-to-Code 的 Blender 程序迭代，并附原论文框架图。
- 点击论文名称展开详情；点击配图查看高清原图。页面无需构建，核心内容在禁用 JavaScript 时仍可阅读。

## 本地运行

在仓库目录运行：

```sh
python -m http.server 8000
```

然后打开 http://localhost:8000/ 。也可以直接打开 index.html。

## 文件

- `index.html`：网页入口，包含样式、交互与所有方法简介。
- `mindmap_assets/`：论文配图。

此仓库保存思维导图网页，不包含视频课程、旁白音频或原始论文 PDF。

## 来源说明

论文配图用于研究学习，来源、图号与解释见网页相应图注；版权归原作者或出版方所有。仓库不为这些第三方图片授予额外许可。方法描述属于学习辅助材料，请结合原始论文核对具体结论与实验条件。

## 2026-10-22 frontier supplement

Added 12 recent primary-paper method cards and 24 short reading entries for the 2026-04-22 to 2026-10-22 window, plus Buffalo and TRELLIS.2 cards already covered in the survey. The map now contains 53 complete cards and 51 original-paper images. All 39 prior anchors remain available. The evaluation and verification topic distinguishes automatic models from human and Oracle studies.

The local survey is maintained in Word, PDF and Markdown. This repository contains the static map and its images; paper PDFs and video lessons are not part of this website upload.
