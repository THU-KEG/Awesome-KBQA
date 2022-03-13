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

1. **Learning to Transform Natural to Formal Language.**\n
*Rohit J. Kit, Yuk Wah Wong, Raymond J. Mooney.* (AAAI 2005). \[[paper](https://www.aaai.org/Papers/AAAI/2005/AAAI05-168.pdf)\]\[code\]

2. **A Generative Model for Parsing Natural Language to Meaning Representations.**\n
*Wei Lu, Hwee Tou Ng, Wee Sun Lee.* (EMNLP 2008). \[[paper](https://aclanthology.org/D08-1082.pdf)\]\[code\]

3. **Lexical Generalization in CCG Grammar Induction for Semantic Parsing.**
*Tom Kwiatkowsk, Luke Zettlemoyer, Sharon Goldwater, Mark Steedman.* (EMNLP 2011). \[[paper](https://aclanthology.org/D11-1140.pdf)\]\[code\]

4. **Sequence to Sequence Learning with Neural Networks.**
*Ilya Sutskever, Oriol Vinyals, Quoc V. Le.* (NIPS 2014). \[[paper](https://proceedings.neurips.cc/paper/2014/file/a14ac55a4f27472c5d894ec1c3c743d2-Paper.pdf)\]\[code\]

5. **Language to logical form with neural attention.**
*Li Dong, Mirella Lapata.* (ACL 2016). \[[paper](https://arxiv.org/pdf/1601.01280.pdf)\]\[code\]

6. **Neural semantic parsing over multiple knowledge-bases.**
*Herzig J, Berant J.* (ACL 2017). \[[paper](https://arxiv.org/pdf/1702.01569.pdf)\]\[[code](https://github.com/donglixp/confidence)\]

7. **Coarse-to-Fine Decoding for Neural Semantic Parsing.**
*Li Dong, Mirella Lapata.* (ACL 2018). \[[paper](https://arxiv.org/pdf/1805.04793.pdf)\]\[code\]

8. **Confidence Modeling for Neural Semantic Parsing.**
*Li Dong, Chris Quirk, Mirella Lapata.* (ACL 2018). \[[paper](https://arxiv.org/pdf/1805.04604.pdf)\]\[[code](https://github.com/donglixp/confidence)\]

9. **Confidence Modeling for Neural Semantic Parsing.**
*Li Dong, Chris Quirk, Mirella Lapata.* (ACL 2018). \[[paper](https://arxiv.org/pdf/1805.04604.pdf)\]\[[code](https://github.com/donglixp/confidence)\]

10. **An Interactive Mechanism to Improve Question Answering Systems via Feedback.**
*Xinbo Zhang, Lei Zou, Sen Hu.* (CIKM 2019). \[[paper](https://www.researchgate.net/profile/Sen-Hu-8/publication/337017751_An_Interactive_Mechanism_to_Improve_Question_Answering_Systems_via_Feedback/links/5ea3b113299bf112560c3373/An-Interactive-Mechanism-to-Improve-Question-Answering-Systems-via-Feedback.pdf)\]\[code\]

11. **Complex question decomposition for semantic parsing.**
*Haoyu Zhang, Jingjing Cai, Jianjun Xu, Ji Wang.* (ACL 2019). \[[paper](https://aclanthology.org/P19-1440.pdf)\]\[[code](https://github.com/cairoHy/HSP)\]

12. **Leveraging frequent query substructures to generate formal queries for complex question answering.**
*Jiwei Ding, Wei Hu, Qixin Xu, Yuzhong Qu.* (EMNLP-IJCNLP 2019). \[[paper](https://arxiv.org/pdf/1908.11053.pdf)\]\[code\]

13. **Graph-based transformer with cross-candidate verification for semantic parsing.**
*Shao B, Gong Y, Qi W, et al.* (AAAI 2020). \[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/6408/6264)\]\[code\]

14. **SPARQA: Skeleton-based semantic parsing for complex questions over knowledge bases.**
*Yawei Sun, Lingling Zhang, Gong Cheng, Yuzhong Qu.* (AAAI 2020). \[[paper](https://arxiv.org/pdf/2003.13956.pdf)\]\[[code](https://github.com/nju-websoft/SPARQA)\]

**Weakly-Supervised Semantic Parsing:**


**Key-Value Memory Network:**


**Differentiable Path:**


**Graph Neural Network:**


**Others:**


### Comments
If you find any errors in the above information, please let us know in Issues. Pull requests are welcomed for adding papers.
