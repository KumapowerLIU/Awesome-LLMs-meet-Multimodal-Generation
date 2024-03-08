
# Contents
- [Contents](#contents)
- [🤗 Introduction](#-introduction)
- [💘 Tips](#-tips)
- [📍 LLMs for Visual-audio Generation](#-llms-for-visual-audio-generation)
  - [Image Generation](#image-generation)
    - [🔅 LLM-based](#-llm-based)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5)
    - [Datasets](#datasets)
  - [Video Generation](#video-generation)
    - [🔅 LLM-based](#-llm-based-1)
    - [Non-LLM-based](#non-llm-based)
    - [Datasets](#datasets-1)
  - [3D Generation](#3d-generation)
    - [🔅 LLM-based](#-llm-based-2)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5-1)
    - [Datasets](#datasets-2)
  - [Audio Generation](#audio-generation)
    - [🔅 LLM-based](#-llm-based-3)
    - [Non-LLM-based](#non-llm-based-1)
    - [Datasets](#datasets-3)
- [📍 LLMs for Visual-audio Editing](#-llms-for-visual-audio-editing)
  - [Image Editing](#image-editing)
    - [🔅 LLM-based](#-llm-based-4)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5-2)
  - [Video Editing](#video-editing)
    - [🔅 LLM-based](#-llm-based-5)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5-3)
  - [3D Editing](#3d-editing)
    - [🔅 LLM-based](#-llm-based-6)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5-4)
  - [Audio Editing](#audio-editing)
    - [🔅 LLM-based](#-llm-based-7)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5-5)
- [📍 Multi-Modal Agents](#-multi-modal-agents)
- [📍 LLMs for Visual-audio Understanding](#-llms-for-visual-audio-understanding)
  - [Image Understanding](#image-understanding)
  - [Video Understanding](#video-understanding)
  - [3D](#3d)
  - [3D Understanding](#3d-understanding)
  - [Audio Understanding](#audio-understanding)
- [📍 Multimodal LLM Safety](#-multimodal-llm-safety)
  - [Attack](#attack)
  - [Defense and Detect](#defense-and-detect)
  - [Alignment](#alignment)
  - [Datasets](#datasets-4)
- [📍 Related Surveys](#-related-surveys)
  - [LLM](#llm)
  - [Vision](#vision)

# 🤗 Introduction
- This repository contains a curated list of LLM-based methods for visual and audio generation.
- The visual generation includes image, video, and 3D modalities based on the text prompts. 
- We welcome contributions to our repository or the addition of your own work. 



# 💘 Tips
- **✅ Paper searching via catatogue**: directly clicking the content of the catatogue to select the area of your research and browse related papers.
- **✅ Paper searching via author name**: Free feel to search papers of a specific author via `ctrl + F` and then type the author name. The dropdown list of authors will automatically expand when searching.
- **✅ Paper searching via tag**: You can also search the related papers via the following tags: `customization`, `iteractive`, `human motion generation`. (More tags are ongoing)


# 📍 LLMs for Visual-audio Generation

## Image Generation

### 🔅 LLM-based

<!-- + **Genie: Generative Interactive Environments** (26 Feb 2024)<details><summary>Jake Bruce, Michael Dennis, Ashley Edwards, et al.</summary> Jake Bruce, Michael Dennis, Ashley Edwards, Jack Parker-Holder, Yuge Shi, Edward Hughes, Matthew Lai, Aditi Mavalankar, Richie Steigerwald, Chris Apps, Yusuf Aytar, Sarah Bechtle, Feryal Behbahani, Stephanie Chan, Nicolas Heess, Lucy Gonzalez, Simon Osindero, Sherjil Ozair, Scott Reed, Jingwei Zhang, Konrad Zolna, Jeff Clune, Nando de Freitas, Satinder Singh, Tim Rocktäschel</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.15391v1) -->





+ **DiffusionGPT: LLM-Driven Text-to-Image Generation System** (18 Jan 2024)<details><summary>Jie Qin, Jie Wu, Weifeng Chen, et al.</summary> Jie Qin, Jie Wu, Weifeng Chen, Yuxi Ren, Huixia Li, Hefeng Wu, Xuefeng Xiao, Rui Wang, Shilei Wen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.10061)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd4b1a1c62a03ccffcf24983eb4fe22335cbb89b6%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/StarVector%3A-Generating-Scalable-Vector-Graphics-Rodriguez-Agarwal/d4b1a1c62a03ccffcf24983eb4fe22335cbb89b6)
[![Code](https://img.shields.io/github/stars/DiffusionGPT/DiffusionGPT.svg?style=social&label=Star)](https://github.com/DiffusionGPT/DiffusionGPT)


+ **StarVector: Generating Scalable Vector Graphics Code from Images** (17 Dec 2023)<details><summary>Juan A. Rodriguez, Shubham Agarwal, Issam H. Laradji, et al.</summary> Juan A. Rodriguez, Shubham Agarwal, Issam H. Laradji, Pau Rodriguez, David Vazquez, Christopher Pal, Marco Pedersoli</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.11556)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F60d3ade5c0085f5de1f5ab944cc058c78706ac66%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/StarVector%3A-Generating-Scalable-Vector-Graphics-Rodriguez-Agarwal/60d3ade5c0085f5de1f5ab944cc058c78706ac66)
[![Code](https://img.shields.io/github/stars/joanrod/star-vector.svg?style=social&label=Star)](https://github.com/joanrod/star-vector)


+ **VL-GPT: A Generative Pre-trained Transformer for Vision and Language Understanding and Generation** (14 Dec 2023)<details><summary>Jinguo Zhu, Xiaohan Ding, Yixiao Ge, et al.</summary> Jinguo Zhu, Xiaohan Ding, Yixiao Ge, Yuying Ge, Sijie Zhao, Hengshuang Zhao, Xiaohua Wang, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09251)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fea6982a936a2b263bbf46ff6eb27fc0b63fddaf7%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VL-GPT%3A-A-Generative-Pre-trained-Transformer-for-Zhu-Ding/ea6982a936a2b263bbf46ff6eb27fc0b63fddaf7)
[![Code](https://img.shields.io/github/stars/AILab-CVC/VL-GPT.svg?style=social&label=Star)](https://github.com/AILab-CVC/VL-GPT)


+ **StoryGPT-V: Large Language Models as Consistent Story Visualizers** (13 Dec 2023)<details><summary>Xiaoqian Shen, Mohamed Elhoseiny</summary> Xiaoqian Shen, Mohamed Elhoseiny</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02252)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe49cb2ab3a7990e3d05042197ae8b3fd934453de%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VL-GPT%3A-A-Generative-Pre-trained-Transformer-for-Zhu-Ding/e49cb2ab3a7990e3d05042197ae8b3fd934453de)



+ **GENIXER: Empowering Multimodal Large Language Models as a Powerful
Data Generator** (11 Dec 2023)<details><summary>Henry Hengyuan Zhao, Pan Zhou, Mike Zheng Shou</summary> Henry Hengyuan Zhao, Pan Zhou, Mike Zheng Shou</details> 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06731)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fcb2295766b2f8f35524f6a9f93ae39d948d50bd4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Genixer%3A-Empowering-Multimodal-Large-Language-as-a-Zhao-Zhou/cb2295766b2f8f35524f6a9f93ae39d948d50bd4)


+ **Customization Assistant for Text-to-image Generation** (5 Dec 2023)<details><summary>Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, et al.</summary> Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, Tong Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03045)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff30bb09dbd95845d792bdac217a9a652635ee8a5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Customization-Assistant-for-Text-to-image-Zhou-Zhang/f30bb09dbd95845d792bdac217a9a652635ee8a5)
Tags: `customization`



+ **CoDi-2: In-Context, Interleaved, and Interactive Any-to-Any Generation** (30 Nov 2023) <details><summary>Zineng Tang, Ziyi Yang, Mahmoud Khademi, et al.</summary>Zineng Tang, Ziyi Yang, Mahmoud Khademi, Yang Liu, Chenguang Zhu, Mohit Bansal</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18775)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F78582ad19779a69d97b797a3c6eb2397f99398b6%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/CoDi-2%3A-In-Context%2C-Interleaved%2C-and-Interactive-Tang-Yang/78582ad19779a69d97b797a3c6eb2397f99398b6)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://codi-2.github.io/)
[![Code](https://img.shields.io/github/stars/microsoft/i-Code.svg?style=social&label=Star)](https://github.com/microsoft/i-Code/tree/main/CoDi-2)


+ **ChatIllusion: Efficient-Aligning Interleaved Generation ability with Visual Instruction Model** (29 Nov 2023) <details><summary>Xiaowei Chi, Yijiang Liu, Zhengkai Jiang, et al.</summary> Xiaowei Chi, Yijiang Liu, Zhengkai Jiang, Rongyu Zhang, Ziyi Lin, Renrui Zhang, Peng Gao, Chaoyou Fu, Shanghang Zhang, Qifeng Liu, Yike Guo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17963)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F22d55c52f43f59634586ab95fefbb7dba8c8b190%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ChatIllusion%3A-Efficient-Aligning-Interleaved-with-Chi-Liu/22d55c52f43f59634586ab95fefbb7dba8c8b190)
[![Code](https://img.shields.io/github/stars/litwellchi/ChatIllusion.svg?style=social&label=Star)](https://github.com/litwellchi/ChatIllusion)


+ **DreamSync: Aligning Text-to-Image Generation with Image Understanding Feedback** (29 Nov 2023) <details><summary>Jiao Sun, Deqing Fu, Yushi Hu, et al.</summary>Jiao Sun, Deqing Fu, Yushi Hu, Su Wang, Royi Rassin, Da-Cheng Juan, Dana Alon, Charles Herrmann, Sjoerd van Steenkiste, Ranjay Krishna, Cyrus Rashtchian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17946)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd16f72b7be526dee5eb49e5afffeea2bddba5e66%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DreamSync%3A-Aligning-Text-to-Image-Generation-with-Sun-Fu/d16f72b7be526dee5eb49e5afffeea2bddba5e66)




+ **COLE: A Hierarchical Generation Framework for Graphic Design** (28 Nov 2023) <details><summary>Peidong Jia, Chenxuan Li, Zeyu Liu, et al.</summary>Peidong Jia, Chenxuan Li, Zeyu Liu, Yichao Shen, Xingru Chen, Yuhui Yuan, Yinglin Zheng, Dong Chen, Ji Li, Xiaodong Xie, Shanghang Zhang, Baining Guo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16974)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8441c30ad4abdca9ee380aa6f22ffd731b10231b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/COLE%3A-A-Hierarchical-Generation-Framework-for-Jia-Li/8441c30ad4abdca9ee380aa6f22ffd731b10231b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://graphic-design-generation.github.io/)



+ **TextDiffuser-2: Unleashing the Power of Language Models for Text Rendering** (28 Nov 2023) <details><summary>Jingye Chen, Yupan Huang, Tengchao Lv, et al.</summary>Jingye Chen, Yupan Huang, Tengchao Lv, Lei Cui, Qifeng Chen, Furu Wei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16465)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1c6e2a4da1ead685a95c079751bf4d7a727d8180%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/TextDiffuser-2%3A-Unleashing-the-Power-of-Language-Chen-Huang/1c6e2a4da1ead685a95c079751bf4d7a727d8180)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jingyechen.github.io/textdiffuser2/)
[![Code](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star)](https://github.com/microsoft/unilm/tree/master/textdiffuser-2)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/JingyeChen22/TextDiffuser-2)




+ **Self-correcting LLM-controlled Diffusion Models** (27 Nov 2023)<details><summary>Tsung-Han Wu, Long Lian, Joseph E. Gonzalez, et al.</summary> Tsung-Han Wu, Long Lian, Joseph E. Gonzalez, Boyi Li, Trevor Darrell</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16090)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F42c4315b5d2e33d7d9a0afdf84e6a47ccd7a700e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Self-correcting-LLM-controlled-Diffusion-Models-Wu-Lian/42c4315b5d2e33d7d9a0afdf84e6a47ccd7a700e)
[![Code](https://img.shields.io/github/stars/tsunghan-wu/SLD.svg?style=social&label=Star)](https://github.com/tsunghan-wu/SLD)


+ **Tokenize and Embed ALL for Multi-modal Large Language Models** (8 Nov 2023)<details><summary>Zhen Yang, Yingxue Zhang, Fandong Meng, et al.</summary> Zhen Yang, Yingxue Zhang, Fandong Meng, Jie Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.04589)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F59d716b442ab760a78f58de6748c0fa1d507bfc1%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/TEAL%3A-Tokenize-and-Embed-ALL-for-Multi-modal-Large-Yang-Zhang/59d716b442ab760a78f58de6748c0fa1d507bfc1)



+ **WordArt Designer: User-Driven Artistic Typography Synthesis using Large Language Models** (20 Oct 2023)<details><summary>Jun-Yan He, Zhi-Qi Cheng, Chenyang Li, et al.</summary> Jun-Yan He, Zhi-Qi Cheng, Chenyang Li, Jingdong Sun, Wangmeng Xiang, Xianhui Lin, Xiaoyang Kang, Zengke Jin, Yusen Hu, Bin Luo, Yifeng Geng, Xuansong Xie, Jingren Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.18332)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F58b77dc0603eb52559d98a383bf9649fd31d0bc5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/TEAL%3A-Tokenize-and-Embed-ALL-for-Multi-modal-Large-Yang-Zhang/58b77dc0603eb52559d98a383bf9649fd31d0bc5)


+ **LLM Blueprint: Enabling Text-to-Image Generation with Complex and Detailed Prompts** (16 Oct 2023)<details><summary>[ICLR 2024] Hanan Gani, Shariq Farooq Bhat, Muzammal Naseer, et al.</summary>Hanan Gani, Shariq Farooq Bhat, Muzammal Naseer, Salman Khan, Peter Wonka</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.10640)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4cb2c262ce34f41974f1b1623fc5a6e32956ded3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LLM-Blueprint%3A-Enabling-Text-to-Image-Generation-Gani-Bhat/4cb2c262ce34f41974f1b1623fc5a6e32956ded3)
[![Code](https://img.shields.io/github/stars/hananshafi/llmblueprint.svg?style=social&label=Star)](https://github.com/hananshafi/llmblueprint)



+ **Making Multimodal Generation Easier: When Diffusion Models Meet LLMs** (13 Oct 2023)<details><summary>Xiangyu Zhao, Bo Liu, Qijiong Liu, et al.</summary>Xiangyu Zhao, Bo Liu, Qijiong Liu, Guangyuan Shi, Xiao-Ming Wu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08949v1)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F833cdd713c27ab5899bb912a1d511c10af61cefb%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Making-Multimodal-Generation-Easier%3A-When-Diffusion-Zhao-Liu/833cdd713c27ab5899bb912a1d511c10af61cefb)
[![Code](https://img.shields.io/github/stars/zxy556677/EasyGen.svg?style=social&label=Star)](https://github.com/zxy556677/EasyGen)


+ **Idea2Img: Iterative Self-Refinement with GPT-4V(ision) for Automatic Image Design and Generation** (12 Oct 2023)<details><summary>Zhengyuan Yang, Jianfeng Wang, Linjie Li, et al.</summary>Zhengyuan Yang, Jianfeng Wang, Linjie Li, Kevin Lin, Chung-Ching Lin, Zicheng Liu, Lijuan Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08541)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1d14a708622917da4b9820ada6d32af24fc1651a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Idea2Img%3A-Iterative-Self-Refinement-with-for-Image-Yang-Wang/1d14a708622917da4b9820ada6d32af24fc1651a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://idea2img.github.io/)
[![Code](https://img.shields.io/github/stars/zyang-ur/Idea2Img.svg?style=social&label=Star)](https://github.com/zyang-ur/Idea2Img)


+ **OpenLEAF: Open-Domain Interleaved Image-Text Generation and Evaluation** (11 Oct 2023)<details><summary>Jie An, Zhengyuan Yang, Linjie Li, et al.</summary>Jie An, Zhengyuan Yang, Linjie Li, Jianfeng Wang, Kevin Lin, Zicheng Liu, Lijuan Wang, Jiebo Luo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07749)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7f1ba5630c3baa09b11cc665b3f71cdb117e5ffb%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/OpenLEAF%3A-Open-Domain-Interleaved-Image-Text-and-An-Yang/7f1ba5630c3baa09b11cc665b3f71cdb117e5ffb)



+ **Mini-DALLE3: Interactive Text to Image by Prompting Large Language Models** (11 Oct 2023)<details><summary>Zeqiang Lai, Xizhou Zhu, Jifeng Dai, et al.</summary>Zeqiang Lai, Xizhou Zhu, Jifeng Dai, Yu Qiao, Wenhai Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07653)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff669d7a6fab0147253178a6fc854e05e3d92fb3f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Mini-DALLE3%3A-Interactive-Text-to-Image-by-Prompting-Lai-Zhu/f669d7a6fab0147253178a6fc854e05e3d92fb3f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://minidalle3.github.io/)
[![Code](https://img.shields.io/github/stars/Zeqiang-Lai/Mini-DALLE3.svg?style=social&label=Star)](https://github.com/Zeqiang-Lai/Mini-DALLE3)


+ **[DALL-E 3] Improving Image Generation with Better Captions** <details><summary>James Betker, Gabriel Goh, Li Jing, et al.</summary>James Betker, Gabriel Goh, Li Jing, Tim Brooks, Jianfeng Wang, Linjie Li, Long Ouyang, Juntang Zhuang, Joyce Lee, Yufei Guo, Wesam Manassra, Prafulla Dhariwal, Casey Chu, Yunxin Jiao, Aditya Ramesh</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://cdn.openai.com/papers/dall-e-3.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fcfee1826dd4743eab44c6e27a0cc5970effa4d80%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Improving-Image-Generation-with-Better-Captions-Betker-Goh/cfee1826dd4743eab44c6e27a0cc5970effa4d80)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://openai.com/dall-e-3)


+ **MiniGPT-5: Interleaved Vision-and-Language Generation via Generative Vokens** (3 Oct 2023)\
Kaizhi Zheng, Xuehai He, Xin Eric Wang.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.02239)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe7d09b6f2bc878cf2c993acf675f409d0b55f35a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MiniGPT-5%3A-Interleaved-Vision-and-Language-via-Zheng-He/e7d09b6f2bc878cf2c993acf675f409d0b55f35a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://eric-ai-lab.github.io/minigpt-5.github.io/)
[![Code](https://img.shields.io/github/stars/eric-ai-lab/MiniGPT-5.svg?style=social&label=Star)](https://github.com/eric-ai-lab/MiniGPT-5)


+ **Making LLaMA SEE and Draw with SEED Tokenizer** (2 Oct 2023)<details><summary>Yuying Ge, Sijie Zhao, Ziyun Zeng, et al.</summary>Yuying Ge, Sijie Zhao, Ziyun Zeng, Yixiao Ge, Chen Li, Xintao Wang, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.01218)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5ba1525dc6d382ee0a4a1ca3c64fc5907ca64c67%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Making-LLaMA-SEE-and-Draw-with-SEED-Tokenizer-Ge-Zhao/5ba1525dc6d382ee0a4a1ca3c64fc5907ca64c67)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/seed/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/SEED.svg?style=social&label=Star)](https://github.com/AILab-CVC/SEED)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://dad1ed9a9fb76fe83b.gradio.live/)



+ **InstructCV: Instruction-Tuned Text-to-Image Diffusion Models as Vision Generalists** (30 Sep 2023)<details><summary>Yulu Gan, Sungwoo Park, Alexander Schubert, et al.</summary>Yulu Gan, Sungwoo Park, Alexander Schubert, Anthony Philippakis, Ahmed M. Alaa</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.00390)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F819f477065088220a6f706cd9ef76dbcb4b4c134%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InstructCV%3A-Instruction-Tuned-Text-to-Image-Models-Gan-Park/819f477065088220a6f706cd9ef76dbcb4b4c134)
[![Code](https://img.shields.io/github/stars/AlaaLab/InstructCV.svg?style=social&label=Star)](https://github.com/AlaaLab/InstructCV)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/alaa-lab/InstructCV)

+ **InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition** (26 Sep 2023)<details><summary>Pan Zhang, Xiaoyi Dong, Bin Wang, et al.</summary> Pan Zhang, Xiaoyi Dong, Bin Wang, Yuhang Cao, Chao Xu, Linke Ouyang, Zhiyuan Zhao, Haodong Duan, Songyang Zhang, Shuangrui Ding, Wenwei Zhang, Hang Yan, Xinyue Zhang, Wei Li, Jingwen Li, Kai Chen, Conghui He, Xingcheng Zhang, Yu Qiao, Dahua Lin, Jiaqi Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15112)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc1e450284e7d6cac1855330a1197df8537df653f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InternLM-XComposer%3A-A-Vision-Language-Large-Model-Zhang-Wang/c1e450284e7d6cac1855330a1197df8537df653f)
[![Code](https://img.shields.io/github/stars/InternLM/InternLM-XComposer.svg?style=social&label=Star)](https://github.com/InternLM/InternLM-XComposer)




+ **Text-to-Image Generation for Abstract Concepts** (26 Sep 2023) <details><summary>Jiayi Liao, Xu Chen, Qiang Fu, et al.</summary>Jiayi Liao, Xu Chen, Qiang Fu, Lun Du, Xiangnan He, Xiang Wang, Shi Han, Dongmei Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14623)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0d38f1edac66b4645cf5fa05abaf9d92cba5d5d3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Text-to-Image-Generation-for-Abstract-Concepts-Liao-Chen/0d38f1edac66b4645cf5fa05abaf9d92cba5d5d3)




+ **DreamLLM: Synergistic Multimodal Comprehension and Creation** (20 Sep 2023)<details><summary>[ICLR 2024] Runpei Dong, Chunrui Han, Yuang Peng, et al.</summary>Runpei Dong, Chunrui Han, Yuang Peng, Zekun Qi, Zheng Ge, Jinrong Yang, Liang Zhao, Jianjian Sun, Hongyu Zhou, Haoran Wei, Xiangwen Kong, Xiangyu Zhang, Kaisheng Ma, Li Yi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.11499)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7b689adb8c156d6158660f90d1c86888ee281f63%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DreamLLM%3A-Synergistic-Multimodal-Comprehension-and-Dong-Han/7b689adb8c156d6158660f90d1c86888ee281f63)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamllm.github.io/)
[![Code](https://img.shields.io/github/stars/RunpeiDong/DreamLLM.svg?style=social&label=Star)](https://github.com/RunpeiDong/DreamLLM)


+ **SwitchGPT: Adapting Large Language Models for Non-Text Outputs** (14 Sep 2023)\
Wang, Xinyu, Bohan Zhuang, and Qi Wu.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.07623)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F366564d210768814bc880e391b909cfbd95f8964%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/SwitchGPT%3A-Adapting-Large-Language-Models-for-Wang-Zhuang/366564d210768814bc880e391b909cfbd95f8964)
[![Code](https://img.shields.io/github/stars/xinke-wang/SwitchGPT.svg?style=social&label=Star)](https://github.com/xinke-wang/SwitchGPT)

+ **NExT-GPT: Any-to-Any Multimodal LLM** (11 Sep 2023)<details><summary>Shengqiong Wu, Hao Fei, Leigang Qu, et al.</summary>Shengqiong Wu, Hao Fei, Leigang Qu, Wei Ji, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.05519)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ffa75a55760e6ea49b39b83cb85c99a22e1088254%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/NExT-GPT%3A-Any-to-Any-Multimodal-LLM-Wu-Fei/fa75a55760e6ea49b39b83cb85c99a22e1088254)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://next-gpt.github.io/)
[![Code](https://img.shields.io/github/stars/NExT-GPT/NExT-GPT.svg?style=social&label=Star)](https://github.com/NExT-GPT/NExT-GPT)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://9704af1b453125102e.gradio.live/)

+ **LayoutLLM-T2I: Eliciting Layout Guidance from LLM for Text-to-Image Generation** (9 Aug 2023)<details><summary>Leigang Qu, Shengqiong Wu, Hao Fei, et al. ACM MM 2023</summary>Leigang Qu, Shengqiong Wu, Hao Fei, Liqiang Nie, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.05095)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7d78238a9bad60433d616abdd93c735087d99670%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LayoutLLM-T2I%3A-Eliciting-Layout-Guidance-from-LLM-Qu-Wu/7d78238a9bad60433d616abdd93c735087d99670)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://layoutllm-t2i.github.io/)
[![Code](https://img.shields.io/github/stars/LayoutLLM-T2I/LayoutLLM-T2I.svg?style=social&label=Star)](https://github.com/LayoutLLM-T2I/LayoutLLM-T2I)

+ **Planting a SEED of Vision in Large Language Model** (16 Jul 2023)<details><summary>Yuying Ge, Yixiao Ge, Ziyun Zeng, et al.</summary>Yuying Ge, Yixiao Ge, Ziyun Zeng, Xintao Wang, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.08041)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F40298b8d50109c52fc10763eddc64a07cf8acb31%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Planting-a-SEED-of-Vision-in-Large-Language-Model-Ge-Ge/40298b8d50109c52fc10763eddc64a07cf8acb31)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/seed/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/SEED.svg?style=social&label=Star)](https://github.com/AILab-CVC/SEED)

+ **Generative Pretraining in Multimodality** (11 Jul 2023)<details><summary>Quan Sun, Qiying Yu, Yufeng Cui, et al.</summary>Quan Sun, Qiying Yu, Yufeng Cui, Fan Zhang, Xiaosong Zhang, Yueze Wang, Hongcheng Gao, Jingjing Liu, Tiejun Huang, Xinlong Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.05222)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F94053805cd59f2e9a47fe3f080c7e7afefb337cc%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Generative-Pretraining-in-Multimodality-Sun-Yu/94053805cd59f2e9a47fe3f080c7e7afefb337cc)
[![Code](https://img.shields.io/github/stars/baaivision/Emu.svg?style=social&label=Star)](https://github.com/baaivision/Emu)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](http://218.91.113.230:9002)

+ **SPAE: Semantic Pyramid AutoEncoder for Multimodal Generation with Frozen LLMs** (30 Jun 2023) <details><summary>Lijun Yu, Yong Cheng, Zhiruo Wang, et al. NeurIPS 2023 spotlight</summary>Lijun Yu, Yong Cheng, Zhiruo Wang, Vivek Kumar, Wolfgang Macherey, Yanping Huang, David A. Ross, Irfan Essa, Yonatan Bisk, Ming-Hsuan Yang, Kevin Murphy, Alexander G. Hauptmann, Lu Jiang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.17842)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F376f494126d1ea4f571ea0263c43ac2b6331800a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/SPAE%3A-Semantic-Pyramid-AutoEncoder-for-Multimodal-Yu-Cheng/376f494126d1ea4f571ea0263c43ac2b6331800a)

+ **Controllable Text-to-Image Generation with GPT-4** (29 May 2023) <details><summary>Tianjun Zhang, Yi Zhang, Vibhav Vineet, et al.</summary>Tianjun Zhang, Yi Zhang, Vibhav Vineet, Neel Joshi, Xin Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18583)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3a79545719fb193a6b4042ef7d1d87cfd267be06%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Controllable-Text-to-Image-Generation-with-GPT-4-Zhang-Zhang/3a79545719fb193a6b4042ef7d1d87cfd267be06)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://github.com/tianjunz/Control-GPT) 

+ **Generating Images with Multimodal Language Models** (26 May 2023)\
Koh, Jing Yu, Daniel Fried, and Ruslan Salakhutdinov. NeurIPS 2023.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.17216)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6fb5c0eff3696ef252aca9638e10176ecce7cecb%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Generating-Images-with-Multimodal-Language-Models-Koh-Fried/6fb5c0eff3696ef252aca9638e10176ecce7cecb)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jykoh.com/gill)
[![Code](https://img.shields.io/github/stars/kohjingyu/gill.svg?style=social&label=Star)](https://github.com/kohjingyu/gill)

+ **LayoutGPT: Compositional Visual Planning and Generation with Large Language Models** (24 May 2023)<details><summary>Weixi Feng, Wanrong Zhu, Tsu-jui Fu, et al. NeurIPS 2023</summary>Weixi Feng, Wanrong Zhu, Tsu-jui Fu, Varun Jampani, Arjun Akula, Xuehai He, Sugato Basu, Xin Eric Wang, William Yang Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.15393)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F66d755730f5d08a6f4fcc5e81f24982ba389dca9%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LayoutGPT%3A-Compositional-Visual-Planning-and-with-Feng-Zhu/66d755730f5d08a6f4fcc5e81f24982ba389dca9)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://layoutgpt.github.io/)
[![Code](https://img.shields.io/github/stars/weixi-feng/LayoutGPT.svg?style=social&label=Star)](https://github.com/weixi-feng/LayoutGPT)

+ **Visual Programming for Text-to-Image Generation and Evaluation** (24 May 2023)\
Jaemin Cho, Abhay Zala, Mohit Bansal. NeurIPS 2023.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.15328)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9837349417e36ef5be06da0fd6c74042148bdaa2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Visual-Programming-for-Text-to-Image-Generation-and-Cho-Zala/9837349417e36ef5be06da0fd6c74042148bdaa2)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://vp-t2i.github.io/)
[![Code](https://img.shields.io/github/stars/j-min/VPGen.svg?style=social&label=Star)](https://github.com/j-min/VPGen)

+ **LLM-grounded Diffusion: Enhancing Prompt Understanding of Text-to-Image Diffusion Models with Large Language Models** (23 May 2023) <details><summary>Long Lian, Boyi Li, Adam Yala, et al.</summary>Long Lian, Boyi Li, Adam Yala, Trevor Darrell</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13655)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe9ae0c76a71b8f302eb17b1c4462b9cc97d87cd0%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LLM-grounded-Diffusion%3A-Enhancing-Prompt-of-Models-Lian-Li/e9ae0c76a71b8f302eb17b1c4462b9cc97d87cd0)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llm-grounded-diffusion.github.io/)
[![Code](https://img.shields.io/github/stars/TonyLianLong/LLM-groundedDiffusion.svg?style=social&label=Star)](https://github.com/TonyLianLong/LLM-groundedDiffusion)

+ **Interactive Data Synthesis for Systematic Vision Adaptation via LLMs-AIGCs Collaboration** (22 May 2023)<details><summary>Qifan Yu, Juncheng Li, Wentao Ye, et al.</summary>Qifan Yu, Juncheng Li, Wentao Ye, Siliang Tang, Yueting Zhuang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.12799)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F43a55dbd95c9d5cd82de8db276f41adeec4a937d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Interactive-Data-Synthesis-for-Systematic-Vision-Yu-Li/43a55dbd95c9d5cd82de8db276f41adeec4a937d)
[![Code](https://img.shields.io/github/stars/Yuqifan1117/Labal-Anything-Pipeline.svg?style=social&label=Star)](https://github.com/Yuqifan1117/Labal-Anything-Pipeline)

+ **CoDi: Any-to-Any Generation via Composable Diffusion** (19 May 2023)<details><summary>Zineng Tang, Ziyi Yang, Chenguang Zhu, et al. NeurIPS 2023.</summary>Zineng Tang, Ziyi Yang, Chenguang Zhu, Michael Zeng, Mohit Bansal</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11846)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9f411fda2ad5b141a3115f707bcf5ee865b3fb94%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Any-to-Any-Generation-via-Composable-Diffusion-Tang-Yang/9f411fda2ad5b141a3115f707bcf5ee865b3fb94)
[![Code](https://img.shields.io/github/stars/microsoft/i-Code.svg?style=social&label=Star)](https://github.com/microsoft/i-Code/tree/main/i-Code-V3)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://codi-gen.github.io/)


+ **LLMScore: Unveiling the Power of Large Language Models in Text-to-Image Synthesis Evaluation** (18 May 2023)<details><summary>Yujie Lu, Xianjun Yang, Xiujun Li, et al. NeurIPS 2023.</summary>Yujie Lu, Xianjun Yang, Xiujun Li, Xin Eric Wang, William Yang Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11116)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F972501b057e2b84d6ce6506f70bcac697bab7872%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Any-to-Any-Generation-via-Composable-Diffusion-Tang-Yang/972501b057e2b84d6ce6506f70bcac697bab7872)
[![Code](https://img.shields.io/github/stars/YujieLu10/LLMScore.svg?style=social&label=Star)](https://github.com/YujieLu10/LLMScore)

+ **SUR-adapter: Enhancing Text-to-Image Pre-trained Diffusion Models with Large Language Models** (9 May 2023)<details><summary>Shanshan Zhong, Zhongzhan Huang, Wushao Wen, et al. ACM MM 2023.</summary>Shanshan Zhong, Zhongzhan Huang, Wushao Wen, Jinghui Qin, Liang Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05189)
[![Code](https://img.shields.io/github/stars/Qrange-group/SUR-adapter.svg?style=social&label=Star)](https://github.com/Qrange-group/SUR-adapter)

+ **Grounding Language Models to Images for Multimodal Inputs and Outputs** (31 Jan 2023)\
Koh, Jing Yu, Ruslan Salakhutdinov, and Daniel Fried. ICML 2023.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.13823)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6173520a1eb2814d067e8c5fd16212b7cbf6ee78%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Grounding-Language-Models-to-Images-for-Multimodal-Koh-Salakhutdinov/6173520a1eb2814d067e8c5fd16212b7cbf6ee78)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jykoh.com/fromage)
[![Code](https://img.shields.io/github/stars/kohjingyu/fromage.svg?style=social&label=Star)](https://github.com/kohjingyu/fromage)

### Non-LLM-based (Clip/T5)
+ **PIXART-α: Fast Training of Diffusion Transformer for Photorealistic Text-to-Image Synthesis** (30 Sep 2023)<details><summary>[ICLR 2024] Junsong Chen, Jincheng Yu, Chongjian Ge, et al.</summary>Junsong Chen, Jincheng Yu, Chongjian Ge, Lewei Yao, Enze Xie, Yue Wu, Zhongdao Wang, James Kwok, Ping Luo, Huchuan Lu, Zhenguo Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.00426)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F144eca44e250cc462f6fc3a172abb865978f66f5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/PixArt-%CE%B1%3A-Fast-Training-of-Diffusion-Transformer-Chen-Yu/7dfe1c9f1d7120102499c7e561efc2326e7a0358)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pixart-alpha.github.io/)
[![Code](https://img.shields.io/github/stars/PixArt-alpha/PixArt-alpha.svg?style=social&label=Star)](https://github.com/PixArt-alpha/PixArt-alpha)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/PixArt-alpha/PixArt-alpha)

+ **TextDiffuser: Diffusion Models as Text Painters** (18 May 2023) <details><summary>Jingye Chen, Yupan Huang, Tengchao Lv, et al. NeurIPS 2023.</summary>Jingye Chen, Yupan Huang, Tengchao Lv, Lei Cui, Qifeng Chen, Furu Wei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10855)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe779781f1bea273573fc9d3f1a5e874bcff2cd2b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/TextDiffuser%3A-Diffusion-Models-as-Text-Painters-Chen-Huang/e779781f1bea273573fc9d3f1a5e874bcff2cd2b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jingyechen.github.io/textdiffuser/)
[![Code](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star)](https://github.com/microsoft/unilm/tree/master/textdiffuser)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/JingyeChen22/TextDiffuser)

+ **TiGAN: Text-Based Interactive Image Generation and Manipulation** (Dec 2022)<details><summary>Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, et al. AAAI 2022.</summary>Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, Chris Tensmeyer, Tong Yu,Changyou Chen, Jinhui Xu, Tong Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ojs.aaai.org/index.php/AAAI/article/view/20270)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F839dc73c1adae268144d9cfb9d70985b2001304f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/TiGAN%3A-Text-Based-Interactive-Image-Generation-and-Zhou-Zhang/839dc73c1adae268144d9cfb9d70985b2001304f)\
Tags: `iteractive`

+ **Multi-Concept Customization of Text-to-Image Diffusion** (8 Dec 2022)<details><summary>Nupur Kumari, Bingliang Zhang, Richard Zhang, et al. CVPR 2023.</summary>Nupur Kumari, Bingliang Zhang, Richard Zhang, Eli Shechtman, Jun-Yan Zhu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.04488)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F144eca44e250cc462f6fc3a172abb865978f66f5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Multi-Concept-Customization-of-Text-to-Image-Kumari-Zhang/144eca44e250cc462f6fc3a172abb865978f66f5)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.cs.cmu.edu/~custom-diffusion/)
[![Code](https://img.shields.io/github/stars/adobe-research/custom-diffusion.svg?style=social&label=Star)](https://github.com/adobe-research/custom-diffusion)\
Tags: `customization`

+ **DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation** (25 Aug 2022)<details><summary>Nataniel Ruiz, Yuanzhen Li, Varun Jampani, et al. CVPR 2023.</summary>Nataniel Ruiz, Yuanzhen Li, Varun Jampani, Yael Pritch, Michael Rubinstein, Kfir Aberman</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2208.12242)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5b19bf6c3f4b25cac96362c98b930cf4b37f6744%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DreamBooth%3A-Fine-Tuning-Text-to-Image-Diffusion-for-Ruiz-Li/5b19bf6c3f4b25cac96362c98b930cf4b37f6744)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreambooth.github.io/)\
Tags: `customization`

+ **An Image is Worth One Word: Personalizing Text-to-Image Generation using Textual Inversion** (2 Aug 2022)<details><summary>Rinon Gal, Yuval Alaluf, Yuval Atzmon, et al. </summary>Rinon Gal, Yuval Alaluf, Yuval Atzmon, Or Patashnik, Amit H. Bermano, Gal Chechik, Daniel Cohen-Or</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2208.01618)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5b19bf6c3f4b25cac96362c98b930cf4b37f6744%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DreamBooth%3A-Fine-Tuning-Text-to-Image-Diffusion-for-Ruiz-Li/5b19bf6c3f4b25cac96362c98b930cf4b37f6744)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreambooth.github.io/)
[![Code](https://img.shields.io/github/stars/rinongal/textual_inversion.svg?style=social&label=Star)](https://github.com/rinongal/textual_inversion)\
Tags: `customization`

+ **Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding** (23 May 2022)\
Saharia, Chitwan, et al. NeurIPS 2022.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.11487)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9695824d7a01fad57ba9c01d7d76a519d78d65e7%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Photorealistic-Text-to-Image-Diffusion-Models-with-Saharia-Chan/9695824d7a01fad57ba9c01d7d76a519d78d65e7)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://imagen.research.google/) 

+ **High-Resolution Image Synthesis with Latent Diffusion Models** (20 Dec 2021)\
Rombach, Robin, et al. CVPR 2022 (Oral).\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.10752)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc10075b3746a9f3dd5811970e93c8ca3ad39b39d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/High-Resolution-Image-Synthesis-with-Latent-Models-Rombach-Blattmann/c10075b3746a9f3dd5811970e93c8ca3ad39b39d)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ommer-lab.com/research/latent-diffusion-models/)
[![Code](https://img.shields.io/github/stars/CompVis/stable-diffusion.svg?style=social&label=Star)](https://github.com/CompVis/stable-diffusion)

### Datasets


+ **MIMIC-IT: Multi-Modal In-Context Instruction Tuning** (8 Jun 2023)<details><summary>Bo Li, Yuanhan Zhang, Liangyu Chen, et al. NeurIPS 2023</summary>Bo Li, Yuanhan Zhang, Liangyu Chen, Jinghao Wang, Fanyi Pu, Jingkang Yang, Chunyuan Li, Ziwei Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.05425)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd47524cd5c3c4b57af2e5a29f6f91c420310f236%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/d47524cd5c3c4b57af2e5a29f6f91c420310f236)
[![Code](https://img.shields.io/github/stars/Luodian/otter.svg?style=social&label=Star)](https://github.com/Luodian/otter)



+ **[LAION-Glyph] GlyphControl: Glyph Conditional Control for Visual Text Generation** (29 May 2023)<details><summary>Yukang Yang, Dongnan Gui, Yuhui Yuan, et al. NeurIPS 2023</summary>Yukang Yang, Dongnan Gui, Yuhui Yuan, Weicong Liang, Haisong Ding, Han Hu, Kai Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18259)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5fbe4c92791fbecb179c1ab79bba9a59b2e155ba%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/5fbe4c92791fbecb179c1ab79bba9a59b2e155ba)
[![Code](https://img.shields.io/github/stars/AIGText/GlyphControl-release.svg?style=social&label=Star)](https://github.com/AIGText/GlyphControl-release)





+ **[MARIO-10M] TextDiffuser: Diffusion Models as Text Painters** (18 May 2023)<details><summary>Jingye Chen, Yupan Huang, Tengchao Lv, et al. NeurIPS 2023</summary>Jingye Chen, Yupan Huang, Tengchao Lv, Lei Cui, Qifeng Chen, Furu Wei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14108)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe779781f1bea273573fc9d3f1a5e874bcff2cd2b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/e779781f1bea273573fc9d3f1a5e874bcff2cd2b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jingyechen.github.io/textdiffuser/)
[![Code](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star)](https://github.com/microsoft/unilm)



+ **DataComp: In search of the next generation of multimodal datasets** (27 Apr 2023)<details><summary>Samir Yitzhak Gadre, Gabriel Ilharco, Alex Fang, et al. NeurIPS 2023</summary>Samir Yitzhak Gadre, Gabriel Ilharco, Alex Fang, Jonathan Hayase, Georgios Smyrnis, Thao Nguyen, Ryan Marten, Mitchell Wortsman, Dhruba Ghosh, Jieyu Zhang, Eyal Orgad, Rahim Entezari, Giannis Daras, Sarah Pratt, Vivek Ramanujan, Yonatan Bitton, Kalyani Marathe, Stephen Mussmann, Richard Vencu, Mehdi Cherti, Ranjay Krishna, Pang Wei Koh, Olga Saukh, Alexander Ratner, Shuran Song, Hannaneh Hajishirzi, Ali Farhadi, Romain Beaumont, Sewoong Oh, Alex Dimakis, Jenia Jitsev, Yair Carmon, Vaishaal Shankar, Ludwig Schmidt</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14108)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff9570989919338079088270a9cf1a7afc8db8093%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/f9570989919338079088270a9cf1a7afc8db8093)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.datacomp.ai/)
[![Code](https://img.shields.io/github/stars/mlfoundations/datacomp.svg?style=social&label=Star)](https://github.com/mlfoundations/datacomp)

+ **[LLava-instruct] Visual Instruction Tuning** (17 Apr 2023)<details><summary>Haotian Liu, Chunyuan Li, Qingyang Wu, et al. NeurIPS 2023</summary>Haotian Liu, Chunyuan Li, Qingyang Wu, Yong Jae Lee</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08485)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa5036f31f0e629dc661f120b8c3b1f374d479ab8%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/a5036f31f0e629dc661f120b8c3b1f374d479ab8)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llava-vl.github.io//)
[![Code](https://img.shields.io/github/stars/haotian-liu/LLaVA.svg?style=social&label=Star)](https://github.com/haotian-liu/LLaVA)



+ **Multimodal C4: An Open, Billion-scale Corpus of Images Interleaved with Text** (14 Apr 2023)<details><summary>Wanrong Zhu, Jack Hessel, Anas Awadalla, et al. NeurIPS 2023</summary>Wanrong Zhu, Jack Hessel, Anas Awadalla, Samir Yitzhak Gadre, Jesse Dodge, Alex Fang, Youngjae Yu, Ludwig Schmidt, William Yang Wang, Yejin Choi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06939)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdf958800014d310b6df34ad83d771314d68fbb2d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/df958800014d310b6df34ad83d771314d68fbb2d)
[![Code](https://img.shields.io/github/stars/allenai/mmc4.svg?style=social&label=Star)](https://github.com/allenai/mmc4)





+ **Language Is Not All You Need: Aligning Perception with Language Models** (27 Feb 2023)<details><summary>Shaohan Huang, Li Dong, Wenhui Wang, et al. NeurIPS 2023</summary>Shaohan Huang, Li Dong, Wenhui Wang, Yaru Hao, Saksham Singhal, Shuming Ma, Tengchao Lv, Lei Cui, Owais Khan Mohammed, Barun Patra, Qiang Liu, Kriti Aggarwal, Zewen Chi, Johan Bjorck, Vishrav Chaudhary, Subhojit Som, Xia Song, Furu Wei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.14045)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ffbfef4723d8c8467d7bd523e1d0b703cce0e0f9c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/fbfef4723d8c8467d7bd523e1d0b703cce0e0f9c)



