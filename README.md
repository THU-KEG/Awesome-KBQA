## Must-read papers on KBQA.
KBQA: answering natual language questions over knowledge bases.


### Datasets
1.**[WebQuestions](https://worksheets.codalab.org/worksheets/0xba659fe363cb46e7a505c5b6a774dc8a)**

**Semantic Parsing on Freebase from Question-Answer Pairs.**

Jonathan Berant, Andrew Chou, Roy Frostig, Percy Liang. EMNLP 2013. [paper](https://aclanthology.org/D13-1160.pdf)

2.**[QALD](http://qald.aksw.org/)**

**Evaluating question answering over linked data.**

Vanessa Lopez, Christina Unger, Philipp Cimiano, Enrico Motta. Web Semantics Science Services And Agents On The World Wide Web 2013. [paper](https://www.sciencedirect.com/science/article/abs/pii/S157082681300022X)

3.**[ComplexQuestions](https://github.com/JunweiBao/MulCQA/tree/ComplexQuestions)**

**Constraint-Based Question Answering with Knowledge Graph.**

Junwei Bao, Nan Duan, Zhao Yan, Ming Zhou, Tiejun Zhao. COLING 2016. [paper](https://aclanthology.org/C16-1236.pdf)

4.**[WebQuestionsSP](https://www.microsoft.com/en-us/download/details.aspx?id=52763)**

**The Value of Semantic Parse Labeling for Knowledge Base Question Answering.**

Wen-tau Yih, Matthew Richardson, Christopher Meek, Ming-Wei Chang, Jina Suh. ACL 2016. [paper](https://aclanthology.org/P16-2033.pdf)

5.**[LC-QuAD 1.0](http://lc-quad.sda.tech/lcquad1.0.html)**

**LC-QuAD: A Corpus for Complex Question Answering over Knowledge Graphs.**

Priyansh Trivedi, Gaurav Maheshwari,  Mohnish Dubey, Jens Lehmann. ISWC 2017. [paper](https://jens-lehmann.org/files/2017/iswc_lcquad.pdf)

6.**[ComplexWebQuestions](https://allenai.org/data/complexwebquestions)**

**The Web as a Knowledge-base for Answering Complex Questions.**

Alon Talmor,  Jonathan Berant. NAACL 2018. [paper](https://arxiv.org/pdf/1803.06643.pdf)

7.**[MetaQA Vanilla](https://github.com/yuyuz/MetaQA)**

**Variational Reasoning for Question Answering with Knowledge Graph.**

Yuyu Zhang, Hanjun Dai, Zornitsa Kozareva, Alexander J. Smola, Le Song. AAAI 2018. [paper](https://arxiv.org/pdf/1709.04071.pdf)

8.**[LC-QuAD 2.0](http://lc-quad.sda.tech/)**

**LC-QuAD 2.0: A Large Dataset for Complex Question Answering over Wikidata and DBpedia.**

Mohnish Dubey, Debayan Banerjee, Abdelrahman Abdelkawi, Jens Lehmann. ISWC 2019. [paper](https://jens-lehmann.org/files/2019/iswc_lcquad2.pdf)

9.**[CFQ](https://github.com/google-research/google-research/tree/master/cfq)**

**MEASURING COMPOSITIONAL GENERALIZATION: A COMPREHENSIVE METHOD ON REALISTIC DATA.**

Daniel Keysers, Nathanael Schärli, Nathan Scales, Hylke Buisman, Daniel Furrer, Sergii Kashubin, Nikola Momchev, Danila Sinopalnikov, Lukasz Stafiniak, Tibor Tihon,
Dmitry Tsarkov, Xiao Wang, Marc van Zee Olivier Bousquet. ICLR 2020. [paper](https://arxiv.org/pdf/1912.09713.pdf)

10.**[KQA Pro](http://thukeg.gitee.io/kqa-pro/)**

**KQA Pro: A Large-Scale Dataset with Interpretable Programs and Accurate SPARQLs for Complex Question Answering over Knowledge Base.**

Jiaxin Shi, Shulin Cao, Liangming Pan, Yutong Xiang, Lei Hou, Juanzi Li, Hanwang Zhang, Bin He. arXiv 2020. [paper](https://arxiv.org/pdf/2007.03875.pdf)

11.**[GrailQA](https://dki-lab.github.io/GrailQA/)**

**Beyond I.I.D.: Three Levels of Generalization for Question Answering on Knowledge Bases.**

Yu Gu, Sue Kase, Michelle T. Vanni, Brian M. Sadler, Percy Liang, Xifeng Yan, Yu Su. WWW 2021. \[[paper](https://arxiv.org/pdf/2011.07743.pdf)


### Leaderboard

KQA Pro: [http://thukeg.gitee.io/kqa-pro/](http://thukeg.gitee.io/kqa-pro/)

GrailQA: [https://dki-lab.github.io/GrailQA/](https://dki-lab.github.io/GrailQA/)


### Survey papers

1. **A Survey on Complex Knowledge Base Question Answering: Methods, Challenges and Solutions.**
*Yunshi Lan*, Gaole He*, Jinhao Jiang, Jing Jiang, Wayne Xin Zhao and Ji-Rong Wen.* IJCAI 2021 (Survey). [paper](https://arxiv.org/pdf/2105.11644.pdf)

### Simple KBQA

**Relation classification**

1. **Semantic parsing for single relation question answering**. *Wen-tau Yih, Xiaodong He, Christopher Meek*. (ACL 2014). [[paper](https://www.aclweb.org/anthology/P14-2105.pdf)]

2. **Information extraction over structured data: Question answering with Freebase**. *Xuchen Yao, Benjamin Van Durme*. (ACL 2014). [[paper](https://www.aclweb.org/anthology/P14-1090.pdf)]

3. **CFO: Conditional Focused Neural Question Answering with Large-scale Knowledge Bases**
   *Zihang Dai, Lei Lir, Wei Xu* (ACL 2016) [[paper](https://aclanthology.org/P16-1076.pdf)] [[code](https://github.com/zihangdai/cfo)]

4. **Question answering on freebase via relation extraction and textual evidence**. *Kun Xu, Siva Reddy, Yansong Feng, Songfang Huang, Dongyan Zhao* (ACL 2016). [[paper](https://www.aclweb.org/anthology/P16-1220.pdf)] [[code](https://github.com/syxu828/QuestionAnsweringOverFB)]

5. **No Need to Pay Attention: Simple Recurrent Neural Networks Work! (for Answering “Simple” Questions)**
   *Ferhan Ture, Oliver Jojic* (EMNLP 2017) [[paper](https://aclanthology.org/D17-1307.pdf)] 

6. **Strong Baselines for Simple Question Answering over Knowledge Graphs with and without Neural Networks**
   *Salman Mohammed, Peng Shi,  Jimmy Lin* (NAACL 2018) [[paper](https://aclanthology.org/N18-2047.pdf)]

7. **SimpleQuestions Nearly Solved:A New Upperbound and Baseline Approach**
   *Michael Petrochuk, Luke Zettlemoyer* (EMNLP 2018) [[paper](https://aclanthology.org/D18-1051.pdf)] [[code](https://github.com/PetrochukM/Simple-QA-EMNLP-2018)]

   
**Semantic matching**

1. **Question answering with subgraph embeddings**. *Antoine Bordes, Sumit Chopra, Jason Weston*. (EMNLP 2014). [[paper](https://arxiv.org/pdf/1406.3676.pdf)]

2. **Question Answering over Freebase with Multi-Column Convolutional Neural Networks**
   *Li Dong, Furu Wei, Ming Zhou, Ke Xu* (ACL 2015) [[paper](https://aclanthology.org/P15-1026.pdf)] 

3. **Large-scale Simple Question Answering with Memory Networks**
   *Antoine Bordes, Nicolas Usunier, Sumit Chopra, Jason Weston* (CoRR 2015) [[paper](https://arxiv.org/pdf/1506.02075.pdf)] 

4. **Simple Question Answering by Attentive Convolutional Neural Network**
   *Bing Xiang, Bowen Zhou, Hinrich Schütze, Mo Yu, Wenpeng Yin* (COLING 2016) [[paper](https://aclanthology.org/C16-1164.pdf)]  [[code]( https://github.com/Gorov/SimpleQuestions-EntityLinking)]

5. **Character-level question answering with attention.**
   *David Golub, Xiaodong He* (EMNLP 2016) [[paper](https://aclanthology.org/D16-1166.pdf)] [[code](https://github.com/davidgolub/simpleqa)]

6. **Question answering over knowledge base using factual memory networks**. *Sarthak Jain*. (NAACL 2016) [[paper](https://www.aclweb.org/anthology/N16-2016.pdf)]

7. **An End-to-End Model for Question Answering over Knowledge Base with Cross-Attention Combining Global Knowledge**
   *Yanchao Hao, Yuanzhe Zhang, Kang Liu, Shizhu He, Jun Zhao* (ACL 2017) [[paper](https://aclanthology.org/P17-1021.pdf)] 

8. **Neural Network-based Question Answering over Knowledge Graphs on Word and Character Level**
   *Denis Lukovnikov, Asja Fischer, Jens Lehmann, Sören Auer* (WWW 2017) [[paper](http://papers.www2017.com.au.s3-website-ap-southeast-2.amazonaws.com/proceedings/p1211.pdf)] [[code](https://github.com/WDAqua/teafacto)]

9. **Improved Neural Relation Detection for Knowledge Base Question Answering**
   *Mo Yu, Bowen Zhou* (ACL 2017) [[paper](https://aclanthology.org/P17-1053.pdf)] 

10. **Dual Constrained Question Embeddings with Relational Knowledge Bases for Simple Question Answering**
    *Kaustubh Kulkarni, Riku Togashi, Hideyuki Maeda, Sumio Fujita* (IJCNLP 2017) [[paper](https://aclanthology.org/I17-2037.pdf)] 

11. **Knowledge Base Relation Detection via Multi-View Matching**
    *Yang Yu, Kazi Saidul Hasan, Mo Yu, Wei Zhang, Zhiguo Wang* (Arixv) [[paper](https://arxiv.org/pdf/1803.00612.pdf)] 

12. **Retrieve and Re-rank: A Simple and Effective IR Approach to Simple
    Question Answering over Knowledge Graphs**
      *Vishal Gupta, Manoj Chinnakotla, Manish Shrivastava* (EMNLP 2018) [[paper](https://aclanthology.org/W18-5504.pdf)] 

13. **Pattern-revising Enhanced Simple Question Answering over Knowledge Bases**
    *Yanchao Hao, Hao Liu, Shizhu He, Kang Liu, Jun Zhao* (COLING 2018) [[paper](https://aclanthology.org/C18-1277.pdf)] 

14. **Knowledge Graph Embedding Based Question Answering**
    *Xiao Huang, Jingyuan Zhang, Dingcheng Li, Ping Li* (WSDM 2019) [[paper](http://research.baidu.com/Public/uploads/5c1c9a58317b3.pdf)] 

15. **Simple Question Answering with Subgraph Ranking and Joint-Scoring**
    *Wenbo Zhao, Tagyoung Chung, Anuj Goyal, Angeliki Metallinou* (NAACL 2019) [[paper](https://arxiv.org/pdf/1904.04049.pdf)] 

16. **Bidirectional Attentive Memory Networks for Question Answering over Knowledge Bases**. *Yu Chen, Lingfei Wu, Mohammed J. Zaki*. (NAACL 2019). [[paper](https://arxiv.org/pdf/1903.02188.pdf)] [[Code](https://github.com/hugochan/BAMnet?utm_source=catalyzex.com)]

17. **Adversarial Training Improved Multi-path Multi-scale Relation Detector for Knowledge Base Question Answering**
    *Yanan Zhang, Guangluan Xu, Xingyu Fu, Li Jin, Tinglei Huang* (IEEE Access 2020) [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9050788)] 

18. **DAM: Transformer-based relation detection for Question Answering over Knowledge Base**
    *Yongrui Chen, Huiying Li* (KBS 2020) [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705120303579?via%3Dihubf)]

    
**Others**

1. **Learning to compose neural networks for question answering**. *Jacob Andreas, Marcus Rohrbach, Trevor Darrell, Dan Klein* (NAACL 2016). [[paper](https://arxiv.org/pdf/1601.01705.pdf)] [[Code](https://github.com/jacobandreas/nmn2)] 
2. **Hybrid question answering over knowledge base and free text**. *Kun Xu, Yansong Feng, Songfang Huang, Dongyan Zhao* (COLING 2016). [[paper](https://www.aclweb.org/anthology/C16-1226.pdf)]
3. **Recovering Question Answering Errors via Query Revision**
   *Semih Yavuz, Izzeddin Gur, Yu Su, Xifeng Yan* (EMNLP 2017) [[paper](https://aclanthology.org/D17-1094.pdf)] 
4. **The APVA-TURBO Approach To Question Answering in Knowledge Base**
   *Yue Wang, Richong Zhang, Cheng Xu, Yongyi Mao* (COLING 2018) [[paper](hhttps://aclanthology.org/C18-1170.pdf)] 
5. **Pattern-revising Enhanced Simple Question Answering over Knowledge Bases**
   *Yanchao Hao, Hao Liu, Shizhu He, Kang Liu, Jun Zhao* (COLING 2018) [[paper](https://aclanthology.org/C18-1277.pdf)] 
6. **Hierarchical Type Constrained Topic Entity Detection forKnowledge Base Question Answering**
   *Yunqi Qiu, Manling Li, Yuanzhuo Wang, Yantao Jia, Xiaolong Jin* (WWW 2018) [[paper](https://dl.acm.org/doi/epdf/10.1145/3184558.3186916)] 
7. **Knowledge Base Question Answering with Topic Units**
   *Yunshi Lan , Shuohang Wang and Jing Jiang* (IJCAI 2019) [[paper](https://www.ijcai.org/Proceedings/2019/0701.pdf)] 
8. **Learning Representation Mapping for Relation Detection in Knowledge Base Question Answering**
   *Peng Wu, Jiajun Chen* (ACL 2019) [[paper](https://aclanthology.org/P19-1616.pdf)] [[code](https://github.com/wudapeng268/KBQA-Adapter)]
9. **Knowledge Graph Simple Question Answering for Unseen Domains**
   *Georgios Sidiropoulos, Nikos Voskarides , Evangelos Kanoulas* (AKBC 2020) [[paper](https://www.akbc.ws/2020/assets/pdfs/Ie2Y94Ty8K.pdf)] 

### Complex KBQA

**Supervised Semantic Parsing:**

1. **Learning to Transform Natural to Formal Language.** <br />
*Rohit J. Kit, Yuk Wah Wong, Raymond J. Mooney.* (AAAI 2005). \[[paper](https://www.aaai.org/Papers/AAAI/2005/AAAI05-168.pdf)\]\[code\]

2. **A Generative Model for Parsing Natural Language to Meaning Representations.**<br />
*Wei Lu, Hwee Tou Ng, Wee Sun Lee.* (EMNLP 2008). \[[paper](https://aclanthology.org/D08-1082.pdf)\]\[code\]

3. **Lexical Generalization in CCG Grammar Induction for Semantic Parsing.** <br />
*Tom Kwiatkowsk, Luke Zettlemoyer, Sharon Goldwater, Mark Steedman.* (EMNLP 2011). \[[paper](https://aclanthology.org/D11-1140.pdf)\]\[code\]

4. **Sequence to Sequence Learning with Neural Networks.** <br />
*Ilya Sutskever, Oriol Vinyals, Quoc V. Le.* (NIPS 2014). \[[paper](https://proceedings.neurips.cc/paper/2014/file/a14ac55a4f27472c5d894ec1c3c743d2-Paper.pdf)\]\[code\]

5. **Language to logical form with neural attention.** <br />
*Li Dong, Mirella Lapata.* (ACL 2016). \[[paper](https://arxiv.org/pdf/1601.01280.pdf)\]\[code\]

6. **Neural semantic parsing over multiple knowledge-bases.** <br />
*Herzig J, Berant J.* (ACL 2017). \[[paper](https://arxiv.org/pdf/1702.01569.pdf)\]\[[code](https://github.com/donglixp/confidence)\]

7. **Coarse-to-Fine Decoding for Neural Semantic Parsing.** <br />
*Li Dong, Mirella Lapata.* (ACL 2018). \[[paper](https://arxiv.org/pdf/1805.04793.pdf)\]\[code\]

8. **Confidence Modeling for Neural Semantic Parsing.** <br />
*Li Dong, Chris Quirk, Mirella Lapata.* (ACL 2018). \[[paper](https://arxiv.org/pdf/1805.04604.pdf)\]\[[code](https://github.com/donglixp/confidence)\]

9. **Confidence Modeling for Neural Semantic Parsing.** <br />
*Li Dong, Chris Quirk, Mirella Lapata.* (ACL 2018). \[[paper](https://arxiv.org/pdf/1805.04604.pdf)\]\[[code](https://github.com/donglixp/confidence)\]

10. **An Interactive Mechanism to Improve Question Answering Systems via Feedback.** <br />
*Xinbo Zhang, Lei Zou, Sen Hu.* (CIKM 2019). \[[paper](https://www.researchgate.net/profile/Sen-Hu-8/publication/337017751_An_Interactive_Mechanism_to_Improve_Question_Answering_Systems_via_Feedback/links/5ea3b113299bf112560c3373/An-Interactive-Mechanism-to-Improve-Question-Answering-Systems-via-Feedback.pdf)\]\[code\]

11. **Complex question decomposition for semantic parsing.** <br />
*Haoyu Zhang, Jingjing Cai, Jianjun Xu, Ji Wang.* (ACL 2019). \[[paper](https://aclanthology.org/P19-1440.pdf)\]\[[code](https://github.com/cairoHy/HSP)\]

12. **Leveraging frequent query substructures to generate formal queries for complex question answering.** <br />
*Jiwei Ding, Wei Hu, Qixin Xu, Yuzhong Qu.* (EMNLP-IJCNLP 2019). \[[paper](https://arxiv.org/pdf/1908.11053.pdf)\]\[code\]

13. **Graph-based transformer with cross-candidate verification for semantic parsing.** <br />
*Shao B, Gong Y, Qi W, et al.* (AAAI 2020). \[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/6408/6264)\]\[code\]

14. **SPARQA: Skeleton-based semantic parsing for complex questions over knowledge bases.** <br />
*Yawei Sun, Lingling Zhang, Gong Cheng, Yuzhong Qu.* (AAAI 2020). \[[paper](https://arxiv.org/pdf/2003.13956.pdf)\]\[[code](https://github.com/nju-websoft/SPARQA)\]

**Weakly-Supervised Semantic Parsing:**

1. **Semantic parsing via staged query graph generation: Question answering with knowledge base.** <br />
*Yih W, Chang M W, He X, et al.* (ACL-IJCNLP 2015). \[[paper](https://www.aaai.org/Papers/AAAI/2005/AAAI05-168.pdf)\]\[[code](https://github.com/scottyih/STAGG)\]

2. **Transforming dependency structures to logical forms for semantic parsing.** <br />
*Reddy S, Täckström O, Collins M, et al.* (ACL 2016). \[[paper](https://watermark.silverchair.com/tacl_a_00088.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAswwggLIBgkqhkiG9w0BBwagggK5MIICtQIBADCCAq4GCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMifgqPAF0iMu01xB_AgEQgIICf0GNI3rzd6RXzmCo_0v0XWbw7OrbX9MkyNEUqzfUyAfaRROyZ0XPikpiSoTRVD5-bgjNTLQH6TKazL1NP8lOBOi1Z8FrnxD8DphHoLJjW4RmZ_VGoREMSNg2VuPWOjnil8n_LfBMr2BaUJFh7mCZ4d2CuqFUVuS17GavXHWuiM52PP4V2KmaPXIgqUtzFmtfuqBD7c1MQOgn-PMJ7Vux1R8ff3oVqVrpvc95oWrC6qjK99r8OHSpw9J11EmQZ0Zh81eOHLGdLofjGFb6KjU_Re2CW3x8M85Tp53OqdPk7q6B5eONS36GZRsZHbhyIhJ3Kc4_C_OWuOPcDZOV5T69Y6PX1vj257HNzJE8ZwMeL4Hthdu4icJbJafMhzAaIVr66tZ82V_HB0Z3vB3DAAr21W1GtL62w4OBVGMcZlCjq43ZrRJTaSG7vrY8b-XoZhN6tszpIi-3NbT1eHWiNXAw8mJ3Gqeb-RV9XZlWVRGrybsrCMZYXvgNVypbBZRTTSTfgq7zHNL_4rYMUNaSYYoEJ8sZsIuEmlDOBpJW6aH4pUs6oBPrc1m0yDDDt7XBTe_mLpyZAoIR6d80HeMw1kg27BiBiszEFQR5RQufF0uQ6qqji1WhOyE_0zsxIQ5XDPHq4EXcCpEebLzUx_RTdFUmD2jfpUSTOxC4YdIZ09eGbZMiPdbCInWnvAkc7yfqAwgZPXfRHK4EBN3x-MDxmW2kmN2RDyyZYZbTG8owW6nUkmdm40zqQzse1LP8ZReIHWEQQ9scUOJpvnWARpNF3dw5fYJdgnxRodcRYVWxvC237ZYmrpXnWK-BqnSct0ILnstWJ6_-tkatJFDY_iqn0DQKJQ)\]\[[code](https://github.com/sivareddyg/deplambda)\]

3. **Inferring logical forms from denotations.** <br />
*Pasupat P, Liang P.* (ACL 2016). \[[paper](https://arxiv.org/pdf/1606.06900.pdf)\]\[code\]

4. **Universal semantic parsing.** <br />
*Reddy S, Täckström O, Petrov S, et al.* (EMNLP 2017). \[[paper](https://arxiv.org/pdf/1702.03196.pdf)\]\[[code](https://github.com/sivareddyg/UDepLambda)\]

5. **Neural Symbolic Machines: Learning Semantic Parsers on Freebase with Weak Supervision.** <br />
*Chen Liang, Jonathan Berant, Quoc Le, Kenneth D. Forbus, Ni Lao.* (ACL 2017). \[[paper](https://arxiv.org/pdf/1611.00020.pdf?source=post_page---------------------------)\]\[[code](https://github.com/crazydonkey200/neural-symbolic-machines)\]

6. **Policy shaping and generalized update equations for semantic parsing from denotations.** <br />
*Dipendra Misra, Ming-Wei Chang, Xiaodong He, Wen-tau Yih.* (EMNLP 2018). \[[paper](https://arxiv.org/pdf/1809.01299.pdf)\]\[[code](https://github.com/dkmisra/nsp)\]

7. **Dialog-to-action: conversational question answering over a large-scale knowledge base.** <br />
*Daya Guo, Duyu Tang, Nan Duan, Ming Zhou, and Jian Yin* (Neurips 2018). \[[paper](https://proceedings.neurips.cc/paper/2018/file/d63fbf8c3173730f82b150c5ef38b8ff-Paper.pdf)\]\[[code](https://github.com/guoday/Dialog-to-Action)\]

8. **A state-transition framework to answer complex questions over knowledge base.** <br />
*YHu S, Zou L, Zhang X.* (EMNLP 2018). \[[paper](https://aclanthology.org/D18-1234.pdf)\]\[[code](https://github.com/scottyih/STAGG)\]

9. **Knowledge base question answering via encoding of complex query graphs.** <br />
*Luo K, Lin F, Luo X, et al.* (EMNLP 2018). \[[paper](https://aclanthology.org/D18-1242.pdf)\]\[[code](https://github.com/lkq1992yeah/CompQA)\]

10. **Modeling semantics with gated graph neural networks for knowledge base question answering.** <br />
*Sorokin D, Gurevych I.* (COLING 2018). \[[paper](https://aclanthology.org/D18-1242.pdf)\]\[[code](https://github.com/UKPLab/coling2018-graph-neural-networks-question-answering)\]

11. **Learning to answer complex questions over knowledge bases with query composition.** <br />
*Bhutani N, Zheng X, Jagadish H V.* (CIKM 2019). \[[paper](https://dl.acm.org/doi/10.1145/3357384.3358033)\]\[code\]

12. **Neural program induction for kbqa without gold programs or query annotations.** <br />
*Ghulam Ahmed Ansari, Amrita Saha, Vishwajeet Kumar, Mohan Bhambhani, Karthik Sankaranarayanan, Soumen Chakrabarti.* (IJCAI 2019). \[[paper](https://www.ijcai.org/proceedings/2019/0679.pdf)\]\[[code](https://github.com/CIPITR/SSRP)\]

13. **Unified Semantic Parsing with Weak Supervision.** <br />
*Priyanka Agrawal, Parag Jain, Ayushi Dalmia, Abhishek Bansal, Ashish Mittal, Karthik Sankaranarayanan.* (ACL 2019). \[[paper](https://arxiv.org/pdf/1906.05062.pdf)\]\[[code](https://github.com/pagrawal-ml/Unified-Semantic-Parsing)\]

14. **Iterative search for weakly supervised semantic parsing.** <br />
*Pradeep Dasigi, Matt Gardnerê, Shikhar Murty,
Luke Zettlemoyer, and Eduard Hovy.* (NAACL 2019). \[[paper](https://aclanthology.org/N19-1273.pdf)\]\[code\]

15. **Learning structured natural language representations for semantic parsing.** <br />
*Jianpeng Cheng, Siva Reddy, Vijay Saraswat, and Mirella Lapata.* (NAACL 2019). \[[paper](https://arxiv.org/pdf/1704.08387.pdf)\]\[[code](https://github.com/cheng6076/scanner)\]

16. **Complex program induction for querying knowledge bases in the absence of gold programs.** <br />
*Amrita Saha, Ghulam Ahmed Ansari, Abhishek Laddha, Karthik Sankaranarayanan, Soumen Chakrabarti.* (TACL 2019). \[[paper](https://watermark.silverchair.com/tacl_a_00262.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAswwggLIBgkqhkiG9w0BBwagggK5MIICtQIBADCCAq4GCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMoPKqRuNyGBu6y56BAgEQgIICf_IxW1T9FpnYE8vbvEq8mXRFcg2xYb1BCmG8wdxLz-oYqKk_XBW3PTT1_mdDXPvIBu-dBHX1dSykate1kRDZT98jZMEeifT7r1FECIliAfqb5JqGjRhYoI3RJ98YzTTBW3acJGXhMoBGh9VuEroysYZargkakiJRv90x4XZUr-JMUZKFsh1tgqurPfRd-YiFXI7ze5x0_kAX5oI6LceanHvZXm5cQeeKcmz4xeIvzjUpTx_3bShn814uzo0s8fkwApf3Fqk9LKflVR0k0duurycnpPCHVOODV4uDnf7MdPfSQ2Tzs9lpSjMtoNcSyZVTeNcej3h2PCfwy9-younXopz_L5n8Mk2MkwtvGwJWHIHKCwDdSBotSoPjomBWl0d1mIZUwNHwB9ex2OsNN3YTKKW06EwJTmWkBBUVFeNZDGD1_J3DIFo5sOJ035zSFUAdPEt-Je11yS2CVNkkuoVlhuUtj5v5yIvtkF6KPRBNaWRlJOW5KQ-Ep4YXZ8BMD2T-iirLKQsdYiU9LAKNTGL0xJUBhIRtsNczDcPsraLrUVjuRLkgiWbe0PqlENZMRtu74Tn0nADxXoQ2LR0Q5GTBlGDA_bEHWqDyJf-Fvvlt1RiosjMaaYjhrsZ11k3awy7op6RpSk9AJtus4kqwgxKddL4kqPCmewOkxLLfJ_PZEOoAHPxAcVnxg1u8Opis32qkYi3Uo6UZsUj_yZ93YvkQpWbDEG8v7xaGlgLqk_n63ru9bT2Cq3v1Sfy3FmjQWMaWakGq3mNsjqmFvQyyRhmzxq7Shnev5z-tb0KMGm5yaWLS18HOMW6LITsphXkwE0iF2HOvrSmaQkkRPn7IYUE5Qw)\]\[[code](https://github.com/CIPITR/CIPITR)\]


**Relation Path:**

1. **An interpretable reasoning network for multi-relation question answering.** <br />
*Mantong Zhou, Minlie Huang, Xiaoyan Zhu.* (COLING 2018). \[[paper](https://arxiv.org/pdf/1801.04726.pdf)\]\[[code](https://github.com/gauravsinha7/IRNQA)\]

2. **UHop: An unrestricted-hop relation extraction framework for knowledge-based question answering.** <br />
*MZi-Yuan Chen, Chih-Hung Chang, Yi-Pei Chen, Jijnasa Nayak, Lun-Wei Ku.* (NAACL 2019). \[[paper](https://arxiv.org/pdf/1904.01246.pdf)\]\[[code](https://github.com/zychen423/UHop)\]


3. **Stepwise reasoning for multi-relation question answering over knowledge graph with weak supervision.** <br />
*Yunqi Qiu, Yuanzhuo Wang, Xiaolong Jin, Kun Zhang.* (WSDM 2020). \[[paper](https://www.researchgate.net/profile/Yunqi-Qiu/publication/338754985_Stepwise_Reasoning_for_Multi-Relation_Question_Answering_over_Knowledge_Graph_with_Weak_Supervision/links/5f916b3ca6fdccfd7b74bf5d/Stepwise-Reasoning-for-Multi-Relation-Question-Answering-over-Knowledge-Graph-with-Weak-Supervision.pdf)\]\[[code](https://github.com/DanSeb1295/multi-relation-QA-over-KG)\]


**Key-Value Memory Network:**

1. **Enhancing key-value memory neural networks for knowledge based question answering.** <br />
*Kun Xu, Yuxuan Lai, Yansong Feng, Zhiguo Wang* (NAACL 2019). \[[paper](https://aclanthology.org/N19-1301.pdf)\]\[[code]()\]


2. **Bidirectional Attentive Memory Networks for Question Answering over Knowledge Bases.** <br />
*Yu Chen, Lingfei Wu, Mohammed J. Zaki* (NAACL 2019). \[[paper](https://aclanthology.org/N19-1301.pdf)\]\[[code](https://github.com/jdfekete/geneaquilt)\]

**Differentiable Path:**

1. **Neural Query Language: A Knowledge Base Query Language for Tensorflow.** <br />
*William W. Cohen, Matthew Siegler, Alex Hofer*. \[[paper](https://arxiv.org/pdf/1905.06209.pdf)\]\[[code](https://github.com/jdfekete/geneaquilt)\]

2. **Scalable neural methods for reasoning with a symbolic knowledge base.** <br />
*William W. Cohen, Haitian Sun, R. Alex Hofer, Matthew Siegler* (ICLR 2020). \[[paper](https://arxiv.org/pdf/2002.06115.pdf)\]\[[code]()\]

3. **Faithful Embeddings for Knowledge Base Queries.** <br />
*Haitian Sun, Andrew O. Arnold, Tania Bedrax-Weiss, Fernando Pereira, William W. Cohen* (NeurIPS 2020). \[[paper](https://arxiv.org/pdf/2004.03658.pdf)\]\[[code](https://github.com/google-research/language)\]

**Graph Neural Network:**


1. **Open domain question answering using early fusion of knowledge bases and text.**<br />
*Haitian Sun, Bhuwan Dhingra, Manzil Zaheer, Kathryn Mazaitis, Ruslan Salakhutdinov, William W. Cohen*. (EMNLP 2018) \[[paper](https://arxiv.org/abs/1809.00782)\]\[[code](https://github.com/haitian-sun/GraftNet)\]


2. **PullNet: Open Domain Question Answering with Iterative Retrieval on Knowledge Bases and Text.** <br />
*Haitian Sun, Tania Bedrax-Weiss, William W. Cohen*. \[[paper](https://arxiv.org/abs/1904.09537)\]\[[code]()\]


**Others:**


1. **Message Passing for Complex Question Answering over Knowledge Graphs.**<br />
*Svitlana Vakulenko, Javier David Fernandez Garcia, Axel Polleres, Maarten de Rijke, Michael Cochez*. (CIKM 2019) \[[paper]([https://arxiv.org/abs/1809.00782](https://arxiv.org/pdf/1908.06917.pdf))\]\[[code](https://github.com/svakulenk0/KBQA)\]


2. **Question answering on freebase via relation extraction and textual evidence.**<br />
*Kun Xu, Siva Reddy, Yansong Feng, Songfang Huang, Dongyan Zhao*. (ACL 2016) \[[paper](https://arxiv.org/abs/1603.00957)\]\[[code](https://github.com/syxu828/QuestionAnsweringOverFB)\]


3. **Query2box: Reasoning over knowledge graphs in vector space using box embeddings.**<br />
*Hongyu Ren, Weihua Hu, Jure Leskovec*. (ICLR 2020) \[[paper](https://arxiv.org/abs/2002.05969)\]\[[code](http://snap.stanford.edu/query2box)\]


### Comments
If you find any errors in the above information, please let us know in Issues. Pull requests are welcomed for adding papers.
