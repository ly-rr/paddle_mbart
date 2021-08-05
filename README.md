# paddle_mbart
论文复现-Multilingual Denoising Pre-training for Neural Machine Translation
Pretrained language  model
论文名称： Multilingual Denoising Pre-training for Neural Machine Translation 
数据集： 2010-2013 TED Zh-En测试集 WMT16 EN-RO WMT16 Ro-En 
验收标准： 1. 复现mbart模型（参考论文和实现链接） 
2. 完成模型权重从pytorch到paddle的转换代码，转换1个预训练权重（“facebook/mbart-large-cc25”） 
3. "facebook/mbart-large-cc25"模型指标： 在WMT16 EN-RO测试集上BLEU scores=37.7， 
在WMT16 Ro-En测试集上BLEU scores=37.8