+ **COYO-700M: Image-Text Pair Dataset** (31 Aug 2022)
[![Code](https://img.shields.io/github/stars/kakaobrain/coyo-dataset.svg?style=social&label=Star)](https://github.com/kakaobrain/coyo-dataset)


+ **LAION-5B: An open large-scale dataset for training next generation image-text models** (16 Oct 2022)<details><summary>Christoph Schuhmann, Romain Beaumont, Richard Vencu, et al. NeurIPS 2022</summary>Christoph Schuhmann, Romain Beaumont, Richard Vencu, Cade Gordon, Ross Wightman, Mehdi Cherti, Theo Coombes, Aarush Katta, Clayton Mullis, Mitchell Wortsman, Patrick Schramowski, Srivatsa Kundurthy, Katherine Crowson, Ludwig Schmidt, Robert Kaczmarczyk, Jenia Jitsev</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.08402)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe5c8960eb2ec034ffbd353ef39fd1cb541d3c7c9%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/e5c8960eb2ec034ffbd353ef39fd1cb541d3c7c9)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://laion.ai/blog/laion-5b/)




+ **LAION COCO: 600M SYNTHETIC CAPTIONS FROM LAION2B-EN** (15 Sep 2022)<details><summary>Christoph Schuhmann, Andreas Köpf , Theo Coombes, et al.</summary>Christoph Schuhmann, Andreas Köpf , Theo Coombes, Richard Vencu, Benjamin Trom , Romain Beaumont</details>
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://laion.ai/blog/laion-coco/)


+ **[M3W] Flamingo: a Visual Language Model for Few-Shot Learning** (29 Apr 2022)<details><summary>Jean-Baptiste Alayrac, Jeff Donahue, Pauline Luc, et al. NeurIPS 2022</summary>Jean-Baptiste Alayrac, Jeff Donahue, Pauline Luc, Antoine Miech, Iain Barr, Yana Hasson, Karel Lenc, Arthur Mensch, Katie Millican, Malcolm Reynolds, Roman Ring, Eliza Rutherford, Serkan Cabi, Tengda Han, Zhitao Gong, Sina Samangooei, Marianne Monteiro, Jacob Menick, Sebastian Borgeaud, Andrew Brock, Aida Nematzadeh, Sahand Sharifzadeh, Mikolaj Binkowski, Ricardo Barreira, Oriol Vinyals, Andrew Zisserman, Karen Simonyan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.14198)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F26218bdcc3945c7edae7aa2adbfba4cd820a2df3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/26218bdcc3945c7edae7aa2adbfba4cd820a2df3)




+ **[LAION-FACE]General Facial Representation Learning in a Visual-Linguistic Manner** (6 Dec 2021)<details><summary>Yinglin Zheng, Hao Yang, Ting Zhang, et al. NeurIPS 2021</summary>Yinglin Zheng, Hao Yang, Ting Zhang, Jianmin Bao, Dongdong Chen, Yangyu Huang, Lu Yuan, Dong Chen, Ming Zeng, Fang Wen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.03109)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F037bab9d26ef7da11ee32d7682836604d2cc8a72%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/037bab9d26ef7da11ee32d7682836604d2cc8a72)
[![Code](https://img.shields.io/github/stars/FacePerceiver/FaRL.svg?style=social&label=Star)](https://github.com/FacePerceiver/FaRL)




+ **[LAION-400M] Open Dataset of CLIP-Filtered 400 Million Image-Text Pairs** (3 Nov 2021)<details><summary>Christoph Schuhmann, Richard Vencu, Romain Beaumont, et al. NeurIPS 2021</summary>Christoph Schuhmann, Richard Vencu, Romain Beaumont, Robert Kaczmarczyk, Clayton Mullis, Aarush Katta, Theo Coombes, Jenia Jitsev, Aran Komatsuzaki</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2111.02114)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb668ce936cff0b0ca8b635cd5f25a62eaf4eb3df%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/b668ce936cff0b0ca8b635cd5f25a62eaf4eb3df)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://laion.ai/laion-400-open-dataset/)




+ **WIT: Wikipedia-based Image Text Dataset for Multimodal Multilingual Machine Learning** (2 Mar 2021)<details><summary>Krishna Srinivasan, Karthik Raman, Jiecao Chen, et al. SIGIR 2021</summary>Krishna Srinivasan, Karthik Raman, Jiecao Chen, Michael Bendersky, Marc Najork</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2103.01913)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F98e565fa06f6c7bf7c46833b5106b26dc45130c4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/98e565fa06f6c7bf7c46833b5106b26dc45130c4)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://github.com/google-research-datasets/wit)

+ **Conceptual 12M: Pushing Web-Scale Image-Text Pre-Training To Recognize Long-Tail Visual Concepts** (17 Feb 2021)<details><summary>Soravit Changpinyo, Piyush Sharma, Nan Ding, et al. CVPR 2021</summary>Soravit Changpinyo, Piyush Sharma, Nan Ding, Radu Soricut</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2102.08981)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F394be105b87e9bfe72c20efe6338de10604e1a11%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/394be105b87e9bfe72c20efe6338de10604e1a11)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://github.com/google-research-datasets/conceptual-12m)


+ **[ALIGN] Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision** (11 Feb 2021)<details><summary>Chao Jia, Yinfei Yang, Ye Xia, et al. ICML 2021</summary>Chao Jia, Yinfei Yang, Ye Xia, Yi-Ting Chen, Zarana Parekh, Hieu Pham, Quoc V. Le, Yunhsuan Sung, Zhen Li, Tom Duerig</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2102.05918)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F141a5033d9994242b18bb3b217e79582f1ee9306%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/141a5033d9994242b18bb3b217e79582f1ee9306)



+ **[MS COCO] Microsoft COCO: Common Objects in Context** (1 May 2014)<details><summary>Tsung-Yi Lin, Michael Maire, Serge Belongie, et al. ECCV 2014</summary>Tsung-Yi Lin, Michael Maire, Serge Belongie, Lubomir Bourdev, Ross Girshick, James Hays, Pietro Perona, Deva Ramanan, C. Lawrence Zitnick, Piotr Dollár</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1405.0312)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F71b7178df5d2b112d07e45038cb5637208659ff7%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/71b7178df5d2b112d07e45038cb5637208659ff7)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cocodataset-org.translate.goog/?_x_tr_sl=en&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=sc#home)



+ **[Im2Text] Describing Images Using 1 Million Captioned Photographs** (12 Dec 2011)<details><summary>Vicente Ordonez Girish Kulkarni Tamara L Berg, NeurIPS 2011</summary>Vicente Ordonez Girish Kulkarni Tamara L Berg</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://papers.nips.cc/paper_files/paper/2011/hash/5dd9db5e033da9c6fb5ba83c7a7ebea9-Abstract.html)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8e080b98efbe65c02a116439205ca2344b9f7cd4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/8e080b98efbe65c02a116439205ca2344b9f7cd4)



## Video Generation

### 🔅 LLM-based


+ **[Sora] Video generation models as world simulators** (15 Feb 2024)<details><summary>Tim Brooks, Bill Peebles, Connor Holmes, et al.</summary>Tim Brooks and Bill Peebles and Connor Holmes and Will DePue and Yufei Guo and Li Jing and David Schnurr and Joe Taylor and Troy Luhman and Eric Luhman and Clarence Ng and Ricky Wang and Aditya Ramesh</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openai.com/research/video-generation-models-as-world-simulators)

+ **Video-LaVIT: Unified Video-Language Pre-training with Decoupled Visual-Motional Tokenization: Content-Consistent Multi-Scene Video Generation with LLM** (2 Jan 2024)<details><summary>Yang Jin, Zhicheng Sun, Kun Xu, et al.</summary>Yang Jin, Zhicheng Sun, Kun Xu, Kun Xu, Liwei Chen, Hao Jiang, Quzhe Huang, Chengru Song, Yuliang Liu, Di Zhang, Yang Song, Kun Gai, Yadong Mu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03161)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc1b5195bc09a2232ec2b69e5a2a6bd39b3162c62%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Video-LaVIT%3A-Unified-Video-Language-Pre-training-Jin-Sun/c1b5195bc09a2232ec2b69e5a2a6bd39b3162c62)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://video-lavit.github.io/)

+ **VideoDrafter: Content-Consistent Multi-Scene Video Generation with LLM** (2 Jan 2024)<details><summary>Fuchen Long, Zhaofan Qiu, Ting Yao, et al.</summary>Fuchen Long, Zhaofan Qiu, Ting Yao, Tao Mei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01256)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ffc84fcf269a37ed7ddcb1b0f2d7d1a00f677eaea%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDrafter%3A-Content-Consistent-Multi-Scene-Video-Long-Qiu/fc84fcf269a37ed7ddcb1b0f2d7d1a00f677eaea)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://videodrafter.github.io/)

+ **[PRO-Motion] Plan, Posture and Go: Towards Open-World Text-to-Motion Generation** (22 Dec 2023)<details><summary>Jinpeng Liu, Wenxun Dai, Chunyu Wang, et al.</summary>Jinpeng Liu, Wenxun Dai, Chunyu Wang, Yiji Cheng, Yansong Tang, Xin Tong</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14828)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4599d5af850da482f591a02a3b17d56e0d358771%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Plan%2C-Posture-and-Go%3A-Towards-Open-World-Generation-Liu-Dai/4599d5af850da482f591a02a3b17d56e0d358771)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://moonsliu.github.io/Pro-Motion/)

+ **VideoPoet: A Large Language Model for Zero-Shot Video Generation** (21 Dec 2023)<details><summary>Dan Kondratyuk, Lijun Yu, Xiuye Gu, et al.</summary>Dan Kondratyuk, Lijun Yu, Xiuye Gu, José Lezama, Jonathan Huang, Rachel Hornung, Hartwig Adam, Hassan Akbari, Yair Alon, Vighnesh Birodkar, Yong Cheng, Ming-Chang Chiu, Josh Dillon, Irfan Essa, Agrim Gupta, Meera Hahn, Anja Hauth, David Hendon, Alonso Martinez, David Minnen, David Ross, Grant Schindler, Mikhail Sirotenko, Kihyuk Sohn, Krishna Somandepalli, Huisheng Wang, Jimmy Yan, Ming-Hsuan Yang, Xuan Yang, Bryan Seybold, Lu Jiang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14125)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0c4f46e4dcae5527018e6432fb60cfe8c3354e97%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoPoet%3A-A-Large-Language-Model-for-Zero-Shot-Kondratyuk-Yu/0c4f46e4dcae5527018e6432fb60cfe8c3354e97)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sites.research.google/videopoet/)

+ **InterControl: Generate Human Motion Interactions by Controlling Every Joint** (27 Nov 2023)<details><summary>Zhenzhi Wang, Jingbo Wang, Dahua Lin, et al.</summary>Zhenzhi Wang, Jingbo Wang, Dahua Lin, Bo Dai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15864)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9cdb7e415a96795dc6705e66f3b798238b4dec2c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InterControl%3A-Generate-Human-Motion-Interactions-by-Wang-Wang/9cdb7e415a96795dc6705e66f3b798238b4dec2c)
[![Code](https://img.shields.io/github/stars/zhenzhiwang/intercontrol.svg?style=social&label=Star)](https://github.com/zhenzhiwang/intercontrol)\
Tags: `human motion generation`

+ **GPT4Motion: Scripting Physical Motions in Text-to-Video Generation via Blender-Oriented GPT Planning** (21 Nov 2023)<details><summary>Jiaxi Lv, Yi Huang, Mingfu Yan, et al.</summary>Jiaxi Lv, Yi Huang, Mingfu Yan, Jiancheng Huang, Jianzhuang Liu, Yifan Liu, Yafei Wen, Xiaoxin Chen, Shifeng Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12631)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9cdb7e415a96795dc6705e66f3b798238b4dec2c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InterControl%3A-Generate-Human-Motion-Interactions-by-Wang-Wang/9cdb7e415a96795dc6705e66f3b798238b4dec2c)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://gpt4motion.github.io/)

