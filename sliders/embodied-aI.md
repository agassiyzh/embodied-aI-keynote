# 具身智能：当AI拥有"身体"

---

> ### 我觉的我们搞错方向了
> 我们希望机器人帮人类扫地、洗碗，是因为人类要去写诗、画画。
>
> 现在是AI都去写诗和画画了，我们人类还在扫地、洗碗

---

## 1. 什么是具身智能？

- 具身智能（Embodied AI）是指拥有物理或虚拟身体，能与环境实时交互、学习和适应的人工智能。
- 研究意义：让AI真正理解和适应现实世界。

--

### 具身智能的核心特征

- 感知-行动闭环
- 与环境持续互动
- 具身认知理论支撑

---

## 2. 具身智能的研究范式

- 感知（Perception） <!-- .element: class="fragment" -->
- 行动（Action） <!-- .element: class="fragment" -->
- 认知（Cognition） <!-- .element: class="fragment" -->
- 学习（Learning） <!-- .element: class="fragment" -->

--

### 感知（Perception）

- 智能体通过视觉、听觉、触觉等多模态传感器获取环境信息 <!-- .element: class="fragment" -->
- 例子：摄像头识别障碍物，麦克风感知声音，触觉传感器检测物体 <!-- .element: class="fragment" -->
- 感知是智能体与环境互动的第一步 <!-- .element: class="fragment" -->

--

### 行动（Action）

- 智能体根据感知结果做出运动控制、路径规划、操作等决策 <!-- .element: class="fragment" -->
- 例子：机器人移动、机械臂抓取、无人车转弯 <!-- .element: class="fragment" -->
- 行动能力决定了智能体能否有效影响环境 <!-- .element: class="fragment" -->

--

### 认知（Cognition）

- 智能体对任务、环境和自身状态的理解与推理 <!-- .element: class="fragment" -->
- 包括目标设定、决策制定、计划生成等 <!-- .element: class="fragment" -->
- 例子：机器人规划清扫路径，理解复杂指令 <!-- .element: class="fragment" -->

--

### 学习（Learning）

- 智能体通过与环境的交互不断优化自身行为 <!-- .element: class="fragment" -->
- 包括强化学习、模仿学习、自监督学习等方法 <!-- .element: class="fragment" -->
- 例子：机器人通过试错学会倒水，虚拟智能体在仿真环境中自我提升 <!-- .element: class="fragment" -->

---

## 3. 典型任务

### 导航（Navigation）

- 智能体在复杂环境中自主移动
- 例子：机器人在房间中寻找目标

--

### 操作（Manipulation）

- 机械臂抓取、搬运、组装等
- 例子：机器人分拣快递包裹

--

### 多智能体协作

- 多个机器人协同完成任务
- 例子：仓库机器人集群协作

--

### 人机交互

- 智能体与人类自然交流与协作
- 例子：陪护机器人、导览机器人

---

## 4. 具身智能的仿真平台

- AI Habitat
- iGibson
- MetaWorld
- RoboTHOR
- PyBullet

--

### AI Habitat

- 由Facebook AI Research开发的高效3D仿真平台
- 支持大规模视觉导航、交互任务
- 特点：高性能、丰富的真实场景数据集
- 常用于视觉导航、房间探索等研究

--

### iGibson

- 斯坦福大学开发的交互式仿真平台
- 支持物理交互、机器人操作、导航等任务
- 特点：高保真物理模拟、丰富的室内场景
- 适合研究机器人操作与环境交互

--

### MetaWorld

- 针对多任务机器人操作的仿真平台
- 包含50+种机械臂操作任务
- 特点：任务多样、适合多任务/迁移学习研究
- 常用于强化学习算法测试

--

### RoboTHOR

- Allen Institute for AI开发的室内导航仿真平台
- 提供真实感强的室内环境和视觉任务
- 特点：支持多智能体、视觉导航、交互任务
- 适合视觉导航和多智能体协作研究

--

### PyBullet

- 开源的物理引擎和机器人仿真平台
- 支持多种机器人模型和物理模拟
- 特点：易用、可扩展、社区活跃
- 常用于机器人控制、强化学习实验

---

## 5. 具身智能的数据集

- 视觉导航数据集
- 操作任务数据集
- 多模态感知数据集

---

## 6. 主流算法与模型

- 端到端强化学习
- 层级强化学习
- 世界模型（World Models）
- 多模态Transformer
- 视觉-语言-动作模型（如RT-2）

--

### 端到端强化学习

- 智能体直接从感知输入到动作输出，自动学习最优策略
- 适合复杂环境下的自主决策
- 例子：DeepMind的DQN、AlphaGo

--

### 层级强化学习

- 将复杂任务分解为多个子任务，分层学习和决策
- 提高学习效率和泛化能力
- 例子：机器人先导航到房间，再抓取物体

--

### 世界模型（World Models）

- 智能体内部构建环境的"模拟器"，预测未来状态
- 支持规划、推理和更高效的学习
- 例子：智能体先在脑中"想象"再行动

--

### 多模态Transformer

- 同时处理视觉、语言、动作等多种信息
- 利用Transformer结构实现跨模态理解和推理
- 例子：视觉问答、图文导航

--

### 视觉-语言-动作模型（如RT-2）

- 将视觉、语言和动作决策整合为统一模型
- 支持复杂任务的端到端学习
- 例子：谷歌RT-2机器人模型，能理解指令并执行操作

---

## 7. 前沿进展与论文推荐

- 重要论文列表
- 经典实验与Benchmark
- 综述与前沿动态

---


<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=114692185982041&bvid=BV1BsMqzgExn&cid=30527000121&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" style="width:90%;height:600px"></iframe>

---

## 8. 竞赛与社区资源

- AI Habitat Challenge
- RoboTHOR Challenge
- 相关学术会议与社区

---

## 9. 学习路径与入门建议

- 推荐课程与教材
- 代码实践与项目建议
- 未来发展方向

---

## 10. 参考资料与扩展阅读

- 书籍、论文、博客、视频等
- [Embodied-AI-Guide](https://github.com/TianxingChen/Embodied-AI-Guide/blob/main/README.md)

---

## 谢谢大家！

### 欢迎提问
