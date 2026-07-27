# WhiteLeer

聚焦实时图形、Unity 工具链、DCC 自动化与资产处理工作流。

![Metrics](./github-metrics.svg)

## 技术链

![个人技术链](./personal-tech-chain.png)

## 当前主要仓库

### 图形、渲染与验收

- [`unity-graphics-lab`](https://github.com/WhiteLeer/unity-graphics-lab)
  - Unity 图形实验场：渲染算法验证、共享预览系统与工程化示例。
  - TIPS:
    - 以实验和验证为主，不承诺最终项目落地。
    - 优先沉淀可复现的场景、参数和对照结果。
    - 新能力先在这里完成验证，再迁移到正式工程。
- [`unity-shadertoy-validation`](https://github.com/WhiteLeer/unity-shadertoy-validation)
  - Shadertoy 参考提取、Unity 移植、效果对照与可复现验收。
  - TIPS:
    - 这里重点保留参考一致性，不承担工程化包装。
    - 每个条目都尽量保留原始参考与验收结果。
    - 可调版本和共享基础设施优先放到 `unity-graphics-lab`。
- [`unity-extraction-validation`](https://github.com/WhiteLeer/unity-extraction-validation)
  - Unity 资源提取后的导入恢复、材质与绑定检查、角色规范化及内容验证。
  - TIPS:
    - 关注提取后资源是否能稳定回到 Unity 语境。
    - 绑定、材质、角色规范化都按验收标准检查。
    - 这里更适合做内容验证，不适合堆叠最终业务逻辑。

### 图形调试与工具

- [`my-renderdoc`](https://github.com/WhiteLeer/my-renderdoc)
  - Personal RenderDoc baseline with game-version-specific branches.
  - TIPS:
    - 作为个人基线仓库使用，保持分支边界清晰。
    - 版本相关改动尽量按游戏版本拆分。
    - 先确保抓帧与分析链路稳定，再扩展工作流。

### 资产与内容工作区

- [`my-assets-studio`](https://github.com/WhiteLeer/my-assets-studio)
  - AnimeStudio 上游基线镜像；资源提取与游戏适配在独立分支维护。
  - TIPS:
    - 保留上游基线，避免把适配修改混进主线说明。
    - 提取与适配分支分开，便于回溯和比对。
    - 对外描述尽量只讲当前职责，不混写历史实验内容。

### 图形知识

- [`graphics-reading-notes`](https://github.com/WhiteLeer/graphics-reading-notes)
  - RTR4、PBRT4 与 GPU Gems 系列图形学笔记的统一归档。
  - TIPS:
    - 以主题归档和持续更新为主，不追求一次性完结。
    - 笔记条目尽量保持可检索、可回看、可引用。
    - 保留原书来源和章节上下文，方便后续交叉查阅。

## 说明

- 本仓库是公开项目导航，不代替各项目自己的文档。
- 私有仓库用于资产研究工作区、每日记录与长期知识沉淀，不在公开主页逐项展示。
- `github-metrics.svg` 由 `.github/workflows/metrics.yml` 自动更新。
