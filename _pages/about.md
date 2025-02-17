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

# 💬About me

Hi, I am Dingyi Jiang. Presently, I am an Artificial Intelligence major bachelor. I graduated from <a href='http://cic.tju.edu.cn/english/home.htm'>the College of Intelligence and Computing, Tianjin University</a>(天津大学智能与计算学部) in 2024 summer. I have several AI-related projects and work experiences. Notably, I participated in an exchange program during 2023 at <a href='https://cse.hkust.edu.hk/'>the Department of Computer Science and Technology at HKUST</a>(香港科技大学计算机科学与技术学院). I won two scholarships during my undergraduate years。\
<img src="images/TJU.png" width = "100" height = "100" alt="" align=center />
<img src="images/HKUST.png" width = "230" height = "170" alt="" align=center />  

# Research interests:
1. Machine learning: Transfer learning, semi-supervised learning, federated learning, and related applications.
2. Large language models: LLM evaluation and enhancement. 


# 📖 Education
- *2021.09 - 2024.07,  Undergraduate, Tianjin University, Artificial Intelligence
- *2023.01 - 2023.06*, Exchange Student, HKUST, Computer Science
- *2019.09 - 2021.06*, Undergraduate, Tianjin University, Applied Chemistry (Changed Major)

# 💬 Paper
  Enhancing Generalization in Chain of Thought Reasoning for Smaller Models: Declined by AAAI 2025 with scores of 4 and 5. Currently under revision.
