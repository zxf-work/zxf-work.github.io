---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



Book Chapter
=======
* Efficient Join Query Processing on the Cloud.  
_Xiaofei Zhang_, Lei Chen. Cloud Computing and Digital Media, 191-234, 2014.

Journals 
=======
* Hu-Fu: Efficient and Secure Spatial Queries over Data Federation.  
Yongxin Tong, Xuchen Pan, Yuxiang Zeng, Yexuan Shi, Chunbo Xue, Zimu Zhou, _Xiaofei Zhang_, Lei Chen, Yi Xu, Ke Xu, Weifeng Lv. Proceedings of the VLDB Endowment Vol. 15 (6), pp. 1159-1172, 2022

* Correlation Constraint Shortest Path over Large Multi-Relation Graphs.  
_Xiaofei Zhang_, M. Tamer Özsu. Proceedings of the VLDB Endowment Vol. 12 (5), pp. 488-501, 2019

* Distance-Aware Selective Online Query Processing Over Large Distributed Graphs.  
_Xiaofei Zhang_, Lei Chen. Data Science and Engineering, Vol. 1, pp. 1-20, 2017

* Bonding Vertex Sets over Distributed Graphs: A Betweenness Aware Approach.  
_Xiaofei Zhang_, Hong Cheng, Lei Chen. Proceedings of the VLDB Endowment Vol. 8 (12), pp. 1418-1429, 2015

* Efficient Parallel Processing of Distance Join Queries Over Distributed Graphs.  
_Xiaofei Zhang_, Lei Chen, Min Wang. IEEE Trans. Knowl. Data Eng. Vol. 27 (3), pp. 740-754, 2015 

* Locality-aware Allocation of Multi-dimensional Correlated Files on the Cloud Platform.  
_Xiaofei Zhang_, Yongxin Tong, Lei Chen, Shicong Feng. Distributed and Parallel Databases Vol. 33 (3), pp. 353-380, 2014

* Efficient Multi-way Theta-join Processing using MapReduce.  
_Xiaofei Zhang_, Lei Chen, Min Wang. Proceedings of the VLDB Endowment Vol. 5 (11), pp. 1184-1195, 2012

Conferences
=======
* A Generic Graph Sparsification Framework using Deep Reinforcement Learning.
Ryan Wickman, _Xiaofei Zhang_, Weizi Li. IEEE International Conference on Data Mining (ICDM), 2022 (to appear)

* ELite: Cost-effective Approximation of Exploration-based Graph Analysis.  
_Xiaofei Zhang_, M. Tamer Özsu, Lei Chen. Proceedings of the 3rd Joint International Workshop on Graph Data Management Experiences & Systems (GRADES) and Network Data Analytics (NDA), 2020

* Tracking Frequent Items over Distributed Probabilistic Data.  
Yongxin Tong, _Xiaofei Zhang_, Lei Chen. World Wide Web, Vol. 19 (4), pp. 579-604, 2016

* Efficient Probabilistic Supergraph Search over Large Uncertain Graphs.  
Yongxin Tong, _Xiaofei Zhang_, Caleb C. Cao, Lei Chen. Proc. 23rd ACM Int. Conf. on Information and Knowledge Management, pp. 809-818, 2014 

* EAGRE: Towards Scalable I/O Efficient SPARQL Query Evaluation on the Cloud.  
_Xiaofei Zhang_, Lei Chen, Yongxin Tong, Min Wang. Proc. 29th Int. Conf. on Data Engineering, pp. 565-576, 2013

* Towards Efficient Join Processing over Large RDF Graph using MapReduce.  
_Xiaofei Zhang_, Lei Chen, Min Wang. Proc. 24th Int. Conf. on Scientific and Statistical  Database Management, pp. 250-259, 2012

* Fault Tolerance Study for Durable Storage on the Cloud.  
_Xiaofei Zhang_, Lei Chen. International Conference on Cloud and Service Computing, pp. 360-365, 2011