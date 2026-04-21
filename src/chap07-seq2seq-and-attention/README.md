# seq2seq and attention

## 模块简介

本章包含 seq2seq 与 attention 的练习脚本，主要任务是“序列逆置”（sequence reversal）：输入一个由 A-Z 组成的字符串序列，输出其逆序序列，并通过示意图辅助理解编码器-解码器结构。

## 主要文件

* sequence_reversal-exercise.py：seq2seq 逆置任务练习
* sequence_reversal_with_attention-exercise.py：带 attention 的逆置任务练习
* seq2seq.png / seq2seq-attn.jpg：结构示意图

## 依赖说明

脚本中使用 TensorFlow / Keras（同时还会用到 numpy、tqdm 等），运行前需准备对应依赖与环境。

## 运行方式

```bash
python sequence_reversal-exercise.py
python sequence_reversal_with_attention-exercise.py
```