+ **[MAGVIT-v2] Language Model Beats Diffusion -- Tokenizer is Key to Visual Generation** (9 Oct 2023)<details><summary>Lijun Yu, José Lezama, Nitesh B. Gundavarapu, et al.</summary>Lijun Yu, José Lezama, Nitesh B. Gundavarapu, Luca Versari, Kihyuk Sohn, David Minnen, Yong Cheng, Agrim Gupta, Xiuye Gu, Alexander G. Hauptmann, Boqing Gong, Ming-Hsuan Yang, Irfan Essa, David A. Ross, Lu Jiang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.05737)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F985f0c89c5a607742ec43c1fdc2cbfe54541cbad%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Language-Model-Beats-Diffusion-Tokenizer-is-Key-to-Yu-Lezama/985f0c89c5a607742ec43c1fdc2cbfe54541cbad)

+ **[LVD] LLM-grounded Video Diffusion Models** (29 Sep 2023)<details><summary>Long Lian, Baifeng Shi, Adam Yala, et al.</summary>Long Lian, Baifeng Shi, Adam Yala, Trevor Darrell, Boyi Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.17444)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F87bf66eb6d22df17f70170a0e575b4f12c4813ef%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LLM-grounded-Video-Diffusion-Models-Lian-Shi/87bf66eb6d22df17f70170a0e575b4f12c4813ef)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llm-grounded-video-diffusion.github.io/)
[![Code](https://img.shields.io/github/stars/TonyLianLong/LLM-groundedVideoDiffusion.svg?style=social&label=Star)](https://github.com/TonyLianLong/LLM-groundedVideoDiffusion)

+ **VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-Guided Planning** (26 Sep 2023)<details><summary>Han Lin, Abhay Zala, Jaemin Cho, et al.</summary>Han Lin, Abhay Zala, Jaemin Cho, Mohit Bansal</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15091)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F16753e0317730e8c1b297338300a8c6163dd06f2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoDirectorGPT%3A-Consistent-Multi-scene-Video-via-Lin-Zala/16753e0317730e8c1b297338300a8c6163dd06f2)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://videodirectorgpt.github.io/)
[![Code](https://img.shields.io/github/stars/HL-hanlin/VideoDirectorGPT.svg?style=social&label=Star)](https://github.com/HL-hanlin/VideoDirectorGPT)

+ **Free-Bloom: Zero-Shot Text-to-Video Generator with LLM Director and LDM Animator** (25 Sep 2023)<details><summary>Hanzhuo Huang, Yufan Feng, Cheng Shi, et al. NIPS 2023.</summary>Hanzhuo Huang, Yufan Feng, Cheng Shi, Lan Xu, Jingyi Yu, Sibei Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14494)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F120aca3e415b6641a0b0cd20695ab85ed7789612%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Free-Bloom%3A-Zero-Shot-Text-to-Video-Generator-with-Huang-Feng/120aca3e415b6641a0b0cd20695ab85ed7789612)
[![Code](https://img.shields.io/github/stars/SooLab/Free-Bloom.svg?style=social&label=Star)](https://github.com/SooLab/Free-Bloom)

+ **[Dysen-VDM] Empowering Dynamics-aware Text-to-Video Diffusion with Large Language Models** (26 Aug 2023)<details><summary>Hao Fei, Shengqiong Wu, Wei Ji, et al.</summary>Hao Fei, Shengqiong Wu, Wei Ji, Hanwang Zhang, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.13812)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd0a7f7fe31e0e0c42b471b4c47a313bd8c8e5206%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Empowering-Dynamics-aware-Text-to-Video-Diffusion-Fei-Wu/d0a7f7fe31e0e0c42b471b4c47a313bd8c8e5206)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](http://haofei.vip/Dysen-VDM/)
[![Code](https://img.shields.io/github/stars/scofield7419/Dysen.svg?style=social&label=Star)](https://github.com/scofield7419/Dysen)

+ **[DirecT2V] Large Language Models are Frame-level Directors for Zero-shot Text-to-Video Generation** (23 May 2023)<details><summary>Susung Hong, Junyoung Seo, Sunghwan Hong, et al.</summary>Susung Hong, Junyoung Seo, Sunghwan Hong, Heeseong Shin, Seungryong Kim</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.14330)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb1750d2a6e3480e690999916a86c8b3876577b39%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Large-Language-Models-are-Frame-level-Directors-for-Hong-Seo/b1750d2a6e3480e690999916a86c8b3876577b39)
[![Code](https://img.shields.io/github/stars/KU-CVLAB/DirecT2V.svg?style=social&label=Star)](https://github.com/KU-CVLAB/DirecT2V)

+ **Text2Motion: From Natural Language Instructions to Feasible Plans** (21 Mar 2023)<details><summary>Kevin Lin, Christopher Agia, Toki Migimatsu, et al.</summary>Kevin Lin, Christopher Agia, Toki Migimatsu, Marco Pavone, Jeannette Bohg</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12153)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8f2d4758e6d525509ae36bb30224dc9259027e6b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Text2Motion%3A-from-natural-language-instructions-to-Lin-Agia/8f2d4758e6d525509ae36bb30224dc9259027e6b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sites.google.com/stanford.edu/text2motion)
[![Code](https://img.shields.io/github/stars/KU-CVLAB/DirecT2V.svg?style=social&label=Star)](https://github.com/KU-CVLAB/DirecT2V)

### Non-LLM-based
+ **VBench: Comprehensive Benchmark Suite for Video Generative Models** (29 Nov 2023)\
Huang, Ziqi, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17982)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4e9a8141da2a8c603722b07d096109207f8e0b66%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VBench%3A-Comprehensive-Benchmark-Suite-for-Video-Huang-He/4e9a8141da2a8c603722b07d096109207f8e0b66)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://vchitect.github.io/VBench-project/)
[![Code](https://img.shields.io/github/stars/Vchitect/VBench.svg?style=social&label=Star)](https://github.com/Vchitect/VBench)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Vchitect/VBench_Leaderboard)

+ **Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets** (25 Nov 2023)\
Blattmann, Andreas, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15127)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1206b05eae5a06ba662ae79fb291b50e359c4f42%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Stable-Video-Diffusion%3A-Scaling-Latent-Video-Models-Blattmann-Dockhorn/1206b05eae5a06ba662ae79fb291b50e359c4f42)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://stability.ai/research/stable-video-diffusion-scaling-latent-video-diffusion-models-to-large-datasets)
[![Code](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social&label=Star)](https://github.com/Stability-AI/generative-models)

+ **VideoCrafter1: Open Diffusion Models for High-Quality Video Generation** (30 Oct 2023)\
Chen, Haoxin, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.19512)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1891c3756f870d902a0b793a1dcd5cc34c778612%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoCrafter1%3A-Open-Diffusion-Models-for-Video-Chen-Xia/1891c3756f870d902a0b793a1dcd5cc34c778612)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/videocrafter/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Star)](https://github.com/AILab-CVC/VideoCrafter)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/VideoCrafter/VideoCrafter)

+ **FreeNoise: Tuning-Free Longer Video Diffusion via Noise Rescheduling** (23 Oct 2023)<details><summary>Haonan Qiu, Menghan Xia, Yong Zhang, et al.</summary>Haonan Qiu, Menghan Xia, Yong Zhang, Yingqing He, Xintao Wang, Ying Shan, Ziwei Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.15169)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd831988859f0c077b38094446d8585a8340af223%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/FreeNoise%3A-Tuning-Free-Longer-Video-Diffusion-via-Qiu-Xia/d831988859f0c077b38094446d8585a8340af223)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](http://haonanqiu.com/projects/FreeNoise.html)
[![Code](https://img.shields.io/github/stars/arthur-qiu/LongerCrafter.svg?style=social&label=Star)](https://github.com/arthur-qiu/LongerCrafter)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/MoonQiu/LongerCrafter)

+ **Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation** (13 Jul 2023)\
He, Yingqing, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06940)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F77040969110fab39a55699cb06f9edf68789445a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Animate-A-Story%3A-Storytelling-with-Video-Generation-He-Xia/77040969110fab39a55699cb06f9edf68789445a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/Animate-A-Story/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/Animate-A-Story.svg?style=social&label=Star)](https://github.com/AILab-CVC/Animate-A-Story)

+ **Make-Your-Video: Customized Video Generation Using Textual and Structural Guidance** (1 Jun 2023)\
Xing, Jinbo, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.00943)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F52b10ae66d025e99fbb602935e155f97f4f0696f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Make-Your-Video%3A-Customized-Video-Generation-Using-Xing-Xia/52b10ae66d025e99fbb602935e155f97f4f0696f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://doubiiu.github.io/projects/Make-Your-Video/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/Make-Your-Video.svg?style=social&label=Star)](https://github.com/AILab-CVC/Make-Your-Video)

+ **Follow Your Pose: Pose-Guided Text-to-Video Generation using Pose-Free Videos** (3 Apr 2023)\
Ma, Yue, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01186)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fee73edebd42626d9c2d91e35fd2ed3cdb0fb26d0%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Follow-Your-Pose%3A-Pose-Guided-Text-to-Video-using-Ma-He/ee73edebd42626d9c2d91e35fd2ed3cdb0fb26d0)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-pose.github.io/)
[![Code](https://img.shields.io/github/stars/mayuelala/FollowYourPose.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourPose)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/YueMafighting/FollowYourPose)

+ **VideoFusion: Decomposed Diffusion Models for High-Quality Video Generation** (15 Mar 2023)\
Luo, Zhengxiong, et al. CVPR 2023.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.08320)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F26c6090b7e7ba4513f82aa28d41360c60770c618%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoFusion%3A-Decomposed-Diffusion-Models-for-Video-Luo-Chen/26c6090b7e7ba4513f82aa28d41360c60770c618)

### Datasets

+ **InternVid: A Large-scale Video-Text Dataset for Multimodal Understanding and Generation** (13 Jul 2023)<details><summary>[ICLR 2024 Spotlight] Yi Wang, Yinan He, Yizhuo Li, et al.</summary>Yi Wang, Yinan He, Yizhuo Li, Kunchang Li, Jiashuo Yu, Xin Ma, Xinhao Li, Guo Chen, Xinyuan Chen, Yaohui Wang, Conghui He, Ping Luo, Ziwei Liu, Yali Wang, Limin Wang, Yu Qiao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06942)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F369b449415d50387fba048bbd4d26ee890df84b5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InternVid%3A-A-Large-scale-Video-Text-Dataset-for-and-Wang-He/369b449415d50387fba048bbd4d26ee890df84b5)
[![Code](https://img.shields.io/github/stars/OpenGVLab/InternVideo.svg?style=social&label=Star)](https://github.com/OpenGVLab/InternVideo)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/datasets/OpenGVLab/InternVid)

+ **[HD-VG-130M] VideoFactory: Swap Attention in Spatiotemporal Diffusions for Text-to-Video Generation** (18 May 2023)<details><summary>Wenjing Wang, Huan Yang, Zixi Tuo, et al.</summary>Wenjing Wang, Huan Yang, Zixi Tuo, Huiguo He, Junchen Zhu, Jianlong Fu, Jiaying Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10874)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F50bbf2c11984d18aa14f964a4909ac25f07e50ea%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoFactory%3A-Swap-Attention-in-Spatiotemporal-for-Wang-Yang/50bbf2c11984d18aa14f964a4909ac25f07e50ea)
[![Code](https://img.shields.io/github/stars/OpenGVLab/InternVideo.svg?style=social&label=Star)](https://github.com/daooshee/HD-VG-130M?tab=readme-ov-file)

+ **[VideoCC3M] Learning Audio-Video Modalities from Image Captions** (18 May 2023)<details><summary>Arsha Nagrani, Paul Hongsuck Seo, Bryan Seybold, et al. [ECCV 2022]</summary>Arsha Nagrani, Paul Hongsuck Seo, Bryan Seybold, Anja Hauth, Santiago Manen, Chen Sun, Cordelia Schmid</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.00679)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Faa1b722485106c84e52c5e35b2d4b2f8c7fb3135%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Learning-Audio-Video-Modalities-from-Image-Captions-Nagrani-Seo/aa1b722485106c84e52c5e35b2d4b2f8c7fb3135)
[![Code](https://img.shields.io/github/stars/OpenGVLab/InternVideo.svg?style=social&label=Star)](https://github.com/google-research-datasets/videoCC-data)

+ **CelebV-Text: A Large-Scale Facial Text-Video Dataset** (26 Mar 2023)<details><summary>Jianhui Yu, Hao Zhu, Liming Jiang, et al. [CVPR 2023]</summary>Jianhui Yu, Hao Zhu, Liming Jiang, Chen Change Loy, Weidong Cai, Wayne Wu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14717)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F484d2194ce8459bfa9da906e556f63812c6ca999%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/CelebV-Text%3A-A-Large-Scale-Facial-Text-Video-Yu-Zhu/484d2194ce8459bfa9da906e556f63812c6ca999)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://celebv-text.github.io/)
[![Code](https://img.shields.io/github/stars/CelebV-Text/CelebV-Text.svg?style=social&label=Star)](https://github.com/CelebV-Text/CelebV-Text)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://www.youtube.com/watch?v=0TS1hQwjNWw)

+ **[HD-VILA-100M] Advancing High-Resolution Video-Language Representation
with Large-Scale Video Transcriptions** (19 Nov 2021)<details><summary>Hongwei Xue, Tiankai Hang, Yanhong Zeng, et al. [CVPR 2022]</summary>Hongwei Xue, Tiankai Hang, Yanhong Zeng, Yuchong Sun, Bei Liu, Huan Yang, Jianlong Fu, Baining Guo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2111.10337)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe1a3e6856b6ac6af3600b5954392e5368603fd1b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Advancing-High-Resolution-Video-Language-with-Video-Xue-Hang/e1a3e6856b6ac6af3600b5954392e5368603fd1b)
[![Code](https://img.shields.io/github/stars/microsoft/XPretrain.svg?style=social&label=Star)](https://github.com/microsoft/XPretrain/blob/main/hd-vila-100m/README.md)

+ **[YT-Temporal-180M] MERLOT: Multimodal Neural Script Knowledge Models** (4 Jun 2021)<details><summary>Rowan Zellers, Ximing Lu, Jack Hessel, et al. [NeurIPS 2021]</summary>Rowan Zellers, Ximing Lu, Jack Hessel, Youngjae Yu, Jae Sung Park, Jize Cao, Ali Farhadi, Yejin Choi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2106.02636)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F90357a6dc817e2f7cec477a51156675fbf545cf1%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MERLOT%3A-Multimodal-Neural-Script-Knowledge-Models-Zellers-Lu/90357a6dc817e2f7cec477a51156675fbf545cf1)
[![Code](https://img.shields.io/github/stars/rowanz/merlot.svg?style=social&label=Star)](https://github.com/rowanz/merlot)

+ **[WebVid-10M] Frozen in Time: A Joint Video and Image Encoder for End-to-End Retrieval** (1 Apr 2021)<details><summary>Max Bain, Arsha Nagrani, Gül Varol, et al. [ICCV 2021]</summary>Max Bain, Arsha Nagrani, Gül Varol, Andrew Zisserman</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2104.00650)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbac87bdb1cabc35fafb8176a234d332ebcc02864%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Frozen-in-Time%3A-A-Joint-Video-and-Image-Encoder-for-Bain-Nagrani/bac87bdb1cabc35fafb8176a234d332ebcc02864)

+ **[WTS70M] Learning Video Representations from Textual Web Supervision** (29 Jul 2020)<details><summary>Jonathan C. Stroud, Zhichao Lu, Chen Sun, et al.</summary>Jonathan C. Stroud, Zhichao Lu, Chen Sun, Jia Deng, Rahul Sukthankar, Cordelia Schmid, David A. Ross</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2007.14937)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fda55208bc9b56b5f394c242239d8cd0734bd5a87%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Learning-Video-Representations-from-Textual-Web-Stroud-Ross/da55208bc9b56b5f394c242239d8cd0734bd5a87)

+ **HowTo100M: Learning a Text-Video Embedding by Watching Hundred Million Narrated Video Clips** (7 Jun 2019)<details><summary>Antoine Miech, Dimitri Zhukov, Jean-Baptiste Alayrac, et al. [ICCV 2019]</summary>Antoine Miech, Dimitri Zhukov, Jean-Baptiste Alayrac, Makarand Tapaswi, Ivan Laptev, Josef Sivic</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1906.03327)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9311779489e597315488749ee6c386bfa3f3512e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/HowTo100M%3A-Learning-a-Text-Video-Embedding-by-Video-Miech-Zhukov/9311779489e597315488749ee6c386bfa3f3512e)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.di.ens.fr/willow/research/howto100m/)
[![Code](https://img.shields.io/github/stars/antoine77340/howto100m.svg?style=social&label=Star)](https://github.com/antoine77340/howto100m?tab=readme-ov-file)

+ **VATEX: A Large-Scale, High-Quality Multilingual Dataset for Video-and-Language Research** (6 Apr 2019)<details><summary>Xin Wang, Jiawei Wu, Junkun Chen, et al. [ICCV 2019 Oral]</summary>Xin Wang, Jiawei Wu, Junkun Chen, Lei Li, Yuan-Fang Wang, William Yang Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1904.03493)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F28b74bb7c8b08cceb2430ec2d54dfa0f3225d796%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VaTeX%3A-A-Large-Scale%2C-High-Quality-Multilingual-for-Wang-Wu/28b74bb7c8b08cceb2430ec2d54dfa0f3225d796)

+ **How2: A Large-scale Dataset for Multimodal Language Understanding** (7 Jun 2019)<details><summary>Ramon Sanabria, Ozan Caglayan, Shruti Palaskar, et al. [NeurIPS 2018]</summary>Ramon Sanabria, Ozan Caglayan, Shruti Palaskar, Desmond Elliott, Loïc Barrault, Lucia Specia, Florian Metze</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1811.00347)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff56cb5dc32b5b280546998418fda7769d0858629%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/How2%3A-A-Large-scale-Dataset-for-Multimodal-Language-Sanabria-Caglayan/f56cb5dc32b5b280546998418fda7769d0858629)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://srvk.github.io/how2-dataset/)
[![Code](https://img.shields.io/github/stars/srvk/how2-dataset.svg?style=social&label=Star)](https://github.com/srvk/how2-dataset)

+ **[ActivityNet Captions] Dense-Captioning Events in Videos** (2 May 2017)<details><summary>Ranjay Krishna, Kenji Hata, Frederic Ren, et al. [ICCV 2017]</summary>Ranjay Krishna, Kenji Hata, Frederic Ren, Li Fei-Fei, Juan Carlos Niebles</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1705.00754)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F96dd1fc39a368d23291816d57763bc6eb4f7b8d6%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Dense-Captioning-Events-in-Videos-Krishna-Hata/96dd1fc39a368d23291816d57763bc6eb4f7b8d6)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cs.stanford.edu/people/ranjaykrishna/densevid/)

+ **[LSMDC] Movie Description** (12 May 2016)<details><summary>Anna Rohrbach, Atousa Torabi, Marcus Rohrbach, et al. [IJCV 2017]</summary>Anna Rohrbach, Atousa Torabi, Marcus Rohrbach, Niket Tandon, Christopher Pal, Hugo Larochelle, Aaron Courville, Bernt Schiele</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1605.03705)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F154c22ca5eef149aedc8a986fa684ca1fd14e7dc%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Movie-Description-Rohrbach-Torabi/154c22ca5eef149aedc8a986fa684ca1fd14e7dc)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/vision-and-language/mpii-movie-description-dataset)


+ **MSR-VTT: A Large Video Description Dataset for Bridging Video and Language** (1 Apr 2021)<details><summary>Jun Xu , Tao Mei , Ting Yao, et al. [CVPR 2016]</summary>Jun Xu , Tao Mei , Ting Yao and Yong Rui</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2016/papers/Xu_MSR-VTT_A_Large_CVPR_2016_paper.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb8e2e9f3ba008e28257195ec69a00e07f260131d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MSR-VTT%3A-A-Large-Video-Description-Dataset-for-and-Xu-Mei/b8e2e9f3ba008e28257195ec69a00e07f260131d)
[![Code](https://img.shields.io/github/stars/crux82/msr-vtt-it.svg?style=social&label=Star)](https://github.com/crux82/msr-vtt-it)





## 3D Generation

### 🔅 LLM-based
+ **SceneCraft: An LLM Agent for Synthesizing 3D Scene as Blender Code** (2 Mar 2024)<details><summary>Ziniu Hu, Ahmet Iscen, Aashi Jain, et al. </summary>Ziniu Hu, Ahmet Iscen, Aashi Jain, Thomas Kipf, Yisong Yue, David A. Ross, Cordelia Schmid, Alireza Fathi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.01248v1)


+ **MotionScript: Natural Language Descriptions for Expressive 3D Human Motions** (19 Dec 2023)<details><summary>Payam Jome Yazdian, Eric Liu, Li Cheng, et al. </summary>Payam Jome Yazdian, Eric Liu, Li Cheng, Angelica Lim</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.12634)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F816792e66f463be2aa1888e4ecb51f8fb2b4dd79%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MotionScript%3A-Natural-Language-Descriptions-for-3D-Yazdian-Liu/816792e66f463be2aa1888e4ecb51f8fb2b4dd79)

+ **HOLODECK: Language Guided Generation of 3D Embodied AI Environments** (19 Dec 2023)<details><summary>Yue Yang, Fan-Yun Sun, Luca Weihs, et al. </summary>Yue Yang, Fan-Yun Sun, Luca Weihs, Eli VanderBilt, Alvaro Herrasti, Winson Han, Jiajun Wu, Nick Haber, Ranjay Krishna, Lingjie Liu, Chris Callison-Burch, Mark Yatskar, Aniruddha Kembhavi, Christopher Clark</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09067)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1dbc2cdcae3e17c3d721d12a5a2d98ced727681a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Holodeck%3A-Language-Guided-Generation-of-3D-Embodied-Yang-Sun/1dbc2cdcae3e17c3d721d12a5a2d98ced727681a)
[![Code](https://img.shields.io/github/stars/allenai/Holodeck.svg?style=social&label=Star)](https://github.com/allenai/Holodeck)

+ **PoseGPT: Chatting about 3D Human Pose** (30 Nov 2023)<details><summary>Yao Feng, Jing Lin, Sai Kumar Dwivedi, et al. </summary>Yao Feng, Jing Lin, Sai Kumar Dwivedi, Yu Sun, Priyanka Patel, Michael J. Black</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18836)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4673c2ac4abb4b055da87171231acb60801ffe74%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/PoseGPT%3A-Chatting-about-3D-Human-Pose-Feng-Lin/4673c2ac4abb4b055da87171231acb60801ffe74)
[![Code](https://img.shields.io/github/stars/yfeng95/PoseGPT.svg?style=social&label=Star)](https://github.com/yfeng95/PoseGPT)

+ **ShapeGPT: 3D Shape Generation with A Unified Multi-modal Language Model** (1 Dec 2023)<details><summary>Fukun Yin, Xin Chen, Chi Zhang, et al. </summary>Fukun Yin, Xin Chen, Chi Zhang, Biao Jiang, Zibo Zhao, Jiayuan Fan, Gang Yu, Taihao Li, Tao Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17618)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5a185965ad1e87367d044b47043706d00b85b007%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ShapeGPT%3A-3D-Shape-Generation-with-A-Unified-Model-Yin-Chen/09157a8c0e7d7263ac035690118ddcbe295cee5c)
[![Code](https://img.shields.io/github/stars/OpenShapeLab/ShapeGPT.svg?style=social&label=Star)](https://github.com/OpenShapeLab/ShapeGPT)

+ **MotionGPT: Human Motion as a Foreign Language** (20 Jul 2023 )<details><summary>Biao Jiang, Xin Chen, Wen Liu, et al. </summary>Biao Jiang, Xin Chen, Wen Liu, Jingyi Yu, Gang Yu, Tao Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.14795)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd212fa27f5868f0fd106e1a7bba908fd47da0816%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MotionGPT%3A-Human-Motion-as-a-Foreign-Language-Jiang-Chen/d212fa27f5868f0fd106e1a7bba908fd47da0816)
[![Code](https://img.shields.io/github/stars/OpenMotionLab/MotionGPT.svg?style=social&label=Star)](https://github.com/OpenMotionLab/MotionGPT)

+ **3D-GPT: Procedural 3D MODELING WITH LARGE LANGUAGE MODELS** (19 Oct 2023)<details><summary>Chunyi Sun*, Junlin Han*, Weijian Deng, et al. </summary>Chunyi Sun, Junlin Han, Weijian Deng, Xinlong Wang, Zishan Qin, Stephen Gould</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.12945)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F588930cdd801f335b5e524d13f99aa94136a20a0%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/3D-GPT%3A-Procedural-3D-Modeling-with-Large-Language-Sun-Han/588930cdd801f335b5e524d13f99aa94136a20a0)
[![Code](https://img.shields.io/github/stars/Chuny1/3DGPT.svg?style=social&label=Star)](https://github.com/Chuny1/3DGPT)




### Non-LLM-based (Clip/T5)
+ **DreamPropeller: Supercharge Text-to-3D Generation with Parallel Sampling** (28 Nov 2023)<details><summary>Linqi Zhou, Andy Shih, Chenlin Meng, et al. </summary>Linqi Zhou, Andy Shih, Chenlin Meng, Stefano Ermon</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17082)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe88d5399956c9d9519a5cfd49308b7d439167543%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DreamPropeller%3A-Supercharge-Text-to-3D-Generation-Zhou-Shih/e88d5399956c9d9519a5cfd49308b7d439167543)
[![Code](https://img.shields.io/github/stars/alexzhou907/DreamPropeller.svg?style=social&label=Star)](https://github.com/alexzhou907/DreamPropeller)

+ **HiFA: High-fidelity Text-to-3D Generation with Advanced Diffusion Guidance** (28 Nov 2023)<details><summary>[ICLR 2024] Junzhe Zhu, Peiye Zhuang. </summary>Junzhe Zhu, Peiye Zhuang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18766)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdaf3b117f789b2b95223e58592979fb57627515e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/HiFA%3A-High-fidelity-Text-to-3D-Generation-with-Zhu-Zhuang/daf3b117f789b2b95223e58592979fb57627515e)
[![Code](https://img.shields.io/github/stars/JunzheJosephZhu/HiFA.svg?style=social&label=Star)](https://github.com/JunzheJosephZhu/HiFA)

+ **ATT3D: Amortized Text-to-3D Object Synthesis** (6 Jun 2023)<details><summary>Jonathan Lorraine, Kevin Xie, Xiaohui Zeng, et al. ICCV 2023 </summary>Jonathan Lorraine, Kevin Xie, Xiaohui Zeng, Chen-Hsuan Lin, Towaki Takikawa, Nicholas Sharp, Tsung-Yi Lin, Ming-Yu Liu, Sanja Fidler, James Lucas</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.07349)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1e8403af2e1e7a8f803d8df9e8daac584f99c2a0%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ATT3D%3A-Amortized-Text-to-3D-Object-Synthesis-Lorraine-Xie/1e8403af2e1e7a8f803d8df9e8daac584f99c2a0)

