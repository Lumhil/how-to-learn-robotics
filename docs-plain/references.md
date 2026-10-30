# 参考资料指南（白话版）

> 原文：[docs/references.md](../docs/references.md)——那里是规范的参考文献列表；这里补充"每份资料是什么、什么时候读"。

原书 13 条参考文献的速查指南，按用途重新分组：

## 教材类（按学习顺序）

| 文献 | 是什么 | 什么时候读 |
|------|--------|-----------|
| [1] Craig《Introduction to Robotics: Mechanics and Control》 | 机器人学入门经典教材，全书"入门"部分的主线 | 入门第一本，配 Khatib 公开课 |
| [2] Khalil & Dombre《Modeling, Identification and Control of Robots》 | 机器人建模、**标定与辨识**的专著 | 入门"标定辨识"一节需要深入时 |
| [3]《Springer Handbook of Robotics》 | 2000 多页的机器人学**手册** | 不通读；每进一个新领域，翻对应章节看大纲、找参考文献 |
| [4] Chapra《Numerical Methods for Engineers》 | 数值计算方法（数值微分/积分等）教材 | 进阶前补数学 |
| [5] Lynch & Park《Modern Robotics》 | 用旋量/指数积（李群语言）重新讲机器人学，面向本科生，官网免费 | 进阶"现代机器人学"主线教材，配 Coursera 课程 |
| [8] Choset 等《Principles of Robot Motion》 | 运动规划教材，**把 C-Space 放在核心位置**是它被推荐的原因 | 进阶"自主规划"主线教材 |
| [9] LaValle《Planning Algorithms》 | 规划算法大全，作者主页免费 | 规划方向的百科全书式参考 |
| [10] Biagiotti & Melchiorri《Trajectory Planning for Automatic Machines and Robots》 | 轨迹规划（插补、时间参数化）专门教材 | "轨迹规划与时间参数化"一节深入时 |
| [13] Sutton & Barto《Introduction to Reinforcement Learning》 | 强化学习"圣经" | 具身智能篇入门 RL 必读，配 GitHub Python 实现 |

## 论文类

| 文献 | 是什么 |
|------|--------|
| [6] Zhang, *A flexible new technique for camera calibration* | 张正友标定法——相机内参标定的奠基论文，OpenCV 标定函数的理论源头 |
| [7] Lowe, *Distinctive image features from scale-invariant keypoints* | SIFT 特征点——"有纹理物体的位姿估计"一节的核心工具 |
| [11] Kim 等, *Tangent Bundle RRT* | 带约束运动规划：在约束流形的切丛上生长 RRT |
| [12] Jaillet & Porta, *Atlas-based RRT* | 带约束运动规划：边规划边给约束流形建"图册" |

## 提示

- 想找某本书/课的获取方式，回到[白话版对应章节](README.md)看正文里的链接，或直接用英文标题搜索；
- 一个实用的顺序建议：入门阶段只需要 [1]；进阶按主线各取 [5]、[8]；其余按需查阅。
