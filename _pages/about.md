---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<script type="text/javascript">
	$(document).ready(function() {
		$('a[href^="http"]').each(function() {
			$(this).attr('target', '_blank');
		});
	});
</script>

<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>

<p style="text-align:justify; text-justify:inter-ideograph;"> I am currently an assistant professor of computer science at Great Bay University, China, leading the YU Vision (YUV) Group. I was a Postdoctoral researcher at ROSE Lab, Nanyang Technological University, working with [Prof. Alex Kot](https://scholar.google.com/citations?user=UGZXLxIAAAAJ&hl=en). I also serve as an advisor on rPPG-based healthcare for [BioTrillion](https://www.biotrillion.com/team), USA. I received my PhD degree in CS at CMVS, University of Oulu in 2022 (supervised by [Prof. Guoying Zhao](https://scholar.google.com/citations?user=hzywrFMAAAAJ&hl=en)). I was a visiting scholar at TVG, University of Oxford, from July to November 2021, supervised by [Prof. Philip Torr](https://scholar.google.com/citations?user=kPxa2w0AAAAJ&hl=en). My research interests include computer vision, biometric security, and multimodal learning.</p>

<p style="text-align:justify; text-justify:inter-ideograph;"><font color=a82e2e>[Urgent Recuritment:] I am recruiting PostDoc (45W/year) and 特任研究员 (35W/year) and Research Assistant (Excellent master student) to join my research team. For prospective collaborators, please email me with your CV and research plan. 每年招收湾大-深大联培硕士，湾大-哈工深联培博士若干.</font></p>

# News
- [2024.11] Our PhysMamba paper is granted [CCBR 2024 Best Paper Honorable Mention Award (最佳论文提名奖)](https://drive.google.com/file/d/1DnuEuENHoEvMs2G6PwrRnq37ArajycrC/view?usp=sharing), Congra. to Chaoqi & Yiping！
- [2024.09] Elected among World's Top 2% Scientists 2024 by Stanford University (入选2024全球前2%顶尖科学家榜单)
- [2024.09] One paper on face forgery detection is accepted by IEEE TIFS
- [2024.07] Our paper is awarded as the [Best Paper Candidate (最佳论文提名)](https://drive.google.com/file/d/1iaYTAUyUO_t7lfUldZ9V3TPZOY88YrRS/view?usp=drive_link) of [ICME 2024](https://2024.ieeeicme.org/awards/)
- [2024.07] One paper on multimedia privacy is accepted by ACM MM 2024
- [2024.07] One paper on manipulation detection is accepted by Cell Patterns
- [2024.07] Four papers are accepted by ECCV 2024
- [2024.06] One paper on generalized face anti-spoofing is accepted by IEEE TIFS
- [2024.05] Organizing IJCB'24 Special Session '[Multimodal Human Behavior Understanding and Generation (MUG)](https://sites.google.com/view/ijcb-mug2024)'
- [2024.05] Will serve as Area Chair (AC) for BMVC 2024

<a onclick="toggleList()" id='more'>Show more</a>
<div id="hiddenList" style="display:none;">
  {% capture hidden_list %}
  - [2024.03] One paper on multimodal face anti-spoofing is accepted by IJCV
  - [2024.02] One paper on multimodal face anti-spoofing is accepted by CVPR 2024 as Highlight!
  - [2024.02] A project on visual anomaly detection is granted by Guangdong Provincial Regional Joint Fund - Regional Cultivation Project
  - [2024.02] Promoted to IEEE Senior Member
  - [2024.01] One paper on unsupervised facial rPPG is accepted by IEEE TMM
  - [2024.01] One paper on joint face spoofing and forgery detection is accepted by IEEE TDSC
  - [2023.12] Our CCBR'23 paper '[Detect Any Deepfake](https://github.com/laiyingxin2/DADF)' is granted IAPR Best Student Paper Award, Congra. to Yingxin！
  - [2023.10] Elected among World's Top 2% Scientists 2023 by Stanford University (入选2023全球前2%顶尖科学家榜单)
  - [2023.08] A project on facial rPPG is granted by Young Scientists Fund of the Natural Science Foundation of China
  - [2023.07] Two papers on face anti-spoofing and deception detection are accepted by ICCV 2023 (One as Oral!)
  - [2023.02] One paper on facial rPPG is accepted by CVPR 2023
  - [2023.02] One paper on facial rPPG is accepted by IJCV
  - [2023.01] Invited keynote talk for [WACV2023 - Workshop on Manipulation, Adversarial, and Presentation Attacks in Biometrics](https://sites.google.com/view/wacv2023-map-a/home)
  {% endcapture %}
  {{ hidden_list | markdownify }}
</div>
<a onclick="toggleList()" id='less' style='display:none;'>Show less</a>
<script>
function toggleList() {
    var list = document.getElementById('hiddenList');
    list.style.display = list.style.display === 'none' ? 'block' : 'none';
    var button = document.getElementById('more');
    button.style.display = button.style.display === 'none' ? 'block' : 'none';
    var buttom_less = document.getElementById('less');
    buttom_less.style.display = buttom_less.style.display === 'none' ? 'block' : 'none';
}
</script>


# Publications
( # equal contribution, * corresponding author)

## Book Chapter
- [2] **Zitong Yu**, Chenxu Zhao and Zhen Lei. "**Face Presentation Attack Detection**". Handbook of Face Recognition (3rd Ed.), 2023
- [1] **Zitong Yu**, Jukka Komulainen, Xiaobai Li, and Guoying Zhao. "**Review of Face Presentation Attack Detection Competitions**." Handbook of Biometric Anti-Spoofing (3rd Ed.), Springer, 2023

## Journals
- [20] Yaning Zhang#, **Zitong Yu#**, Xiaobin Huang, Linlin Shen, and Jianfeng Ren. "**GenFace: A Large-Scale Fine-Grained Face Forgery Benchmark and Cross Appearance-Edge Learning**", IEEE Transactions on Information Forensics and Security (TIFS), 2024
- [19] Xun Lin, Wenzhong Tang, Haoran Wang, Yizhong Liu, Yakun Ju, Shuai Wang* and **Zitong Yu***. "**Exposing Image Splicing Traces in Scientific Publications via Uncertainty-guided Refinement**". Patterns, Cell, 2024
- [18] Rizhao Cai, **Zitong Yu***, Chenqi Kong, Haoliang Li, Changsheng Chen, Yongjian Hu and Alex Kot. "**S-Adapter: Generalizing Vision Transformer for Face Anti-Spoofing with Statistical Tokens**". IEEE Transactions on Information Forensics and Security (TIFS), 2024
- [17] Daiyuan Li, Guo Chen, Xixian Wu, **Zitong Yu*** and Mingkui Tan*. "**Cross-stage relation extraction and presentation attack material perception for face anti-spoofing**". Neural Networks, 2024
- [16] **Zitong Yu**, Rizhao Cai, Yawen Cui, Xin Liu, Yongjian Hu and Alex Kot. "**Rethinking Vision Transformer and Masked Autoencoder in Multimodal Face Anti-Spoofing**". International Journal of Computer Vision (IJCV), 2024
- [15] Xin Liu, Yuting Zhang, **Zitong Yu***, Hao Lu, Huanjing Yue and Jingyu Yang*. "**rPPG-MAE: Self-supervised Pre-training with Masked Autoencoders for Remote Physiological Measurement**". IEEE Transactions on Multimedia (TMM), 2024
- [14] **Zitong Yu**, Rizhao Cai, Zhi Li, Wenhan Yang, Jingang Shi, and Alex C Kot. "**Benchmarking Joint Face Spoofing and Forgery Detection with Visual and Physiological Cues**". IEEE Transactions on Dependable and Secure Computing (TDSC), 2024
- [13] **Zitong Yu**, Yuming Shen, Jingang Shi, Hengshuang Zhao, Yawen Cui, Jiehua Zhang, Philip Torr and Guoying Zhao. "**PhysFormer++: Facial Video-based Physiological Measurement with SlowFast Temporal Difference Transformer**". International Journal of Computer Vision (IJCV), 2023
- [12] Zezheng Wang#, **Zitong Yu#**, Xun Wang, Yunxiao Qin, Jiahong Li, Chenxu Zhao, Zhen Lei, Xin Liu, Size Li and Zhongyuan Wang. "**Consistency Regularization for Deep Face Anti-Spoofing**", IEEE Transactions on Information Forensics and Security (TIFS), 2022
- [11] **Zitong Yu**, Yunxiao Qin, Xiaobai Li, Chenxu Zhao, Zhen Lei, and Guoying Zhao. "**Deep Learning for Face Anti-Spoofing: A Survey**", IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2022
- [10] Ajian Liu#, Chenxu Zhao#, **Zitong Yu#**, Jun Wan, Anyang Su, Xing Liu, Zichang Tan, Sergio Escalera, Junliang Xing, Yanyan Liang, Guodong Guo, Zhen Lei, Stan Z Li, and Du Zhang. "**Contrastive context-aware learning for 3d high-fidelity mask face presentation attack detection**", IEEE Transactions on Information Forensics and Security (TIFS), 2022
- [9] Mingxin Liu, Jiong Mu*, **Zitong Yu***, Kun Ruan, Baiyi Shu, and Jie Yang. "**Adversarial learning and decomposition-based domain generalization for face anti-spoofing**." Pattern Recognition Letters (PRL), 2021
- [8] **Zitong Yu***, Xiaobai Li*, and Guoying Zhao. "**Facial Video-based Physiological Signal Measurement: Recent Advances and Affective Applications**." IEEE Signal Processing Magazine (SPM), 2021
- [7] Yunxiao Qin, **Zitong Yu**, Longbin Yan, Zezheng Wang, Chenxu Zhao, and Zhen Lei. "**Meta-Teacher For Face Anti-Spoofing**." IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2021
- [8] Dong Huang, Xiaoyi Feng, Haixi Zhang, **Zitong Yu**, Jinye Peng, Guoying Zhao, and Zhaoqiang Xia. "**Spatio-Temporal Pain Estimation Network with Measuring Pseudo Heart Rate Gain**." IEEE Transactions on Multimedia (TMM), 2021
- [6] **Zitong Yu**, Xiaobai Li, Pichao Wang, and Guoying Zhao. "**TransRPPG: Remote Photoplethysmography Transformer for 3d Mask Face Presentation Attack Detection**." IEEE Signal Processing Letters (SPL), 2021
- [5] **Zitong Yu#**, Benjia Zhou#, Jun Wan, Pichao Wang, Haoyu Chen, Xin Liu, Stan Z Li, and Guoying Zhao. "**Searching Multi-Rate and Multi-Modal Temporal Enhanced Networks for Gesture Recognition**." IEEE Transactions on Image Processing (TIP), 2021
- [4] **Zitong Yu**, Xiaobai Li, Jingang Shi, Zhaoqiang Xia, and Guoying Zhao. "**Revisiting Pixel-Wise Supervision for Face Anti-Spoofing**." IEEE Transactions on Biometrics, Behavior, and Identity Science (TBIOM), 2021
- [3] **Zitong Yu**, Jun Wan, Yunxiao Qin, Xiaobai Li, Stan Z. Li, and Guoying Zhao. "**NAS-FAS: Static-Dynamic Central Difference Network Search for Face Anti-Spoofing**." IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2020
- [2] **Zitong Yu**, Xiaobai Li, Xuesong Niu, Jingang Shi, and Guoying Zhao. "**AutoHR: A Strong End-to-end Baseline for Remote Heart Rate Measurement with Neural Searching**." IEEE Signal Processing Letters, 2020
- [1] Jingang Shi, Iman Alikhani, Xiaobai Li, **Zitong Yu**, Tapio Seppänen, and Guoying Zhao. "**Atrial fibrillation detection from face videos by fusing subtle variations**." IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), 2019

## Conferences
- [24] Xun Lin, Yi Yu, **Zitong Yu***, Ruohan Meng, Jiale Zhou, Ajian Liu, Yizhong Liu, Shuai Wang, Wenzhong Tang, Zhen Lei, Alex Kot. "**HideMIA: Hidden Wavelet Mining for Privacy-Enhancing Medical Image Analysis**", ACM MM 2024
- [23] Qilang Ye, **Zitong Yu***, Rui Shao, Xinyu Xie, Philip Torr, Xiaochun Cao. "**CAT: Enhancing Multimodal Large Language Model to Answer Questions in Dynamic Audio-Visual Scenarios**", ECCV 2024
- [22] Kaishen Yuan#, **Zitong Yu#***, Xin Liu*, Weicheng Xie, Huanjing Yue, Jingyu Yang. "**AUFormer: Vision Transformers are Parameter-Efficient Facial Action Unit Detectors**", ECCV 2024
- [21] Xinxu Ge, Xin Liu*, **Zitong Yu***, Jingang Shi, Chun Qi, Jie Li, Heikki Kälviäinen. "**DiffFAS: Face Anti-Spoofing via Generative Diffusion Models**", ECCV 2024
- [20] Qingzheng Huang, Xilin He, Xiaole Xian, Qinliang Lin, Weicheng Xie, Siyang Song, Linlin Shen, **Zitong Yu**. "**MTaDCS: Moving Trace and Feature Density-based Confidence Sample Selection under Label Noise**", ECCV 2024
- [19] Xun Lin, Shuai Wang, Rizhao Cai, Yizhong Liu, Ying Fu, **Zitong Yu***, Wenzhong Tang, Alex Kot. "**Suppress and Balance: Towards Generalized Multi-Modal Face Anti-Spoofing**", CVPR 2024 (Highlight)
- [18] Rizhao Cai, Yawen Cui, Zhi Li, **Zitong Yu***, Haoliang Li, Yongjian Hu, Alex Kot. "**Rehearsal-Free Domain Continual Face Anti-Spoofing: Generalize More and Forget Less**", ICCV 2023 (Oral)
- [17] Xiaobao Guo, Nithish Muthuchamy Selvaraj, **Zitong Yu***, Wai-Kin Adams Kong, Bingquan Shen, Alex Kot. "**Audio-Visual Deception Detection: DOLOS Dataset and Parameter-Efficient Crossmodal Learning**", ICCV 2023
- [16] Hao Lu, **Zitong Yu**, Xuesong Niu, Ying-Cong Chen. "**Neuron Structure Modeling for Generalized Remote Physiological Measurement**", CVPR 2023
- [15] Jianwei Li#, **Zitong Yu#**, Jingang Shi. "**Learning Motion-Robust Remote Photoplethysmography through Arbitrary Resolution Videos**", AAAI 2023
- [14] Jingang Shi, Yusi Wang, Songlin Dong,Changxin Wang, Xiaopeng Hong, **Zitong Yu ***, Fei Wang, Yihong Gong. "**IDPT: Interconnected Dual Pyramid Transformer for Face Super-Resolution**", IJCAI 2022
- [13] **Zitong Yu**, Yuming Shen, Jingang Shi, Hengshuang Zhao, Philip Torr, Guoying Zhao. "**PhysFormer: Facial Video-based Physiological Measurement with Temporal Difference Transformer**", CVPR 2022
- [12] Zhuo Wang, Zezheng Wang, **Zitong Yu**, Weihong Deng, Jiahong Li, Tingting Gao, Zhongyuan Wang . "**Domain Generalization via Shuffled Style Assembly for Face Anti-Spoofing**", CVPR 2022
- [11] Haoyu Chen, Hao Tang, **Zitong Yu**, Nicu Sebe, Guoying Zhao. "**Geometry-Contrastive Transformer for Generalized 3D Pose Transfer**", AAAI 2022
- [10] Zhuo Su, Wenzhe Liu, **Zitong Yu**, Dewen Hu, Qing Liao, Qi Tian, Matti Pietikäinen, and Li Liu. "**Pixel Difference Networks for Efficient Edge Detection**", ICCV 2021 (Oral)
- [9] **Zitong Yu**, Yunxiao Qin, Hengshuang Zhao, Xiaobai Li, and Guoying Zhao. "**Dual-Cross Central Difference Network for Face Anti-Spoofing**." IJCAI 2021
- [8] Ruijing Yang, Ziyu Guan, **Zitong Yu**, Guoying Zhao, Xiaoyi Feng and Jinye Peng. "**Non-contact Pain Recognition from Video Sequences with Remote Physiological Measurements Prediction**." IJCAI 2021
- [7] Xin Liu , Henglin Shi , Haoyu Chen, **Zitong Yu**, Xiaobai Li, and Guoying Zhao. "**iMiGUE: An Identity-free Video Dataset for Micro-Gesture Understanding and Emotion Analysis**." CVPR 2021
- [6] **Zitong Yu**, Xiaobai Li, Xuesong Niu, Jingang Shi, and Guoying Zhao. "**Face anti-spoofing with human material perception**." ECCV 2020
- [5] Xuesong Niu, **Zitong Yu**, Hu Han, Xiaobai Li, Shiguang Shan, and Guoying Zhao. "**Video-based Remote Physiological Measurement via Cross-verified Feature Disentangling**." ECCV 2020 (Oral)
- [4] **Zitong Yu**, Chenxu Zhao, Zezheng Wang, Yunxiao Qin, Zhuo Su, Xiaobai Li, Feng Zhou, and Guoying Zhao. "**Searching central difference convolutional networks for face anti-spoofing**." CVPR 2020
- [3] Zezheng Wang, **Zitong Yu**, Chenxu Zhao, Xiangyu Zhu, Yunxiao Qin, Qiusheng Zhou, Feng Zhou, and Zhen Lei. "**Deep spatial gradient and temporal depth learning for face anti-spoofing**." CVPR 2020 (Oral)
- [2] Yunxiao Qin, Chenxu Zhao, Xiangyu Zhu, Zezheng Wang, **Zitong Yu**, Tianyu Fu, Feng Zhou, Jingping Shi, and Zhen Lei. "**Learning meta model for zero-and few-shot face anti-spoofing**." AAAI 2020 (Spotlight)
- [1] **Zitong Yu#**, Wei Peng#, Xiaobai Li, Xiaopeng Hong, and Guoying Zhao. "**Remote heart rate measurement from highly compressed facial videos: an end-to-end deep learning solution with video enhancement**." ICCV 2019

# Research Grants
- Young Scientists Fund of the Natural Science Foundation of China (PI), 300k RMB, Grant No. 62306061, 2024-01 to 2026-12.
- Open Project of National Engineering Laboratory for Big Data System Computing Technology, Shenzhen University, (PI), 50k RMB, Grant No. SZU-BDSC-OF2024-02, 2024-01 to 2025-12.
- Guangdong Provincial Regional Joint Fund - Regional Cultivation Project (PI), 300k RMB, Grant No. 2023A1515140037, 2024-01 to 2026-12.

# Honors & Awards
- Recipient of Best Paper Honorable Mention Award (最佳论文提名) of CCBR 2024
- Recipient of Best Paper Candidate (最佳论文提名) of ICME 2024
- Recipient of IAPR Best Student Paper Award of CCBR'23 (IAPR最佳学生论文奖)
- Recipient of World's Top 2% Scientists 2023-2024 (连续两年入选（2023-2024）斯坦福全球前2%顶尖科学家榜单)
- Recipient of the second prize of the IEEE Finland Jt. Chapter SP/CAS Best Paper Award (2022)
- Recipient of Chinese Government Award 2021 for Outstanding Self-financed Students Abroad (国家优秀自费留学生奖)
- Recipient of IEEE Finland Section best student conference paper award 2020
- 1st Place in the ChaLearn multi-modal face anti-spoofing attack detection challenge @ CVPR 2020
- 2nd Place on Action Recognition Track of ECCV 2020 VIPriors Challenges
- 3rd Place on the "WIN THE FUTURE" 2021 Venture Contest for International Entrepreneurs (Finland Contest Area)
- Master Program Scholarship of Pays de la Loire, France

# Membership
- IEEE Senior Member, CCF/CSIG/CAAI/CAA Member
- CCF东莞分部秘书长
- 中国图象图形学会数字媒体取证与安全专委会委员，中国自动化学会模式识别与机器智能专业委员会委员

# Organizing scientific activities
- Co-organizing 3D High-Fidelity Mask Face Presentation Attack Detection Challenge ICCV2021
- Co-organizing the first Challenge on Remote Physiological Signal Sensing (RePSS) with CVPR 2020

# Invited talks
- KEYNOTE 'Facial Physiological and Emotional Analysis', ACM MM2024 - Multimodal and Responsible Affective Computing (MRAC 2023), 01.11.2024
- '多模态大模型幻觉与鲁棒的一些思考', CCBR 2024 - 生物特征安全论坛, 24.11.2024
- '垂类视觉基础模型的一些思考', Visual Intelligence“视觉基础模型”专刊交流会, 21.07.2024
- '可信人脸生理感知与安全', SAILING讲坛第十四期，广东省安全智能新技术重点实验室, 24.06.2024
- '迈向可信赖的人脸生理感知和安全系统', 第三届多媒体智能安全学术研讨会 (隐者联盟∙洪都论道 MAS'2024), 14.04.2024
- KEYNOTE 'Towards Trustworthy Face Physiological Sensing and Security Systems', WACV2023 - Workshop on Manipulation, Adversarial, and Presentation Attacks in Biometrics, 07.01.2023
- 'Towards Trustworthy Face Physiological Sensing and Security Systems', Valse Webinar, 14.12.2022
- 'Non-Contact Human Sensing and Biometric Security’, Hong Kong Baptist University, 02.11.2021
- 'Non-Contact Human Sensing and Biometric Security’, Southern University of Science and Technology, 08.11.2021
- 'Face Anti-Spoofing Attack Detection Techniques’, University of Jyväskylä, 28.03.2022

# Invited Journal Reviewer
- IEEE Transactions on Pattern Analysis and Machine Intelligence (since 2021)
- International Journal of Computer Vision (since 2022)
- IEEE Transactions on Image Processing (since 2020)
- IEEE Transactions on Neural Networks and Learning Systems (since 2021)
- IEEE Transactions on Information Forensics and Security (since 2021)
- IEEE Transactions on Dependable and Secure Computing (since 2021)
- IEEE Transactions on Circuits and Systems for Video Technology (since 2020)
- IEEE Transactions on Biometrics, Behavior, and Identity Science (since 2020)
- Pattern Recognition & Pattern Recognition Letters (since 2020)
- IEEE Journal of Biomedical and Health Informatics (since 2020)
- IET Biometrics (since 2022)
- Security and Communication Networks (since 2021)
- Journal of Visual Communication and Image Representation (since 2021)
- ACM Transactions on Multimedia Computing, Communications and Applications (TOMM) (since 2021)

# Associate Editor
- [Frontiers in Artificial Intelligence](https://loop.frontiersin.org/people/2376790/overview) (IF=4.0)

# Guest Editors
- Special Issue "Deep Learning Approach for Secure and Trustworthy Biometric System" on MDPI Electronics (IF=2.69)

# Invited Conference Area Chair
- ICME'23, BMVC'24, IJCB'24, AAAI'25 (SPC)

# Invited Conference Reviewer
- CVPR'25
- AAAI'24, ICLR'24, CVPR'24, IJCAI'24, ECCV'24, PRCV'24, NeurIPS'24
- AAAI'23, CVPR'23, IJCAI'23, ICCV'23, IJCB'23, NeurIPS'23, SIGGRAPH Asia'23, PRCV'23
- AAAI'22, CVPR'22, ICME'22, IJCAI'22, ECCV'22, PRCV'22
- ICME'21, ICCV'21

# Teaching
- Teaching assistant (TA) for Computer Graphics (521140S), University of Oulu, Spring 2020, 2021