+ **SweetDreamer: Aligning Geometric Priors in 2D Diffusion for Consistent Text-to-3D** (20 Oct 2023 )<details><summary>Weiyu Li, Rui Chen, Xuelin Chen, et al.</summary>Weiyu Li, Rui Chen, Xuelin Chen, Ping Tan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.02596)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F438e9fb79c9e37d43223e61bb575ebd2dae0b0a7%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/SweetDreamer%3A-Aligning-Geometric-Priors-in-2D-for-Li-Chen/438e9fb79c9e37d43223e61bb575ebd2dae0b0a7)
[![Code](https://img.shields.io/github/stars/wyysf-98/SweetDreamer.svg?style=social&label=Star)](https://github.com/wyysf-98/SweetDreamer)

+ **Text-to-3D with Classifier Score Distillation** (26 Oct 2023 )<details><summary>[ICLR 2024] Xin Yu, Yuan-Chen Guo, Yangguang Li, et al. </summary>Xin Yu, Yuan-Chen Guo, Yangguang Li, Ding Liang, Song-Hai Zhang, Xiaojuan Qi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.19415)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4e21879b564cc2e803b16edf0dda9f1edb91b497%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Text-to-3D-with-Classifier-Score-Distillation-Yu-Guo/4e21879b564cc2e803b16edf0dda9f1edb91b497)
[![Code](https://img.shields.io/github/stars/CVMI-Lab/Classifier-Score-Distillation.svg?style=social&label=Star)](https://github.com/CVMI-Lab/Classifier-Score-Distillation)

+ **LucidDreamer: Towards High-Fidelity Text-to-3D Generation via Interval Score Matching** (2 Dec 2023)<details><summary>Yixun Liang, Xin Yang, Jiantao Lin, et al. (CVPR 2024) </summary>Yixun Liang, Xin Yang, Jiantao Lin, Haodong Li, Xiaogang Xu, Yingcong Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11284)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6f709278506813d04a074e6fa20188cce9bb927b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LucidDreamer%3A-Towards-High-Fidelity-Text-to-3D-via-Liang-Yang/6f709278506813d04a074e6fa20188cce9bb927b)
[![Code](https://img.shields.io/github/stars/EnVision-Research/LucidDreamer.svg?style=social&label=Star)](https://github.com/EnVision-Research/LucidDreamer)


+ **Noise-Free Score Distillation** (26 Oct 2023)<details><summary>[ICLR 2024] Oren Katzir, Or Patashnik, Daniel Cohen-Or, et al.</summary>Oren Katzir, Or Patashnik, Daniel Cohen-Or, Dani Lischinski</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.17590)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F85a70c0a048cba4f53dcf332ee73f6032a2e53bc%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Noise-Free-Score-Distillation-Katzir-Patashnik/85a70c0a048cba4f53dcf332ee73f6032a2e53bc)
[![Code](https://img.shields.io/github/stars/orenkatzir/nfsd.svg?style=social&label=Star)](https://github.com/orenkatzir/nfsd)


+ **DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation** (28 Sep 2023)<details><summary>[ICLR 2024] Jiaxiang Tang, Jiawei Ren, Hang Zhou, et al.</summary>Jiaxiang Tang, Jiawei Ren, Hang Zhou, Ziwei Liu, Gang Zeng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.16653)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fcc1a674bb164d09a060cf5b26fe518c02fae0ddc%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DreamGaussian%3A-Generative-Gaussian-Splatting-for-3D-Tang-Ren/cc1a674bb164d09a060cf5b26fe518c02fae0ddc)
[![Code](https://img.shields.io/github/stars/dreamgaussian/dreamgaussian.svg?style=social&label=Star)](https://github.com/dreamgaussian/dreamgaussian)

+ **GaussianDreamer: Fast Generation from Text to 3D Gaussians by Bridging 2D and 3D Diffusion Models** (12 Oct 2023 )<details><summary>Taoran Yi, Jiemin Fang, Junjie Wang, et al. (CVPR 2024) </summary>Taoran Yi, Jiemin Fang, Junjie Wang, Guanjun Wu, Lingxi Xie, Xiaopeng Zhang, Wenyu Liu, Qi Tian, Xinggang Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08529)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc5e9fd131cde68c218d0ea69cd617a67c7f35d42%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ProlificDreamer%3A-High-Fidelity-and-Diverse-with-Wang-Lu/c5e9fd131cde68c218d0ea69cd617a67c7f35d42)
[![Code](https://img.shields.io/github/stars/hustvl/GaussianDreamer.svg?style=social&label=Star)](https://github.com/hustvl/GaussianDreamer)

+ **Text2Room: Extracting Textured 3D Meshes from 2D Text-to-Image Models** (10 Sep 2023)<details><summary>Lukas Höllein, Ang Cao, Andrew Owens, et al. (ICCV 2023) </summary>Lukas Höllein, Ang Cao, Andrew Owens, Justin Johnson, Matthias Nießner</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.11989)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F95aa6fa4e42387561cff22378348d528adea37f2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Text2Room%3A-Extracting-Textured-3D-Meshes-from-2D-H%C3%B6llein-Cao/95aa6fa4e42387561cff22378348d528adea37f2)
[![Code](https://img.shields.io/github/stars/lukasHoel/text2room.svg?style=social&label=Star)](https://github.com/lukasHoel/text2room)

+ **ProlificDreamer: High-Fidelity and Diverse Text-to-3D Generation with Variational Score Distillation** (25 May 2023)<details><summary>Zhengyi Wang, Cheng Lu, Yikai Wang, et al. (NeurIPS 2023 Spotlight) </summary>Zhengyi Wang, Cheng Lu, Yikai Wang, Fan Bao, Chongxuan Li, Hang Su, Jun Zhu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13873)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc5e9fd131cde68c218d0ea69cd617a67c7f35d42%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ProlificDreamer%3A-High-Fidelity-and-Diverse-with-Wang-Lu/c5e9fd131cde68c218d0ea69cd617a67c7f35d42)
[![Code](https://img.shields.io/github/stars/KU-CVLAB/3DFuse-threestudio.svg?style=social&label=Star)](https://github.com/KU-CVLAB/3DFuse-threestudio)

+ **Fantasia3D: Disentangling Geometry and Appearance for High-quality Text-to-3D Content Creation** (24 Mar 2023)<details><summary>Rui Chen, Yongwei Chen, Ningxin Jiao, et al. (ICCV 2023) </summary>Rui Chen, Yongwei Chen, Ningxin Jiao, Kui Jia</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13873)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0cbb518c364067200476a51e5ce7476a4f582770%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Fantasia3D%3A-Disentangling-Geometry-and-Appearance-Chen-Chen/0cbb518c364067200476a51e5ce7476a4f582770)
[![Code](https://img.shields.io/github/stars/Gorilla-Lab-SCUT/Fantasia3D.svg?style=social&label=Star)](https://github.com/Gorilla-Lab-SCUT/Fantasia3D)

+ **Re-imagine the Negative Prompt Algorithm: Transform 2D Diffusion into 3D, alleviate Janus problem and Beyond** (11 Apr 2023)<details><summary>Mohammadreza Armandpour, Ali Sadeghian, Huangjie Zheng, et al. </summary>Mohammadreza Armandpour, Ali Sadeghian, Huangjie Zheng, Amir Sadeghian, Mingyuan Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.04968)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb19ca192a5bebbc3473be61989baf085ff21daa5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Re-imagine-the-Negative-Prompt-Algorithm%3A-Transform-Armandpour-Sadeghian/b19ca192a5bebbc3473be61989baf085ff21daa5)
[![Code](https://img.shields.io/github/stars/Perp-Neg/Perp-Neg-stablediffusion.svg?style=social&label=Star)](https://github.com/Perp-Neg/Perp-Neg-stablediffusion)

+ **Let 2D Diffusion Model Know 3D-Consistency for Robust Text-to-3D Generation** (11 Apr 2023)<details><summary>[ICLR 2024] Junyoung Seo, Wooseok Jang, Min-Seop Kwak, et al.</summary>Junyoung Seo, Wooseok Jang, Min-Seop Kwak, Hyeonsu Kim, Jaehoon Ko, Junho Kim, Jin-Hwa Kim, Jiyoung Lee, Seungryong Kim</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.07937)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5356c3dac654854a0842753bcc2e3433dc4a2afd%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Let-2D-Diffusion-Model-Know-3D-Consistency-for-Seo-Jang/5356c3dac654854a0842753bcc2e3433dc4a2afd)
[![Code](https://img.shields.io/github/stars/eladrich/latent-nerf.svg?style=social&label=Star)](https://github.com/eladrich/latent-nerf)

+ **Latent-NeRF for Shape-Guided Generation of 3D Shapes and Textures** (14 Nov 2022)<details><summary>Gal Metzer, Elad Richardson, Or Patashnik, et al. (CVPR 2023) </summary>Gal Metzer, Elad Richardson, Or Patashnik, Raja Giryes, Daniel Cohen-Or</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.07600)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F793939b83e10903f58d8edbb7534963df627a1fe%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Latent-NeRF-for-Shape-Guided-Generation-of-3D-and-Metzer-Richardson/793939b83e10903f58d8edbb7534963df627a1fe)
[![Code](https://img.shields.io/github/stars/eladrich/latent-nerf.svg?style=social&label=Star)](https://github.com/eladrich/latent-nerf)

+ **Magic3D: High-Resolution Text-to-3D Content Creation** (18 Nov 2022)<details><summary>Chen-Hsuan Lin, Jun Gao, Luming Tang, et al. (CVPR2023 HighLight) </summary>Chen-Hsuan Lin, Jun Gao, Luming Tang, Towaki Takikawa, Xiaohui Zeng, Xun Huang, Karsten Kreis, Sanja Fidler, Ming-Yu Liu, Tsung-Yi Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2023/papers/Lin_Magic3D_High-Resolution_Text-to-3D_Content_Creation_CVPR_2023_paper.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbdf4af8311637c681904e71cf50f96fd0026f578%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Magic3D%3A-High-Resolution-Text-to-3D-Content-Lin-Gao/bdf4af8311637c681904e71cf50f96fd0026f578)

+ **Score Jacobian Chaining: Lifting Pretrained 2D Diffusion Models for 3D Generation** (1 Dec 2022)<details><summary>Haochen Wang, Xiaodan Du, Jiahao Li, et al. (CVPR2023) </summary>Haochen Wang, Xiaodan Du, Jiahao Li, Raymond A. Yeh, Greg Shakhnarovich</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.00774)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ffc011ed5ee986332523a62d2783adee1179dc1ed%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Score-Jacobian-Chaining%3A-Lifting-Pretrained-2D-for-Wang-Du/fc011ed5ee986332523a62d2783adee1179dc1ed)
[![Code](https://img.shields.io/github/stars/pals-ttic/sjc.svg?style=social&label=Star)](https://github.com/pals-ttic/sjc)

+ **DreamFusion: Text-to-3D using 2D Diffusion** (29 Sep 2022)<details><summary>[ICLR 2023 Oral]Ben Poole, Ajay Jain, Jonathan T. Barron, et al.</summary>Ben Poole, Ajay Jain, Jonathan T. Barron, Ben Mildenhall</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.14988)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4c94d04afa4309ec2f06bdd0fe3781f91461b362%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DreamFusion%3A-Text-to-3D-using-2D-Diffusion-Poole-Jain/4c94d04afa4309ec2f06bdd0fe3781f91461b362)

+ **Clip-forge: Towards zero-shot text-to-shape generation** (28 Apr 2022)<details><summary>Aditya Sanghi, Hang Chu, Joseph G. Lambourne, et al. (CVPR 2022) </summary>Aditya Sanghi, Hang Chu, Joseph G. Lambourne, Ye Wang, Chin-Yi Cheng, Marco Fumero, Kamal Rahimi Malekshan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2110.02624)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F738e3e0623054da29dc57fc6aee5e6711867c4e8%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/CLIP-Forge%3A-Towards-Zero-Shot-Text-to-Shape-Sanghi-Chu/738e3e0623054da29dc57fc6aee5e6711867c4e8)
[![Code](https://img.shields.io/github/stars/AutodeskAILab/Clip-Forge.svg?style=social&label=Star)](https://github.com/AutodeskAILab/Clip-Forge)

+ **Zero-Shot Text-Guided Object Generation with Dream Fields** (2 Dec 2021) <details><summary>Ajay Jain, Ben Mildenhall, Jonathan T. Barron, et al. (CVPR2022)</summary>Ajay Jain, Ben Mildenhall, Jonathan T. Barron, Pieter Abbeel, Ben Poole</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.01455)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2c6392491b6a942e08db46c8fff0ef5ba1fd9de8%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Zero-Shot-Text-Guided-Object-Generation-with-Dream-Jain-Mildenhall/03e1c3b5fdad9b21bbed3d13af7e8d6c73cbcfa6)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ajayj.com/dreamfields)
[![Code](https://img.shields.io/github/stars/google-research/google-research.svg?style=social&label=Star)](https://github.com/google-research/google-research/)

+ **X-Mesh: Towards Fast and Accurate Text-driven 3D Stylization via Dynamic Textual Guidance** (28 Mar 2023) <details><summary>Yiwei Ma, Xiaioqing Zhang, Xiaoshuai Sun, et al. (ICCV 2023)</summary>Yiwei Ma, Xiaioqing Zhang, Xiaoshuai Sun, Jiayi Ji, Haowei Wang, Guannan Jiang, Weilin Zhuang, Rongrong Ji</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.15764)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff8bf2225a2993e3ead73d886b5797378d6e53186%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/X-Mesh%3A-Towards-Fast-and-Accurate-Text-driven-3D-Ma-Zhang/f8bf2225a2993e3ead73d886b5797378d6e53186)
[![Code](https://img.shields.io/github/stars/xmu-xiaoma666/X-Mesh.svg?style=social&label=Star)](https://github.com/xmu-xiaoma666/X-Mesh)

+ **TextMesh: Generation of Realistic 3D Meshes From Text Prompts** (24 Apr 2023) <details><summary>Christina Tsalicoglou, Fabian Manhardt, Alessio Tonioni, et al. (3DV 2023)</summary>Christina Tsalicoglou, Fabian Manhardt, Alessio Tonioni, Michael Niemeyer, Federico Tombari</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.12439)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd15b27edf3630728cdb40f49946365d9011641cf%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/TextMesh%3A-Generation-of-Realistic-3D-Meshes-From-Tsalicoglou-Manhardt/2c6392491b6a942e08db46c8fff0ef5ba1fd9de8)
[![Code](https://img.shields.io/github/stars/threestudio-project/threestudio.svg?style=social&label=Star)](https://github.com/threestudio-project/threestudio)

+ **Text2Mesh: Text-Driven Neural Stylization for Meshes** (6 Dec 2021) <details><summary>Oscar Michel, Roi Bar-On, Richard Liu, et al. (CVPR 2022) </summary>Oscar Michel, Roi Bar-On, Richard Liu, Sagie Benaim, Rana Hanocka</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2110.02624)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd15b27edf3630728cdb40f49946365d9011641cf%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Text2Mesh%3A-Text-Driven-Neural-Stylization-for-Michel-Bar-On/d15b27edf3630728cdb40f49946365d9011641cf)
[![Code](https://img.shields.io/github/stars/threedle/text2mesh.svg?style=social&label=Star)](https://github.com/threedle/text2mesh)

+ **TANGO: Text-driven Photorealistic and Robust 3D Stylization via Lighting Decomposition** (20 Oct 2022) <details><summary>Yongwei Chen, Rui Chen, Jiabao Lei, et al. (NeurIPS 2022 Spotlight) </summary>Yongwei Chen, Rui Chen, Jiabao Lei, Yabin Zhang, Kui Jia</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.11277)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F44e49f72fb6b97f52c25a30f0adc68c2384430ba%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/TANGO%3A-Text-driven-Photorealistic-and-Robust-3D-via-Chen-Chen/44e49f72fb6b97f52c25a30f0adc68c2384430ba)
[![Code](https://img.shields.io/github/stars/Gorilla-Lab-SCUT/tango.svg?style=social&label=Star)](https://github.com/Gorilla-Lab-SCUT/tango)

+ **CLIP-Mesh: Generating textured meshes from text using pretrained image-text models** (24 Mar 2022) <details><summary>Nasir Mohammad Khalid, Tianhao Xie, Eugene Belilovsky, et al. (SIGGRAPH ASIA 2022) </summary>Nasir Mohammad Khalid, Tianhao Xie, Eugene Belilovsky, Tiberiu Popa</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.13333)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8941e477b2f39eb92712f04400412da60d349ec1%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/CLIP-Mesh%3A-Generating-textured-meshes-from-text-Khalid-Xie/8941e477b2f39eb92712f04400412da60d349ec1)
[![Code](https://img.shields.io/github/stars/NasirKhalid24/CLIP-Mesh.svg?style=social&label=Star)](https://github.com/NasirKhalid24/CLIP-Mesh)

+ **MotionCLIP: Exposing Human Motion Generation to CLIP Space** (15 Mar 2022) <details><summary>Guy Tevet, Brian Gordon, Amir Hertz, et al. (ECCV 2022) </summary>Guy Tevet, Brian Gordon, Amir Hertz, Amit H. Bermano, Daniel Cohen-Or</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.08063)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe82df4b6a3628501fce67835ad8316d6525ad133%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MotionCLIP%3A-Exposing-Human-Motion-Generation-to-Tevet-Gordon/e82df4b6a3628501fce67835ad8316d6525ad133)
[![Code](https://img.shields.io/github/stars/GuyTevet/MotionCLIP.svg?style=social&label=Star)](https://github.com/GuyTevet/MotionCLIP)

  
### Datasets



## Audio Generation

### 🔅 LLM-based

+ **Diffsound: Discrete Diffusion Model for Text-to-sound Generation** (Wed, 20 Jul 2022)<details><summary>Dongchao Yang, Jianwei Yu, Helin Wang, et al. (TASLP2022)</summary>Dongchao Yang, Jianwei Yu, Helin Wang, Wen Wang, Chao Weng, Yuexian Zou, Dong Yu</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2207.09983)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc036f75da24ba64a583e0b6d41c5b792347bffa6%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Diffsound%3A-Discrete-Diffusion-Model-for-Generation-Yang-Yu/c036f75da24ba64a583e0b6d41c5b792347bffa6)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dongchaoyang.top/text-to-sound-synthesis-demo/)
[![Code](https://img.shields.io/github/stars/yangdongchao/Text-to-sound-Synthesis.svg?style=social&label=Star)](https://github.com/yangdongchao/Text-to-sound-Synthesis)

+ **Riffusion: Stable diffusion for real-time music generation** (2022)\
Forsgren, Seth and Martiros, Hayk\
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.riffusion.com/)

+ **MusicLM: Generating Music From Text** (26 Jan 2023)<details><summary>Andrea Agostinelli, Timo I. Denk, Zalán Borsos, et al.</summary>Andrea Agostinelli, Timo I. Denk, Zalán Borsos, Jesse Engel, Mauro Verzetti, Antoine Caillon, Qingqing Huang, Aren Jansen, Adam Roberts, Marco Tagliasacchi, Matt Sharifi, Neil Zeghidour, Christian Frank</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.11325)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F428854d9e75f94f0e61f37c6887c77800437d516%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MusicLM%3A-Generating-Music-From-Text-Agostinelli-Denk/428854d9e75f94f0e61f37c6887c77800437d516)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://google-research.github.io/seanet/musiclm/examples/)

+ **Moûsai: Text-to-Music Generation with Long-Context Latent Diffusion** (27 Jan 2023)<details><summary>Flavio Schneider, Ojasv Kamal, Zhijing Jin, et al.</summary>Flavio Schneider, Ojasv Kamal, Zhijing Jin, Bernhard Schölkopf</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.11757)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc5eb040156adf687d7b9a97b3b16f6f243a1a514%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Mo%5C%5Eusai%3A-Text-to-Music-Generation-with-Latent-Schneider-Kamal/c5eb040156adf687d7b9a97b3b16f6f243a1a514)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://diligent-pansy-4cb.notion.site/Music-Generation-with-Diffusion-ebe6e9e528984fa1b226d408f6002d87)
[![Code](https://img.shields.io/github/stars/archinetai/audio-diffusion-pytorch.svg?style=social&label=Star)](https://github.com/archinetai/audio-diffusion-pytorch)

+ **Audioldm: Text-to-audio generation with latent diffusion models** (29 Jan 2023)<details><summary>Haohe Liu, Zehua Chen, Yi Yuan, et al.</summary>Haohe Liu, Zehua Chen, Yi Yuan, Xinhao Mei, Xubo Liu, Danilo Mandic, Wenwu Wang, Mark D. Plumbley</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.12503)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ffa0f3d8aa20e8987dbc7a516d5399cfa3dc97b1b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/AudioLDM%3A-Text-to-Audio-Generation-with-Latent-Liu-Chen/fa0f3d8aa20e8987dbc7a516d5399cfa3dc97b1b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://audioldm.github.io)
[![Code](https://img.shields.io/github/stars/haoheliu/audioldm2.svg?style=social&label=Star)](https://github.com/haoheliu/audioldm2)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/haoheliu/audioldm-text-to-audio-generation)

+ **Make-an-audio: Text-to-audio generation with prompt-enhanced diffusion models** (30 Jan 2023)<details><summary>Rongjie Huang, Jiawei Huang, Dongchao Yang, et al.</summary>Rongjie Huang, Jiawei Huang, Dongchao Yang, Yi Ren, Luping Liu, Mingze Li, Zhenhui Ye, Jinglin Liu, Xiang Yin, Zhou Zhao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.12661)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6d1433f3342fbee85ad1e2809e62734aec5c3853%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Make-An-Audio%3A-Text-To-Audio-Generation-with-Models-Huang-Huang/6d1433f3342fbee85ad1e2809e62734aec5c3853)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://text-to-audio.github.io/)
[![Code](https://img.shields.io/github/stars/Text-to-Audio/Make-An-Audio.svg?style=social&label=Star)](https://github.com/Text-to-Audio/Make-An-Audio)

+ **Noise2music: Text-conditioned music generation with diffusion models** (8 Feb 2023)<details><summary>Qingqing Huang, Daniel S. Park, Tao Wang, et al.</summary>Qingqing Huang, Daniel S. Park, Tao Wang, Timo I. Denk, Andy Ly, Nanxin Chen, Zhengdong Zhang, Zhishuai Zhang, Jiahui Yu, Christian Frank, Jesse Engel, Quoc V. Le, William Chan, Zhifeng Chen, Wei Han</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.03917)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F02540ae926814f4b7972d3fa4dd33932fdc4b58b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Noise2Music%3A-Text-conditioned-Music-Generation-with-Huang-Park/02540ae926814f4b7972d3fa4dd33932fdc4b58b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://google-research.github.io/noise2music/)

+ **Text-to-Audio Generation using Instruction-Tuned LLM and Latent Diffusion Model** (24 Apr 2023)<details><summary>Deepanway Ghosal, Navonil Majumder, Ambuj Mehrish, et al.</summary>Deepanway Ghosal, Navonil Majumder, Ambuj Mehrish, Soujanya Poria</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.13731)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff51bc74814a3452009ea5ca262d9768d08149ee6%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Text-to-Audio-Generation-using-Instruction-Tuned-Ghosal-Majumder/f51bc74814a3452009ea5ca262d9768d08149ee6)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tango-web.github.io/)
[![Code](https://img.shields.io/github/stars/declare-lab/tango.svg?style=social&label=Star)](https://github.com/declare-lab/tango)

+ **Audiogpt: Understanding and generating speech, music, sound, and talking head** (25 Apr 2023)<details><summary>Rongjie Huang, Mingze Li, Dongchao Yang, et al.</summary>Rongjie Huang, Mingze Li, Dongchao Yang, Jiatong Shi, Xuankai Chang, Zhenhui Ye, Yuning Wu, Zhiqing Hong, Jiawei Huang, Jinglin Liu, Yi Ren, Zhou Zhao, Shinji Watanabe</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.12995)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8bc617c9139648d7a92991d70c671230bac7b2e2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/AudioGPT%3A-Understanding-and-Generating-Speech%2C-and-Huang-Li/8bc617c9139648d7a92991d70c671230bac7b2e2)
[![Code](https://img.shields.io/github/stars/AIGC-Audio/AudioGPT.svg?style=social&label=Star)](https://github.com/AIGC-Audio/AudioGPT)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/AIGC-Audio/AudioGPT)

+ **Listen, Think, and Understand** (18 May 2023)<details><summary>Yuan Gong, Hongyin Luo, Alexander H. Liu, et al.</summary>Yuan Gong, Hongyin Luo, Alexander H. Liu, Leonid Karlinsky, James Glass</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10790)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4bb0b12803791764d641a4cef1e0ce39cf049542%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Listen%2C-Think%2C-and-Understand-Gong-Luo/4bb0b12803791764d641a4cef1e0ce39cf049542)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/yuangongfdu/LTU)

+ **Efficient neural music generation** (25 May 2023)<details><summary>Max W. Y. Lam, Qiao Tian, Tang Li, et al.</summary>Max W. Y. Lam, Qiao Tian, Tang Li, Zongyu Yin, Siyuan Feng, Ming Tu, Yuliang Ji, Rui Xia, Mingbo Ma, Xuchen Song, Jitong Chen, Yuping Wang, Yuxuan Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.15719)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F38b93d01e08ab19ada89a40051a1ed4309fbe834%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Efficient-Neural-Music-Generation-Lam-Tian/38b93d01e08ab19ada89a40051a1ed4309fbe834)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://efficient-melody.github.io/)

+ **Make-An-Audio 2: Temporal-Enhanced Text-to-Audio Generation** (29 May 2023)<details><summary>Jiawei Huang, Yi Ren, Rongjie Huang, et al.</summary>Jiawei Huang, Yi Ren, Rongjie Huang, Dongchao Yang, Zhenhui Ye, Chen Zhang, Jinglin Liu, Xiang Yin, Zejun Ma, Zhou Zhao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18474)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F83d4b22d803ae856cf6b308482bd504fa151d39e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Make-An-Audio-2%3A-Temporal-Enhanced-Text-to-Audio-Huang-Ren/83d4b22d803ae856cf6b308482bd504fa151d39e)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://make-an-audio-2.github.io/)

+ **MuseCoco: Generating Symbolic Music from Text** (31 May 2023)<details><summary>Peiling Lu, Xin Xu, Chenfei Kang, et al.</summary>Peiling Lu, Xin Xu, Chenfei Kang, Botao Yu, Chengyi Xing, Xu Tan, Jiang Bian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.00110)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa559acac0e84319d62cefd564a5eecbf9d566ec4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MuseCoco%3A-Generating-Symbolic-Music-from-Text-Lu-Xu/a559acac0e84319d62cefd564a5eecbf9d566ec4)
[![Code](https://img.shields.io/github/stars/microsoft/muzic/tree/main/musecoco.svg?style=social&label=Star)](https://github.com/microsoft/muzic/tree/main/musecoco)

+ **Simple and Controllable Music Generation** (8 Jun 2023)<details><summary>Jade Copet, Felix Kreuk, Itai Gat, et al.</summary>Jade Copet, Felix Kreuk, Itai Gat, Tal Remez, David Kant, Gabriel Synnaeve, Yossi Adi, Alexandre Défossez</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.05284)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4cc8e18f5eece0b0d8e1abcb8ee10fb33680fbb2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Simple-and-Controllable-Music-Generation-Copet-Kreuk/4cc8e18f5eece0b0d8e1abcb8ee10fb33680fbb2)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ai.honu.io/papers/musicgen/)
[![Code](https://img.shields.io/github/stars/facebookresearch/audiocraft.svg?style=social&label=Star)](https://github.com/facebookresearch/audiocraft)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/facebook/MusicGen)

+ **AudioPaLM: A Large Language Model That Can Speak and Listen** (22 Jun 2023)<details><summary>Paul K. Rubenstein, Chulayuth Asawaroengchai, Duc Dung Nguyen, et al.</summary>Paul K. Rubenstein, Chulayuth Asawaroengchai, Duc Dung Nguyen, Ankur Bapna, Zalán Borsos, Félix de Chaumont Quitry, Peter Chen, Dalia El Badawy, Wei Han, Eugene Kharitonov, Hannah Muckenhirn, Dirk Padfield, James Qin, Danny Rozenberg, Tara Sainath, Johan Schalkwyk, Matt Sharifi, Michelle Tadmor Ramanovich, Marco Tagliasacchi, Alexandru Tudor, Mihajlo Velimirović, Damien Vincent, Jiahui Yu, Yongqiang Wang, Vicky Zayats, Neil Zeghidour, Yu Zhang, Zhishuai Zhang, Lukas Zilka, Christian Frank</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.12925)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3efb81de24eb88017d6dbcf22cb4215084223fd8%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/AudioPaLM%3A-A-Large-Language-Model-That-Can-Speak-Rubenstein-Asawaroengchai/3efb81de24eb88017d6dbcf22cb4215084223fd8)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://google-research.github.io/seanet/audiopalm/examples/)

