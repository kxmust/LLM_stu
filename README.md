## 主要内容如下：
1. 大语言模型的本地部署：01 deepseek_deploy
2. 利用LoRA对本地大语言模型进行微调：02 lora_fine_tuning
3. 微调后的模型测试：03 fine_tuning_model_test
4. 数据工程，如何将自己的数据处理成大语言模型的训练数据：04 build_dataset
5. 利用GRPO 算法来训练 LLM 模型：05 RLHF

## 其他数据：
1. dataset.json 用来测试微调的数据
2. document.md 用来测试数据工程的本地文档
3. new_dataset.json 基于本地文档生成的新的训练数据
4. model 文件夹 用来保存下载的开源模型
5. lora_results 文件夹 用来保存微调生成的模型。

## 核心包：
1. trl==1.1.0
2. transformers==5.5.4
3. python==3.10
4. torch==2.10.0

## 设备：
Macbook Pro m4pro 24+512
