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

5. **Policy shaping and generalized update equations for semantic parsing from denotations.** <br />
*Dipendra Misra, Ming-Wei Chang, Xiaodong He, Wen-tau Yih.* (EMNLP 2018). \[[paper](https://arxiv.org/pdf/1809.01299.pdf)\]\[[code](https://github.com/dkmisra/nsp)\]

6. **Neural symbolic machines: Learning semantic parsers on freebase with weak supervision.** <br />
*Chen Liang, Jonathan Berant, Quoc Le, Kenneth D. Forbus, Ni Lao.* (ACL 2017). \[[paper](https://arxiv.org/pdf/1611.00020.pdf)\]\[code\]

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

13. **Neural program induction for kbqa without gold programs or query annotations.** <br />
*Amrita Saha, Ghulam Ahmed Ansari, Abhishek Laddha, Karthik Sankaranarayanan, Soumen Chakrabarti.* (ACL 2019). \[[paper](https://watermark.silverchair.com/tacl_a_00262.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAswwggLIBgkqhkiG9w0BBwagggK5MIICtQIBADCCAq4GCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMt50kO9XTmD-9DlQQAgEQgIICf-mXS6J2_I7kpRt4QCzNe_BH_8ivDERheFUHhoJHtNwbdBS6N0bFOGy0CfBeXPMW8q5IebtDL4NosBPtY8H_ov-tVnbNGesD1UC0-zHCvCDAwSFmCfbzR8ujblmFTfL1tyXxUCBGtGy-BqEEedWepPyGDr6ZKM-hbb2REkRm5VGG6bM1eA5HIIE0HowY5ovholxHQxxfJpxSXnXH7S3AzvBoffACTdUCyKxXfDEaLQcKP-ojai5hqfn62_lujPia-00_YKG7AlGp4NwU-v5sWknsK_4-hLpvDvZgAce2jYLUiDRK1Pr8oMpE3j5i605YEmrHch_6BVxP5rYjziF4mgH_VPCdoXoaxFoTiRieSV1nDJIDahz80wZwUTWHyL6zH2XjdDpaTo6wHKC_iL_xjTwFYBJ-ovKIhnxmvTwQY6f6qQN-5zYIrctIXR4EJS-9QNSZcRpTnjrkb_QIsMW0YyxM8NVAEB2XpH4WJFjw_MSaiyKxCLZ_5HBnO_1_QUYYMI6Q8necvRMMg4juxGb7uR06DaCZq0DwWNa_rCtNu08TeSiVzf4fYWjON22sc8f7CtzcyMEfZkReKUEwEFJTKsFQp2rHqQAX-1zybgs4ycmpmig1i3MtdeHtPnzQbbIObMzzfcJhL6E9sScwA1k9gxNwLjzR6AH276R8KnbteyOIAQzv5_nko7SfymmYMn_L0mtRytR0m9nsFqhD2qnbkMJ_1I3ecJ7quo9loNfXu9NjJR1eZFrhe06uOMwe-naEQG-EgPw0d7MTmMDz0tfo_xTKpkG1zfWTTOu5Cie94SKTh7YicV6sk-RCUZFwYyoBhbwJ7qByPAq48YkXitlk-A)\]\[[code](https://github.com/CIPITR/CIPITR)\]

14. **Unified Semantic Parsing with Weak Supervision.** <br />
*Priyanka Agrawal, Parag Jain, Ayushi Dalmia, Abhishek Bansal, Ashish Mittal, Karthik Sankaranarayanan.* (ACL 2019). \[[paper](https://arxiv.org/pdf/1906.05062.pdf)\]\[[code](https://github.com/pagrawal-ml/Unified-Semantic-Parsing)\]

15. **Iterative search for weakly supervised semantic parsing.** <br />
*Pradeep Dasigi, Matt Gardnerê, Shikhar Murty,
Luke Zettlemoyer, and Eduard Hovy.* (NAACL 2019). \[[paper](https://aclanthology.org/N19-1273.pdf)\]\[code\]

16. **Learning structured natural language representations for semantic parsing.** <br />
*Jianpeng Cheng, Siva Reddy, Vijay Saraswat, and Mirella Lapata.* (NAACL 2019). \[[paper](https://arxiv.org/pdf/1704.08387.pdf)\]\[[code](https://github.com/cheng6076/scanner)\]

**Key-Value Memory Network:**


**Differentiable Path:**


**Graph Neural Network:**


**Others:**


### Comments
If you find any errors in the above information, please let us know in Issues. Pull requests are welcomed for adding papers.
