# Awesome datasets for LLMs

Awesome training/finetuning datasets for LLMs

## fine-tuning

* [`alpaca_data.json`](https://github.com/tatsu-lab/stanford_alpaca/blob/main/alpaca_data.json): 52K instruction data generated by `text-davinci-003` (from [tatsu-lab/stanford_alpaca](https://github.com/tatsu-lab/stanford_alpaca))

* BELLE/[1.0M](https://huggingface.co/datasets/BelleGroup/train_1M_CN), [0.5M](https://huggingface.co/datasets/BelleGroup/train_0.5M_CN): 由ChatGPT生成的1.5M中文数据集，包含数个不同指令类型、不同领域的子集 (from [LianjiaTech/BELLE](https://github.com/LianjiaTech/BELLE))

* BELLE/[`School Math`](https://huggingface.co/datasets/BelleGroup/school_math_0.25M), [`Multiturn Chat`](https://huggingface.co/datasets/BelleGroup/multiturn_chat_0.8M): 由BELLE项目开源的10M数据集，目前已开放数学习题和多轮对话 (from [LianjiaTech/BELLE](https://github.com/LianjiaTech/BELLE))

* [Anthropic HH RLHF](https://huggingface.co/datasets/Anthropic/hh-rlhf): Human preference data about helpfulness and harmlessness / Human-generated red teaming data

* [Stanford Human Preferences Dataset (SHP)](https://huggingface.co/datasets/stanfordnlp/SHP): 385K collective human preferences over responses to questions/instructions in 18 different subject areas, from cooking to legal advice

* [`instinwild_en.json`](https://drive.google.com/file/d/1qOfrl0RIWgH2_b1rYCEVxjHF3u3Dwqay/view?usp=sharing), [instinwild_ch.json](https://drive.google.com/file/d/1OqfOUWYfrK6riE9erOx-Izp3nItfqz_K/view?usp=sharing): A larger set of instructions generated by 479 seed instructions (from [XueFuzhao/InstructionWild](https://github.com/XueFuzhao/InstructionWild))

## spec

* [HealthCareMagic-200k](https://drive.google.com/file/d/1lyfqIwlLSClhgrCutWuEe_IACNq6XNUt/view?usp=sharing): 200k real conversations between patients and doctors from HealthCareMagic.com (from [Kent0n-Li/ChatDoctor](https://github.com/Kent0n-Li/ChatDoctor))

* [icliniq-15k](https://drive.google.com/file/d/1ZKbqgYqWc7DJHs3N9TQYQVPdDQmZaClA/view?usp=sharing): 15k real conversations between patients and doctors from icliniq.com (from [Kent0n-Li/ChatDoctor](https://github.com/Kent0n-Li/ChatDoctor))

* [`ADGEN dataset`](https://drive.google.com/file/d/13_vf0xRTQsyneRKdD1bZIr93vBGOczrk/view)/[`清华备份`](https://cloud.tsinghua.edu.cn/f/b3f119a008264b1cabd1/?dl=1): 根据输入（content）生成一段广告词（summary） (from [THUDM/ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B/tree/main/ptuning#%E4%B8%8B%E8%BD%BD%E6%95%B0%E6%8D%AE%E9%9B%86))


