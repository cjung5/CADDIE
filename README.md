# CADDIE — Project Page

Project page for **CADDIE: Compact Adaptive Detection-Driven Inference for Real-Time Golf Club Pose Estimation** (CVsports Workshop @ CVPR 2026).

Live: <https://cjung5.github.io/CADDIE/>

## About

CADDIE is a compact, markerless framework for real-time golf club pose estimation. A two-stage top-down pipeline (ConvNeXtV2-Atto detection + heatmap & offset pose head) tracks a universal five-keypoint schema — grip, shaft, neck, head-in, head-out — across drivers, woods, and irons. At only **14.3M parameters** it runs at **69 FPS** with **88.52% PCK@5px**, beating HRNet-W32 and ViTPose-B while being 2–6× smaller. An adaptive temporal-smoothing scheme further scales inference up to **238 FPS** with under 1% accuracy loss.

This site presents the paper at a glance: abstract, the GolfClub dataset, method, results vs. baselines, and a qualitative comparison. The full paper PDF is linked from the **Paper** button at the top.
