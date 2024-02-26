# 立项背景
&emsp;如今，SFT微调llm遇到的最大的难点之一就是SFT数据处理。对于对话角色而言，可以通过人物名字的前后文关系来捕捉对话数据对，从而进行提取。
&emsp;但对于大量爬取或得到的纸质专业书籍，大多都是知识点或者章节逻辑性的罗列，很难获取较高的高质量SFT数据。这对垂域llm的训练提出了严峻的挑战！！ 
# 立项目标 
- 搭建一个对于书本、课本等结构化文本到高质量SFT数据创造的工具链，并进一步完善其内在的特征知识提取关系，从而进一步提升llm在垂域的能力。  
- 重点在sft数据制造，能够为各大项目起到促进作用！！ 
- 为各大sft项目生成效果提供可量化的评测metric。 
# 立项难点
- 从pdf等文件中提取文本关系的噪声清洗  
- 书本中大量的表格，图片，公式等非文本数据的处理
- 微调的prompt构造，以及上述数据清理的自动化处理规则
- 如何构造准确的metric进行定量的评测
# 项目亮点
1. 项目瞄准llm微调中的数据问题，能够对各个sft项目起到促进作用。
2. 项目后续会提供完善的评价metric流程，能够定量的评估垂域性能。
4. 项目后续会更近RAG与知识图谱，RLHF等功能对垂域性能做进一步的尝试。

# 项目规划
- [x] 获取垂域pdf资料
- [ ] 数据ocr提取与清洗
- [ ] 图像、表格公式等特殊数据处理
- [ ] 模型微调
- [ ] metric指标创建
- [ ] 模型评测
- [ ] 接入RAG
- [ ] 接入知识图谱
- [ ] 接入RLHF
