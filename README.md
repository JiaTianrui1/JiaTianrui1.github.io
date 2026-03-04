# 贾天瑞 · Tianrui Jia

大模型 / NLP / 推荐检索方向应届算法求职者（北京理工大学 数学与应用数学 硕士在读）。  
研究与工程兴趣：**LLM 微调（SFT/LoRA）、RAG 检索增强、Agent 工具调用、双塔召回与 Rerank 排序、向量检索与评估体系**。

🌐 个人主页（本仓库 GitHub Pages）：https://jiatianrui1.github.io/

---

## 亮点概览

- **LLM & 微调**：熟悉 Transformer，掌握 **SFT / LoRA / P-Tuning v2 / Adapter**，了解推理优化与压缩（量化/剪枝/蒸馏）。
- **RAG & Agent**：具备从文档解析、Chunk 策略、混合检索、Rerank 到评估闭环的全链路经验；熟悉 **LangChain / LlamaIndex / Function Call / ReAct / CoT**。
- **推荐与检索排序**：两阶段架构经验（**Embedding 双塔召回 + ANN + Reranker 精排**），关注线上延迟与离线指标一致性。
- **工程化与落地**：熟悉 **PyTorch / Milvus / Faiss / FastAPI / Docker / Linux**，能够完成从数据→训练→评估→服务化部署。

---

## 代表项目

### 车载音乐个性化推荐检索排序系统（理想汽车 · 大模型实习）
- 两阶段链路：**双塔召回（ANN TopK） → 策略过滤 → Reranker 精排 Top10**
- 数据闭环：画像/行为/曲库多源整合，构建训练对与负采样策略（in-batch / hard negative）
- 文本标准化：Query/Item schema 固化与模板化，提升训练/检索一致性与鲁棒性
- 评估体系：Recall@K / MRR / NDCG 分桶评估 & badcase 分析闭环

### EduRAG：教育场景智能问答系统（独立负责人）
- 多格式文档解析、OCR、分块与索引，向量检索 + Rerank
- 意图识别（Sentence-BERT）与 Query 重写（历史融合 / HyDE），生成端格式控制
- RagAS 自动评估与 FastAPI 服务化上线

### NeurIPS 2025 Google Code Golf（全球第 13，银牌区第 1）
- 构建自动化压缩与验证流水线，Agent 闭环迭代（生成→校验→筛选）
- GitHub Actions 自动化 CI/CD，PR 自动合并与提交

> 更详细经历见主页简历 PDF：`assets/resume.pdf`

---

## 科研与论文（节选）

- BSPC（Q2）已录用，第一作者：扩散模型/Rectified Flow 音频增强与分类
- INTERSPEECH 2025（CCF-C）：EMD + 频谱多分支网络（ASD 小鼠超声叫声）
- IEEE JBHI（Q1 TOP 在投，共同一作）：EMG 预测（无归一化 Transformer）
- Pattern Recognition（Q1 TOP 准备投稿，二作）：多模态抑郁检测（EEG+Audio）

---

## 技术栈

- **LLM/NLP**：Qwen / LLaMA / GLM，SFT / LoRA / P-Tuning v2 / Adapter  
- **RAG/检索**：Milvus / Faiss，混合检索，Rerank（bge-reranker），评估（RagAS）  
- **推荐系统**：双塔召回（InfoNCE / in-batch），ANN 索引，排序特征与离线评估  
- **工程**：PyTorch，FastAPI，Docker，Linux，GitHub Actions

---

## 联系方式

- Email：j18614269732@163.com  
- 主页： https://jiatianrui1.github.io/

---

## 本仓库说明（GitHub Pages）

这是我的个人主页仓库，包含：
- `index.html`：主页
- `assets/style.css`：样式
- `assets/resume.pdf`：简历 PDF（主页中可预览/下载）

### 部署
Settings → Pages  
- Source：Deploy from a branch  
- Branch：`main` / `(root)`

### 更新简历 PDF
替换 `assets/resume.pdf` 后提交：
```bash
git add assets/resume.pdf
git commit -m "Update resume"
git push
