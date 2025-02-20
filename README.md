<!-- <div style="text-align: center;">

    <h1><img src="assets/logo.png" height="28px" /> Tool Learning Papers </h1>

</div> -->

# Awesome-Tool-Learning Papers

[![Awesome](https://camo.githubusercontent.com/64f8905651212a80869afbecbf0a9c52a5d1e70beab750dea40a994fa9a9f3c6/68747470733a2f2f617765736f6d652e72652f62616467652e737667)](xx) [![License: MIT](https://camo.githubusercontent.com/fd551ba4b042d89480347a0e74e31af63b356b2cac1116c7b80038f41b04a581/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d677265656e2e737667)](https://opensource.org/licenses/MIT) <img src="https://img.shields.io/github/last-commit/tensorflow/tensorflow.svg"/> [![img](https://camo.githubusercontent.com/eafac29b763e18c4d80c680d6a179f348cfa2afbc8d3a45642df19fd580d2404/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d57656c636f6d652d726564)](https://camo.githubusercontent.com/eafac29b763e18c4d80c680d6a179f348cfa2afbc8d3a45642df19fd580d2404/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d57656c636f6d652d726564)

Awesome papers and tools on tool learning.

## Table of Contents

- [Papers](#papers)

  - [Survey](#survey)

  - [Tool Use Via Fine-tuning](#Tool-Use-Via-Fine-Tuning)

  - [Tool Use Via In-Context Learning](#Tool-Use-Via-In-Context-Learning)

  - [Evalution](#Evalution)

- [Contribution](#contribution)

## Papers

### Survey

- **Augmented Language Models: a Survey**, Preprint 2023.02 

  *Grégoire Mialon, Roberto Dessì, Maria Lomeli, Christoforos Nalmpantis, Ram Pasunuru, Roberta Raileanu, Baptiste Rozière, Timo Schick, Jane Dwivedi-Yu, Asli Celikyilmaz, Edouard Grave, Yann LeCun, Thomas Scialom*. [[pdf](https://arxiv.org/abs/2302.07842)]

- **Tool Learning with Foundation Models**, Preprint 2023.04 

  *Yujia Qin, Shengding Hu, Yankai Lin, Weize Chen, Ning Ding, Ganqu Cui, Zheni Zeng, Yufei Huang, Chaojun Xiao, Chi Han, Yi Ren Fung, Yusheng Su, Huadong Wang, Cheng Qian, Runchu Tian, Kunlun Zhu, Shihao Liang, Xingyu Shen, Bokai Xu, Zhen Zhang, Yining Ye, Bowen Li, Ziwei Tang, Jing Yi, Yuzhang Zhu, Zhenning Dai, Lan Yan, Xin Cong, Yaxi Lu, Weilin Zhao, Yuxiang Huang, Junxi Yan, Xu Han, Xian Sun, Dahai Li, Jason Phang, Cheng Yang, Tongshuang Wu, Heng Ji, Zhiyuan Liu, Maosong Sun*. [[pdf](https://arxiv.org/abs/2304.08354)],[[github](https://github.com/thunlp/ToolLearningPapers/tree/master)]

### Tool Use Via Fine-tuning

- **TALM: Tool Augmented Language Models** Preprint 2022.05 

  *Aaron Parisi, Yao Zhao, Noah Fiedel* [[pdf](https://arxiv.org/abs/2205.12255)]

- **Toolformer: Language Models Can Teach Themselves to Use Tools** Preprint 2023.02

  *Timo Schick, Jane Dwivedi-Yu, Roberto Dessì, Roberta Raileanu, Maria Lomeli, Luke Zettlemoyer, Nicola Cancedda, Thomas Scialom* [[pdf](https://arxiv.org/abs/2302.04761)]

- **ToolCoder: Teach Code Generation Models to use API search tools** Preprint 2023.05

    *Kechi Zhang, Huangzhao Zhang, Ge Li, Jia Li, Zhuo Li, Zhi Jin* [[pdf](https://arxiv.org/abs/2305.04032)]

- **ToolAlpaca: Generalized Tool Learning for Language Models with 3000 Simulated Cases** Preprint 2023.06 

  *Qiaoyu Tang, Ziliang Deng, Hongyu Lin, Xianpei Han, Qiao Liang, Le Sun* [[pdf](https://arxiv.org/abs/2306.05301)]

- **Gorilla: Large Language Model Connected with Massive APIs** Preprint 2023.05

  *Shishir G. Patil, Tianjun Zhang, Xin Wang, Joseph E. Gonzalez* [[pdf](https://arxiv.org/abs/2305.15334)]

- **GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction** Preprint 2023.05

    *Rui Yang, Lin Song, Yanwei Li, Sijie Zhao, Yixiao Ge, Xiu Li, Ying Shan* [[pdf](https://arxiv.org/abs/2305.18752)],[[github](https://github.com/StevenGrove/GPT4Tools)]

- **ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings** Preprint 2023.05 

  *Shibo Hao, Tianyang Liu, Zhen Wang, Zhiting Hu* [[pdf](https://arxiv.org/abs/2305.11554)][[github](https://github.com/Ber666/ToolkenGPT)]

- **Making Language Models Better Tool Learners with Execution Feedback** Preprint 2023.05

  *Shuofei Qiao, Honghao Gui, Huajun Chen, Ningyu Zhang* [[pdf](https://arxiv.org/abs/2305.13068)]

- **WebGPT: Browser-assisted question-answering with human feedback** Preprint 2022.06

    *Reiichiro Nakano, Jacob Hilton, Suchir Balaji, Jeff Wu, Long Ouyang, Christina Kim, Christopher Hesse, Shantanu Jain, Vineet Kosaraju, William Saunders, Xu Jiang, Karl Cobbe, Tyna Eloundou, Gretchen Krueger, Kevin Button, Matthew Knight, Benjamin Chess, John Schulman* [[pdf](https://arxiv.org/abs/2112.09332)]

- **WebCPM: Interactive Web Search for Chinese Long-form Question Answering** Preprint 2023.06 

  *Yujia Qin, Zihan Cai, Dian Jin, Lan Yan, Shihao Liang, Kunlun Zhu, Yankai Lin, Xu Han, Ning Ding, Huadong Wang, Ruobing Xie, Fanchao Qi, Zhiyuan Liu, Maosong Sun, Jie Zhou* [[pdf](https://arxiv.org/abs/2305.06849)]

- **WebGLM: Towards An Efficient Web-Enhanced Question Answering System with Human Preferences** KDD 2023.06

  *Xiao Liu, Hanyu Lai, Hao Yu, Yifan Xu, Aohan Zeng, Zhengxiao Du, Peng Zhang, Yuxiao Dong, Jie Tang* [[pdf](https://arxiv.org/abs/2306.07906)]

- **WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents** ACL 2023.02

    *Yujia Qin, Zihan Cai, Dian Jin, Lan Yan, Shihao Liang, Kunlun Zhu, Yankai Lin, Xu Han, Ning Ding, Huadong Wang, Ruobing Xie, Fanchao Qi, Zhiyuan Liu, Maosong Sun, Jie Zhou* [[pdf](https://arxiv.org/abs/2207.01206)],[[github](https://webshop-pnlp.github.io/)]

### Tool Use via In-Context Learning

- **TaskMatrix.AI: Completing Tasks by Connecting Foundation Models with Millions of APIs** Preprint 2023.05

  *Yaobo Liang, Chenfei Wu, Ting Song, Wenshan Wu, Yan Xia, Yu Liu, Yang Ou, Shuai Lu, Lei Ji, Shaoguang Mao, Yun Wang, Linjun Shou, Ming Gong, Nan Duan* [[pdf](https://arxiv.org/abs/2303.16434)]

- **RestGPT: Connecting Large Language Models with Real-World Applications via RESTful APIs** Preprint 2023.06

    *Yifan Song, Weimin Xiong, Dawei Zhu, Cheng Li, Ke Wang, Ye Tian, Sujian Li* [[pdf](https://arxiv.org/abs/2306.06624)]

- **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face** Preprint 2023.05

  *Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang* [[pdf](https://arxiv.org/abs/2303.17580)]

- **PAL: Program-aided Language Models** Preprint 2023.01

    *Luyu Gao, Aman Madaan, Shuyan Zhou, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan, Graham Neubig* [[pdf](https://arxiv.org/abs/2211.10435)],[[github](https://reasonwithpal.com/)]

- **Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models** Preprint 2023.04

  *Pan Lu, Baolin Peng, Hao Cheng, Michel Galley, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Jianfeng Gao* [[pdf](https://arxiv.org/abs/2304.09842)],[[github](https://chameleon-llm.github.io/)]

- **ChemCrow: Augmenting large-language models with chemistry tools** Preprint 2023.04

    *Andres M Bran, Sam Cox, Andrew D White, Philippe Schwaller* [[pdf](https://arxiv.org/abs/2304.05376)]

- **OpenAGI: When LLM Meets Domain Experts** Preprint 2023.04

  *Yingqiang Ge, Wenyue Hua, Kai Mei, Jianchao Ji, Juntao Tan, Shuyuan Xu, Zelong Li, Yongfeng Zhang* [[pdf](https://arxiv.org/abs/2304.04370)]

- **ART: Automatic multi-step reasoning and tool-use for large language models** Preprint 2023.05

    *Bhargavi Paranjape, Scott Lundberg, Sameer Singh, Hannaneh Hajishirzi, Luke Zettlemoyer, Marco Tulio Ribeiro* [[pdf](https://arxiv.org/abs/2303.09014)],[[github](https://reasonwithpal.com/)]

- **ChatCoT: Tool-Augmented Chain-of-Thought Reasoning on Chat-based Large Language Models** Preprint 2023.05

  *Zhipeng Chen, Kun Zhou, Beichen Zhang, Zheng Gong, Wayne Xin Zhao, Ji-Rong Wen* [[pdf](https://arxiv.org/abs/2305.14323)]

- **MultiTool-CoT: GPT-3 Can Use Multiple External Tools with Chain of Thought Prompting** ACL 2023.06

    *Tatsuro Inaba, Hirokazu Kiyomaru, Fei Cheng, Sadao Kurohashi* [[pdf](https://arxiv.org/abs/2305.16896)],[[project](https://github.com/InabaTatsuro/MultiTool-CoT)]

- **Skills-in-Context Prompting: Unlocking Compositionality in Large Language Models** Preprint 2023.08

  *Jiaao Chen, Xiaoman Pan, Dian Yu, Kaiqiang Song, Xiaoyang Wang, Dong Yu, Jianshu Chen* [[pdf](https://arxiv.org/abs/2308.00304)]

- **Tool Documentation Enables Zero-Shot Tool-Usage with Large Language Models** Preprint 2023.08

    *Cheng-Yu Hsieh, Si-An Chen, Chun-Liang Li, Yasuhisa Fujii, Alexander Ratner, Chen-Yu Lee, Ranjay Krishna, Tomas Pfister* [[pdf](https://arxiv.org/abs/2308.00675)]

- **GeneGPT: Augmenting Large Language Models with Domain Tools for Improved Access to Biomedical Information** Preprint 2023.04

  *Qiao Jin, Yifan Yang, Qingyu Chen, Zhiyong Lu* [[pdf](https://arxiv.org/abs/2304.09667)],[[github](https://chameleon-llm.github.io/)]

- **AssistGPT: A General Multi-modal Assistant that can Plan, Execute, Inspect, and Learn** Preprint 2023.06

    *Difei Gao, Lei Ji, Luowei Zhou, Kevin Qinghong Lin, Joya Chen, Zihan Fan, Mike Zheng Shou* [[pdf](https://arxiv.org/abs/2306.08640)],[[project](https://showlab.github.io/assistgpt/)]

- **TPTU: Task Planning and Tool Usage of Large Language Model-based AI Agents** Preprint 2023.08

  *Jingqing Ruan, Yihong Chen, Bin Zhang, Zhiwei Xu, Tianpeng Bao, Guoqing Du, Shiwei Shi, Hangyu Mao, Xingyu Zeng, Rui Zhao* [[pdf](https://arxiv.org/abs/2308.03427)]

- **Large Language Models as Tool Makers** Preprint 2023.05

    *Tianle Cai, Xuezhi Wang, Tengyu Ma, Xinyun Chen, Denny Zhou* [[pdf](https://arxiv.org/abs/2305.17126)],[[github](https://github.com/ctlllll/LLM-ToolMaker)]

- **CREATOR: Disentangling Abstract and Concrete Reasonings of Large Language Models through Tool Creation** Preprint 2023.05

    *Cheng Qian, Chi Han, Yi R. Fung, Yujia Qin, Zhiyuan Liu, Heng Ji* [[pdf](https://arxiv.org/abs/2305.14318)]

- **TPTU: Task Planning and Tool Usage of Large Language Model-based AI Agents** Preprint 2022.11

  *Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks* [[pdf](https://arxiv.org/abs/2211.12588)]

- **GEAR: Augmenting Language Models with Generalizable and Efficient Tool Resolution** Preprint 2023.07

    *Yining Lu, Haoping Yu, Daniel Khashabi* [[pdf](https://arxiv.org/abs/2307.08775)]

### Evalution

- **API-Bank: A Benchmark for Tool-Augmented LLMs** Preprint 2023.06

    *Difei Gao, Lei Ji, Luowei Zhou, Kevin Qinghong Lin, Joya Chen, Zihan Fan, Mike Zheng Shou* [[pdf](https://arxiv.org/abs/2306.08640)],[[project](https://showlab.github.io/assistgpt/)]

- **On the Tool Manipulation Capability of Open-source Large Language Models** Preprint 2023.06

  *Qiantong Xu, Fenglu Hong, Bo Li, Changran Hu, Zhengyu Chen, Jian Zhang* [[pdf](https://arxiv.org/abs/2305.16504)]

- **ToolQA: A Dataset for LLM Question Answering with External Tools** Preprint 2023.05

    *Yuchen Zhuang, Yue Yu, Kuan Wang, Haotian Sun, Chao Zhangu* [[pdf](https://arxiv.org/abs/2306.13304)]

- **Evaluating and Improving Tool-Augmented Computation-Intensive Math Reasoning** Preprint 2023.06

    *Beichen Zhang, Kun Zhou, Xilin Wei, Wayne Xin Zhao, Jing Sha, Shijin Wang, Ji-Rong Wen* [[pdf](https://arxiv.org/abs/2306.02408)]

- **TOOLLLM: FACILITATING LARGE LANGUAGE MODELS TO MASTER 16000+ REAL-WORLD APIS** Preprint 2023.07

  *Yujia Qin, Shihao Liang, Yining Ye, Kunlun Zhu, Lan Yan, Yaxi Lu, Yankai Lin, Xin Cong, Xiangru Tang, Bill Qian, Sihan Zhao, Runchu Tian, Ruobing Xie, Jie Zhou, Mark Gerstein, Dahai Li, Zhiyuan Liu, Maosong Sun* [[pdf](https://arxiv.org/abs/2307.16789?utm_source=tldrai)]

- **AgentBench: Evaluating LLMs as Agents** Preprint 2023.08

    *Xiao Liu, Hao Yu, Hanchen Zhang, Yifan Xu, Xuanyu Lei, Hanyu Lai, Yu Gu, Hangliang Ding, Kaiwen Men, Kejuan Yang, Shudan Zhang, Xiang Deng, Aohan Zeng, Zhengxiao Du, Chenhui Zhang, Sheng Shen, Tianjun Zhang, Yu Su, Huan Sun, Minlie Huang, Yuxiao Dong, Jie Tang* [[pdf](https://arxiv.org/abs/2308.03688)]