+ **Wavjourney: Compositional audio creation with large language models** (26 Jul 2023)<details><summary>Xubo Liu, Zhongkai Zhu, Haohe Liu, et al.</summary>Xubo Liu, Zhongkai Zhu, Haohe Liu, Yi Yuan, Meng Cui, Qiushi Huang, Jinhua Liang, Yin Cao, Qiuqiang Kong, Mark D. Plumbley, Wenwu Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.14335)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Faa7bcd1f9453c9096ec78900a7b94e816ed0e1c5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/WavJourney%3A-Compositional-Audio-Creation-with-Large-Liu-Zhu/aa7bcd1f9453c9096ec78900a7b94e816ed0e1c5)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://audio-agi.github.io/WavJourney_demopage/)
[![Code](https://img.shields.io/github/stars/Audio-AGI/WavJourney.svg?style=social&label=Star)](https://github.com/Audio-AGI/WavJourney)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Audio-AGI/WavJourney)

+ **MusicLDM: Enhancing Novelty in Text-to-Music Generation Using Beat-Synchronous Mixup Strategies** (3 Aug 2023)<details><summary>Ke Chen, Yusong Wu, Haohe Liu, et al.</summary>Ke Chen, Yusong Wu, Haohe Liu, Marianna Nezhurina, Taylor Berg-Kirkpatrick, Shlomo Dubnov</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.01546)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F464edfd902f652d3ab6a25dbb6d9fa47cc3246a9%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MusicLDM%3A-Enhancing-Novelty-in-Text-to-Music-Using-Chen-Wu/464edfd902f652d3ab6a25dbb6d9fa47cc3246a9)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://musicldm.github.io/)
[![Code](https://img.shields.io/github/stars/RetroCirce/MusicLDM/.svg?style=social&label=Star)](https://github.com/RetroCirce/MusicLDM/)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/ucsd-reach/musicldm)

+ **Jen-1: Text-guided universal music generation with omnidirectional diffusion models** (9 Aug 2023)<details><summary>Peike Li, Boyu Chen, Yao Yao, et al.</summary>Peike Li, Boyu Chen, Yao Yao, Yikai Wang, Allen Wang, Alex Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.04729)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F880bf72f9e2c6a99a759d3be702046e57ce2b423%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/JEN-1%3A-Text-Guided-Universal-Music-Generation-with-Li-Chen/880bf72f9e2c6a99a759d3be702046e57ce2b423)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.futureverse.com/research/jen/demos/jen1)

+ **AudioLDM 2: Learning holistic audio generation with self-supervised pretraining** (10 Aug 2023)<details><summary>Haohe Liu, Qiao Tian, Yi Yuan, et al.</summary>Haohe Liu, Qiao Tian, Yi Yuan, Xubo Liu, Xinhao Mei, Qiuqiang Kong, Yuping Wang, Wenwu Wang, Yuxuan Wang, Mark D. Plumbley</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.05734)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F33de773be1733347a01cb07a5bb1b6cdfa956a47%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/AudioLDM-2%3A-Learning-Holistic-Audio-Generation-with-Liu-Tian/33de773be1733347a01cb07a5bb1b6cdfa956a47)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://audioldm.github.io/audioldm2/)
[![Code](https://img.shields.io/github/stars/haoheliu/audioldm2.svg?style=social&label=Star)](https://github.com/haoheliu/audioldm2)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/haoheliu/audioldm2-text2audio-text2music)

+ **Music understanding LLaMA: Advancing text-to-music generation with question answering and captioning** (22 Aug 2023)<details><summary>Shansong Liu, Atin Sakkeer Hussain, Chenshuo Sun, et al.</summary>Shansong Liu, Atin Sakkeer Hussain, Chenshuo Sun, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.11276)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa33b437618be733fea7176bd98e18b6362af0838%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Music-Understanding-LLaMA%3A-Advancing-Text-to-Music-Liu-Hussain/a33b437618be733fea7176bd98e18b6362af0838)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://crypto-code.github.io/MU-LLaMA-Demo/)
[![Code](https://img.shields.io/github/stars/crypto-code/MU-LLaMA.svg?style=social&label=Star)](https://github.com/crypto-code/MU-LLaMA)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/datasets/mu-llama/MusicQA)

+ **Audiogen: Textually guided audio generation** (30 Sep 2022)<details><summary>[ICLR 2022] Felix Kreuk, Gabriel Synnaeve, Adam Polyak, et al.</summary>Felix Kreuk, Gabriel Synnaeve, Adam Polyak, Uriel Singer, Alexandre Défossez, Jade Copet, Devi Parikh, Yaniv Taigman, Yossi Adi</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.15352)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Febb85974e06c4879b451fdfcb4f472a09471935b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/AudioGen%3A-Textually-Guided-Audio-Generation-Kreuk-Synnaeve/ebb85974e06c4879b451fdfcb4f472a09471935b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://felixkreuk.github.io/audiogen/)

+ **MusicAgent: An AI Agent for Music Understanding and Generation with Large Language Models** (18 Oct 2023)<details><summary>Dingyao Yu, Kaitao Song, Peiling Lu, et al.</summary>Dingyao Yu, Kaitao Song, Peiling Lu, Tianyu He, Xu Tan, Wei Ye, Shikun Zhang, Jiang Bian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.11954)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbeaf64df85f8204b8cd89a7f46827608e6d16922%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MusicAgent%3A-An-AI-Agent-for-Music-Understanding-and-Yu-Song/beaf64df85f8204b8cd89a7f46827608e6d16922)
[![Code](https://img.shields.io/github/stars/microsoft/muzic/tree/main/musicagent.svg?style=social&label=Star)](https://github.com/microsoft/muzic/tree/main/musicagent)

+ **JEN-1 Composer: A Unified Framework for High-Fidelity Multi-Track Music Generation** (29 Oct 2023)<details><summary>Yao Yao, Peike Li, Boyu Chen, et al.</summary>Yao Yao, Peike Li, Boyu Chen, Alex Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.19180)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F53612c6896c680c9113f967d4c2dae908dd10bfe%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/JEN-1-Composer%3A-A-Unified-Framework-for-Multi-Track-Yao-Li/53612c6896c680c9113f967d4c2dae908dd10bfe)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.jenmusic.ai/audio-demos)

+ **Controllable Music Production with Diffusion Models and Guidance Gradients** (1 Nov 2023)<details><summary>Mark Levy, Bruno Di Giorgi, Floris Weers, et al. (NeurIPS 2023)</summary>Mark Levy, Bruno Di Giorgi, Floris Weers, Angelos Katharopoulos, Tom Nickson</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00613)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F87e36f66b0c28ca7a327257ccb00282bdf7fe7d5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Controllable-Music-Production-with-Diffusion-Models-Levy-Giorgi/87e36f66b0c28ca7a327257ccb00282bdf7fe7d5)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://machinelearning.apple.com/research/controllable-music)

+ **Music ControlNet: Multiple Time-varying Controls for Music Generation** (13 Nov 2023)<details><summary>Shih-Lun Wu, Chris Donahue, Shinji Watanabe, et al.</summary>Shih-Lun Wu, Chris Donahue, Shinji Watanabe, Nicholas J. Bryan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.07069)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F42239e71a712d70cd24e06ffc0cf0d22fc628a36%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Music-ControlNet%3A-Multiple-Time-varying-Controls-Wu-Donahue/42239e71a712d70cd24e06ffc0cf0d22fc628a36)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://musiccontrolnet.github.io/web/)

+ **Mustango: Toward Controllable Text-to-Music Generation** (14 Nov 2023)<details><summary>Jan Melechovsky, Zixun Guo, Deepanway Ghosal, et al.</summary>Jan Melechovsky, Zixun Guo, Deepanway Ghosal, Navonil Majumder, Dorien Herremans, Soujanya Poria</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.08355)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F26d51f1353353fc4e87d8cb2db0caf255e9ee434%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Mustango%3A-Toward-Controllable-Text-to-Music-Melechovsk%C3%BD-Guo/26d51f1353353fc4e87d8cb2db0caf255e9ee434)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://amaai-lab.github.io/mustango/)
[![Code](https://img.shields.io/github/stars/amaai-lab/mustango.svg?style=social&label=Star)](https://github.com/amaai-lab/mustango)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/declare-lab/mustango)

+ **M2UGen: Multi-modal Music Understanding and Generation with the Power of Large Language Models** (19 Nov 2023)<details><summary>Atin Sakkeer Hussain, Shansong Liu, Chenshuo Sun, et al.</summary>Atin Sakkeer Hussain, Shansong Liu, Chenshuo Sun, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11255)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1e84d7c45f70038574fcdb7bc1b20da9b348a092%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/M2UGen%3A-Multi-modal-Music-Understanding-and-with-of-Hussain-Liu/1e84d7c45f70038574fcdb7bc1b20da9b348a092)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://crypto-code.github.io/M2UGen-Demo/)
[![Code](https://img.shields.io/github/stars/shansongliu/M2UGen.svg?style=social&label=Star)](https://github.com/shansongliu/M2UGen)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/M2UGen/M2UGen-Demo)

+ **Audiobox: Unified Audio Generation with Natural Language Prompts** (25 Dec 2023)\
Apoorv Vyas, Bowen Shi, Matthew Le\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.15821)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff124ae1e4663359193be32adb37b07b3252d5329%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Audiobox%3A-Unified-Audio-Generation-with-Natural-Vyas-Shi/f124ae1e4663359193be32adb37b07b3252d5329)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://audiobox.metademolab.com/)
[![Code](https://img.shields.io/github/stars/.svg?style=social&label=Star)]()
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://audiobox.metademolab.com/capabilities)

### Non-LLM-based

### Datasets

# 📍 LLMs for Visual-audio Editing

## Image Editing

### 🔅 LLM-based

+ **InstructPix2Pix: Learning to Follow Image Editing Instructions** (17 Nov 2022)\
Brooks, Tim, Aleksander Holynski, and Alexei A. Efros. CVPR 2023 (Highlight).\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.09800)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa2d2bbe4c542173662a444b33b76c66992697830%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InstructPix2Pix%3A-Learning-to-Follow-Image-Editing-Brooks-Holynski/a2d2bbe4c542173662a444b33b76c66992697830)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.timothybrooks.com/instruct-pix2pix)
[![Code](https://img.shields.io/github/stars/timothybrooks/instruct-pix2pix.svg?style=social&label=Star)](https://github.com/timothybrooks/instruct-pix2pix)


+ **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models** (8 Mar 2023) <details><summary>Chenfei Wu, Shengming Yin, Weizhen Qi, et al.</summary> Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.04671)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Faf997821231898a5f8d0fd78dad4eec526acabe5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Visual-ChatGPT%3A-Talking%2C-Drawing-and-Editing-with-Wu-Yin/af997821231898a5f8d0fd78dad4eec526acabe5)
[![Code](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)](https://github.com/moymix/TaskMatrix)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/microsoft/visual_chatgpt)


+ **HIVE: Harnessing Human Feedback for Instructional Visual Editing** (16 Mar 2023)<details><summary>Shu Zhang, Xinyi Yang, Yihao Feng, et al.</summary> Shu Zhang, Xinyi Yang, Yihao Feng, Can Qin, Chia-Chih Chen, Ning Yu, Zeyuan Chen, Huan Wang, Silvio Savarese, Stefano Ermon, Caiming Xiong, Ran Xu.</details>ArXiv 2023. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09618)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F372bc41602bbd21f192305775f0a58de9880e454%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/HIVE%3A-Harnessing-Human-Feedback-for-Instructional-Zhang-Yang/372bc41602bbd21f192305775f0a58de9880e454)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://shugerdou.github.io/hive/)
[![Code](https://img.shields.io/github/stars/salesforce/HIVE.svg?style=social&label=Star)](https://github.com/salesforce/HIVE)


+ **CHATEDIT: Towards Multi-turn Interactive Facial Image Editing via Dialogue** (20 Mar 2023)<details><summary>Xing Cui, Zekun Li, Peipei Li, et al.</summary> Xing Cui, Zekun Li, Peipei Li, Yibo Hu, Hailin Shi, Zhaofeng He</details>EMNLP 2023. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.11108)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5a185965ad1e87367d044b47043706d00b85b007%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/CHATEDIT%3A-Towards-Multi-turn-Interactive-Facial-via-Cui-Li/5a185965ad1e87367d044b47043706d00b85b007)
[![Code](https://img.shields.io/github/stars/cuixing100876/ChatEdit.svg?style=social&label=Star)](https://github.com/cuixing100876/ChatEdit)

+ **Guiding Instruction-based Image Editing via Multimodal Large Language Models** <details><summary>[ICLR 2024 (Spotlight)] Tsu-Jui Fu, Wenze Hu, Xianzhi Du, et al.</summary> Tsu-Jui Fu, Wenze Hu, Xianzhi Du, William Yang Wang, Yinfei Yang, Zhe Gan</details> \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.17102v1)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F092245d86b77181c36f972b1b7a17a59cd989c4a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Guiding-Instruction-based-Image-Editing-via-Large-Fu-Hu/092245d86b77181c36f972b1b7a17a59cd989c4a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mllm-ie.github.io/)
[![Code](https://img.shields.io/github/stars/tsujuifu/pytorch_mgie.svg?style=social&label=Star)](https://github.com/tsujuifu/pytorch_mgie)



+ **Emu Edit: Precise Image Editing via Recognition and Generation Tasks** (16 Nov 2023)<details><summary>Shelly Sheynin, Adam Polyak, Uriel Singer, et al.</summary> Shelly Sheynin, Adam Polyak, Uriel Singer, Yuval Kirstain, Amit Zohar, Oron Ashual, Devi Parikh, Yaniv Taigman</details>ArXiv 2023. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10089)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5bcb0153dd0840113eb27d4d6f753414ef656a03%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Emu-Edit%3A-Precise-Image-Editing-via-Recognition-and-Sheynin-Polyak/5bcb0153dd0840113eb27d4d6f753414ef656a03)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://emu-edit.metademolab.com/)


+ **Self-correcting LLM-controlled Diffusion Models** (27 Nov 2023)<details><summary>Tsung-Han Wu, Long Lian, Joseph E. Gonzalez, et al.</summary> Tsung-Han Wu, Long Lian, Joseph E. Gonzalez, Boyi Li, Trevor Darrell</details>CVPR 2024. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16090)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F42c4315b5d2e33d7d9a0afdf84e6a47ccd7a700e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Self-correcting-LLM-controlled-Diffusion-Models-Wu-Lian/42c4315b5d2e33d7d9a0afdf84e6a47ccd7a700e)


+ **SmartEdit: Exploring Complex Instruction-based Image Editing with Multimodal Large Language Models** (11 Dec 2023)<details><summary>Yuzhou Huang, Liangbin Xie, Xintao Wang, et al.</summary> Yuzhou Huang, Liangbin Xie, Xintao Wang, Ziyang Yuan, Xiaodong Cun, Yixiao Ge, Jiantao Zhou, Chao Dong, Rui Huang, Ruimao Zhang, Ying Shan</details>CVPR 2024. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06739)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F388b0f44faf0a14cc402c2554ec36a868cf59129%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/SmartEdit%3A-Exploring-Complex-Instruction-based-with-Huang-Xie/388b0f44faf0a14cc402c2554ec36a868cf59129)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yuzhou914.github.io/SmartEdit/)
[![Code](https://img.shields.io/github/stars/TencentARC/SmartEdit.svg?style=social&label=Star)](https://github.com/TencentARC/SmartEdit)



### Non-LLM-based (Clip/T5)


+ **SDEdit: Guided Image Synthesis and Editing with Stochastic Differential Equations** (2 Aug 2021)<details><summary>[ICLR 2022] Chenlin Meng, Yutong He, Yang Song, et al.</summary> Chenlin Meng, Yutong He, Yang Song, Jiaming Song, Jiajun Wu, Jun-Yan Zhu, Stefano Ermon. </details> 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2108.01073)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff671a09e3e5922e6d38cb77dda8d76d5ceac2a27%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/SDEdit%3A-Guided-Image-Synthesis-and-Editing-with-Meng-He/f671a09e3e5922e6d38cb77dda8d76d5ceac2a27)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sde-image-editing.github.io/)
[![Code](https://img.shields.io/github/stars/ermongroup/SDEdit.svg?style=social&label=Star)](https://github.com/ermongroup/SDEdit)


+ **DiffusionCLIP: Text-Guided Diffusion Models for Robust Image Manipulation** (6 Oct 2021)\
Gwanghyun Kim, Taesung Kwon, Jong Chul Ye. CVPR 2022. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2110.02711)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8f8dedb511c0324d1cb7f9750560109ca9290b5f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DiffusionCLIP%3A-Text-Guided-Diffusion-Models-for-Kim-Kwon/8f8dedb511c0324d1cb7f9750560109ca9290b5f)
[![Code](https://img.shields.io/github/stars/gwang-kim/DiffusionCLIP.svg?style=social&label=Star)](https://github.com/gwang-kim/DiffusionCLIP)


+ **DiffEdit: Diffusion-based semantic image editing with mask guidance** (20 Oct 2022) <details><summary>[ICLR 2023] Guillaume Couairon, Jakob Verbeek, Holger Schwenk, et al.</summary> Guillaume Couairon, Jakob Verbeek, Holger Schwenk, Matthieu Cord. </details> 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.11427)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F064ccebc03d3afabaae30fe29a457c1cfcdff7e3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DiffEdit%3A-Diffusion-based-semantic-image-editing-Couairon-Verbeek/064ccebc03d3afabaae30fe29a457c1cfcdff7e3)
<!-- [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ashmrz.github.io/WatchYourSteps/) -->
<!-- [![Code](https://img.shields.io/github/stars/Xiang-cd/DiffEdit-stable-diffusion.svg?style=social&label=Star)](https://github.com/Xiang-cd/DiffEdit-stable-diffusion) -->


+ **Prompt-to-Prompt Image Editing with Cross Attention Control** <details><summary>[ICLR 2023] Amir Hertz, Ron Mokady, Jay Tenenbaum, et al.</summary> Amir Hertz, Ron Mokady, Jay Tenenbaum, Kfir Aberman, Yael Pritch, Daniel Cohen-Or. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2208.01626)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F04e541391e8dce14d099d00fb2c21dbbd8afe87f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Prompt-to-Prompt-Image-Editing-with-Cross-Attention-Hertz-Mokady/04e541391e8dce14d099d00fb2c21dbbd8afe87f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://prompt-to-prompt.github.io/)
[![Code](https://img.shields.io/github/stars/google/prompt-to-prompt.svg?style=social&label=Star)](https://github.com/google/prompt-to-prompt)

+ **Null-text Inversion for Editing Real Images using Guided Diffusion Models**<details><summary>[ICLR 2023] Ron Mokady, Amir Hertz, Kfir Aberman, et al.</summary> Ron Mokady, Amir Hertz, Kfir Aberman, Yael Pritch, Daniel Cohen-Or. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.09794)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4de94949daf9bc8dd0e5161d20dfe83198d20ec1%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Null-text-Inversion-for-Editing-Real-Images-using-Mokady-Hertz/4de94949daf9bc8dd0e5161d20dfe83198d20ec1)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://null-text-inversion.github.io/)
[![Code](https://img.shields.io/github/stars/google/prompt-to-prompt.svg?style=social&label=Star)](https://github.com/google/prompt-to-prompt/#null-text-inversion-for-editing-real-images)

+ **Imagic: Text-Based Real Image Editing with Diffusion Models** (17 Oct 2022)<details><summary>Bahjat Kawar, Shiran Zada, Oran Lang, et al.</summary> Bahjat Kawar, Shiran Zada, Oran Lang, Omer Tov, Huiwen Chang, Tali Dekel, Inbar Mosseri, Michal Irani. </details>CVPR 2023. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.09276)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F23e261a20a315059b4de5492ed071c97a20c12e7%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Imagic%3A-Text-Based-Real-Image-Editing-with-Models-Kawar-Zada/23e261a20a315059b4de5492ed071c97a20c12e7)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://imagic-editing.github.io/)
<!-- [![Code](https://img.shields.io/github/stars/pix2pixzero/pix2pix-zero.svg?style=social&label=Star)](https://github.com/pix2pixzero/pix2pix-zero) -->


+ **Plug-and-Play Diffusion Features for Text-Driven Image-to-Image Translation** (22 Nov 2022)<details><summary>Narek Tumanyan, Michal Geyer, Shai Bagon, et al.</summary> Narek Tumanyan, Michal Geyer, Shai Bagon, Tali Dekel. </details>CVPR 2023. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.12572)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb000d6865db824af1563708fb7a545ddd65c6b3a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Plug-and-Play-Diffusion-Features-for-Text-Driven-Tumanyan-Geyer/b000d6865db824af1563708fb7a545ddd65c6b3a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pnp-diffusion.github.io/)
[![Code](https://img.shields.io/github/stars/MichalGeyer/plug-and-play.svg?style=social&label=Star)](https://github.com/MichalGeyer/plug-and-play)

+ **Interactive Image Manipulation with Complex Text Instructions** (25 Nov 2022)<details><summary>Ryugo Morita, Zhiqiang Zhang, Man M. Ho, et al.</summary> Ryugo Morita, Zhiqiang Zhang, Man M. Ho, Jinjia Zhou. </details>WACV 2023. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.15352)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F387144d293567408c363313aac971294e7ec8547%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Interactive-Image-Manipulation-with-Complex-Text-Morita-Zhang/387144d293567408c363313aac971294e7ec8547)

+ **SINE: SINgle Image Editing with Text-to-Image Diffusion Models** (8 Dec 2022)<details><summary>Zhixing Zhang, Ligong Han, Arnab Ghosh, et al.</summary> Zhixing Zhang, Ligong Han, Arnab Ghosh, Dimitris Metaxas, Jian Ren. </details>CVPR 2023. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.04489)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa6ad30123bef4b19ee40c3d63cfabf00d211f0ef%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/SINE%3A-SINgle-Image-Editing-with-Text-to-Image-Zhang-Han/a6ad30123bef4b19ee40c3d63cfabf00d211f0ef)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zhang-zx.github.io/SINE/)
[![Code](https://img.shields.io/github/stars/zhang-zx/SINE.svg?style=social&label=Star)](https://github.com/zhang-zx/SINE)


+ **Zero-shot Image-to-Image Translation** (6 Feb 2023)<details><summary>Gaurav Parmar, Krishna Kumar Singh, Richard Zhang, et al.</summary> Gaurav Parmar, Krishna Kumar Singh, Richard Zhang, Yijun Li, Jingwan Lu, Jun-Yan Zhu. </details>SIGGRAPH 2023. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.03027)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdaf61010eee0fbf6f9bab7db71c395ffca6f3ff3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Zero-shot-Image-to-Image-Translation-Parmar-Singh/daf61010eee0fbf6f9bab7db71c395ffca6f3ff3)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pix2pixzero.github.io/)
[![Code](https://img.shields.io/github/stars/pix2pixzero/pix2pix-zero.svg?style=social&label=Star)](https://github.com/pix2pixzero/pix2pix-zero)

+ **PAIR-Diffusion: A Comprehensive Multimodal Object-Level Image Editor** (30 Mar 2023)<details><summary>Vidit Goel, Elia Peruzzo, Yifan Jiang, et al.</summary> Vidit Goel, Elia Peruzzo, Yifan Jiang, Dejia Xu, Xingqian Xu, Nicu Sebe, Trevor Darrell, Zhangyang Wang, Humphrey Shi. </details>arXiv 2023. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.17546)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc614a4da924466f62ca39002af425c9d14d240a3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/PAIR-Diffusion%3A-A-Comprehensive-Multimodal-Image-Goel-Peruzzo/c614a4da924466f62ca39002af425c9d14d240a3)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://vidit98.github.io/publication/conference-paper/pair_diff.html)
[![Code](https://img.shields.io/github/stars/pix2pixzero/pix2pix-zero.svg?style=social&label=Star)](https://github.com/Picsart-AI-Research/PAIR-Diffusion)


+ **MasaCtrl: Tuning-Free Mutual Self-Attention Control for Consistent Image Synthesis and Editing** (17 Apr 2023)<details><summary>Mingdeng Cao, Xintao Wang, Zhongang Qi, et al.</summary> Mingdeng Cao, Xintao Wang, Zhongang Qi, Ying Shan, Xiaohu Qie, Yinqiang Zheng. </details>ICCV 2023. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.08947)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F85963807c11abe38e9a2797d9860e012238607ef%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MasaCtrl%3A-Tuning-Free-Mutual-Self-Attention-Control-Cao-Wang/85963807c11abe38e9a2797d9860e012238607ef)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ljzycmd.github.io/projects/MasaCtrl/)
[![Code](https://img.shields.io/github/stars/TencentARC/MasaCtrl.svg?style=social&label=Star)](https://github.com/TencentARC/MasaCtrl)

+ **Visual Instruction Inversion: Image Editing via Visual Prompting** (26 Jul 2023)<details><summary>Thao Nguyen, Yuheng Li, Utkarsh Ojha, et al.</summary> Thao Nguyen, Yuheng Li, Utkarsh Ojha, Yong Jae Lee. </details>arXiv 2023. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.14331)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff4c62aa336de45273e0fdfcfbd65b3c2e552ad56%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Visual-Instruction-Inversion%3A-Image-Editing-via-Nguyen-Li/f4c62aa336de45273e0fdfcfbd65b3c2e552ad56)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://thaoshibe.github.io/visii/)
[![Code](https://img.shields.io/github/stars/thaoshibe/visii.svg?style=social&label=Star)](https://github.com/thaoshibe/visii)

+ **Differential Diffusion: Giving Each Pixel Its Strength** (1 Jun 2023)\
[ArXiv 2023] Eran Levin, Ohad Fried. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.14331)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6e5760e5d4b468bbf01a95a6f64bd65c3aa3d798%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Differential-Diffusion%3A-Giving-Each-Pixel-Its-Levin-Fried/6e5760e5d4b468bbf01a95a6f64bd65c3aa3d798)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://differential-diffusion.github.io/)
[![Code](https://img.shields.io/github/stars/exx8/differential-diffusion.svg?style=social&label=Star)](https://github.com/exx8/differential-diffusion)


+ **Dragondiffusion: Enabling drag-style manipulation on diffusion models** (5 Jul 2023)<details><summary>[ICLR 2024] Chong Mou, Xintao Wang, Jiechong Song, et al.</summary>Chong Mou, Xintao Wang, Jiechong Song, Ying Shan, Jian Zhang. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.14331)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2cfaa5b3571d3b75f040f6d639359a3c673f5561%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DragonDiffusion%3A-Enabling-Drag-style-Manipulation-Mou-Wang/2cfaa5b3571d3b75f040f6d639359a3c673f5561)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mc-e.github.io/project/DragonDiffusion/)
[![Code](https://img.shields.io/github/stars/MC-E/DragonDiffusion.svg?style=social&label=Star)](https://github.com/MC-E/DragonDiffusion)


+ **Watch Your Steps: Local Image and Scene Editing by Text Instructions** (17 Aug 2023 )<details><summary>Ashkan Mirzaei, Tristan Aumentado-Armstrong, Marcus A. Brubaker, et al.</summary>Ashkan Mirzaei, Tristan Aumentado-Armstrong, Marcus A. Brubaker, Jonathan Kelly, Alex Levinshtein, Konstantinos G. Derpanis, Igor Gilitschenski. </details>arXiv 2023. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.08947)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F737ad8905228cd410e3342b5cceefd4feb57d166%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Watch-Your-Steps%3A-Local-Image-and-Scene-Editing-by-Mirzaei-Aumentado-Armstrong/737ad8905228cd410e3342b5cceefd4feb57d166)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ashmrz.github.io/WatchYourSteps/)


+ **ZONE: Zero-Shot Instruction-Guided Local Editing** (28 Dec 2023)<details><summary>Shanglin Li, Bohan Zeng, Yutang Feng, et al.</summary>Shanglin Li, Bohan Zeng, Yutang Feng, Sicheng Gao, Xuhui Liu, Jiaming Liu, Li Lin, Xu Tang, Yao Hu, Jianzhuang Liu, Baochang Zhang. </details>arXiv 2024. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.16794)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F05eb2ad3af471c05a24abbf70258688e579cdf22%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ZONE%3A-Zero-Shot-Instruction-Guided-Local-Editing-Li-Zeng/05eb2ad3af471c05a24abbf70258688e579cdf22)


