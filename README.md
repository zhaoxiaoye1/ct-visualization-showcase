# 科研三维可视化 / Research visualization

## 为什么做这个

研究沉积物微观结构对海底地质薄弱层的影响，需要把压缩前后的内部颗粒结构与运动联系起来。项目从二维 CT 灰度切片出发，组织三维结构、分割、邻居关系与 DVC 位移核查，帮助理解和检查跨阶段变化。

[打开作品展示 / View showcase](https://zhaoxiaoye1.github.io/ct-visualization-showcase/)

围绕沉积物微观结构研究，将三维 CT、颗粒分割和 DVC 位移信息整理为直观的对照与核查视图。

- **颗粒分割**：在五个压缩阶段、五个相对高度切换查看二值掩码与颗粒实例。
- **局部连接**：观察 192³ 子区域的整体网络，以及中心颗粒和周围邻居。
- **运动核查**：结合抽样颗粒表面与质心，比较 DVC 位移预测和后续扫描观测。

页面支持中英文切换、处理前后对照和独立动画演示。动画中间帧采用位置或位移插值，颜色用于区分当前画面中的颗粒实例。

## 从切片到三维

CT 扫描形成沿扫描方向排列的二维灰度切片。展示页先用精选切片和堆叠示意解释体积数据，再呈现三维颗粒结构、分割前后对照，以及整体与局部核查视图。灰度示例采用 160 × 160 像素的展示图。

## Research workflow

This work explores sediment microstructure through particle segmentation, local contact networks and DVC-assisted motion inspection. The showcase combines five-stage image comparisons, a 192³ neighborhood view and animated comparisons of displacement predictions with subsequent scan observations.

The presentation supports Chinese and English, before-and-after views and standalone animations. Intermediate frames use position or displacement interpolation; instance colors distinguish particles within each image.

[已发表论文 / Published paper](https://doi.org/10.1016/j.aiig.2026.100273)
