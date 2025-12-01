# 越狱论文复现

## 越狱性能测试
本项目将对五种论文里的越狱性能进行测试，使用的数据集与测试的指标可能与原文不同。具体将测试以下五种越狱方法（语言大模型越狱方法，均为对应论文里的主要攻击方法）：
1.PsyJailbreak
2.DeepInception
3.FFA
4.HEA
5.Cipher

## 文件结构
- `PsyJailbreak/`: PsyJailbreak的源代码文件夹
- `DeepInception/`: DeepInception的源代码文件夹
- `FFA/`: FFA的源代码文件夹
- `HEA/`: HEA的源代码文件夹
- `Cipher/`: Cipher的源代码文件夹
- `data_set/`: 测试数据集文件夹，包含测试数据集 
- `results/`: 结果文件夹，包含各种越狱方法的测试结果  

## 使用的恶意数据集
1. HarmEval https://huggingface.co/datasets/SoftMINER-Group/HarmEval
2. Advbech https://huggingface.co/datasets/walledai/AdvBench