+ **DiffEditor: Boosting Accuracy and Flexibility on Diffusion-based Image Editing** (4 Feb 2024)<details><summary>Chong Mou, Xintao Wang, Jiechong Song, et al.</summary>Chong Mou, Xintao Wang, Jiechong Song, Ying Shan, Jian Zhang. </details>CVPR 2024. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.02583)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F198b3d809594a76bc473927af37b858132ac7fdd%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DiffEditor%3A-Boosting-Accuracy-and-Flexibility-on-Mou-Wang/198b3d809594a76bc473927af37b858132ac7fdd)
[![Code](https://img.shields.io/github/stars/MC-E/DragonDiffusion.svg?style=social&label=Star)](https://github.com/MC-E/DragonDiffusion)

## Video Editing

### 🔅 LLM-based

+ **InstructVid2Vid: Controllable Video Editing with Natural Language Instructions** (21 May 2023)<details><summary>Bosheng Qin, Juncheng Li, Siliang Tang, et al.</summary>Bosheng Qin, Juncheng Li, Siliang Tang, Tat-Seng Chua, Yueting Zhuang. </details>arXiv 2023. 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.12328)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F205d2ed0906440f07a0275d7d6a63bced60951fc%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InstructVid2Vid%3A-Controllable-Video-Editing-with-Qin-Li/205d2ed0906440f07a0275d7d6a63bced60951fc)
<!-- [![Code](https://img.shields.io/github/stars/duyguceylan/pix2video.svg?style=social&label=Star)](https://github.com/duyguceylan/pix2video) -->

+ **CONSISTENT VIDEO-TO-VIDEO TRANSFER USING SYNTHETIC DATASET** (1 Nov 2023)\
Jiaxin Cheng, Tianjun Xiao, Tong He. ArXiv 2023.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00213)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe8bbffb8413cb1f88e99a7ecbabd21a6eac82271%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Consistent-Video-to-Video-Transfer-Using-Synthetic-Cheng-Xiao/e8bbffb8413cb1f88e99a7ecbabd21a6eac82271)
[![Code](https://img.shields.io/github/stars/amazon-science/instruct-video-to-video.svg?style=social&label=Star)](https://github.com/amazon-science/instruct-video-to-video)



### Non-LLM-based (Clip/T5)

+ **M3L: Language-based Video Editing via Multi-Modal Multi-Level Transformers** (2 Apr 2021)<details><summary>Tsu-Jui Fu, Xin Eric Wang, Scott T. Grafton, et al.</summary>Tsu-Jui Fu, Xin Eric Wang, Scott T. Grafton, Miguel P. Eckstein, William Yang Wang. </details>CVPR 2022.
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2104.01122)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F81349524489f8ba0812ac2529eac92ec45959782%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Language-based-Video-Editing-via-Multi-Modal-Fu-Wang/81349524489f8ba0812ac2529eac92ec45959782)

+ **Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation** (22 Dec 2022)<details><summary>Jay Zhangjie Wu, Yixiao Ge, Xintao Wang, et al.</summary>Jay Zhangjie Wu, Yixiao Ge, Xintao Wang, Weixian Lei, Yuchao Gu, Yufei Shi, Wynne Hsu, Ying Shan, Xiaohu Qie, Mike Zheng Shou. </details>ICCV 2023.
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.11565)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1367dcff4ccb927a5e95c452041288b3f0dd0eff%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Tune-A-Video%3A-One-Shot-Tuning-of-Image-Diffusion-Wu-Ge/1367dcff4ccb927a5e95c452041288b3f0dd0eff)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fate-zero-edit.github.io/)
[![Code](https://img.shields.io/github/stars/showlab/Tune-A-Video.svg?style=social&label=Star)](https://tuneavideo.github.io/)

+ **Dreamix: Video Diffusion Models are General Video Editors** (2 Feb 2023)<details><summary>Eyal Molad, Eliahu Horwitz, Dani Valevski, et al.</summary>Eyal Molad, Eliahu Horwitz, Dani Valevski, Alex Rav Acha, Yossi Matias, Yael Pritch, Yaniv Leviathan, Yedid Hoshen. </details>arXiv 2023.
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.01329)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9758ddd6ffbaac75aa0447a9664e6989811a05e2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Dreamix%3A-Video-Diffusion-Models-are-General-Video-Molad-Horwitz/9758ddd6ffbaac75aa0447a9664e6989811a05e2)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamix-video-editing.github.io/)

+ **Video-P2P: Video Editing with Cross-attention Control** (8 Mar 2023)<details><summary>Shaoteng Liu, Yuechen Zhang, Wenbo Li, et al.</summary>Shaoteng Liu, Yuechen Zhang, Wenbo Li, Zhe Lin, Jiaya Jia. </details>arXiv 2023.
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.04761)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6283502d6900a0b403e2454b1cb1cf16ddefd5a7%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Video-P2P%3A-Video-Editing-with-Cross-attention-Liu-Zhang/6283502d6900a0b403e2454b1cb1cf16ddefd5a7)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://video-p2p.github.io/)
[![Code](https://img.shields.io/github/stars/ShaoTengLiu/Video-P2P.svg?style=social&label=Star)](https://github.com/ShaoTengLiu/Video-P2P)

+ **FateZero: Fusing Attentions for Zero-shot Text-based Video Editing** (16 Mar 2023)<details><summary>Chenyang Qi, Xiaodong Cun, Yong Zhang, et al.</summary>Chenyang Qi, Xiaodong Cun, Yong Zhang, Chenyang Lei, Xintao Wang, Ying Shan, Qifeng Chen. </details>ICCV 2023 (Oral).
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09535)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F14ccb8bcceb6de10eda6ad08bec242a4f2946497%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/FateZero%3A-Fusing-Attentions-for-Zero-shot-Video-Qi-Cun/14ccb8bcceb6de10eda6ad08bec242a4f2946497)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fate-zero-edit.github.io/)
[![Code](https://img.shields.io/github/stars/ChenyangQiQi/FateZero.svg?style=social&label=Star)](https://github.com/ChenyangQiQi/FateZero)


+ **Pix2Video: Video Editing using Image Diffusion** (22 Mar 2023)\
Ceylan, Duygu, Chun-Hao P. Huang, and Niloy J. Mitra. ICCV 2023.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12688)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F32a3c2fbd3e733bd0eea938517fec2ff8dc7c701%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Pix2Video%3A-Video-Editing-using-Image-Diffusion-Ceylan-Huang/32a3c2fbd3e733bd0eea938517fec2ff8dc7c701)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://duyguceylan.github.io/pix2video.github.io/)
[![Code](https://img.shields.io/github/stars/duyguceylan/pix2video.svg?style=social&label=Star)](https://github.com/duyguceylan/pix2video)

+ **Make-A-Protagonist: Generic Video Editing with An Ensemble of Experts** (15 May 2023)
Michal Geyer, Omer Bar-Tal, Shai Bagon, Tali Dekel. arXiv 2023.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.08850)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5f51eda9f7abddca027941d50fb0b6bf6f508eff%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Make-A-Protagonist%3A-Generic-Video-Editing-with-An-Zhao-Xie/5f51eda9f7abddca027941d50fb0b6bf6f508eff)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://make-a-protagonist.github.io/)
[![Code](https://img.shields.io/github/stars/HeliosZhao/Make-A-Protagonist.svg?style=social&label=Star)](https://github.com/HeliosZhao/Make-A-Protagonist)

+ **ControlVideo: Adding Conditional Control for One Shot Text-to-Video Editing** (26 May 2023)<details><summary>Min Zhao, Rongzhen Wang, Fan Bao, et al.</summary>Min Zhao, Rongzhen Wang, Fan Bao, Chongxuan Li, Jun Zhu. </details>arXiv 2023.
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.17098)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F14acc36d8c87f31f8dcbbf8433b91af70a2a516a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ControlVideo%3A-Conditional-Control-for-One-shot-and-Zhao-Wang/14acc36d8c87f31f8dcbbf8433b91af70a2a516a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ml.cs.tsinghua.edu.cn/controlvideo/)
[![Code](https://img.shields.io/github/stars/thu-ml/controlvideo.svg?style=social&label=Star)](https://github.com/thu-ml/controlvideo)

+ **Rerender A Video: Zero-Shot Text-Guided Video-to-Video Translation** (13 Jun 2023)<details><summary>Shuai Yang, Yifan Zhou, Ziwei Liu, et al.</summary>Shuai Yang, Yifan Zhou, Ziwei Liu, Chen Change Loy. </details>arXiv 2023.
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.07954)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1e09b83fe064826a9a1ac61a7bdc00f26be41aee%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Rerender-A-Video%3A-Zero-Shot-Text-Guided-Translation-Yang-Zhou/1e09b83fe064826a9a1ac61a7bdc00f26be41aee)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.mmlab-ntu.com/project/rerender/)
[![Code](https://img.shields.io/github/stars/williamyang1991/Rerender_A_Video.svg?style=social&label=Star)](https://github.com/williamyang1991/Rerender_A_Video)


+ **TokenFlow: Consistent Diffusion Features for Consistent Video Editing** (19 Jul 2023) <details><summary>Michal Geyer, Omer Bar-Tal, Shai Bagon, et al.</summary>Michal Geyer, Omer Bar-Tal, Shai Bagon, Tali Dekel. </details>arXiv 2023.
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.10373)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4761f173965195798cd3046ef4af608a83504e4d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/TokenFlow%3A-Consistent-Diffusion-Features-for-Video-Geyer-Bar-Tal/4761f173965195798cd3046ef4af608a83504e4d)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://diffusion-tokenflow.github.io/)
[![Code](https://img.shields.io/github/stars/omerbt/TokenFlow.svg?style=social&label=Star)](https://github.com/omerbt/TokenFlow)


+ **CoDeF: Content Deformation Fields for Temporally Consistent Video Processing** (15 Aug 2023) <details><summary>Hao Ouyang, Qiuyu Wang, Yuxi Xiao, et al.</summary>Hao Ouyang, Qiuyu Wang, Yuxi Xiao, Qingyan Bai, Juntao Zhang, Kecheng Zheng, Xiaowei Zhou, Qifeng Chen. </details>arXiv 2023.
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.07926)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc2d65fc3a7fde3f7662c6ef9448e5737d7e5551f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/CoDeF%3A-Content-Deformation-Fields-for-Temporally-Hao-Wang/c2d65fc3a7fde3f7662c6ef9448e5737d7e5551f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://qiuyu96.github.io/CoDeF/)
[![Code](https://img.shields.io/github/stars/qiuyu96/CoDeF.svg?style=social&label=Star)](https://github.com/qiuyu96/CoDeF)


+ **StableVideo: Text-driven Consistency-aware Diffusion Video Editing** (18 Aug 2023)<details><summary>Wenhao Chai, Xun Guo, Gaoang Wang, et al.</summary>Wenhao Chai, Xun Guo, Gaoang Wang, Yan Lu. </details>ICCV 2023.
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.09592)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F05cbac9a5101f47a6fabad72398616506572c9fa%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/StableVideo%3A-Text-driven-Consistency-aware-Video-Chai-Guo/05cbac9a5101f47a6fabad72398616506572c9fa)
[![Code](https://img.shields.io/github/stars/rese1f/StableVideo.svg?style=social&label=Star)](https://github.com/rese1f/StableVideo)


+ **MagicEdit: High-Fidelity Temporally Coherent Video Editing** (28 Aug 2023) <details><summary>Jun Hao Liew, Hanshu Yan, Jianfeng Zhang, et al.</summary>Jun Hao Liew, Hanshu Yan, Jianfeng Zhang, Zhongcong Xu, Jiashi Feng. </details>arXiv 2023.
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.14749)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8819777e104f8c4197c262e11a01b070b50007aa%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MagicEdit%3A-High-Fidelity-and-Temporally-Coherent-Liew-Yan/8819777e104f8c4197c262e11a01b070b50007aa)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://magic-edit.github.io/)
[![Code](https://img.shields.io/github/stars/magic-research/magic-edit.svg?style=social&label=Star)](https://github.com/magic-research/magic-edit)

+ **MagicStick: Controllable Video Editing via Control Handle Transformations** (1 Nov 2023)<details><summary>Yue Ma, Xiaodong Cun, Yingqing He, et al.</summary>Yue Ma, Xiaodong Cun, Yingqing He, Chenyang Qi, Xintao Wang, Ying Shan, Xiu Li, Qifeng Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03047)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fxxx%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Consistent-Video-to-Video-Transfer-Using-Synthetic-Cheng-Xiao/xxx)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://magic-stick-edit.github.io/)
[![Code](https://img.shields.io/github/stars/mayuelala/MagicStick.svg?style=social&label=Star)](https://github.com/mayuelala/MagicStick)


+ **LATENTWARP: CONSISTENT DIFFUSION LATENTS FOR ZERO-SHOT VIDEO-TO-VIDEO TRANSLATION** (1 Nov 2023)<details><summary>Yuxiang Bao, Di Qiu, Guoliang Kang, et al.</summary>Yuxiang Bao, Di Qiu, Guoliang Kang, Baochang Zhang, Bo Jin, Kaiye Wang, Pengfei Yan. </details>arXiv 2023.
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00353)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1b4323a5324ee20fe9b2ff2a65ec26550a51ec2c%3Ffields%3DcitationCount)](https://semanticscholar.org/paper/LatentWarp%3A-Consistent-Diffusion-Latents-for-Bao-Qiu/1b4323a5324ee20fe9b2ff2a65ec26550a51ec2c)
<!-- [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://diffusion-tokenflow.github.io/) -->
<!-- [![Code](https://img.shields.io/github/stars/omerbt/TokenFlow.svg?style=social&label=Star)](https://github.com/omerbt/TokenFlow) -->



## 3D Editing

### 🔅 LLM-based


### Non-LLM-based (Clip/T5)
+ **3D Paintbrush: Local Stylization of 3D Shapes with Cascaded Score Distillation** (16 Nov 2023)<details><summary>Dale Decatur, Itai Lang, Kfir Aberman, et al.</summary>Dale Decatur, Itai Lang, Kfir Aberman, Rana Hanocka</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.09571)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F496bdd2804a231a3336463fca8e0a4c6a46f0304%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/3D-Paintbrush%3A-Local-Stylization-of-3D-Shapes-with-Decatur-Lang/496bdd2804a231a3336463fca8e0a4c6a46f0304)
[![Code](https://img.shields.io/github/stars/threedle/3d-paintbrush?style=social&label=Star)](https://github.com/threedle/3d-paintbrush)

+ **Blending-NeRF: Text-Driven Localized Editing in Neural Radiance Fields** (23 Aug 2023)<details><summary>Hyeonseop Song, Seokhun Choi, Hoseok Do, et al. </summary>Hyeonseop Song, Seokhun Choi, Hoseok Do, Chul Lee, Taehyeong Kim</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.11974)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbf7f31e07d9b128a0f555c275bc3fdb851f725b8%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Blending-NeRF%3A-Text-Driven-Localized-Editing-in-Song-Choi/bf7f31e07d9b128a0f555c275bc3fdb851f725b8)

+ **SINE: Semantic-driven Image-based NeRF Editing with Prior-guided Editing Field** (23 Mar 2023)<details><summary>Chong Bao, Yinda Zhang, Bangbang Yang, et al. (CVPR 2023)</summary>Chong Bao, Yinda Zhang, Bangbang Yang, Tianxing Fan, Zesong Yang, Hujun Bao, Guofeng Zhang, Zhaopeng Cui</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13277)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F222c47b81fe04598fd84fe8b9a43f694415ec7e9%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/SINE%3A-Semantic-driven-Image-based-NeRF-Editing-with-Bao-Zhang/222c47b81fe04598fd84fe8b9a43f694415ec7e9)
[![Code](https://img.shields.io/github/stars/zju3dv/SINE?style=social&label=Star)](https://github.com/zju3dv/SINE)

+ **TextDeformer: Geometry Manipulation using Text Guidance** (26 Apr 2023)<details><summary>William Gao, Noam Aigerman, Thibault Groueix, et al. (TVCG 2022)</summary>William Gao, Noam Aigerman, Thibault Groueix, Vladimir G. Kim, Rana Hanocka</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.13348)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4974186c3b5b50112cfd909de115d5fbe25411fd%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/TextDeformer%3A-Geometry-Manipulation-using-Text-Gao-Aigerman/4974186c3b5b50112cfd909de115d5fbe25411fd)
[![Code](https://img.shields.io/github/stars/threedle/TextDeformer.svg?style=social&label=Star)](https://github.com/threedle/TextDeformer)

+ **Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions** (22 Mar 2023)<details><summary>Ayaan Haque, Matthew Tancik, Alexei A. Efros, et al. (SIGGRAPH Asia 2023)</summary>Ayaan Haque, Matthew Tancik, Alexei A. Efros, Aleksander Holynski, Angjoo Kanazawa</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12789)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F26c22380282a00166273038bc5ba785d845d61ad%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Instruct-NeRF2NeRF%3A-Editing-3D-Scenes-with-Haque-Tancik/26c22380282a00166273038bc5ba785d845d61ad)
[![Code](https://img.shields.io/github/stars/ayaanzhaque/instruct-nerf2nerf.svg?style=social&label=Star)](https://github.com/ayaanzhaque/instruct-nerf2nerf)

+ **DreamEditor: Text-Driven 3D Scene Editing with Neural Fields** (23 Jun 2023)<details><summary>Jingyu Zhuang, Chen Wang, Lingjie Liu, et al. (SIGGRAPH Asia 2023)</summary>Jingyu Zhuang, Chen Wang, Lingjie Liu, Liang Lin, Guanbin Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.13455)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F029f3e2c215edac138be26ade67b3d70b8f74dd7%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DreamEditor%3A-Text-Driven-3D-Scene-Editing-with-Zhuang-Wang/029f3e2c215edac138be26ade67b3d70b8f74dd7)
[![Code](https://img.shields.io/github/stars/zjy526223908/DreamEditor.svg?style=social&label=Star)](https://github.com/zjy526223908/DreamEditor)

+ **SKED: Sketch-guided Text-based 3D Editing** (19 Mar 2023)<details><summary>Aryan Mikaeili, Or Perel, Mehdi Safaee, et al. (ICCV 2023)</summary>Aryan Mikaeili, Or Perel, Mehdi Safaee, Daniel Cohen-Or, Ali Mahdavi-Amiri</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.10735)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6ebec1ece44daa090158ff2531d6fabb94a4e683%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/SKED%3A-Sketch-guided-Text-based-3D-Editing-Mikaeili-Perel/6ebec1ece44daa090158ff2531d6fabb94a4e683)
[![Code](https://img.shields.io/github/stars/aryanmikaeili/SKED.svg?style=social&label=Star)](https://github.com/aryanmikaeili/SKED)

+ **Blended-NeRF: Zero-Shot Object Generation and Blending in Existing Neural Radiance Fields** (22 Jun 2023)<details><summary>Ori Gordon, Omri Avrahami, Dani Lischinski. (ICCVW 2023)</summary>Ori Gordon, Omri Avrahami, Dani Lischinski</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.12760)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3a5d4352d3dd53148a9544233bb59f88d2504910%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Blended-NeRF%3A-Zero-Shot-Object-Generation-and-in-Gordon-Avrahami/3a5d4352d3dd53148a9544233bb59f88d2504910)


+ **ClipFace: Text-guided Editing of Textured 3D Morphable Modelssting Neural Radiance Fields** (2 Dec 2022)<details><summary>Shivangi Aneja, Justus Thies, Angela Dai, et al. (SIGGRAPH 2023)</summary>Shivangi Aneja, Justus Thies, Angela Dai, Matthias Nießner</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.01406)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff21e8eddf42580d1f38a11ec5acd8891c0454a1f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ClipFace%3A-Text-guided-Editing-of-Textured-3D-Models-Aneja-Thies/f21e8eddf42580d1f38a11ec5acd8891c0454a1f)
[![Code](https://img.shields.io/github/stars/cassiePython/CLIPNeRF.svg?style=social&label=Star)](https://github.com/cassiePython/CLIPNeRF)

+ **CLIP-NeRF: Text-and-Image Driven Manipulation of Neural Radiance Fieldsadiance Fields** (9 Dec 2021)<details><summary>Can Wang, Menglei Chai, Mingming He, et al. (CVPR 2022)</summary>Can Wang, Menglei Chai, Mingming He, Dongdong Chen, Jing Liao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.05139)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0483be6c3ec6cd41ffe248f86effc7468d3ac7be%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/CLIP-NeRF%3A-Text-and-Image-Driven-Manipulation-of-Wang-Chai/0483be6c3ec6cd41ffe248f86effc7468d3ac7be)
[![Code](https://img.shields.io/github/stars/shivangi-aneja/ClipFace.svg?style=social&label=Star)](https://github.com/shivangi-aneja/ClipFace)





## Audio Editing

### 🔅 LLM-based

+ **AUDIT: Audio Editing by Following Instructions with Latent Diffusion Models** (3 Apr 2023)\
Yuancheng Wang, Zeqian Ju, Xu Tan\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.00830)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F187703129bb0da27e0d3bda51320bb85efd34821%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/AUDIT%3A-Audio-Editing-by-Following-Instructions-with-Wang-Ju/187703129bb0da27e0d3bda51320bb85efd34821)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://audit-demo.github.io/)

+ **Voicebox: Text-guided multilingual universal speech generation at scale** (23 Jun 2023)\
Matthew Le, Apoorv Vyas, Bowen Shi\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.15687)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa9e00c216ce69325a15fd139da0624978e54058a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Voicebox%3A-Text-Guided-Multilingual-Universal-Speech-Le-Vyas/a9e00c216ce69325a15fd139da0624978e54058a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://voicebox.metademolab.com/)

+ **UniAudio: An Audio Foundation Model Toward Universal Audio Generation** (1 Oct 2023)\
Dongchao Yang, Jinchuan Tian, Xu Tan\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.00704)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F74bfbbb7307a7af2686043ea97ab8b34cb062ba8%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/UniAudio%3A-An-Audio-Foundation-Model-Toward-Audio-Yang-Tian/74bfbbb7307a7af2686043ea97ab8b34cb062ba8)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dongchaoyang.top/UniAudio_demo/)
[![Code](https://img.shields.io/github/stars/yangdongchao/UniAudio.svg?style=social&label=Star)](https://github.com/yangdongchao/UniAudio)

+ **Loop Copilot: Conducting AI Ensembles for Music Generation and Iterative Editing** (19 Oct 2023)<details><summary>Yixiao Zhang, Akira Maezawa, Gus Xia, et al.</summary>Yixiao Zhang, Akira Maezawa, Gus Xia, Kazuhiko Yamamoto, Simon Dixon</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.12404)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fcca4218dd7c10c1614bbd84aa7cd7e00027bdc7c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Loop-Copilot%3A-Conducting-AI-Ensembles-for-Music-and-Zhang-Maezawa/cca4218dd7c10c1614bbd84aa7cd7e00027bdc7c)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sites.google.com/view/loop-copilot)
[![Code](https://img.shields.io/github/stars/ldzhangyx/loop-copilot/.svg?style=social&label=Star)](https://github.com/ldzhangyx/loop-copilot/)

+ **M2UGen: Multi-modal Music Understanding and Generation with the Power of Large Language Models** (19 Nov 2023)<details><summary>Atin Sakkeer Hussain, Shansong Liu, Chenshuo Sun, et al.</summary>Atin Sakkeer Hussain, Shansong Liu, Chenshuo Sun, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11255)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1e84d7c45f70038574fcdb7bc1b20da9b348a092%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/M2UGen%3A-Multi-modal-Music-Understanding-and-with-of-Hussain-Liu/1e84d7c45f70038574fcdb7bc1b20da9b348a092)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://crypto-code.github.io/M2UGen-Demo/)
[![Code](https://img.shields.io/github/stars/shansongliu/M2UGen.svg?style=social&label=Star)](https://github.com/shansongliu/M2UGen)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/M2UGen/M2UGen-Demo)

+ **InstructME: An Instruction Guided Music Edit And Remix Framework with Latent Diffusion Models** (12 Dec 2023)<details><summary>Bing Han, Junyu Dai, Weituo Hao, et al.</summary>Bing Han, Junyu Dai, Weituo Hao, Xinyan He, Dong Guo, Jitong Chen, Yuxuan Wang, Yanmin Qian, Xuchen Song</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)]()
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F96a7ca4a9687ef1170f5b5518798ab3fd228e845%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InstructME%3A-An-Instruction-Guided-Music-Edit-And-Han-Dai/96a7ca4a9687ef1170f5b5518798ab3fd228e845)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://musicedit.github.io/)

### Non-LLM-based (Clip/T5)

# 📍 Multi-Modal Agents

