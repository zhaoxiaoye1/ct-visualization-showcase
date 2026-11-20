# 科研三维可视化 / Research visualization

[打开作品展示 / View showcase](https://zhaoxiaoye1.github.io/ct-visualization-showcase/)

围绕沉积物微观结构研究，展示颗粒分割、局部邻居网络和 DVC 辅助运动核查的可视化工作。

- **分割**：二值掩码与颗粒实例分割的 5 × 5 画面对照。
- **局部连接**：192³ 子区域的整体网络与单颗粒邻居。
- **运动核查**：抽样颗粒表面、质心运动与局部预测/观测对照。

本仓库只包含展示页面和精选栅格画面。三维演示以动画播放，不能提取或交互查询科研对象。原始 CT、分割标签数组、颗粒编号、坐标、网格、测量表、完整追踪结果及定量结论均未提供。动画中间帧为插值演示，不是额外的 CT 实测时刻，样例也不代表整体准确率或最终地质结论。

The repository contains presentation code and selected raster visuals only. It does not distribute CT volumes, segmentation arrays, particle IDs, coordinates, meshes, measurements, tracking tables, or quantitative findings. Intermediate animation frames are interpolated for visualization, not additional CT observations.

[已发表论文 / Published paper](https://doi.org/10.1016/j.aiig.2026.100273)

在研材料的版权保留。Published research visuals are not licensed for dataset reuse. UI source code may be read to understand the presentation implementation; no scientific processing pipeline is distributed here.
