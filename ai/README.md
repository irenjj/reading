# AI 阅读资料

共 191 份 PDF，按主要内容分为 5 类，不设更深的子目录。每篇只存放一份，文件名保留英文字母、数字和下划线；PDF 使用 Git LFS 管理。

| 分类 | 数量 | 内容 |
| --- | ---: | --- |
| [algo](algo/) | 79 | 算法基础、模型架构、优化方法、计算机视觉、强化学习与对齐、模型技术报告 |
| [mlsys](mlsys/) | 77 | 分布式训练、推理服务、RL 训练系统、量化、调度、通信及性能分析 |
| [gpu_and_compiler](gpu_and_compiler/) | 7 | GPU 编程、算子实现、FlashAttention、CuTeDSL、CUDA Graph；也作为后续编译器资料的入口 |
| [data_and_eval](data_and_eval/) | 19 | 分词、语料与数据集、Scaling Laws、模型评测及安全 |
| [books_and_guides](books_and_guides/) | 9 | 综合教材、学习路线、开发环境及工具指南 |

## 归类约定

- 按内容归类，不按课程、下载批次或资料来源归类。
- 跨领域资料按主要用途归类：PPO、DPO 等算法放 `algo`，verl、Slime、OpenRLHF 的工程实现放 `mlsys`。
- 专题教材跟随主题：GPU 编程教材放 `gpu_and_compiler`，分布式训练与系统扩展指南放 `mlsys`；Tiny-LLM、Spinning Up 等综合教材放 `books_and_guides`。
- `gpu_and_compiler` 当前以 GPU 编程和算子优化为主，未来编译器资料也放在这里。

## 常用入口

- [Transformer 原始论文](algo/Attention_Is_All_You_Need.pdf)
- [Scaling Laws](data_and_eval/Scaling_Laws_for_Neural_Language_Models.pdf)
- [Chinchilla](data_and_eval/Training_Compute_Optimal_Large_Language_Models.pdf)
- [Awesome ML SYS Tutorial](books_and_guides/Awesome_ML_SYS_Tutorial.pdf)
- [Modern GPU Programming for MLsys](gpu_and_compiler/Modern_GPU_Programming_for_MLsys.pdf)
- [Tiny-LLM](books_and_guides/Tiny_LLM.pdf)