# 💻 Work 
- *2024.09 - Now*, Algorithm Researcher, [Baidu](https://www.baidu.com/), China.
  1. Focus on developing strategies aligned with Baidu’s core dual-engine (search + feed) business model, enhancing the end-to-end feed recommendation experience and providing platform-based recommendation services.
  2. Conduct research on cutting-edge technologies in data mining and statistical learning, applying them to solve and optimize real-world problems.
  3. Distributed computing. Using google mapper-reducer architecture for data producing and data analysing.

- *2023.06 - 2023.12*, LLM Intern, [Frontis（衔远科技）](https://frontis.cn/), China.
  1. Responsible for uplifting the performance of LLMs by SFT using the Slurm cluster.
  2. Given that the few-shot capability of LLMs is far superior to their zero-shot capability, we have studied the application of <a href='https://github.com/mechsihao/FaissSearcher'>search algorithms</a> in commercial real-time user interactions to provide pre-prepared examples to the LLM in order to enhance the model's performance.
  3. Conduct data analysis and data cleaning for Llama large model SFT and pretraining, including manual sampling, multi-threaded character-level processing, and quality and coherence evaluation using the Bert model.
  4. Perform benchmark evaluations and ranking for large models.
    
- *2021.06 - 2021.09*, AI Intern, [AI Cyber](https://www.aicyber.com/), China.
  1. Provide deep learning experiments and slides for Tianjin college students. My projects included *CNN, HMM, quality assessment in speech synthesis, and the prosodic* and *intonation of Chinese in speech synthesis*.
  2. During this period,l became proficient in the operation of Linux on the server and the running of code on  GPU using Python.



# 📖 Study Performance
<a href='https://peterjiangdingyi.github.io/transcripts.github.io/main.html'>Click Here to Visit My Overall GPA.</a>

Because my first two years at Tianjin University were studying applied chemistry and after that, I changed major, so my transcripts contain lots of non-computer-related courses. Therefore, I put my core GPA which just contains computer-related courses together here.

|NO.|Courses|Credit|Grade(100)|Grade(4.0)|
|:--:|:------------------------------------------:|:------:|:---------:|:---------:|
|1|Data Structure|3.0|91|4.0|
|2|Programming practice|1.5|94|4.0|
|3|Programming Principles|3.0|90|4.0|
|4|Data Mining|2.0|92|4.0|
|5|Operating System Principle|3.0|94|4.0|
|6|Algorithm Design and Analysis|3.0|88|3.7|
|7|Probability Theory and Mathematic Statistics|3.0|87|3.7|
|8|Discrete Mathematics|4.0|65|2.7|
|9|Linear Algebra and Application|3.5|69|2.7|
|10|Advanced Mathematics|5.0|83|3.3|
|11|Mathematical Model(flip)|3.0|97|4.0|
|12|Mathematical Foundations of Artificial Intelligence|3.0|88|3.7|
|13|Principles of Database|2.0|95|4.0|
|14|Natural Language Processing|2.0|93|4.0|
|15|Machine Learning|2.0|81|3.0|
|16|Knowledge Engineering|2.0|97|4.0|
|17|Knowledge Graph|1.5|93|4.0|
|18|Neural Networks and Deep Learning|1.5|81.3|3.3|
|19|Speech Information Processing|2.0|88|3.7|
|20|Introduction to Computer Systems |2.0|87|3.7|
|21|Selected topics in advanced mathematics competitionof college students|2.0|93|4.0|
|22|Introduction to cognitive science|2.0|91|4.0|
|23|Introduction to Computer Systems|3.0|93|4.0|
|24|Digital Logic and Digital System|3.0|94|4.0|
|25|Python Programming and Application|2.5|86|3.7|
|26|Computer Networks|2.0|80|3.0|
|27|The Comprehensive Practice of Computer System|1.5|90|4.0|
|28|Comprehensive practice of machine learning|1.5|92.8|4.0|
|29|Comprehensive Practice Course for KnowledgeEngineering|1.5|87.4|3.7|
||**Weighted Average**||**87.31**|**3.67**|

**TOEFL Score**

<img src="images/toefl.png" width = "900" height = "170" alt="" align=center /> 


# 📝 Researchs 

- *2022.04 - 2023.05* Acted as Leader in Municipal College Students Innovation and Entrepreneurship Training Program， *Intelligent Visualization of the Attributes of the Global Burden of Disease*, supervised by Professor <a href='http://geoanalytics.tju.edu.cn/jieli'>Jie Li</a> and <a href='https://www.ai.pku.edu.cn/info/1140/2160.htm'>Dr. Liang Zhou</a>.
  
  In this project, We conducted a Graph Neural Network to analyze the similarity between diseases worldwide.
  1. By utilizing meta-path-related GNN to identify the correlation between diseases, converting the heterogeneous graph into an isomorphic graph, and then applying deepwalk to the isomorphic graph to obtain the representation of t-SNE dimensionality reduction visualization, a verification function can be provided.
  2. Research visualization result:

        -<a href='https://peterjiangdingyi.github.io/ghdx.github.io/DCD.html'>Graph Constructed by Meta-Path </a> \
           <img src="images/diseases.png" width = "500" height = "250" alt="" align=center />
     
        -<a href='https://peterjiangdingyi.github.io/ghdx.github.io/embed.html'>The similarity between diseases worldwide </a> \
           <img src="images/Similarity.png" width = "500" height = "250" alt="" align=center />  
    4. The edges of the project:
         (1) By using all kinds of meta-path, we can construct any arbitrary pattern to analyze topological information on the burden of diseases.
         (2) By using GNN, we can utilize the homogeneous graph derived from metapath to form embeddings to accurately analyze the similarity of diseases.
    
- *2022.04 - 2023.05* Acted as Researcher in Intelligent Fire Control Project, supervised by Professor <a href='http://cic.tju.edu.cn/faculty/yangliu/index.html'>Liu Yang</a>.
  1. In collaboration with <a href='http://www.farwide-electric.com/'>Shenzhen farwide-electric Co., Ltd (深圳弘远电气有限公司)</a>, a research project has been undertaken to explore the potential of Al in the field of hazardous fire protection, This project seeks to utilize Al technology to detect high voltage in order to preemptively control fires
  2. In this undertaking, l was responsible for the comprehensive upkeep of the system which encompasses an Al algorithm (such as SVM) and a Flask web framework, This necessitates a thorough understanding of the intricate interplay between the two components as well as the ability to identify and rectify any issues that may arise. Furthermore, I must guarantee its optimal performance (accuracy uplifted from 85% to 90%).
     
- *2023.04 - 2023.05* HKUST COMP 4901v Final Project, *Transformer-based Semantic Segmentation on 3D Point Clouds for Autonomous Driving*, supervised by Professor <a href='https://www.danxurgb.net/'> Dan XU</a>, and groupmates Martin R. Inauen, Mikhail Tsirlin.
  1. We reproduced the effort of the paper <a href='https://arxiv.org/abs/2012.09164'> Point Transformer</a> and delved into the potential of self-attention networks for self-driven related 3D point cloud processing. Our study involves understanding and using self-attention layers specifically for point clouds, which serve as fundamental building blocks for constructing self-attention networks deployed in semantic scene segmentation.
  2. <a href='https://peterjiangdingyi.github.io/transcripts.github.io/COMP4901v_Research.html'>CLICK Here to Browse Our Research Paper </a> \
             <img src="images/point.png" width = "500" height = "250" alt="" align=center /> 

     
# 🎖 Honors and Awards
- *2023.04* MCM/ICM Honorable Nomination. \
<img src="images/MA.jpg" width = "250" height = "270" alt="" align=center />  
- Coursera Deeplearning online course (Andrew Y Ngon) certification.\
<img src="images/standford_online.jpg" width = "250" height = "200" alt="" align=center />  

  



  
