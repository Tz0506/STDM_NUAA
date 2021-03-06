## [1. Survey](#content)
1. **Deep Learning for Spatio-Temporal Data Mining:A Survey.** [paper](https://github.com/Tz0506/STDM_NUAA/tree/main/paper/STDM.pdf)

    *Senzhang Wang, Jiannong Cao, Philip S. Yu.* 

1. **Deep Learning for Spatio-Temporal Data Mining:A Survey.** [paper](https://arxiv.org/pdf/1906.04928.pdf)

    *Senzhang Wang, Jiannong Cao, Philip S. Yu.* 


1. **SeqST-GAN: Seq2Seq Generative Adversarial Nets for Multi-step Urban Crowd Flow Prediction.** [paper](https://dl.acm.org/doi/pdf/10.1145/3378889)

    *Senzhang Wang, Jiannong Cao, Hao Chen, Hao Peng, Zhiqiu Huang.* -->
    
1. **Analyzing Big Spatial and Big Spatiotemporal Data: A Case Study of Methods and Applications.** Big Data Analytics. 33(239). 2015. [book](https://www.sciencedirect.com/science/article/pii/B9780444634924000101)

    *Varun Chandola, Ranga Raju Vatsavai, Devashish Kumar, Auroop Ganguly.* 

1. **Spatiotemporal data mining in the era of big spatial data: algorithms and applications.** In SIGSPATIAL international workshop on analytics for big geospatial data, 2012. [paper](https://dl.acm.org/doi/pdf/10.1145/2447481.2447482)

    *R. R. Vatsavai, V. Chandola, S. Klasky, A. Ganguly, A. Stefanidis, S. Shekhar.*

1. **Spatiotemporal Pattern Mining: Algorithms
and Applications.** Frequent Pattern Mining. [paper](https://faculty.ist.psu.edu/jessieli/Publications/bk14-zli-freq-pattern.pdf)

    *Z. Li.*

1. **Spatiotemporal data mining.** Handbookd of Regional Science, pages 1173-1193, 2014. [book](https://www.researchgate.net/publication/283435990_Spatiotemporal_Data_Mining_A_Computational_Perspective)

    *Shashi Shekhar, Zhe Jiang, Reem Y. Ali, Emre Eftelioglu.*

1. **Spatiotemporal Data Mining: A Computational Perspective.** ISPRS International Journal of Geo-Information, 4:2306-2338, 2015. [paper](https://www.mdpi.com/2220-9964/4/4/2306/htm)

    *S. Shekhar, Z. Jiang, R. Y. Ali, E. Eftelioglu, X. Tang, V. M. V. Gunturi, X. Zhou.*

1. **Trajectory data mining: A review of methods and applications.** Journal of Spatial Information Science, (13):61-99, 2016. [journal](https://www.researchgate.net/publication/311844493_Trajectory_data_mining_A_review_of_methods_and_applications)

    *J. D. Mazimpaka, S. Timpf.*

1. **Spatio-temporal clustering: a survey.** Data Mining and Knowledge Discovery Handbook, Springer, 2015. [book](https://www.semanticscholar.org/paper/Spatio-Temporal-Clustering-%3A-a-Survey-Clustering-%3A-Kisilevich-Mansmann/7ec5ecb29eef3ec64877f70ca9c7c59a444526ea?p2df)

    *S. Kisilevich, F. Mansmann, M. Nanni, S. Rinzivillo.*

1. **Spatio-temporal data mining: A survey of problems and methods.** ACM Computing Surveys(CSUR), 51(4):83, 2018. [paper](https://arxiv.org/pdf/1711.04710.pdf)

    *G. Atluri, A. Karpatne, V. Kumar.*
    
1. **Deep learning
methods in transportation domain: a review.** IET Intelligent Transport Systems, 12(9):998-1004, 2018. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8490353)

    *H. Nguyen, L.-M. Kieu, T. Wen, C. Cai.*

1. **Enhancing transportation systems via deep learning: A survey.** Transportation Reserach Part C: Emerging Technologies, 2018. [paper](https://www.researchgate.net/publication/329835108_Enhancing_transportation_systems_via_deep_learning_A_survey)

    *Y. Wang, D. Zhang, Y. Liu, B. Dai, L. H. Lee.*
    
## [2. Spatio-Temporal Data](#content)   
### [2.1 Event Data](#content)
*  Event data comprise of discrete events occur- ring at point locations and times (e.g., crime events in the city and traffic accident events in a transportation network). An event can generally be characterized by a point location and time, which denotes where and when the event occurred, respectively. For example, a crime event can be characterized as such a tuple (ei,li,ti), where ei is the crime type, li is the location where the crime occurs and ti is the time when it occurs.  


*  Fig. (a) shows an illustration of the event data. It shows three types of events denoted by different shapes of the symbol. ST event data are common in real- world applications such as criminology (incidence of crime and related events), epidemiology (disease outbreak events), transportation (car accident), and social network (social event and trending topics).

<div align=center>
<img src="https://github.com/Tz0506/STDM_NUAA/blob/main/image/2.png" div align="center"  width="200"  alt="   "/><br/>
</div>


### [2.2 Trajectory Data](#content)
*  Trajectories denote the paths traced by bodies moving in space over time. (e.g., the moving route of a bike trip or taxi trip). Trajectory data are usually collected by the sensors deployed on the moving objects that can periodically transmit the location of the object over time, such as GPS on a taxi.
*  Fig. (b) shows an illustration of two trajectories. 

<div align=center>
<img src="https://github.com/Tz0506/STDM_NUAA/blob/main/image/b.png" div align="center"  width="200"  alt=" "/><br/>
</div>



### [2.3 Point Reference Data](#content)
*  Point reference data consist of measurements of a continuous ST field such as tempera- ture, vegetation, or population over a set of moving refer- ence points in space and time.
*  Fig. 3 shows an example of the point reference data (e.g. sea surface temperature) in a continuous ST field at two time stamps. They are measured by the sensors at reference locations (shown as while circles) on the two time stamps. Note that the locations of the temperature sensors change over time.

<div align=center>
<img src="https://github.com/Tz0506/STDM_NUAA/blob/main/image/3.png" div align="center"  width="300"  alt=" "/><br/>
</div>





### [2.4 Raster Data](#content)
*  Raster data are the measurements of a contin- uous or discrete ST field that are recorded at fixed locations in space and at fixed time points. The major difference between point reference data and raster data is that the locations of the point reference data keep changing while the locations of the raster data are fixed. The locations and times for measuring the ST field can be regularly or irregularly distributed. 
*  Fig. 4 shows an example of the traffic flow raster data of a transportation network. Each road is deployed a traffic sensor to collect real time traffic flow data. The traffic flow data of all the road sensors in a whole day (24 hours) form a raster data.

<div align=center>
<img src="https://github.com/Tz0506/STDM_NUAA/blob/main/image/4.png" div align="center"  width="300"  alt=" "/><br/>
</div>



### [2.5 Video Data](#content)
*   A video that consists of a sequence of images can be also considered as a type of ST data. In the spatial domain, the neighbor pixels usually have similar RGB values and thus present high spatial correlations. In the temporal domain, the images of consecutive frames usually change smoothly and  present high temporal dependency. 
*   A video can be generally represented as a three dimensional tensor with one dimension representing time t and the other two representing an image. Actually, video data can be also considered as a special raster data if we assume that there is a “sensor” deployed at each pixel and at each frame the “sensors” will collect the RGB values. Deep learning based video data analysis is extremely hot and a large number of papers are published in recent years. Although we categorize videos as a type of ST data, we focus on reviewing related works from the perspective of data mining and video data analysis falls into the research areas of computer vision and pattern recognition. Thus in this survey we do not cover the ST data type of videos.


## [3. Models](#content)
### [3.1 CNN](#content)
### [3.3 RNN/LSTM](#content)
### [3.4 ConvLSTM](#content)
### [3.5 AE/SAE](#content)
### [3.6 RBM/DBN](#content)
### [3.8 Hybrid](#content)
### [3.9 Others](#content)




## [4. Applications](#content)
### [4.1 Transportation](#content)
### [4.2 On-Demand Service](#content)
### [4.3 Climate & Weather](#content)
### [4.4 Human Mobility](#content)
### [4.5 Location-Based Social Networks(LBSNs)](#content)