+ **LLaVA-Interactive: An All-in-One Demo for Image Chat, Segmentation, Generation and Editing** (1 Nov 2023) <details><summary>Wei-Ge Chen, Irina Spiridonova, Jianwei Yang, et al.</summary> Wei-Ge Chen, Irina Spiridonova, Jianwei Yang, Jianfeng Gao, Chunyuan Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00571)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc020f15be1dee20f9e2e0c5a6f05f272b5508325%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LLaVA-Interactive%3A-An-All-in-One-Demo-for-Image-and-Chen-Spiridonova/c020f15be1dee20f9e2e0c5a6f05f272b5508325)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llava-vl.github.io/llava-interactive)
[![Code](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Interactive-Demo.svg?style=social&label=Star)](https://github.com/LLaVA-VL/LLaVA-Interactive-Demo)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://llavainteractive.ngrok.app/)\
**Tags:** `Image Chat` `Image Segmentation`, `Image Generation` `Image Editing`

+ **ControlLLM: Augment Language Models with Tools by Searching on Graphs** (26 Oct 2023) <details><summary>Zhaoyang Liu, Zeqiang Lai, Zhangwei Gao, et al.</summary>Zhaoyang Liu, Zeqiang Lai, Zhangwei Gao, Erfei Cui, Ziheng Li, Xizhou Zhu, Lewei Lu, Qifeng Chen, Yu Qiao, Jifeng Dai, Wenhai Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.17796)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F288e7224d53d68669eb67f2496e068dc965c639e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ControlLLM%3A-Augment-Language-Models-with-Tools-by-Liu-Lai/288e7224d53d68669eb67f2496e068dc965c639e)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://controlllm.github.io/)
[![Code](https://img.shields.io/github/stars/OpenGVLab/ControlLLM.svg?style=social&label=Star)](https://github.com/OpenGVLab/ControlLLM)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://cllm.opengvlab.com/)\
**Tags:** `Image Understanding` `Image Generation` `Image Editing` `Video Understanding` `Video Generation` `Video Editing` `Audio Understanding` `Audio Generation`

+ **ImageBind-LLM: Multi-modality Instruction Tuning** (7 Sep 2023) <details><summary>Jiaming Han, Renrui Zhang, Wenqi Shao, et al.</summary>Jiaming Han, Renrui Zhang, Wenqi Shao, Peng Gao, Peng Xu, Han Xiao, Kaipeng Zhang, Chris Liu, Song Wen, Ziyu Guo, Xudong Lu, Shuai Ren, Yafei Wen, Xiaoxin Chen, Xiangyu Yue, Hongsheng Li, Yu Qiao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.03905)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F54c68b8623505dc6bf7a0b08aaa77ca9165f2d7f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ImageBind-LLM%3A-Multi-modality-Instruction-Tuning-Han-Zhang/54c68b8623505dc6bf7a0b08aaa77ca9165f2d7f)
[![Code](https://img.shields.io/github/stars/OpenGVLab/LLaMA-Adapter.svg?style=social&label=Star)](https://github.com/OpenGVLab/LLaMA-Adapter)\
**Modalities:** `text` `image` `video` `audio` `point cloud`

+ **ModelScope-Agent: Building Your Customizable Agent System with Open-source Large Language Models** (2 Sep 2023) <details><summary>Chenliang Li, Hehong Chen, Ming Yan, et al.</summary>Chenliang Li, Hehong Chen, Ming Yan, Weizhou Shen, Haiyang Xu, Zhikai Wu, Zhicheng Zhang, Wenmeng Zhou, Yingda Chen, Chen Cheng, Hongzhu Shi, Ji Zhang, Fei Huang, Jingren Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.00986)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe2f1f04f648a8863d11439aa4c80ee65d6caccda%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ModelScope-Agent%3A-Building-Your-Customizable-Agent-Li-Chen/e2f1f04f648a8863d11439aa4c80ee65d6caccda)
[![Code](https://img.shields.io/github/stars/modelscope/modelscope-agent.svg?style=social&label=Star)](https://github.com/modelscope/modelscope-agent)

+ **InternGPT: Solving Vision-Centric Tasks by Interacting with ChatGPT Beyond Language** (9 May 2023) <details><summary>Zhaoyang Liu, Yinan He, Wenhai Wang, et al.</summary>Zhaoyang Liu, Yinan He, Wenhai Wang, Weiyun Wang, Yi Wang, Shoufa Chen, Qinglong Zhang, Zeqiang Lai, Yang Yang, Qingyun Li, Jiashuo Yu, Kunchang Li, Zhe Chen, Xue Yang, Xizhou Zhu, Yali Wang, Limin Wang, Ping Luo, Jifeng Dai, Yu Qiao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05662)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F54a8b153ed04a872da878d695239bdc413dc782c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InternGPT%3A-Solving-Vision-Centric-Tasks-by-with-Liu-He/54a8b153ed04a872da878d695239bdc413dc782c)
[![Code](https://img.shields.io/github/stars/OpenGVLab/InternGPT.svg?style=social&label=Star)](https://github.com/OpenGVLab/InternGPT)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://igpt.opengvlab.com/)\
**Condition Modality:** `text` `image` `video` `audio`

+ **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face** (30 Mar 2023) <details><summary>Yongliang Shen, Kaitao Song, Xu Tan, et al.</summary>Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.17580)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd1120d67b700e4dfe8b39eb1e48fbdea4e1a0c43%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/HuggingGPT%3A-Solving-AI-Tasks-with-ChatGPT-and-its-Shen-Song/d1120d67b700e4dfe8b39eb1e48fbdea4e1a0c43)
[![Code](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)](https://github.com/microsoft/JARVIS)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/microsoft/HuggingGPT)

+ **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models** (8 Mar 2023) <details><summary>Chenfei Wu, Shengming Yin, Weizhen Qi, et al.</summary>Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.04671)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Faf997821231898a5f8d0fd78dad4eec526acabe5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Visual-ChatGPT%3A-Talking%2C-Drawing-and-Editing-with-Wu-Yin/af997821231898a5f8d0fd78dad4eec526acabe5)
[![Code](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)](https://github.com/moymix/TaskMatrix)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/microsoft/visual_chatgpt)

+ **AutoGPT: build & use AI agents**\
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://news.agpt.co/)
[![Code](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT.svg?style=social&label=Star)](https://github.com/Significant-Gravitas/AutoGPT)


# 📍 LLMs for Visual-audio Understanding
## Image Understanding
+ **InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks** (21 Dec 2023)<details><summary>Zhe Chen, Jiannan Wu, Wenhai Wang, et al.</summary>Zhe Chen, Jiannan Wu, Wenhai Wang, Weijie Su, Guo Chen, Sen Xing, Muyan Zhong, Qinglong Zhang, Xizhou Zhu, Lewei Lu, Bin Li, Ping Luo, Tong Lu, Yu Qiao, Jifeng Dai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14238)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6a33e58ef961a3a0a5657518b2be86395eb7c8d0%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InternVL%3A-Scaling-up-Vision-Foundation-Models-and-Chen-Wu/6a33e58ef961a3a0a5657518b2be86395eb7c8d0)
[![Code](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star)](https://github.com/OpenGVLab/InternVL)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://internvl.opengvlab.com/)

+ **LLaMA-VID: An Image is Worth 2 Tokens in Large Language Models** (28 Nov 2023)\
Yanwei Li, Chengyao Wang, Jiaya Jia\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17043)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F486c2df78cbb770a90a55f7fa3fe19102fba2c24%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LLaMA-VID%3A-An-Image-is-Worth-2-Tokens-in-Large-Li-Wang/486c2df78cbb770a90a55f7fa3fe19102fba2c24)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llama-vid.github.io/)
[![Code](https://img.shields.io/github/stars/dvlab-research/LLaMA-VID.svg?style=social&label=Star)](https://github.com/dvlab-research/LLaMA-VID)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](http://103.170.5.190:7864/)

+ **CogVLM: Visual Expert for Pretrained Language Models** (6 Nov 2023)<details><summary>Weihan Wang, Qingsong Lv, Wenmeng Yu, et al.</summary>Weihan Wang, Qingsong Lv, Wenmeng Yu, Wenyi Hong, Ji Qi, Yan Wang, Junhui Ji, Zhuoyi Yang, Lei Zhao, Xixuan Song, Jiazheng Xu, Bin Xu, Juanzi Li, Yuxiao Dong, Ming Ding, Jie Tang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.03079)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3bf842dec99016da2d309ea8cbd7e25343032317%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/CogVLM%3A-Visual-Expert-for-Pretrained-Language-Wang-Lv/3bf842dec99016da2d309ea8cbd7e25343032317)
[![Code](https://img.shields.io/github/stars/THUDM/CogVLM.svg?style=social&label=Star)](https://github.com/THUDM/CogVLM)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](http://36.103.203.44:7861/)

+ **MiniGPT-v2: large language model as a unified interface for vision-language multi-task learning** (14 Oct 2023)<details><summary>Jun Chen, Deyao Zhu, Xiaoqian Shen, et al.</summary>Jun Chen, Deyao Zhu, Xiaoqian Shen, Xiang Li, Zechun Liu, Pengchuan Zhang, Raghuraman Krishnamoorthi, Vikas Chandra, Yunyang Xiong, Mohamed Elhoseiny</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.09478)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1ddbd08ad8cf22a5c66c4242194c4286328533bf%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MiniGPT-v2%3A-large-language-model-as-a-unified-for-Chen-Zhu/1ddbd08ad8cf22a5c66c4242194c4286328533bf)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://minigpt-v2.github.io/)
[![Code](https://img.shields.io/github/stars/Vision-CAIR/MiniGPT-4.svg?style=social&label=Star)](https://github.com/Vision-CAIR/MiniGPT-4)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Vision-CAIR/MiniGPT-v2)

+ **OphGLM: Training an Ophthalmology Large Language-and-Vision Assistant based on Instructions and Dialogue** (21 Jun 2023)<details><summary>Weihao Gao, Zhuo Deng, Zhiyuan Niu, et al.</summary>Weihao Gao, Zhuo Deng, Zhiyuan Niu, Fuju Rong, Chucheng Chen, Zheng Gong, Wenze Zhang, Daimin Xiao, Fang Li, Zhenjie Cao, Zhaoyi Ma, Wenbin Wei, Lan Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.12174)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0f8d12775a4685575f1489796b5dee9e11fbdfb5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/OphGLM%3A-Training-an-Ophthalmology-Large-Assistant-Gao-Deng/0f8d12775a4685575f1489796b5dee9e11fbdfb5)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://minigpt-v2.github.io/)
[![Code](https://img.shields.io/github/stars/ML-AILab/OphGLM.svg?style=social&label=Star)](https://github.com/ML-AILab/OphGLM)


+ **InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition** (26 Sep 2023)<details><summary>Pan Zhang, Xiaoyi Dong, Bin Wang, et al.</summary> Pan Zhang, Xiaoyi Dong, Bin Wang, Yuhang Cao, Chao Xu, Linke Ouyang, Zhiyuan Zhao, Haodong Duan, Songyang Zhang, Shuangrui Ding, Wenwei Zhang, Hang Yan, Xinyue Zhang, Wei Li, Jingwen Li, Kai Chen, Conghui He, Xingcheng Zhang, Yu Qiao, Dahua Lin, Jiaqi Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15112)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc1e450284e7d6cac1855330a1197df8537df653f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InternLM-XComposer%3A-A-Vision-Language-Large-Model-Zhang-Wang/c1e450284e7d6cac1855330a1197df8537df653f)
[![Code](https://img.shields.io/github/stars/InternLM/InternLM-XComposer.svg?style=social&label=Star)](https://github.com/InternLM/InternLM-XComposer)

+ **[LaVIT] Unified Language-Vision Pretraining in LLM with Dynamic Discrete Visual Tokenization** (9 Sep 2023)<details><summary>Yang Jin, Kun Xu, Kun Xu, et al.</summary>Yang Jin, Kun Xu, Kun Xu, Liwei Chen, Chao Liao, Jianchao Tan, Quzhe Huang, Bin Chen, Chenyi Lei, An Liu, Chengru Song, Xiaoqiang Lei, Di Zhang, Wenwu Ou, Kun Gai, Yadong Mu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.04669)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbcac614f9774488447221ebb4f16f05e3975ec1e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Unified-Language-Vision-Pretraining-in-LLM-with-Jin-Xu/bcac614f9774488447221ebb4f16f05e3975ec1e)
[![Code](https://img.shields.io/github/stars/jy0205/LaVIT.svg?style=social&label=Star)](https://github.com/jy0205/LaVIT)

+ **NExT-GPT: Any-to-Any Multimodal LLM** (11 Sep 2023)<details><summary>Shengqiong Wu, Hao Fei, Leigang Qu, et al.</summary>Shengqiong Wu, Hao Fei, Leigang Qu, Wei Ji, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.05519)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ffa75a55760e6ea49b39b83cb85c99a22e1088254%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/NExT-GPT%3A-Any-to-Any-Multimodal-LLM-Wu-Fei/fa75a55760e6ea49b39b83cb85c99a22e1088254)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://next-gpt.github.io/)
[![Code](https://img.shields.io/github/stars/NExT-GPT/NExT-GPT.svg?style=social&label=Star)](https://github.com/NExT-GPT/NExT-GPT)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://1ca8b1601858a12830.gradio.live/)

+ **Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond** (24 Aug 2023)<details><summary>Jinze Bai, Shuai Bai, Shusheng Yang, et al.</summary>Jinze Bai, Shuai Bai, Shusheng Yang, Shijie Wang, Sinan Tan, Peng Wang, Junyang Lin, Chang Zhou, Jingren Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.12966)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ffc6a2f7478f68adefd69e2071f27e38aa1647f2f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Qwen-VL%3A-A-Versatile-Vision-Language-Model-for-Text-Bai-Bai/fc6a2f7478f68adefd69e2071f27e38aa1647f2f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://github.com/QwenLM/Qwen-VL/blob/master/TUTORIAL.md)
[![Code](https://img.shields.io/github/stars/QwenLM/Qwen-VL.svg?style=social&label=Star)](https://github.com/QwenLM/Qwen-VL)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://modelscope.cn/studios/qwen/Qwen-VL-Chat-Demo/summary)

+ **VisionLLM: Large Language Model is also an Open-Ended Decoder for Vision-Centric Tasks** (18 May 2023)<details><summary>Wenhai Wang, Zhe Chen, Xiaokang Chen, et al. NeurIPS 2023.</summary>Wenhai Wang, Zhe Chen, Xiaokang Chen, Jiannan Wu, Xizhou Zhu, Gang Zeng, Ping Luo, Tong Lu, Jie Zhou, Yu Qiao, Jifeng Dai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11175)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F42a30dc5470f54ec249f25d3c31e05d7c376c8e3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VisionLLM%3A-Large-Language-Model-is-also-an-Decoder-Wang-Chen/42a30dc5470f54ec249f25d3c31e05d7c376c8e3)
[![Code](https://img.shields.io/github/stars/OpenGVLab/VisionLLM.svg?style=social&label=Star)](https://github.com/OpenGVLab/VisionLLM)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://github.com/OpenGVLab/InternGPT)

+ **InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning** (11 May 2023)<details><summary>Wenliang Dai, Junnan Li, Dongxu Li, et al.</summary>Wenliang Dai, Junnan Li, Dongxu Li, Anthony Meng Huat Tiong, Junqi Zhao, Weisheng Wang, Boyang Li, Pascale Fung, Steven Hoi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.06500)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8bd6a2a89503be083176f2cc26fabedb79238cbd%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/InstructBLIP%3A-Towards-General-purpose-Models-with-Dai-Li/8bd6a2a89503be083176f2cc26fabedb79238cbd)
[![Code](https://img.shields.io/github/stars/QwenLM/Qwen-VL.svg?style=social&label=Star)](https://github.com/QwenLM/Qwen-VL)

+ **MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models** (20 Apr 2023)<details><summary>Deyao Zhu, Jun Chen, Xiaoqian Shen, et al.</summary>Deyao Zhu, Jun Chen, Xiaoqian Shen, Xiang Li, Mohamed Elhoseiny</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.10592)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fca6a2bc279be5a3349a22bfd6866ed633d18734b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MiniGPT-4%3A-Enhancing-Vision-Language-Understanding-Zhu-Chen/ca6a2bc279be5a3349a22bfd6866ed633d18734b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://minigpt-4.github.io/)
[![Code](https://img.shields.io/github/stars/Vision-CAIR/MiniGPT-4.svg?style=social&label=Star)](https://github.com/Vision-CAIR/MiniGPT-4)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Vision-CAIR/MiniGPT-v2)

+ **Visual Instruction Tuning** (17 Apr 2023)<details><summary>Liu, Haotian, et al. NeurIPS 2023 (Oral).</summary>Haotian Liu, Chunyuan Li, Qingyang Wu, Yong Jae Lee</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08485)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1a8eb2cae1833df3bf12fe3b41b03d60b4a4a98d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Visual-Instruction-Tuning-Liu-Li/1a8eb2cae1833df3bf12fe3b41b03d60b4a4a98d)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llava-vl.github.io/)
[![Code](https://img.shields.io/github/stars/haotian-liu/LLaVA.svg?style=social&label=Star)](https://github.com/haotian-liu/LLaVA)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://llava.hliu.cc/)


## Video Understanding
+ **MovieChat: From Dense Token to Sparse Memory for Long Video Understanding**  (3 Dec 2023) \
Enxin, Song, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.16449)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6f9b7c8cde1be2e62a503c31cac883c6d44c9d0d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MovieChat%3A-From-Dense-Token-to-Sparse-Memory-for-Song-Chai/6f9b7c8cde1be2e62a503c31cac883c6d44c9d0d)
[![Code](https://img.shields.io/github/stars/rese1f/MovieChat.svg?style=social&label=Star)](https://github.com/rese1f/MovieChat)

+ **LLaMA-VID: An Image is Worth 2 Tokens in Large Language Models**  (28 Nov 2023) \
Yanwei, Li, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17043)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F486c2df78cbb770a90a55f7fa3fe19102fba2c24%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LLaMA-VID%3A-An-Image-is-Worth-2-Tokens-in-Large-Li-Wang/486c2df78cbb770a90a55f7fa3fe19102fba2c24)
[![Code](https://img.shields.io/github/stars/dvlab-research/LLaMA-VID.svg?style=social&label=Star)](https://github.com/dvlab-research/LLaMA-VID)

+ **Video-Bench: A Comprehensive Benchmark and Toolkit for Evaluating Video-based Large Language Models** (27 Nov 2023)\
Ning, Munan, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16103)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb037bb09aa162d8a543e64ec777ca0edc732d2af%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Video-Bench%3A-A-Comprehensive-Benchmark-and-Toolkit-Ning-Zhu/b037bb09aa162d8a543e64ec777ca0edc732d2af)
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Video-Bench.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Video-Bench)

+ **PG-Video-LLaVA: Pixel Grounding Large Video-Language Models** (22 Nov 2023)\
Munasinghe, Shehan, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.13435)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4edbb942c2d20a6f5a4e3caa763a9761be953231%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/PG-Video-LLaVA%3A-Pixel-Grounding-Large-Models-Munasinghe-Thushara/4edbb942c2d20a6f5a4e3caa763a9761be953231)
[![Code](https://img.shields.io/github/stars/mbzuai-oryx/Video-LLaVA.svg?style=social&label=Star)](https://github.com/mbzuai-oryx/Video-LLaVA)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mbzuai-oryx.github.io/Video-LLaVA/)

+ **Video-LLaVA: Learning United Visual Representation by Alignment Before Projection** (16 Nov 2023)\
Lin, Bin, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10122)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F107fb6eec2febbae12db29bf3e311aaf5680027c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Video-LLaVA%3A-Learning-United-Visual-Representation-Lin-Zhu/107fb6eec2febbae12db29bf3e311aaf5680027c)
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Video-LLaVA.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Video-LLaVA)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/LanguageBind/Video-LLaVA)

+ **Chat-UniVi: Unified Visual Representation Empowers Large Language Models with Image and Video Understanding** (14 Nov 2023)\
Jin, Peng, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.08046)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Faad3d2e690f6c73f04a14622ceff51464bbc560e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Chat-UniVi%3A-Unified-Visual-Representation-Empowers-Jin-Takanobu/aad3d2e690f6c73f04a14622ceff51464bbc560e)
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Chat-UniVi.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Chat-UniVi)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Chat-UniVi/Chat-UniVi)


+ **Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video Understanding** (5 Jun 2023)\
Zhang, Hang, Xin Li, and Lidong Bing. EMNLP 2023's demo track. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.02858)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5d321194696f1f75cf9da045e6022b2f20ba5b9c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Video-LLaMA%3A-An-Instruction-tuned-Audio-Visual-for-Zhang-Li/5d321194696f1f75cf9da045e6022b2f20ba5b9c)
[![Code](https://img.shields.io/github/stars/DAMO-NLP-SG/Video-LLaMA.svg?style=social&label=Star)](https://github.com/DAMO-NLP-SG/Video-LLaMA)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/DAMO-NLP-SG/Video-LLaMA)

+ **AntGPT: Can Large Language Models Help Long-term Action Anticipation from Videos?** (31 Jul 2023)\
Zhao, Qi, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.16368)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6024f320e0a5b9b8fc29b86903aa9a96956b26dd%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/AntGPT%3A-Can-Large-Language-Models-Help-Long-term-Zhao-Zhang/6024f320e0a5b9b8fc29b86903aa9a96956b26dd)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://brown-palm.github.io/AntGPT/)

+ **Valley: Video Assistant with Large Language model Enhanced ability** (12 Jun 2023)\
Luo, Ruipu, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.07207)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4c4d176c6e28f48041f215d563f6ee8633534cff%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Valley%3A-Video-Assistant-with-Large-Language-model-Luo-Zhao/4c4d176c6e28f48041f215d563f6ee8633534cff)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://valley-vl.github.io/)
[![Code](https://img.shields.io/github/stars/RupertLuo/Valley.svg?style=social&label=Star)](https://github.com/RupertLuo/Valley)

+ **Video-ChatGPT: Towards Detailed Video Understanding via Large Vision and Language Models** (8 Jun 2023)\
Muhammad Maaz, Hanoona Rasheed, Salman Khan, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.05424)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbf7025a2e5dbb3c09deae02a1aa98a256ca559e2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Video-ChatGPT%3A-Towards-Detailed-Video-Understanding-Maaz-Rasheed/bf7025a2e5dbb3c09deae02a1aa98a256ca559e2)
[![Code](https://img.shields.io/github/stars/mbzuai-oryx/Video-ChatGPT.svg?style=social&label=Star)](https://github.com/mbzuai-oryx/Video-ChatGPT)

+ **VideoChat: Chat-Centric Video Understanding** (10 May 2023)\
Li, KunChang, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.06355)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd48cb91b9e555194f7494c4d4bb9815021d3ee45%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoChat%3A-Chat-Centric-Video-Understanding-Li-He/d48cb91b9e555194f7494c4d4bb9815021d3ee45)
[![Code](https://img.shields.io/github/stars/OpenGVLab/Ask-Anything.svg?style=social&label=Star)](https://github.com/OpenGVLab/Ask-Anything)

+ **VideoLLM: Modeling Video Sequence with Large Language Models** (22 May 2023)\
Chen, Guo, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13292)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff9bfc6d9ba1665b73af3323d46c7642b852759ef%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/VideoLLM%3A-Modeling-Video-Sequence-with-Large-Models-Chen-Zheng/f9bfc6d9ba1665b73af3323d46c7642b852759ef)
[![Code](https://img.shields.io/github/stars/cg1177/VideoLLM.svg?style=social&label=Star)](https://github.com/cg1177/VideoLLM)

+ **Learning video embedding space with Natural Language Supervision** (25 Mar 2023)\
Uppala, Phani Krishna, Shriti Priya, and Vaidehi Joshi.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14584)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4e54a45d2118b61ae1baec07308af3fdd2c48759%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Learning-video-embedding-space-with-Natural-Uppala-Bamotra/4e54a45d2118b61ae1baec07308af3fdd2c48759)



<<<<<<< HEAD
## 3D
+ **LiDAR-LLM: Exploring the Potential of Large Language Models for 3D LiDAR Understanding** (19 Nov 2023)<details><summary>Senqiao Yang, Jiaming Liu, Ray Zhang, et al.</summary>Senqiao Yang, Jiaming Liu, Ray Zhang, Mingjie Pan, Zoey Guo, Xiaoqi Li, Zehui Chen, Peng Gao, Yandong Guo, Shanghang Zhang</details>
=======
## 3D Understanding

+ **LiDAR-LLM: Exploring the Potential of Large Language Models for 3D LiDAR Understanding** (21 Dec 2023)\
Senqiao Yang*, Jiaming Liu*, Ray Zhang, et al.\
>>>>>>> 4cc6ea21ba22fb7e33e3132587355aa12e1abc19
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14074)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5edf706467dc76cd09319592d18db0ad4e1fb64d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LiDAR-LLM%3A-Exploring-the-Potential-of-Large-Models-Yang-Liu/5edf706467dc76cd09319592d18db0ad4e1fb64d)

+ **3D-LLM: Injecting the 3D World into Large Language Models** (24 Jul 2023)<details><summary>Yining Hong, Haoyu Zhen, Peihao Chen, et al. (NeurIPS 2023 Spotlight)</summary>Yining Hong, Haoyu Zhen, Peihao Chen, Shuhong Zheng, Yilun Du, Zhenfang Chen, Chuang Gan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.12981)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7637ed79d30d0139901175ae4abedd822c217ab4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/3D-LLM%3A-Injecting-the-3D-World-into-Large-Language-Hong-Zhen/7637ed79d30d0139901175ae4abedd822c217ab4)
[![Code](https://img.shields.io/github/stars/UMass-Foundation-Model/3D-LLM.svg?style=social&label=Star)](https://github.com/UMass-Foundation-Model/3D-LLM)

+ **PointLLM: Empowering Large Language Models to Understand Point Clouds** (31 Aug 2023)<details><summary>Runsen Xu, Xiaolong Wang, Tai Wang, et al. (NeurIPS 2023 Spotlight)</summary>Runsen Xu, Xiaolong Wang, Tai Wang, Yilun Chen, Jiangmiao Pang, Dahua Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2308.16911.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6bcc6ab9c28805d4067e99b2cdc7524550fe80e1%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/PointLLM%3A-Empowering-Large-Language-Models-to-Point-Xu-Wang/6bcc6ab9c28805d4067e99b2cdc7524550fe80e1)
[![Code](https://img.shields.io/github/stars/OpenRobotLab/PointLLM.svg?style=social&label=Star)](https://github.com/OpenRobotLab/PointLLM)

+ **PointCLIP: Point Cloud Understanding by CLIP** (31 Aug 2023)<details><summary>Renrui Zhang, Ziyu Guo, Wei Zhang,, et al. (CVPR2022)</summary>Renrui Zhang, Ziyu Guo, Wei Zhang, Kunchang Li, Xupeng Miao, Bin Cui, Yu Qiao, Peng Gao, Hongsheng Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2112.02413.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff3ce9ba3fcec362b70263a7ed63d9404975496a0%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/PointCLIP%3A-Point-Cloud-Understanding-by-CLIP-Zhang-Guo/f3ce9ba3fcec362b70263a7ed63d9404975496a0)
[![Code](https://img.shields.io/github/stars/ZrrSkywalker/PointCLIP.svg?style=social&label=Star)](https://github.com/ZrrSkywalker/PointCLIP)



## Audio Understanding
+ **Audiogpt: Understanding and generating speech, music, sound, and talking head** (25 Apr 2023)<details><summary>Rongjie Huang, Mingze Li, Dongchao Yang, et al.</summary>Rongjie Huang, Mingze Li, Dongchao Yang, Jiatong Shi, Xuankai Chang, Zhenhui Ye, Yuning Wu, Zhiqing Hong, Jiawei Huang, Jinglin Liu, Yi Ren, Zhou Zhao, Shinji Watanabe</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.12995)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8bc617c9139648d7a92991d70c671230bac7b2e2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/AudioGPT%3A-Understanding-and-Generating-Speech%2C-and-Huang-Li/8bc617c9139648d7a92991d70c671230bac7b2e2)
[![Code](https://img.shields.io/github/stars/AIGC-Audio/AudioGPT.svg?style=social&label=Star)](https://github.com/AIGC-Audio/AudioGPT)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/AIGC-Audio/AudioGPT)

+ **Joint Audio and Speech Understanding** (25 Sep 2023)<details><summary>Yuan Gong, Alexander H. Liu, Hongyin Luo, et al.</summary>Yuan Gong, Alexander H. Liu, Hongyin Luo, Leonid Karlinsky, James Glass</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14405)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc14db8b4c1bd65a18a604236cdbc3549ee75f3bd%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Joint-Audio-and-Speech-Understanding-Gong-Liu/c14db8b4c1bd65a18a604236cdbc3549ee75f3bd)
[![Code](https://img.shields.io/github/stars/yuangongnd/ltu.svg?style=social&label=Star)](https://github.com/yuangongnd/ltu)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/yuangongfdu/ltu-2)

+ **M2UGen: Multi-modal Music Understanding and Generation with the Power of Large Language Models** (19 Nov 2023)<details><summary>Atin Sakkeer Hussain, Shansong Liu, Chenshuo Sun, et al.</summary>Atin Sakkeer Hussain, Shansong Liu, Chenshuo Sun, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11255)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1e84d7c45f70038574fcdb7bc1b20da9b348a092%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/M2UGen%3A-Multi-modal-Music-Understanding-and-with-of-Hussain-Liu/1e84d7c45f70038574fcdb7bc1b20da9b348a092)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://crypto-code.github.io/M2UGen-Demo/)
[![Code](https://img.shields.io/github/stars/shansongliu/M2UGen.svg?style=social&label=Star)](https://github.com/shansongliu/M2UGen)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/M2UGen/M2UGen-Demo)

+ **Unified-IO 2: Scaling Autoregressive Multimodal Models with Vision, Language, Audio, and Action** (28 Dec 2023)<details><summary>Jiasen Lu, Christopher Clark, Sangho Lee, et al.</summary>Jiasen Lu, Christopher Clark, Sangho Lee, Zichen Zhang, Savya Khosla, Ryan Marten, Derek Hoiem, Aniruddha Kembhavi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.17172)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6c64ddd2190909de2c680dd18abc9b92e80c39f9%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Unified-IO-2%3A-Scaling-Autoregressive-Multimodal-and-Lu-Clark/6c64ddd2190909de2c680dd18abc9b92e80c39f9)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://unified-io-2.allenai.org/)
[![Code](https://img.shields.io/github/stars/allenai/unified-io-2.svg?style=social&label=Star)](https://github.com/allenai/unified-io-2)


# 📍 Multimodal LLM Safety
## Attack
+ **Ignore previous prompt: Attack techniques for language models** (17 Nov 2022)\
Fábio Perez, Ian Ribeiro\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.09527.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8fdd34153d1035d09dd4a6efa9cb0c91d23d0045?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/More-than-you%27ve-asked-for%3A-A-Comprehensive-of-to-Greshake-Abdelnabi/8fdd34153d1035d09dd4a6efa9cb0c91d23d0045?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/agencyenterprise/PromptInject.svg?style=social&label=Star)](https://github.com/agencyenterprise/PromptInject)

+ **Adversarial Examples for Evaluating Reading Comprehension Systems** (23 Jul 2017)\
Robin Jia, Percy Liang\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1707.07328.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fffb949d3493c3b2f3c9acf9c75cb03938933ddf0?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Adversarial-Examples-for-Evaluating-Reading-Systems-Jia-Liang/ffb949d3493c3b2f3c9acf9c75cb03938933ddf0?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/robinjia/adversarial-squad.svg?style=social&label=Star)](https://github.com/robinjia/adversarial-squad)

+ **Prompt injection attack against llm-integrated applications** (8 Jun 2023)<details><summary>Yi Liu, Gelei Deng, Yuekang Li, et al.</summary>Yi Liu, Gelei Deng, Yuekang Li, Kailong Wang, Tianwei Zhang, Yepang Liu, Haoyu Wang, Yan Zheng, Yang Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2306.05499.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdb4cf9f6a653d5c15973e836c800ea47743251ae?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Prompt-Injection-attack-against-LLM-integrated-Liu-Deng/db4cf9f6a653d5c15973e836c800ea47743251ae?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/liu00222/Open-Prompt-Injection.svg?style=social&label=Star)](https://github.com/liu00222/Open-Prompt-Injection)

+ **Defending chatgpt against jailbreak attack via self-reminders.** (Dec 2023)<details><summary>Yueqi Xie, Jingwei Yi, Jiawei Shao, et al.</summary>Yueqi Xie, Jingwei Yi, Jiawei Shao, Justin Curl, Lingjuan Lyu, Qifeng Chen, Xing Xie, Fangzhao Wu </details>
[![Code](https://img.shields.io/github/stars/yjw1029/Self-Reminder.svg?style=social&label=Star)](https://github.com/yjw1029/Self-Reminder)

+ **Exploiting programmatic behavior of llms: Dual-use through standard security attacks.** (11 Feb 2023)<details><summary>Daniel Kang, Xuechen Li, Ion Stoica, et al.</summary>Daniel Kang, Xuechen Li, Ion Stoica, Carlos Guestrin, Matei Zaharia, Tatsunori Hashimoto</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2302.05733.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0cf694b8f85ab2e11d45595de211a15cfbadcd22?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Exploiting-Programmatic-Behavior-of-LLMs%3A-Dual-Use-Kang-Li/0cf694b8f85ab2e11d45595de211a15cfbadcd22?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/chawins/llm-sp.svg?style=social&label=Star)](https://github.com/chawins/llm-sp)

+ **Universal Adversarial Triggers for Attacking and Analyzing NLP** (20 Aug 2019)<details><summary>Eric Wallace, Shi Feng, Nikhil Kandpal, et al.</summary>Eric Wallace, Shi Feng, Nikhil Kandpal, Matt Gardner, Sameer Singh</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/1908.07125.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F18a1c21f35153c45d0ef30c564bffb7d70a13ccc?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Universal-Adversarial-Triggers-for-Attacking-and-Wallace-Feng/18a1c21f35153c45d0ef30c564bffb7d70a13ccc?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/robinjia/adversarial-squad.svg?style=social&label=Star)](https://github.com/robinjia/adversarial-squad)

+ **Automatically Auditing Large Language Models via Discrete Optimization** (8 Mar 2023)<details><summary>Erik Jones, Anca Dragan, Aditi Raghunathan, et al.</summary>Erik Jones, Anca Dragan, Aditi Raghunathan, Jacob Steinhardt</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2303.04381.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2f94f03fdac62d05f0f416b7b3855d1f597afee9?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Automatically-Auditing-Large-Language-Models-via-Jones-Dragan/2f94f03fdac62d05f0f416b7b3855d1f597afee9?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/ejones313/auditing-llms.svg?style=social&label=Star)](https://github.com/ejones313/auditing-llms)

+ **Universal and Transferable Adversarial Attacks on Aligned Language Models** (27 Jul 2023)<details><summary>Andy Zou, Zifan Wang, Nicholas Carlini, et al.</summary>Andy Zou, Zifan Wang, Nicholas Carlini, Milad Nasr, J. Zico Kolter, Matt Fredrikson</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2307.15043.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F47030369e97cc44d4b2e3cf1be85da0fd134904a?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Universal-and-Transferable-Adversarial-Attacks-on-Zou-Wang/47030369e97cc44d4b2e3cf1be85da0fd134904a?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/llm-attacks/llm-attacks.svg?style=social&label=Star)](https://github.com/llm-attacks/llm-attacks)

+ **Misusing Tools in Large Language Models With Visual Adversarial Examples** (4 Oct 2023)<details><summary>Xiaohan Fu, Zihan Wang, Shuheng Li, et al.</summary>Xiaohan Fu, Zihan Wang, Shuheng Li, Rajesh K. Gupta, Niloofar Mireshghallah, Taylor Berg-Kirkpatrick, Earlence Fernandes</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2310.03185.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F142e934dd5d6c53f877c30243d436255e3a0dde7?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Visual-Adversarial-Examples-Jailbreak-Aligned-Large-Qi-Huang/142e934dd5d6c53f877c30243d436255e3a0dde7?utm_source=direct_link)

