# 英文到中文的机器翻译
此模型整体结构和参数设置与我的另一个项目[中文聊天机器人](https://github.com/jiayiwang5/Chinese-ChatBot)完全一致<br>
此外，可以和我另一个基于Transformer的机器翻译项目[MachineTranslation-Transformer](https://github.com/jiayiwang5/MachineTranslation-Transformer)对比学习，二者原始数据一致
## 环境配置
| 程序         | 版本      |
| ---------- | ------- |
| python     | 3.68    |
| tensorflow | 1.13.1  |
| Keras      | 2.2.4   |
| windows10  |         |
| jupyter    |         |
## 实际效果
(注：英文输入单词和符号均需用空格分开)
| 输入英文 |输出中文  |
| :------------: |:---------------:|
| Where are you ?      | 你 在 哪儿 ? |
| I love you !      |  我 爱 你 。       |
| Do you love me ?  |  你 爱 我 吗 ？       |

## 运行
### 方式一：完整过程
- **数据预处理**<br>
  `get_data`<br>
- **模型训练**<br>
  `Translation_train`<br>
- **模型预测**<br>
  `Translation_inference`<br>
### 方式二：加载现有模型
- 运行`Translation_inference`<br>
- 加载`models/W--189-0.5900-.h5` 
