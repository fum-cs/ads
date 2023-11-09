---
layout: page
title: Algorithms for Data Science 
description: Listing of course modules and topics.
---

## <a name="Main-TextBooks"></a>Main TextBooks:

* [Data Mining and Analysis: Fundamental Concepts and Algorithms](https://dataminingbook.info/) by Mohammed J. Zaki and Wagner Meira Jr. (Data Mining & Analysis) [PDF](https://fumdrive.um.ac.ir/index.php/f/4160875)
* [Pattern Recognition](https://darmanto.akakom.ac.id/pengenalanpola/Pattern%20Recognition%204th%20Ed.%20(2009).pdf), by Sergios Theodoridis & ,Konstantinos Koutroumpas, 2009
* [The Elements of Statistical Learning (ESL)](https://fumdrive.um.ac.ir/index.php/s/FH8nB4SwGkJrMeQ)


## 1402/07/08
### <a name="L1"></a>Introduction to Data Science  
- Slide: [Introduction to Data Science](https://www.datasciencecourse.org/slides/15388_S22_Lecture_1_intro.pdf) by Zico Kolter
- Slide: [Introduction to Data Science](https://github.com/justmarkham/DAT8/blob/master/slides/01_intro_to_data_science.pdf) by Kevin Markham  
- Slide: [Clustering](https://mattdickenson.com/assets/clustering2.pdf) by Matt Dickenson 

**HW1**{: .label .label-red }[Generate random points with uniform distribution in the unit sphere](https://vu.um.ac.ir/mod/assign/view.php?id=441612), due date: 1402/07/21 (Extended)
    
### <a name="L2"></a>Python Programming
        
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)

**HW2**{: .label .label-red }[Satisfiability Table](https://vu.um.ac.ir/mod/assign/view.php?id=441616), due date: 1402/07/21 (Extended)


## 1402/07/10
Discrete Optimization
: Draft version of My Book: [Meta Heuristic Algorithms](https://www.dropbox.com/s/8bnxpzvfgiwma0k/combopt-PSO-20160514.pdf?dl=0)

Some Examples:
- N-Queen Problem
- Knight-Tour, [My old Delphi program](https://www.dropbox.com/s/okfa4lmzf1qqyus/NQueen-KnightTour.zip?dl=1), previous century!
- Traveling Salesman Problem
- Packing & Cutting Problems, [My old Delphi program](https://www.dropbox.com/s/3ztaqqlpki9e2ep/Thesis.zip?dl=1), previous century! My MSc. Project.

**Further Reading**{: .label .label-yellow }
- [Some published papers about the above programs](https://fumcs.github.io/projects/comb-opt/)

## 1402/07/15
: Random Search
  : Chapter 1 & 2 of [My Book](https://www.dropbox.com/s/8bnxpzvfgiwma0k/combopt-PSO-20160514.pdf?dl=0) + [My NP-Complete Paper](https://www.dropbox.com/s/gdwuin9xycbvxwa/1379-npcomplete.pdf?dl=0)

**HW3**{: .label .label-red }[Python Code of Program 1.2, Page 11 of My book - RS](https://vu.um.ac.ir/mod/assign/view.php?id=449054&forceview=1), due: 1402/07/25

## 1402/07/17
**HW1-Sol**{: .label .label-green }, Solution: **Colab**{: .label .label-green }[Unit Sphere](https://colab.research.google.com/github/fum-cs/fds/blob/main/code/hw1/fatehinia_data_algo.ipynb)
* SAT
* SA, Continue
  : Chapter 3 of [My Book](https://www.dropbox.com/s/8bnxpzvfgiwma0k/combopt-PSO-20160514.pdf?dl=0)

**HW4**{: .label .label-red }[Python Code of Program 1.3, Page 23 of My book - SA](https://vu.um.ac.ir/mod/assign/view.php?id=449055&forceview=1), due: 1402/07/26

**Further Reading**{: .label .label-yellow }
* [Simulated Annealing From Scratch in Python](https://machinelearningmastery.com/simulated-annealing-from-scratch-in-python/)
* [Simulated Annealing Tutorial, 2D Example](http://apmonitor.com/me575/index.php/Main/SimulatedAnnealing)


## 1402/07/22
: PSO
  : Chapter 6 of [My Book](https://www.dropbox.com/s/8bnxpzvfgiwma0k/combopt-PSO-20160514.pdf?dl=0)

**HW5**{: .label .label-red }Use one the Python packages to find the minimum of f(x)=3sin(x)+(0.1x-3)^2: [PSO for function 1.2](https://vu.um.ac.ir/mod/assign/view.php?id=449056&forceview=1), due: 1402/07/28

Some Python packages for PSO:
  * [Pymoo](https://pymoo.org/algorithms/soo/pso.html)
  * [PySwarms](https://pyswarms.readthedocs.io/en/latest/index.html)

**Further Reading**{: .label .label-yellow }
- [A Gentle Introduction to Particle Swarm Optimization](https://machinelearningmastery.com/a-gentle-introduction-to-particle-swarm-optimization/)
- **Paper**{: .label .label-blue }: [A Fish School Clustering Algorithm: Applied to Student Sectioning Problem](https://www.dropbox.com/scl/fi/89p637l3ok3k7zobc1msp/A-Fish-School-Clustering-Algorithm-Applied-to-Student-Sectioning-Problem.pdf?rlkey=0540d3lwox88jdxx781swxd2q&dl=0)


## 1402/07/24

* Chapter 11 & 12 of Pattern Recognition, Theodoridis
* Chapeter 11:
  - Page 602, Section 11.2 PROXIMITY MEASURES - Page 604
  - Page 606, Section B. Similarity Measures: The inner product & Pearson’s correlation coefficient
  - Page 607, Discrete-Valued Vectors & contingency table
  - Page 616, 11.2.3 Proximity Functions between a Point and a Set

* Chapter 12:
  - 12.1 INTRODUCTION
  - 12.3 SEQUENTIAL CLUSTERING ALGORITHMS

## 1402/07/29
* **HW2-Sol**{: .label .label-green }, Solution: 
  - **Colab**{: .label .label-green }[Fatehinia](https://colab.research.google.com/github/fum-cs/fds/blob/main/code/hw2/Fatehinia.ipynb)
  - **Colab**{: .label .label-green }[Bagherpour](https://colab.research.google.com/github/fum-cs/fds/blob/main/code/hw2/Bagherpour.ipynb)

* Stirling Numbers, Recursive Functions & SAT Table
  - **Colab**{: .label .label-green }[SAT Table](https://colab.research.google.com/github/fum-cs/fds/blob/main/code/SAT_Table.ipynb)

## 1402/08/01

* SAT Table & Brute Force Algorithm for Clustering
  - **Colab**{: .label .label-green }[Brute Force Alg for Clustering](https://colab.research.google.com/github/fum-cs/fds/blob/main/code/BF-clustering.ipynb)
  
**HW6**{: .label .label-red } [Generate data & Clustering](https://vu.um.ac.ir/mod/assign/view.php?id=454178), due: 1402/08/04

**HW7**{: .label .label-red }[BSAS Algorithm](https://vu.um.ac.ir/mod/assign/view.php?id=454181), due: 1402/08/07

### Image Processing and Computer Vision, Intro

**Colab**{: .label .label-green }[Image Segmentation 01](https://colab.research.google.com/github/fum-cs/fds/blob/main/code/image_seg_01.ipynb)

  
## 1402/08/06

### Representative-Based Clustering

* Section 14.3.5 of [ESL](https://fumdrive.um.ac.ir/index.php/s/FH8nB4SwGkJrMeQ)
   - Page 527/764 ESL, Eq. 14.28: W(C)
   - The problem with one unknown variable becomes a problem with two unknowns!
* Section 8.3 of [K-means Clustering](https://www.dropbox.com/s/mrxdshg6nx98ojk/kmeans-clustering.pdf?dl=1)
* **Colab**{: .label .label-green }[Image Segmentation 02- kmeans clustering](https://colab.research.google.com/github/fum-cs/fds/blob/main/code/image_seg_02_k-means.ipynb)
* Chapter 13 of [Data Mining & Analysis](https://dataminingbook.info/)  
* [Slides (Representative-based Clustering)](https://www.cs.rpi.edu/~zaki/DMML/slides/pdf/ychap13.pdf)

**Further Reading**{: .label .label-yellow }

* [Lloyd’s, MacQueen’s and Hartigan-Wong’s k-Means](https://towardsdatascience.com/three-versions-of-k-means-cf939b65f4ea)
* [Convergence in Hartigan-Wong k-means method and other algorithms](https://datascience.stackexchange.com/questions/9858/convergence-in-hartigan-wong-k-means-method-and-other-algorithms)

### 1402/08/13

* [sklearn.datasets.make_blobs](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_blobs.html)
* Section 14.3.6 of [ESL](https://fumdrive.um.ac.ir/index.php/s/FH8nB4SwGkJrMeQ)
   - Page 528/764 ESL, K-means

### 1402/08/15
* Section 14.3.9 of [ESL](https://fumdrive.um.ac.ir/index.php/s/FH8nB4SwGkJrMeQ)
   - Page 533/764 Vector Quantization

* **Colab**{: .label .label-green }[Image Segmentation 03- kmeans clustering](https://colab.research.google.com/github/fum-cs/fds/blob/main/code/image_seg_03_k-means_centers.ipynb)

* **Colab**{: .label .label-green }[LVQ](https://colab.research.google.com/github/fum-cs/fds/blob/main/code/LVQ.ipynb)

**HW8**{: .label .label-red }[K-means on color images](https://vu.um.ac.ir/mod/assign/view.php?id=458799), due: 1402/08/19

**Further Reading**{: .label .label-yellow }

* [Clustering, Lecture 14, New York University](https://people.csail.mit.edu/dsontag/courses/ml12/slides/lecture14.pdf) 
* [CSC 411 Lecture 15: K-Means, University of Toronto](https://www.cs.toronto.edu/~rgrosse/courses/csc411_f18/slides/lec15-slides.pdf)


# TBA


## 1402/08/20

### The curse of dimensionality

* Section 2.5 of [ESL](https://fumdrive.um.ac.ir/index.php/s/FH8nB4SwGkJrMeQ)
   - Page 41/764 Vector Quantization

* **Colab**{: .label .label-green }[The curse of dimensionality-KNN](https://colab.research.google.com/github/fum-cs/fds/blob/main/code/CD_KNN.ipynb)

* **Colab**{: .label .label-green }[Clustering of images](https://colab.research.google.com/github/fum-cs/fds/blob/main/code/image_clustering.ipynb)

## 1402/08/22

### Bias-Variance Tradeoff
* [Wiki](https://en.wikipedia.org/wiki/Bias%E2%80%93variance_tradeoff)
* [MLU-Explain bias-variance](https://mlu-explain.github.io/bias-variance/)
* [MLU-Explain double-descent, part 1](https://mlu-explain.github.io/double-descent/)

**Further Reading**{: .label .label-yellow }

* [MLU-Explain double-descent, part 2](https://mlu-explain.github.io/double-descent2/)
* [Sec 22.3 of Zaki](https://fumdrive.um.ac.ir/index.php/f/4160875)

**Paper**{: .label .label-blue }[Reconciling modern machine-learning practice and the classical bias–variance trade-off](https://www.pnas.org/doi/10.1073/pnas.1903070116#:~:text=This%20%E2%80%9Cdouble%2Ddescent%E2%80%9D%20curve,interpolation%20results%20in%20improved%20performance.)

**Paper**{: .label .label-blue }[Understanding the double descent curve in Machine Learning](https://arxiv.org/abs/2211.10322)

* Sec 5.11 of [JakeVanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/05.11-k-means.html)

**Paper**{: .label .label-blue } [كلاسه بندی فازی بهینه دانشجویان با استفاده از یك تابع فازی در حل مسئله برنامه ریزی ژنتیكی دروس هفتگی دانشگاه](https://www.dropbox.com/s/7ohrff9c6im8bye/1382-StudentSectioning.pdf?dl=1)

* [Bilateral K-Means for Superpixel Computation](https://hal-enpc.archives-ouvertes.fr/hal-03651336/document)
* [Balanced clustering - Wikipedia](https://en.wikipedia.org/wiki/Balanced_clustering) 
* [balanced-kmeans · PyPI](https://pypi.org/project/balanced-kmeans/)
* [K-means using PyTorch (github.com)](https://github.com/subhadarship/kmeans_pytorch)
* [Balanced K-Means for Clustering](https://link.springer.com/chapter/10.1007/978-3-662-44415-3_4)
* [Balanced k-Means Revisited](https://openreview.net/forum?id=VndsvZYlMo&amp;referrer=%5BTMLR%5D(%2Fgroup%3Fid%3DTMLR))
* [K-Means Clustering in Python: A Practical Guide – Real Python](https://realpython.com/k-means-clustering-python/)
* [Data clustering: 50 years beyond K-means - ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0167865509002323)
* [K-Means Factorization](https://www.dropbox.com/s/2fsmpj7i7x3rngy/K-Means%20Factorizaton1512.07548.pdf?dl=1)

### Image Processing and Computer Vision
- Website: [Image Processing in Python with Scikit-image](https://blog.faradars.org/image-processing-in-python/) by M. Jaderian 
  * [Scikit-image documentation](https://scikit-image.org/docs/stable/)
  * [Scikit-image examples](https://scikit-image.org/docs/stable/auto_examples/index.html)
- Website: [Image Processing in Python with OpenCV](https://www.m-vision.ir/%D8%A2%D9%85%D9%88%D8%B2%D8%B4/%D9%BE%D8%B1%D8%AF%D8%A7%D8%B2%D8%B4-%D8%AA%D8%B5%D9%88%DB%8C%D8%B1/opencv/%D8%A2%D9%85%D9%88%D8%B2%D8%B4-%D9%BE%D8%B1%D8%AF%D8%A7%D8%B2%D8%B4-%D8%AA%D8%B5%D9%88%DB%8C%D8%B1-%D8%A8%D8%A7-%D9%BE%D8%A7%DB%8C%D8%AA%D9%88%D9%86-%D8%AA%D9%88%D8%B3%D8%B7-opencv/) by M. Kiani 
- Github: [Tutorial for Image Processing in Python](https://github.com/zengsn/image-processing-python) by Shaoning Zeng 
- Book: [Image processing tutorials](https://github.com/yg42/iptutorials/blob/master/book/tutorials_python.pdf)
    

**Further Reading**{: .label .label-yellow }
: [Some published papers](https://fumcs.github.io/projects/computer-vision/)
* [الگوریتم مجارستانی - ویکی‌پدیا، دانشنامهٔ آزاد (wikipedia.org)](https://fa.wikipedia.org/wiki/%D8%A7%D9%84%DA%AF%D9%88%D8%B1%DB%8C%D8%AA%D9%85_%D9%85%D8%AC%D8%A7%D8%B1%D8%B3%D8%AA%D8%A7%D9%86%DB%8C)

### <a name="L4"></a>Image Matting
- Github Rep.: [A Python library for alpha matting](https://github.com/pymatting/pymatting) [https://pymatting.github.io/](https://pymatting.github.io/) by Y. Gavet & J. Debayle  

### Image Segmentation
**Paper**{: .label .label-blue }


1402/08
### Representative-Based Clustering

- Chapter 13 of [Data Mining & Analysis](https://dataminingbook.info/)  
- **HW**{: .label .label-red } 13.5: Q2, Q4, Q6, Q7 
- Slides (Representative-based Clustering): [PDF](https://www.cs.rpi.edu/~zaki/DMML/slides/pdf/ychap13.pdf)
- Slide: [Introduction to Machine Learning (Clustering and EM)](http://www.cs.cmu.edu/~aarti/Class/10701_Spring14/slides/EM.pdf) by Barnabás Póczos & Aarti Singh 
- Tutorial: [The Expectation Maximization Algorithm](https://www.cs.utah.edu/~piyush/teaching/EM_algorithm.pdf) by 
Sean Borman 
- Tutorial: [What is Bayesian Statistics?](http://www.bandolier.org.uk/painres/download/whatis/What_is_Bay_stats.pdf) by John W Stevens
    
**Further Reading**{: .label .label-yellow }
    
- Slide: [Tutorial on Estimation and Multivariate Gaussians](http://ttic.uchicago.edu/~shubhendu/Slides/Estimation.pdf) by Shubhendu Trivedi 
- Slide: [Mixture Model](https://cse.buffalo.edu/~jing/cse601/fa12/materials/clustering_mixture.pdf) by Jing Gao 
- Paper: [Fast Exact k-Means, k-Medians and Bregman Divergence Clustering in 1D](https://cs.au.dk/~larsen/papers/1dkmeans.pdf) 
- Paper: [k-Means Requires Exponentially Many Iterations Even in the Plane](http://cseweb.ucsd.edu/~avattani/papers/kmeans.pdf) by Andrea Vattani 
- Book: [Understanding Machine Learning: From Theory to Algorithms](https://www.amazon.com/Understanding-Machine-Learning-Theory-Algorithms/dp/1107057132) by Shai Shalev-Shwartz and Shai Ben-David 
### <a name="L9"></a>Hierarchical Clustering 


1402/07
**EXAM**{: .label .label-purple }

## 1402/08
### <a name="L8"></a>Hierarchical Clustering
- Chapter 14 of [Data Mining & Analysis](https://dataminingbook.info/)  
- **HW**{: .label .label-red } 14.4: Q4 
- Slides (Hierarchical Clustering): [PDF](https://www.cs.rpi.edu/~zaki/DMML/slides/pdf/ychap14.pdf)
- Slide: [Hierarchical Clustering](http://statweb.stanford.edu/~jtaylo/courses/stats202/restricted/notes/hierarchical.pdf) by Jonathan Taylor 
- Slide: [Data Structures (Heap)](http://www.cs.nthu.edu.tw/~wkhon/ds/ds11/lecture/lecture4.pdf) by Wing-Kai Hon 
    
**Further Reading**{: .label .label-yellow }
    
- Slide: [Hierarchical Clustering for Gene Expression Data Analysis](http://homes.di.unimi.it/valenti/SlideCorsi/MB0910/HierarchicalClustering.pdf) by Giorgio Valentini 
- Slide: [Hierarchical Clustering](https://cse.buffalo.edu/~jing/cse601/fa12/materials/clustering_hierarchical.pdf) by Jing Gao 
- Slide: [Binary Heaps](https://courses.cs.washington.edu/courses/cse373/06sp/handouts/lecture10.pdf) 
- A Short Note: [Proof for the Complexity of Building a Heap](http://www.cse.msu.edu/~huding/331material/timecomplexity_for_heap.pdf) by Hu Ding 
- Lecture: [Finding Meaningful Clusters in Data](https://cseweb.ucsd.edu/~dasgupta/291-unsup/lec5.pdf) by Sanjoy Dasgupta 
- Paper: [An Impossibility Theorem for Clustering](https://www.cs.cornell.edu/home/kleinber/nips15.pdf) by Jon Kleinberg 

## 1402 Fall
### <a name="L12"></a>Clustering Validation
- Chapter 17 of [Data Mining & Analysis](https://dataminingbook.info/)  
- Slides of Section 17.1 (Clustering Validation): [PDF](https://www.cs.rpi.edu/~zaki/DMML/slides/pdf/ychap17.pdf)
- Slide: [Clustering Analysis](http://www.mind.disco.unimib.it/public/opere/143.pdf) by Enza Messina 
- Slide: [Information Theory](http://www2.eng.cam.ac.uk/~js851/3F1MM13/L1.pdf) by Jossy Sayir 
- Slide: [Normalized Mutual Information: Estimating Clustering Quality](https://course.ccs.neu.edu/cs6140sp15/7_locality_cluster/Assignment-6/NMI.pdf) by Bilal Ahmed  
    
**Further Reading**{: .label .label-yellow }
    
- Slide: [Clustering Evaluation (II)](http://eniac.cs.qc.cuny.edu/andrew/gcml/lecture23.pdf) by Andrew Rosenberg 
- Slide: [Evaluation (I)](http://eniac.cs.qc.cuny.edu/andrew/gcml/lecture22.pdf) by Andrew Rosenberg 

## 1402 Fall
### <a name="L10"></a>Density-Based Clustering
- Chapter 15 of [Data Mining & Analysis](https://dataminingbook.info/)  
- Slides of Section 15.1 (Density-based Clustering): [PDF](https://www.cs.rpi.edu/~zaki/DMML/slides/pdf/ychap15.pdf)
- Slide: [Spatial Database Systems](http://dna.fernuni-hagen.de/Tutorial-neu.pdf) by 
Ralf Hartmut Güting 

## 1402 Fall
### <a name="L11"></a>Kernel Method
    
- Chapter 5 of [Data Mining & Analysis](https://dataminingbook.info/)  
- Kernel-Kmeans Chapter 13 of [Data Mining & Analysis](https://dataminingbook.info/) 
- **HW**{: .label .label-red } TBA

## 1402/08/xx
**EXAM**{: .label .label-purple }

## 1402 Fall
### <a name="L11"></a>Spectral and Graph Clustering  
- Chapter 16 of [Data Mining & Analysis](https://dataminingbook.info/)  
    **Exercises** 16.5: Q2, Q3, Q6 
- Slides (Spectral and Graph Clustering): [PDF](https://www.cs.rpi.edu/~zaki/DMML/slides/pdf/ychap16.pdf) 
- Slide: [Spectral Clustering](http://eniac.cs.qc.cuny.edu/andrew/gcml/lecture21.pdf) by Andrew Rosenberg 
- Slide: [Introduction to Spectral Clustering](http://www.cvl.isy.liu.se:82/education/graduate/spectral-clustering/SC_course_part1.pdf) by Vasileios Zografos and Klas Nordberg 
    
**Further Reading**{: .label .label-yellow }
    
- Slide: [Spectral Methods](https://cse.buffalo.edu/~jing/cse601/fa12/materials/clustering_spectral.pdf) by Jing Gao 
- Tutorial: [A Tutorial on Spectral Clustering](https://arxiv.org/pdf/0711.0189.pdf) by Ulrike von Luxburg 
- Tutorial: [Matrix Differentiation](https://atmos.washington.edu/~dennis/MatrixCalculus.pdf) by 
Randal J. Barnes
- Lecture: [Spectral Methods](https://cseweb.ucsd.edu/~dasgupta/291-unsup/lec7.pdf) by Sanjoy Dasgupta 
- Paper: [Positive Semidefinite Matrices and Variational Characterizations of Eigenvalues
](http://www.ee.cuhk.edu.hk/~wkma/engg5781/new_notes/lecture%204-%20PSD-%20note.pdf) by Wing-Kin Ma  



## 1402 Winter
**EXAM**{: .label .label-purple }

## 1402 Winter
### <a name="L7"></a>Dimensionality Reduction
- Chapter 7 of [Data Mining & Analysis](https://dataminingbook.info/)  
- PCA
- LDA
- Kernel-PCA

## 1402 Winter
### <a name="L7"></a>Itemset Mining
- Chapter 8 of [Data Mining & Analysis](https://dataminingbook.info/)  

## 1402 Winter
### <a name="L6"></a>Link Analysis         
- Ranking Graph Vertices, [Page Rank](http://mct.iranjournals.ir/article_263_d3eae82ca520e66df01732cb07fd6841.pdf)

**Further Reading**{: .label .label-yellow }

- Chapter 5 of [Mining of Massive Datasets](http://www.mmds.org)  
- Slide of Sections 5.1, 5.2 (PageRank, Efficient Computation of PageRank): [Analysis of Large Graphs 1](http://www.mmds.org/mmds/v2.1/ch05-linkanalysis1.pdf)
- Slide of Sections 5.3-5.5 (Topic-Sensitive PageRank, Link Spam, Hubs and Authorities): [Analysis of Large Graphs 2](http://www.mmds.org/mmds/v2.1/ch05-linkanalysis1.pdf)
- Slide: [The Linear Algebra Aspects of PageRank](http://www4.ncsu.edu/~ipsen/ps/slides_dagstuhl07071.pdf) by Ilse Ipsen     
- Paper: [A Survey on Proximity Measures for Social Networks](https://link.springer.com/chapter/10.1007/978-3-642-34213-4_13) by Sara Cohen, Benny Kimelfeld, Georgia Koutrika 

### <a name="Additional-Slides"></a>Additional Slides:
* [Practical Data Science](http://www.datasciencecourse.org/lectures/) by Zico Kolter
* [Course: Data Mining](https://datalab.snu.ac.kr/~ukang/courses/18S-DM/) by U Kang
* [Statistical Data Mining Tutorials](http://www.cs.cmu.edu/~./awm/tutorials/index.html) by  Andrew W. Moore  