+ **Image Hijacks: Adversarial Images can Control Generative Models at Runtime.** (18 Sep 2023)<details><summary>Luke Bailey, Euan Ong, Stuart Russell, et al.</summary>Luke Bailey, Euan Ong, Stuart Russell, Scott Emmons</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2309.00236.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F92b9d8b8c81c4c53ea62000c0924500b2dd11bce?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Jailbreak-in-pieces%3A-Compositional-Adversarial-on-Shayegani-Dong/92b9d8b8c81c4c53ea62000c0924500b2dd11bce?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/euanong/image-hijacks.svg?style=social&label=Star)](https://github.com/euanong/image-hijacks)

+ **Jailbreaking gpt-4v via self-adversarial attacks with system prompts.** (20 Jan 2024)<details><summary>Yuanwei Wu, Xiang Li, Yixin Liu, et al.</summary>Yuanwei Wu, Xiang Li, Yixin Liu, Pan Zhou, Lichao Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2311.09127.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F18a8b97d75a87e8fef07542d8875d4a62b553744?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Jailbreaking-GPT-4V-via-Self-Adversarial-Attacks-Wu-Li/18a8b97d75a87e8fef07542d8875d4a62b553744?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/ThuCCSLab/lm-ssp.svg?style=social&label=Star)](https://github.com/ThuCCSLab/lm-ssp)

+ **Poisoning Web-Scale Training Datasets is Practical** (20 Feb 2023)<details><summary>Nicholas Carlini, Matthew Jagielski, Christopher A. Choquette-Choo, et al.</summary>Nicholas Carlini, Matthew Jagielski, Christopher A. Choquette-Choo, Daniel Paleka, Will Pearce, Hyrum Anderson, Andreas Terzis, Kurt Thomas, Florian Tramèr</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2302.10149.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2cf43a61d0937ad25f23eaef7c90253ab799b3c7?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Poisoning-Web-Scale-Training-Datasets-is-Practical-Carlini-Jagielski/2cf43a61d0937ad25f23eaef7c90253ab799b3c7?utm_source=direct_link)



## Defense and Detect


+ **Smoothllm: Defending large language models against jailbreaking attacks.** (5 Oct 2023)<details><summary>Alexander Robey, Eric Wong, Hamed Hassani, et al.</summary>Alexander Robey, Eric Wong, Hamed Hassani, George J. Pappas</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2310.03684.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8cf9b49698fdb1b754df2556576412a7b44929f6?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/SmoothLLM%3A-Defending-Large-Language-Models-Against-Robey-Wong/8cf9b49698fdb1b754df2556576412a7b44929f6?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/chawins/llm-sp.svg?style=social&label=Star)](https://github.com/chawins/llm-sp)

+ **Jailbreak and guard aligned language models with only few in-context demonstrations** (10 Oct 2023)\
Zeming Wei, Yifei Wang, Yisen Wang\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2310.06387.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8fd29e810540c40846cddce3cbdf5060cd59fb57?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Intention-Analysis-Makes-LLMs-A-Good-Jailbreak-Zhang-Ding/8fd29e810540c40846cddce3cbdf5060cd59fb57?utm_source=direct_link)

+ **Unsafe Diffusion: On the Generation of Unsafe Images and Hateful Memes From Text-To-Image Models** (23 May 2023)<details><summary>Yiting Qu, Xinyue Shen, Xinlei He, et al.</summary>Yiting Qu, Xinyue Shen, Xinlei He, Michael Backes, Savvas Zannettou, Yang Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2305.13873.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F91d85905a8e9ae6ba62e562bba32d61c619a8155?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Groot%3A-Adversarial-Testing-for-Generative-Models-Liu-Yang/91d85905a8e9ae6ba62e562bba32d61c619a8155?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/YitingQu/unsafe-diffusion.svg?style=social&label=Star)](https://github.com/YitingQu/unsafe-diffusion)

+ **Mitigating Inappropriate Degeneration in Diffusion Models** (9 Nov 2022)<details><summary>Patrick Schramowski, Manuel Brack, Björn Deiseroth, et al.</summary>Patrick Schramowski, Manuel Brack, Björn Deiseroth, Kristian Kersting</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2211.05105.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F35805599dcc62ab5f02257c94977092a3b993b54?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Self-Discovering-Interpretable-Diffusion-Latent-for-Li-Shen/35805599dcc62ab5f02257c94977092a3b993b54?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/ml-research/safe-latent-diffusion.svg?style=social&label=Star)](https://github.com/ml-research/safe-latent-diffusion)

+ **A Watermark for Large Language Models** (6 Jun 2023)<details><summary>John Kirchenbauer, Jonas Geiping, Yuxin Wen, et al.</summary>John Kirchenbauer, Jonas Geiping, Yuxin Wen, Jonathan Katz, Ian Miers, Tom Goldstein</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2301.10226.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fcb5b71a622aff47014d4f28a958679629a8b6363?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/A-Watermark-for-Large-Language-Models-Kirchenbauer-Geiping/cb5b71a622aff47014d4f28a958679629a8b6363?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/BrianPulfer/LMWatermark.svg?style=social&label=Star)](https://github.com/BrianPulfer/LMWatermark)

+ **TRAK: Attributing Model Behavior at Scale** (3 Apr 2023)<details><summary>Sung Min Park, Kristian Georgiev, Andrew Ilyas, et al.</summary>Sung Min Park, Kristian Georgiev, Andrew Ilyas, Guillaume Leclerc, Aleksander Madry</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2303.14186.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4f2ae5fa2dc74af9c36ee57b359a4b3241006a92?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/TRAK%3A-Attributing-Model-Behavior-at-Scale-Park-Georgiev/4f2ae5fa2dc74af9c36ee57b359a4b3241006a92?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/MadryLab/trak.svg?style=social&label=Star)](https://github.com/MadryLab/trak)

+ **Extracting Training Data from Large Language Models** (15 Jun 2021)<details><summary>Nicholas Carlini, Florian Tramer, Eric Wallace, et al.</summary>Nicholas Carlini, Florian Tramer, Eric Wallace, Matthew Jagielski, Ariel Herbert-Voss, Katherine Lee, Adam Roberts, Tom Brown, Dawn Song, Ulfar Erlingsson, Alina Oprea, Colin Raffel</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2012.07805.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdf7d26339adf4eb0c07160947b9d2973c24911ba?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Extracting-Training-Data-from-Large-Language-Models-Carlini-Tram%C3%A8r/df7d26339adf4eb0c07160947b9d2973c24911ba?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/weichen-yu/LM-Extraction.svg?style=social&label=Star)](https://github.com/weichen-yu/LM-Extraction)

+ **Detecting Pretraining Data from Large Language Models** (3 Nov 2023)<details><summary>Weijia Shi, Anirudh Ajith, Mengzhou Xia, et al.</summary>Weijia Shi, Anirudh Ajith, Mengzhou Xia, Yangsibo Huang, Daogao Liu, Terra Blevins, Danqi Chen, Luke Zettlemoyer</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2310.16789.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3422d5e0cdfdc935d6a84a1e3d3f96659265fe3a?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Detecting-Pretraining-Data-from-Large-Language-Shi-Ajith/3422d5e0cdfdc935d6a84a1e3d3f96659265fe3a?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/swj0419/detect-pretrain-code.svg?style=social&label=Star)](https://github.com/swj0419/detect-pretrain-code)

+ **Detecting and correcting hate speech in multimodal memes with large visual language model.** (12 Nov 2023)\
Minh-Hao Van, Xintao Wu\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2311.06737.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F60f4dc690ea42fb77b04fc685e9d9c3a1e209319?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Detecting-and-Correcting-Hate-Speech-in-Multimodal-Van-Wu/60f4dc690ea42fb77b04fc685e9d9c3a1e209319?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/harjeet-blue/Multimodal-hateful-meme-detection.svg?style=social&label=Star)](https://github.com/harjeet-blue/Multimodal-hateful-meme-detection)




## Alignment

+ **Scalable agent alignment via reward modeling: a research direction** (19 Nov 2018)<details><summary>Jan Leike, David Krueger, Tom Everitt, et al.</summary>Jan Leike, David Krueger, Tom Everitt, Miljan Martic, Vishal Maini, Shane Legg</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/1811.07871.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc6f913e4baa7f2c85363c0625c87003ad3b3a14c?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Scalable-agent-alignment-via-reward-modeling%3A-a-Leike-Krueger/c6f913e4baa7f2c85363c0625c87003ad3b3a14c?utm_source=direct_link)

+ **Proximal policy optimization algorithms** (20 Jul 2017)<details><summary>John Schulman, Filip Wolski, Prafulla Dhariwal, et al.</summary>John Schulman, Filip Wolski, Prafulla Dhariwal, Alec Radford, Oleg Klimov</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/1707.06347.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdce6f9d4017b1785979e7520fd0834ef8cf02f4b?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Proximal-Policy-Optimization-Algorithms-Schulman-Wolski/dce6f9d4017b1785979e7520fd0834ef8cf02f4b?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/morikatron/PPO.svg?style=social&label=Star)](https://github.com/morikatron/PPO)

+ **Direct Preference Optimization: Your Language Model is Secretly a Reward Model** (13 Dec 2023)<details><summary>Rafael Rafailov, Archit Sharma, Eric Mitchell, et al.</summary>Rafael Rafailov, Archit Sharma, Eric Mitchell, Stefano Ermon, Christopher D. Manning, Chelsea Finn</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2305.18290.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0d1c76d45afa012ded7ab741194baf142117c495?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Direct-Preference-Optimization%3A-Your-Language-Model-Rafailov-Sharma/0d1c76d45afa012ded7ab741194baf142117c495?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/lucidrains/self-rewarding-lm-pytorch.svg?style=social&label=Star)](https://github.com/lucidrains/self-rewarding-lm-pytorch)

+ **Better aligning text-to-image models with human preference** (22 Aug 2023)<details><summary>Xiaoshi Wu, Keqiang Sun, Feng Zhu, et al.</summary>Xiaoshi Wu, Keqiang Sun, Feng Zhu, Rui Zhao, Hongsheng Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2303.14420.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F14c3cf58192774b9b6fc6188df99efd6ab5fc739?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Better-Aligning-Text-to-Image-Models-with-Human-Wu-Sun/14c3cf58192774b9b6fc6188df99efd6ab5fc739?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/tgxs002/align_sd.svg?style=social&label=Star)](https://github.com/tgxs002/align_sd)

+ **Raft: Reward ranked fine tuning for generative foundation model alignment** (1 Dec 2023)<details><summary>Hanze Dong, Wei Xiong, Deepanshu Goyal, et al.</summary>Hanze Dong, Wei Xiong, Deepanshu Goyal, Yihan Zhang, Winnie Chow, Rui Pan, Shizhe Diao, Jipeng Zhang, Kashun Shum, Tong Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2304.06767.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3ab661db57d924f4ff1706e05ac807873ca00e0a?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/RAFT%3A-Reward-rAnked-FineTuning-for-Generative-Model-Dong-Xiong/3ab661db57d924f4ff1706e05ac807873ca00e0a?utm_source=direct_link)
<!-- [![Code](https://img.shields.io/github/stars/https://optimalscale.github.io/LMFlow/examples/raft.html.svg?style=social&label=Star)](https://optimalscale.github.io/LMFlow/examples/raft.html) -->

## Datasets

+ **Can pre-trained vision and language models answer visual information-seeking questions?** (17 Oct 2023)<details><summary>Yang Chen, Hexiang Hu, Yi Luan, et al.</summary>Yang Chen, Hexiang Hu, Yi Luan, Haitian Sun, Soravit Changpinyo, Alan Ritter, Ming-Wei Chang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2302.11713.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff890b4dfe915174b23db909b07c515d465eaeff2?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Can-Pre-trained-Vision-and-Language-Models-Answer-Chen-Hu/f890b4dfe915174b23db909b07c515d465eaeff2?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/edchengg/infoseek_eval.svg?style=social&label=Star)](https://github.com/edchengg/infoseek_eval)

+ **Can language models be instructed to protect personal information?** (3 Oct 2023)<details><summary>Yang Chen, Ethan Mendes, Sauvik Das, et al.</summary>Yang Chen, Ethan Mendes, Sauvik Das, Wei Xu, Alan Ritter</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2310.02224.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2403c8e72a90d9c778970fc0812ecdcc58800c5d?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/Can-Language-Models-be-Instructed-to-Protect-Chen-Mendes/2403c8e72a90d9c778970fc0812ecdcc58800c5d?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/ethanm88/llm-access-control.svg?style=social&label=Star)](https://github.com/ethanm88/llm-access-control)

+ **Goat-bench: Safety insights to large multimodal models through meme-based social abuse.** (7 Jan 2024)<details><summary>Hongzhan Lin, Ziyang Luo, Bo Wang, et al.</summary>Hongzhan Lin, Ziyang Luo, Bo Wang, Ruichao Yang, Jing Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2401.01523.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd98aa44f79fe798ad5ff0cac6e7bf32ee30bd156?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/GOAT-Bench%3A-Safety-Insights-to-Large-Multimodal-Lin-Luo/d98aa44f79fe798ad5ff0cac6e7bf32ee30bd156?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/isXinLiu/MLLM-Safety-Collection.svg?style=social&label=Star)](https://github.com/isXinLiu/MLLM-Safety-Collection)

+ **Safety assessment of chinese large language models** (20 Apr 2023)<details><summary>Hao Sun, Zhexin Zhang, Jiawen Deng, et al.</summary>Hao Sun, Zhexin Zhang, Jiawen Deng, Jiale Cheng, Minlie Huang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2304.10436.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4f0c7f4df04f07609bdb67944af2a529d5a4517b?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/paper/A-Survey-of-Safety-and-Trustworthiness-of-Large-the-Huang-Ruan/4f0c7f4df04f07609bdb67944af2a529d5a4517b?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/thu-coai/Safety-Prompts.svg?style=social&label=Star)](https://github.com/thu-coai/Safety-Prompts)

+ **Beavertails: Towards improved safety alignment of llm via a human-preference dataset** (7 Nov 2023)<details><summary>Jiaming Ji, Mickel Liu, Juntao Dai, et al.</summary>Jiaming Ji, Mickel Liu, Juntao Dai, Xuehai Pan, Chi Zhang, Ce Bian, Chi Zhang, Ruiyang Sun, Yizhou Wang, Yaodong Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2307.04657.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F92930ed3560ea6c86d53cf52158bc793b089054d?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/BeaverTails%3A-Towards-Improved-Safety-Alignment-of-a-Ji-Liu/92930ed3560ea6c86d53cf52158bc793b089054d?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/Yangyi-Chen/Multimodal-AND-Large-Language-Models.svg?style=social&label=Star)](https://github.com/Yangyi-Chen/Multimodal-AND-Large-Language-Models)

+ **Safetybench: Evaluating the safety of large language models with multiple choice questions** (13 Sep 2023)<details><summary>Zhexin Zhang, Leqi Lei, Lindong Wu, et al.</summary>Zhexin Zhang, Leqi Lei, Lindong Wu, Rui Sun, Yongkang Huang, Chong Long, Xiao Liu, Xuanyu Lei, Jie Tang, Minlie Huang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2309.07045.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9b9a4fa3ed510fc6eb1bf831979235f3d9f8b556?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/SafetyBench%3A-Evaluating-the-Safety-of-Large-Models-Zhang-Lei/9b9a4fa3ed510fc6eb1bf831979235f3d9f8b556?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/thu-coai/SafetyBench.svg?style=social&label=Star)](https://github.com/thu-coai/SafetyBench)

+ **Tovilag: Your visual-language generative model is also an evildoer.** (13 Dec 2023)<details><summary>Xinpeng Wang, Xiaoyuan Yi, Han Jiang, et al.</summary>Xinpeng Wang, Xiaoyuan Yi, Han Jiang, Shanlin Zhou, Zhihua Wei, Xing Xie</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](http://export.arxiv.org/pdf/2312.11523)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F10280c290825fc0b0c884e988f4f1dedb80e4e80?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ToViLaG%3A-Your-Visual-Language-Generative-Model-is-Wang-Yi/10280c290825fc0b0c884e988f4f1dedb80e4e80?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/victorup/ToViLaG.svg?style=social&label=Star)](https://github.com/victorup/ToViLaG)

+ **Figstep: Jailbreaking large vision-language models via typographic visual prompts.** (13 Dec 2023)<details><summary>Yichen Gong, Delong Ran, Jinyuan Liu, et al.</summary>Yichen Gong, Delong Ran, Jinyuan Liu, Conglei Wang, Tianshuo Cong, Anyu Wang, Sisi Duan, Xiaoyun Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2311.05608.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2313afae52d98e569da2dedbf14daf9efc74e7cf?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/CogVLM%3A-Visual-Expert-for-Pretrained-Language-Wang-Lv/2313afae52d98e569da2dedbf14daf9efc74e7cf?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/ThuCCSLab/FigStep.svg?style=social&label=Star)](https://github.com/ThuCCSLab/FigStep)

+ **Query-relevant images jailbreak large multi-modal models.** (29 Nov 2023)<details><summary>Xin Liu, Yichen Zhu, Yunshi Lan, et al.</summary>Xin Liu, Yichen Zhu, Yunshi Lan, Chao Yang, Yu Qiao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2311.17600.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F74423a9ee66085e74cd2b2e42303f28359c74eb6?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Query-Relevant-Images-Jailbreak-Large-Multi-Modal-Liu-Zhu/74423a9ee66085e74cd2b2e42303f28359c74eb6?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/isXinLiu/MM-SafetyBench.svg?style=social&label=Star)](https://github.com/isXinLiu/MM-SafetyBench)

+ **Dress: Instructing large vision-language models to align and interact with humans via natural language feedback.** (16 Nov 2023)<details><summary>Yangyi Chen, Karan Sikka, Michael Cogswell, et al.</summary>Yangyi Chen, Karan Sikka, Michael Cogswell, Heng Ji, Ajay Divakaran</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2311.10081.pdf)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F391eaeb1092c2b145ff0e5a2fa61637a42921fce?utm_source=direct_link%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/DRESS%3A-Instructing-Large-Vision-Language-Models-to-Chen-Sikka/391eaeb1092c2b145ff0e5a2fa61637a42921fce?utm_source=direct_link)
[![Code](https://img.shields.io/github/stars/isXinLiu/MLLM-Safety-Collection.svg?style=social&label=Star)](https://github.com/isXinLiu/MLLM-Safety-Collection)





# 📍 Related Surveys
## LLM


+ **MM-LLMs: Recent Advances in MultiModal Large Language Models** (24 Jan 2024)<details><summary>Duzhen Zhang, Yahan Yu, Chenxing Li</summary>Duzhen Zhang, Yahan Yu, Chenxing Li, Jiahua Dong, Dan Su, Chenhui Chu, Dong Yu</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.13601)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa050c9b0c321839e4427ab9defa3463be7825ac4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MM-LLMs%3A-Recent-Advances-in-MultiModal-Large-Models-Zhang-Yu/a050c9b0c321839e4427ab9defa3463be7825ac4)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mm-llms.github.io/)


+ **A Survey on Multimodal Large Language Models** (23 Jun 2023)<details><summary>Shukang Yin, Chaoyou Fu, Sirui Zhao, et al.</summary>Shukang Yin, Chaoyou Fu, Sirui Zhao, Ke Li, Xing Sun, Tong Xu, Enhong Chen</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.13549)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fefa1647594b236361610a20d507127f0586a379b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/A-Survey-on-Multimodal-Large-Language-Models-Yin-Fu/ebedc4d7a2356090904baba4104ef0832bc236df)
[![Code](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models.svg?style=social&label=Star)](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)


+ **Multimodal Large Language Models: A Survey** (22 Nov 2023)<details><summary>Jiayang Wu, Wensheng Gan, Zefeng Chen, et al. [IEEE BigData 2023]</summary>Jiayang Wu, Wensheng Gan, Zefeng Chen, Shicheng Wan, Philip S. Yu</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.13165)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F52941cadbd340344f3e0a6f50719fe55b3de5088%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Multimodal-Large-Language-Models%3A-A-Survey-Wu-Gan/52941cadbd340344f3e0a6f50719fe55b3de5088)


+ **A Survey of Large Language Models** (31 Mar 2023)<details><summary>Wayne Xin Zhao, Kun Zhou, Junyi Li, et al.</summary>Wayne Xin Zhao, Kun Zhou, Junyi Li, Tianyi Tang, Xiaolei Wang, Yupeng Hou, Yingqian Min, Beichen Zhang, Junjie Zhang, Zican Dong, Yifan Du, Chen Yang, Yushuo Chen, Zhipeng Chen, Jinhao Jiang, Ruiyang Ren, Yifan Li, Xinyu Tang, Zikang Liu, Peiyu Liu, Jian-Yun Nie, Ji-Rong Wen</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.18223)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc61d54644e9aedcfc756e5d6fe4cc8b78c87755d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/A-Survey-of-Large-Language-Models-Zhao-Zhou/c61d54644e9aedcfc756e5d6fe4cc8b78c87755d)
[![Code](https://img.shields.io/github/stars/RUCAIBox/LLMSurvey.svg?style=social&label=Star)](https://github.com/RUCAIBox/LLMSurvey?tab=readme-ov-file#timeline-of-llms)


## Vision


+ **State of the Art on Diffusion Models for Visual Computing** (11 Oct 2023)<details><summary>Ryan Po, Wang Yifan, Vladislav Golyanik, et al.</summary>Ryan Po, Wang Yifan, Vladislav Golyanik, Kfir Aberman, Jonathan T. Barron, Amit H. Bermano, Eric Ryan Chan, Tali Dekel, Aleksander Holynski, Angjoo Kanazawa, C. Karen Liu, Lingjie Liu, Ben Mildenhall, Matthias Nießner, Björn Ommer, Christian Theobalt, Peter Wonka, Gordon Wetzstein</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07204)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6487ec82f6d8082a5b402a5416ea03009acb1679%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/State-of-the-Art-on-Diffusion-Models-for-Visual-Po-Yifan/6487ec82f6d8082a5b402a5416ea03009acb1679)
[![Code](https://img.shields.io/github/stars/CroitoruAlin/Diffusion-Models-in-Vision-A-Survey.svg?style=social&label=Star)](https://github.com/CroitoruAlin/Diffusion-Models-in-Vision-A-Survey)

+ **Diffusion Models in Vision: A Survey** (10 Sep 2022)<details><summary>Florinel-Alin Croitoru, Vlad Hondru, Radu Tudor Ionescu, et al. [TPAMI 2023]</summary>Florinel-Alin Croitoru, Vlad Hondru, Radu Tudor Ionescu, Mubarak Shah</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.04747)
[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fefa1647594b236361610a20d507127f0586a379b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Diffusion-Models-in-Vision%3A-A-Survey-Croitoru-Hondru/efa1647594b236361610a20d507127f0586a379b)
[![Code](https://img.shields.io/github/stars/CroitoruAlin/Diffusion-Models-in-Vision-A-Survey.svg?style=social&label=Star)](https://github.com/CroitoruAlin/Diffusion-Models-in-Vision-A-Survey)
