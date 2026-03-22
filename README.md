# 贾天瑞 · Tianrui Jia

大模型算法 / 推荐检索 / Agent 方向求职者  
北京理工大学数学硕士在读（2024.09—2027.06）

当前关注：
- LLM 微调与推理优化
- RAG 与 Agent
- 推荐检索排序
- Diffusion 与多模态建模

🌐 个人主页：https://jiatianrui1.github.io/

---

## 亮点概览
- **大模型算法与微调**：熟悉 Transformer / Attention，具备 SFT、LoRA、P-Tuning v2、Adapter 等微调经验，覆盖 Qwen、LLaMA、GLM 等主流模型
- **RAG 与 Agent**：熟悉文档解析、分块、混合检索、Rerank、RagAS 评估；掌握 LangChain、LlamaIndex、Function Call、ReAct、CoT
- **推荐检索与排序**：具备双塔召回、ANN 向量检索、DIN 精排、离线评估体系设计经验
- **多模态与工程化**：熟悉 Diffusion / Rectified Flow、音频信号处理、多模态融合；具备 PyTorch、Faiss、Milvus、FastAPI、Docker、Linux 工程经验

---

## 实习经历

### 理想汽车｜大模型实习生（2026.02—2026.04）
**智能汽车群组-软件本体-理想同学-理想同学智能体部**

**车载音乐个性化推荐检索排序系统**
- 面向车机端音乐个性化推荐场景，构建双塔召回 → ANN 粗排 → Diffusion + DIN 精排的多阶段推荐链路
- 基于 Qwen3-Embedding 进行双塔监督微调，构建 Faiss IVF-PQ 索引缓存，支撑千万级向量检索
- 基于全参数微调 Qwen2.5-1.5B 做 Query/Item 文本改写增强
- 阶段性效果：**NDCG@10 +6.8%**、**MRR@10 +9.3%**、**Recall@200 提升至 87.4%**

**理想同学音乐 Agent 深度规划**
- 围绕搜歌、点播、推荐、切换播放模式、上下文续播等业务场景，累计构造高质量训练数据 **1W+**
- 协助完成基于 MCP Server 的 Plan-Execute 规划算法设计，开展 SFT、GRPO、GSPO、DAPO 等训练实验
- 基于 eagle-3 完成适配音乐 Agent 的投机解码头训练，优化端侧推理吞吐与响应速度

> 注：以上为企业内部项目，代码未开源。

---

## 代表项目（公开仓库）

### NeurIPS 2025 Google Code Golf 锦标赛｜自动化代码压缩 Agent
Repo: https://github.com/JiaTianrui1/codegolf
- 面向 ARC-GEN 任务构建自动化代码压缩与验证框架，最终获得全球第 13 名（银牌区第 1 名）
- 设计多智能体闭环流程，实现“候选解生成 → 正确性校验 → 最优解筛选”的自动化迭代
- 搭建基于 GitHub Actions 的 CI/CD 流水线，实现 PR 自动合并、版本管理及 Kaggle API 自动提交

### EduRAG｜基于 RAG 的教育场景智能问答系统
Repo: https://github.com/JiaTianrui1/integrated-qa-system
- 从 0 到 1 构建教育场景智能问答系统，整合课程、政策等多源异构知识
- 基于 Milvus 构建向量索引，实施稀疏 + 稠密混合检索与 BGE-Reranker 重排序
- 基于 Qwen2.5-7B 进行指令微调，构建 RagAS 自动评估与 FastAPI 服务化部署

---

## 科研成果
- **[BSPC, Q2｜已录用｜第一作者]** Breaking Through Data Scarcity: A Novel Diffusion Model Approach for Snoring Sound Augmentation
- **[INTERSPEECH 2025, CCF-B｜主要贡献者]** Exploring EMD for Sensing the Sound of Silence: Mice Autism Detection via Ultrasonic Vocalization
- **[ESWA, Q1 TOP｜共同一作｜在投]** Robust EMG Forecasting for IoT Healthcare via Adaptive Mapping & Normalization-Free Transformer
- **[Pattern Recognition, Q1 TOP｜学生二作｜大修]** Bayesian Knowledge-Guided Confidence-Aware Method for Depression Detection

---

## 联系方式
- Email：j18614269732@163.com
- Homepage：https://jiatianrui1.github.io/
- GitHub：https://github.com/JiaTianrui1

---

## 本仓库说明
- `index.html`：个人主页
- `assets/style.css`：样式文件
- `assets/resume.pdf`：简历 PDF（主页可在线预览）

### 更新方法
替换 `assets/resume.pdf` 后，提交变更即可同步主页简历。
