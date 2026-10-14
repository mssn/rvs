# Supplementary Materials for **Re**alistic **V**iew Synthesis for **Ve**rtical **L**anding (ReVeL)

This repository contains supplementary material for ReVeL: Realistic View Synthesis for Vertical Landing, including raw render result images, ground truth images, and additional illustration of comparisons for House A (`fig2`), House B (`fig6`) and Building C (`fig7`).

`house_a.png`, `house_b.png`, and `building_c.png` show the collected landing ground-truth trajectories.
- `fig2` uses markers 1, 2, 3, 5, 6, and 7 as the train set and marker 4 as the test/evaluation set.
- `fig6` uses markers 11, 10, 15, 17, 18, and 22 as the train set and marker 14 as the test/evaluation set.
- `fig7` uses markers 27, 28, 19, 33, 35, and 36 as the train set and marker 34 as the test/evaluation set.

Directory organization:
```
fig2
├── ...
fig6
├── ...
fig7
├── <altitude in meters>
│   ├── GroundTruth.jpg
│   ├── <Method Name>.jpg (rendered image)
│   ├── ...
└── all.jpg (matrix of all images side by side, along with LPIPS and DISTS metric heatmaps)
```