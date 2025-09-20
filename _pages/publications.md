---
permalink: /publications/
title: "Publications"
classes: "wide"
---
<script>
function toggleText(textIdToShow, textIdToHide) {
  var textToShow = document.getElementById(textIdToShow);
  var textToHide = document.getElementById(textIdToHide);
  
  // Toggle visibility of text to show
  if (textToShow.style.display === "none") {
    textToShow.style.display = "block";
  } else {
    textToShow.style.display = "none";
  }
  
  // Hide the other text
  textToHide.style.display = "none";
}
</script>

### 2025
- **Build Code Needs Maintenance Too: A Study on Refactoring and Technical Debt in Build Systems**
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Anwar Ghammam, Dhia Elhaq Rzig, Mohamed Almukhtar, Rania Khalsi, Foyzul Hassan, Marouane Kessentini <br>
	</font>
	    <i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://arxiv.org/pdf/2504.01907">Pre-print</a>
   </div>

### 2022

- **Serverless on machine learning: A systematic mapping study** <br>
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	A. Barrak, Fabio Petrillo, Fehmi Jaafar <br>
	<i class="fa-solid fa-location-dot"></i>  IEEE Access. <br>
	</font>
   <i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://ieeexplore.ieee.org/iel7/6287639/6514899/09888122.pdf">Pre-print</a>
	<br>
      <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2022-2', 'abstract-2022-2')">Citation</button>
      <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2022-2', 'citation-2022-2')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2022-2" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
@inproceedings{ghammam2025build,
<br>
  title={Build Code Needs Maintenance Too: A Study on Refactoring and Technical Debt in Build Systems},
  <br>
  author={Ghammam, Anwar and Rzig, Dhia Elhaq and Almukhtar, Mohamed and Khalsi, Rania and Hassan, Foyzul and Kessentini, Marouane},
  <br>
  booktitle={2025 IEEE/ACM 22nd International Conference on Mining Software Repositories (MSR)},
  <br>
  pages={616--628},
  <br>
  year={2025},
  <br>
  organization={IEEE}
  <br>
}
      </div>
      <div class="alert alert-success" role="alert" id="abstract-2022-2" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
In modern software engineering, build systems play the crucial role of facilitating the conversion of source code into software artifacts. Recent research has explored high-level causes of build failures, but has largely overlooked the structural properties of build files. Akin to source code, build systems face technical debt challenges that hinder maintenance and optimization. While refactoring is often seen as a key tool for addressing technical debt in source code, there is a significant research gap regarding the specific refactoring changes developers apply to build code and whether these refactorings effectively address technical debt.In this paper, we address this gap by examining refactorings applied to build scripts in open-source projects, covering the widely used build systems of Gradle, Ant, and Maven. Additionally, we investigate whether these refactorings are used to tackle technical debts in build systems. Our analysis was conducted on 725 examined build-file-related commits. We identified 24 build-related refactorings, which we divided into 6 main categories. These refactorings are organized into the first empirically derived taxonomy of build system refactorings. Furthermore, we investigate how developers employ these refactoring types to address technical debts via a manual commitanalysis and a developer survey. In this context, we identified 5 technical debts addressed by these refactorings and discussed their correlation with the different refactorings. Finally, we introduce BuildRefMiner, an LLM-powered tool leveraging GPT40 to automate the detection of refactorings within build systems. We evaluated its performance and found that it achieves an F1 score of 0.76 across all build systems.This study will serve as a foundational building block for guiding future research and practice in the maintenance and optimization of build systems. BuildRefMiner and the replication package for this study are available at [1]
      </div>
   </div>

### 2021


- **Why do builds fail?—A conceptual replication study** <br>
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Amine Barrak, Ellis E Eghan, Bram Adams, Foutse Khomh <br>
	<i class="fa-solid fa-location-dot"></i>  Journal of Systems and Software. <br>
	</font> 
	<i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://mcis.cs.queensu.ca/publications/2021/jss_amine.pdf">Pre-print</a>
	<br>
      <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2021-2', 'abstract-2021-2')">Citation</button>
      <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2021-2', 'citation-2021-2')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2021-2" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
@article{DBLP:journals/jss/BarrakEAK21,
<br>
author       = {Amine Barrak and
                  Ellis E. Eghan and
                  Bram Adams and
                  Foutse Khomh},
<br>
title        = {Why do builds fail? - {A} conceptual replication study},
<br> 
journal      = {J. Syst. Softw.},
<br>
volume       = {177},
<br>
pages        = {110939},
<br>
year         = {2021},
<br>
url          = {https://doi.org/10.1016/j.jss.2021.110939},
<br>
doi          = {10.1016/J.JSS.2021.110939},
<br>
timestamp    = {Sat, 09 Apr 2022 12:28:16 +0200},
<br>
biburl       = {https://dblp.org/rec/journals/jss/BarrakEAK21.bib},
<br>
bibsource    = {dblp computer science bibliography, https://dblp.org}
<br>
}
   </div>
      <div class="alert alert-success" role="alert" id="abstract-2021-2" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
Previous studies have investigated a wide range of factors potentially explaining software build breakages, focusing primarily on build-triggering code changes or previous CI outcomes. However, code quality factors such as the presence of code/test smells have not been yet evaluated in the context of CI, even though such factors have been linked to problems of comprehension and technical debt, and hence might introduce bugs and build breakages. This paper performs a conceptual replication study on 27,675 Travis CI builds of 15 GitHub projects, considering the features reported by Rausch et al. and Zolfagharinia et al., as well as those related to code/test smells. Using a multivariate model constructed from nine dimensions of features, results indicate a precision (recall) ranging between 58.3% and 79.0% (52.4% and 69.6%) in balanced project datasets, and between 2.5% and 37.5% (2.5% and 12.4%) in imbalanced project datasets. Models trained on our balanced project datasets were later used to perform cross-project prediction on the imbalanced projects, achieving an average improvement of 9.3% (16.2%) in precision (recall). Statistically, the results confirm that features from the build history, author, code complexity, and code/test smell dimensions are the most important predictors of build failures.
      </div>
   </div>

## Conferences
### 2024

- **Securing AWS Lambda: Advanced Strategies and Best Practices**
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	A. Barrak, G. FOFE, E. KOUAM, L. MACKOWIAK and Fehmi JAAFAR <br>
	<i class="fa-solid fa-location-dot"></i>  The 11th IEEE International Conference on Cyber Security and Cloud Computing (CSCLOUD 2024). <br>
	</font>
   </div>

## 2023
- **SPIRT: A Fault-Tolerant and Reliable Peer-to-Peer Serverless ML Training Architecture** <br>
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Amine Barrak, Mayssa Jaziri, Ranim Trabelsi, Fehmi Jaafar, Fabio Petrillo <br>
	<i class="fa-solid fa-location-dot"></i>  2023 IEEE 23rd International Conference on Software Quality, Reliability and Security (QRS). <br>
	</font> 
	<i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://arxiv.org/pdf/2309.14148">Pre-print</a>
	<br>
      <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2023-3', 'abstract-2023-3')">Citation</button>
      <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2023-3', 'citation-2023-3')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2023-3" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
@inproceedings{DBLP:conf/qrs/BarrakJTJP23,
<br>
author       = {Amine Barrak and
                  Mayssa Jaziri and
                  Ranim Trabelsi and
                  Fehmi Jaafar and
                  F{\'{a}}bio Petrillo},
<br>
title        = {\'{SPIRT:} \'{A} Fault-Tolerant and Reliable Peer-to-Peer Serverless \'{ML}
                  Training Architecture},
<br>
booktitle    = {23rd \'{IEEE} International Conference on Software Quality, Reliability,
                  and Security, \'{QRS} 2023, Chiang Mai, Thailand, October 22-26, 2023},
<br>
pages        = {650--661},
<br>
publisher    = {\'{IEEE}},
<br>
year         = {2023},
<br>
url          = {https://doi.org/10.1109/QRS60937.2023.00069},
<br>
doi          = {10.1109/QRS60937.2023.00069},
<br>
timestamp    = {Tue, 23 Jan 2024 09:45:31 +0100},
<br>
biburl       = {https://dblp.org/rec/conf/qrs/BarrakJTJP23.bib},
<br>
bibsource    = {dblp computer science bibliography, https://dblp.org}
<br>
}
      </div>
      <div class="alert alert-success" role="alert" id="abstract-2023-3" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
The advent of serverless computing has ushered in notable advancements in distributed machine learning, particularly within parameter server-based architectures. Yet, the integration of serverless features within peer-to-peer (P2P) distributed networks remains largely uncharted. In this paper, we introduce SPIRT, a fault-tolerant, reliable, scalable and secure serverless P2P ML training architecture. designed to bridge this existing gap. Capitalizing on the inherent robustness and reliability innate to P2P systems, we emphasized Intra-peer scalability for concurrent gradient to mitigate communication overhead from increased peer interactions. SPIRT, employs RedisAI for in-database operations, achieves an 82% reduction in model update times. This architecture showcases resilience against peer failures and adeptly manages the integration of new peers. Furthermore, SPIRT ensures secure communication between peers, enhancing the reliability of distributed machine learning tasks. Even in the face of Byzantine attacks, the system’s robust aggregation algorithms maintain high levels of accuracy. These findings illuminate the promising potential of serverless architectures in P2P distributed machine learning, offering a significant stride towards the development of more efficient, scalable, and resilient applications.
      </div>
   </div>

- **Exploring the Impact of Serverless Computing on Peer To Peer Training Machine Learning** <br>
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Amine Barrak, Ranim Trabelsi, Fehmi Jaafar, Fabio Petrillo <br>
	<i class="fa-solid fa-location-dot"></i>  IC2E 2023 11th IEEE International Conference on Cloud Engineering. <br>
	</font> 
	<i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://arxiv.org/pdf/2309.14139">Pre-print</a>
	<br>
      <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2023-2', 'abstract-2023-2')">Citation</button>
      <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2023-2', 'citation-2023-2')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2023-2" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
@inproceedings{DBLP:conf/ic2e/BarrakTJP23,
<br>
author       = {Amine Barrak and
                  Ranim Trabelsi and
                  Fehmi Jaafar and
                  F{\'{a}}bio Petrillo},
<br>
title        = {Exploring the Impact of Serverless Computing on Peer To Peer Training
                  Machine Learning},
<br>
booktitle    = {\'{IEEE} International Conference on Cloud Engineering, {IC2E} 2023,
                  Boston, MA, USA, September 25-29, 2023},
<br>
pages        = {141--152},
<br>
publisher    = \'{IEEE},
<br>
year         = {2023},
<br>
url          = {https://doi.org/10.1109/IC2E59103.2023.00024},
<br>
doi          = {10.1109/IC2E59103.2023.00024},
<br>
timestamp    = {Tue, 21 Nov 2023 22:37:14 +0100},
<br>
biburl       = {https://dblp.org/rec/conf/ic2e/BarrakTJP23.bib},
<br>
bibsource    = {dblp computer science bibliography, https://dblp.org}
<br>
}
   </div>
      <div class="alert alert-success" role="alert" id="abstract-2023-2" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
The increasing demand for computational power in big data and machine learning has driven the development of distributed training methodologies. Among these, peer-to-peer (P2P) networks provide advantages such as enhanced scalability and fault tolerance. However, they also encounter challenges related to resource consumption, costs, and communication overhead as the number of participating peers grows. In this paper, we introduce a novel architecture that combines serverless computing with P2P networks for distributed training and present a method for efficient parallel gradient computation under resource constraints.
Our findings show a significant enhancement in gradient computation time, with up to a 97.34\% improvement compared to conventional P2P distributed training methods. As for costs, our examination confirmed that the serverless architecture could incur higher expenses, reaching up to 5.4 times more than instance-based architectures. It is essential to consider that these higher costs are associated with marked improvements in computation time, particularly under resource-constrained scenarios. Despite the cost-time trade-off, the serverless approach still holds promise due to its pay-as-you-go model. Utilizing dynamic resource allocation, it enables faster training times and optimized resource utilization, making it a promising candidate for a wide range of machine learning applications.
      </div>
   </div>

- **Architecting Peer-to-Peer Serverless Distributed Machine Learning Training for Improved Fault Tolerance** <br>
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Amine Barrak, Fabio Petrillo, Fehmi Jaafar <br>
	<i class="fa-solid fa-location-dot"></i>  arXiv preprint arXiv:2302.13995. <br>
	</font>
   <i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://arxiv.org/pdf/2302.13995">Pre-print</a>
	<br>
     <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2023-1', 'abstract-2023-1')">Citation</button>
     <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2023-1', 'citation-2023-1')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2023-1" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
@article{DBLP:journals/corr/abs-2302-13995,
<br>
author       = {Amine Barrak and
                  F{\'{a}}bio Petrillo and
                  Fehmi Jaafar},
<br>
title        = {Architecting Peer-to-Peer Serverless Distributed Machine Learning
                  Training for Improved Fault Tolerance},
<br>
journal      = {CoRR},
<br>
volume       = {abs/2302.13995},
<br>
year         = {2023},
<br>
url          = {https://doi.org/10.48550/arXiv.2302.13995},
<br>
doi          = {10.48550/ARXIV.2302.13995},
<br>
eprinttype    = {arXiv},
<br>
eprint       = {2302.13995},
<br>
timestamp    = {Tue, 28 Feb 2023 14:02:05 +0100},
<br>
biburl       = {https://dblp.org/rec/journals/corr/abs-2302-13995.bib},
<br>
bibsource    = {dblp computer science bibliography, https://dblp.org}
<br>
}
      </div>
      <div class="alert alert-success" role="alert" id="abstract-2023-1" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
Distributed Machine Learning refers to the practice of training a model on multiple computers or devices that can be called nodes. Additionally, serverless computing is a new paradigm for cloud computing that uses functions as a computational unit. Serverless computing can be effective for distributed learning systems by enabling automated resource scaling, less manual intervention, and cost reduction. By distributing the workload, distributed machine learning can speed up the training process and allow more complex models to be trained. Several topologies of distributed machine learning have been established (centralized, parameter server, peer-to-peer). However, the parameter server architecture may have limitations in terms of fault tolerance, including a single point of failure and complex recovery processes. Moreover, training machine learning in a peer-to-peer (P2P) architecture can offer benefits in terms of fault tolerance by eliminating the single point of failure. In a P2P architecture, each node or worker can act as both a server and a client, which allows for more decentralized decision making and eliminates the need for a central coordinator. In this position paper, we propose exploring the use of serverless computing in distributed machine learning training and comparing the performance of P2P architecture with the parameter server architecture, focusing on cost reduction and fault tolerance.
      </div>
   </div>

## 2021

- **Identification of compromised IoT devices: Combined approach based on energy consumption and network traffic analysis** <br>
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Fehmi Jaafar, Darine Ameyed, Amine Barrak, Mohamed Cheriet <br>
	<i class="fa-solid fa-location-dot"></i>  2021 IEEE 21st International Conference on Software Quality, Reliability and Security (QRS). <br>
	</font> 
	<i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://ieeexplore.ieee.org/abstract/document/9724945">Pre-print</a>
   <br>
   <i class="fa-solid fa-display"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://onedrive.live.com/view?id=DE0A56702379341E!3033&resid=DE0A56702379341E!3033&authkey=!AIe4HdglUatZG10&wdSlideId=256&wdModeSwitchTime=1714927528422&wdo=2&cid=de0a56702379341e">Presentation</a>
	<br>
      <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2021-3', 'abstract-2021-3')">Citation</button>
      <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2021-3', 'citation-2021-3')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2021-3" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
@inproceedings{DBLP:conf/qrs/JaafarABC21,
<br>
author       = {Fehmi Jaafar and
                  Darine Ameyed and
                  Amine Barrak and
                  Mohamed Cheriet},
<br>
title        = {Identification of Compromised IoT Devices: Combined Approach Based
                  on Energy Consumption and Network Traffic Analysis},
<br>
booktitle    = {21st \'{IEEE} International Conference on Software Quality, Reliability
                  and Security, \'{QRS} 2021, Hainan, China, December 6-10, 2021},
<br>
pages        = {514--523},
<br>
publisher    = {\'{IEEE}},
<br>
year         = {2021},
<br>
url          = {https://doi.org/10.1109/QRS54544.2021.00062},
<br>
doi          = {10.1109/QRS54544.2021.00062},
<br>
timestamp    = {Wed, 16 Mar 2022 22:32:22 +0100},
<br>
biburl       = {https://dblp.org/rec/conf/qrs/JaafarABC21.bib},
<br>
bibsource    = {dblp computer science bibliography, https://dblp.org}
<br>
}

   </div>
      <div class="alert alert-success" role="alert" id="abstract-2021-3" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
In the burgeoning age of digitalization, the Internet of Things presents a core part of the digital ecosystem. Unfortunately, as the deployment of connected devices is increasing tremendously, so are cyber-attacks. The consequences of cyber-attacks could be devastating as they gain access to sensitive data and even damages critical infrastructures. This urges the development and integration of proactive and intelligent security breach detection mechanisms in different levels of the IoT platforms including the devices themselves. Several empirical observations indicated a change in the energy consumption and network behaviour of compromised devices. Thus, we propose in this paper a machine learning based approach to identify compromised IoT devices using their energy consumption footprint and network traffic. We base our study on real data collected from real experiments using different commercially available IoT devices infected with authentic IoT botnets. Our results show that machine learning algorithms can classify correctly attacks reaching 98.40% precision for Mirai, over 99.91% for Ufonet and respectively 97.63% and 99.93% performance. Overall, our exploratory study is one of the very first of its kind to explore the energy consumption combined with network behavior analysis to detect IoT compromised devices and its outcomes will be a starting point for further research on this topic.
      </div>
   </div>


- **On the Co-evolution of ML pipelines and source code-empirical study of DVC projects** <br>
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Amine Barrak, Ellis E Eghan, Bram Adams <br>
	<i class="fa-solid fa-location-dot"></i>  2021 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER). <br>
	</font> 
	<i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://mcis.cs.queensu.ca/publications/2021/saner.pdf">Pre-print</a>
   <br>
   <i class="fa-solid fa-display"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://onedrive.live.com/view?id=DE0A56702379341E!2991&resid=DE0A56702379341E!2991&authkey=!ANp5K_OunoTMgGM&wdSlideId=256&wdModeSwitchTime=1714927573622&wdo=2&cid=de0a56702379341e">Presentation</a>
   <br>
   <i class="fa-solid fa-video"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://www.youtube.com/watch?v=aiV_xk26p44">Video</a>
	<br>
      <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2021-1', 'abstract-2021-1')">Citation</button>
      <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2021-1', 'citation-2021-1')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2021-1" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
@inproceedings{DBLP:conf/wcre/BarrakEA21,
<br>
author       = {Amine Barrak and
                  Ellis E. Eghan and
                  Bram Adams},
<br>
title        = {On the Co-evolution of {ML} Pipelines and Source Code - Empirical
                  Study of {DVC} Projects},
<br>
booktitle    = {28th {IEEE} International Conference on Software Analysis, Evolution
                  and Reengineering, {SANER} 2021, Honolulu, HI, USA, March 9-12, 2021},
<br>
pages        = {422--433},
<br>
publisher    = {{IEEE}},
<br>
year         = {2021},
<br>
url          = {https://doi.org/10.1109/SANER50967.2021.00046},
<br>
doi          = {10.1109/SANER50967.2021.00046},
<br>
timestamp    = {Sat, 09 Apr 2022 12:37:46 +0200},
<br>
biburl       = {https://dblp.org/rec/conf/wcre/BarrakEA21.bib},
<br>
bibsource    = {dblp computer science bibliography, https://dblp.org}
<br>
}
      </div>
      <div class="alert alert-success" role="alert" id="abstract-2021-1" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
The growing popularity of machine learning (ML) applications has led to the introduction of software engineering tools such as Data Versioning Control (DVC), MLFlow and Pachyderm that enable versioning ML data, models, pipelines and model evaluation metrics. Since these versioned ML artifacts need to be synchronized not only with each other, but also with the source and test code of the software applications into which the models are integrated, prior findings on co-evolution and coupling between software artifacts might need to be revisited. Hence, in order to understand the degree of coupling between ML-related and other software artifacts, as well as the adoption of ML versioning features, this paper empirically studies the usage of DVC in 391 Github projects, 25 of which in detail. Our results show that more than half of the DVC files in a project are changed at least once every one-tenth of the project's lifetime. Furthermore, we observe a tight coupling between DVC files and other artifacts, with 1/4 pull requests changing source code and 1/2 pull requests changing tests requiring a change to DVC files. As additional evidence of the observed complexity associated with adopting ML-related software engineering tools like DVC, an average of 78% of the studied projects showed a non-constant trend in pipeline complexity.
      </div>
   </div>

## 2018

- **Just-in-time detection of protection-impacting changes on WordPress and MediaWiki** <br>
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Amine Barrak, Marc-André Laverdière, Foutse Khomh, Le An, Ettore Merlo <br>
	<i class="fa-solid fa-location-dot"></i>  Proceedings of the 28th Annual International Conference on Computer Science and Software Engineering. <br>
	</font> 
	<i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://publications.polymtl.ca/3684/1/2018_MohamedAmineBarrak.pdf">Pre-print</a>
   <a class="btn btn--info btn--small" target="_blank" href="https://amine-barrak.gitlab.io/personal/Thesis/Master_AmineBarrak_2018.pdf">Thesis</a>
   <br>
   <i class="fa-solid fa-display"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://onedrive.live.com/view?id=DE0A56702379341E!3014&resid=DE0A56702379341E!3014&authkey=!AOG395gPpfq2wCA&wdSlideId=583&wdModeSwitchTime=1714927637999&wdo=2&cid=de0a56702379341e">Presentation</a>
   <a class="btn btn--info btn--small" target="_blank" href="https://onedrive.live.com/view?id=DE0A56702379341E!3011&resid=DE0A56702379341E!3011&authkey=!ANSBKX7v-x5vL2w&wdSlideId=307&wdModeSwitchTime=1714927873128&wdo=2&cid=de0a56702379341e">Presentation</a>
   <br>
   <i class="fa-solid fa-newspaper"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://amine-barrak.gitlab.io/personal/Thesis/bulletin/Master_bulletin_AmineBarrak.pdf">Bulletin</a>
	<br>
      <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2018-2', 'abstract-2018-2')">Citation</button>
      <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2018-2', 'citation-2018-2')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2018-2" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
@inproceedings{DBLP:conf/cascon/BarrakLKAM08,
<br>
author       = {Amine Barrak and
                  Marc{-}Andr{\'{e}} Laverdi{\`{e}}re and
                  Foutse Khomh and
                  Le An and
                  Ettore Merlo},
<br>
editor       = {Iosif{-}Viorel Onut and
                  Andrew Jaramillo and
                  Guy{-}Vincent Jourdan and
                  Dorina C. Petriu and
                  Wang Chen},
<br>
title        = {Just-in-time detection of protection-impacting changes on WordPress
                  and MediaWiki},
<br>
booktitle    = {Proceedings of the 28th Annual International Conference on Computer
                  Science and Software Engineering, {CASCON} 2018, Markham, Ontario,
                  Canada, October 29-31, 2018},
<br>
pages        = {178--188},
<br>
publisher    = {{ACM}},
<br>
year         = {2018},
<br>
url          = {https://dl.acm.org/citation.cfm?id=3291310},
<br>
timestamp    = {Tue, 19 Feb 2019 07:16:26 +0100},
<br>
biburl       = {https://dblp.org/rec/conf/cascon/BarrakLKAM08.bib},
<br>
bibsource    = {dblp computer science bibliography, https://dblp.org}
<br>
}
   </div>
      <div class="alert alert-success" role="alert" id="abstract-2018-2" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
Access control mechanisms based on roles and privileges restrict the access of users to security sensitive resources in a multi-user software system. Unintentional privilege protection changes may occur during the evolution of a system, which may introduce security vulnerabilities; threatening user's confidential data, and causing other severe problems. In this paper, we use the Pattern Traversal Flow Analysis technique to identify definite protection differences in WordPress and MediaWiki systems. We analyse the evolution of privilege protections across 211 and 193 releases from respectively WordPress and Mediawiki, and observe that around 60% of commits affect privileges protections in both projects. We refer to these commits as protection-impacting change (PIC) commits. To help developers identify PIC commits just-in-time, we extract a series of metrics from commit logs and source code, and build statistical models. The evaluation of these models revealed that they can achieve a precision up to 73.8% and a recall up to 98.8% in WordPress and for MediaWiki, a precision up to 77.2% and recall up to 97.8%. Among the metrics examined, commit churn, bug fixing, author experiences and code complexity between two releases are the most important predictors in the models. We performed a qualitative analysis of false positives and false negatives and observe that PIC commits detectors should ignore documentation-only commits and process code changes without the comments.
Software organizations can use our proposed approach and models, to identify unintentional privilege protection changes as soon as they are introduced, in order to prevent the introduction of vulnerabilities in their systems.
      </div>
   </div>


- **The state of practice on virtual reality (VR) applications: An exploratory study on github and stack overflow** <br>
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Naoures Ghrairi, Segla Kpodjedo, Amine Barrak, Fabio Petrillo, Foutse Khomh <br>
	<i class="fa-solid fa-location-dot"></i>  2018 IEEE International Conference on Software Quality, Reliability and Security (QRS). <br>
	</font> 
	<i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://www.researchgate.net/profile/Mohamed-Barrak/publication/326861571_The_State_of_Practice_on_Virtual_Reality_VR_Applications_An_Exploratory_Study_on_Github_and_Stack_Overflow/links/5d001f1d4585157d15a42420/The-State-of-Practice-on-Virtual-Reality-VR-Applications-An-Exploratory-Study-on-Github-and-Stack-Overflow.pdf">Pre-print</a>
   <br>
   <i class="fa-solid fa-display"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://onedrive.live.com/view?id=DE0A56702379341E!3008&resid=DE0A56702379341E!3008&authkey=!AGk2P3CV1i4RADE&wdSlideId=256&wdModeSwitchTime=1714927709775&wdo=2&cid=de0a56702379341e">Presentation</a>
	<br>
      <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2018-1', 'abstract-2018-1')">Citation</button>
      <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2018-1', 'citation-2018-1')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2018-1" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
@inproceedings{DBLP:conf/qrs/GhrairiKBPK18,
<br>
author       = {Naoures Ghrairi and
                  Segla Kpodjedo and
                  Amine Barrak and
                  F{\'{a}}bio Petrillo and
                  Foutse Khomh},
<br>
title        = {The State of Practice on Virtual Reality {(VR)} Applications: An Exploratory
                  Study on Github and Stack Overflow},
<br>
booktitle    = {2018 {IEEE} International Conference on Software Quality, Reliability
                  and Security, {QRS} 2018, Lisbon, Portugal, July 16-20, 2018},
<br>
pages        = {356--366},
<br>
publisher    = {{IEEE}},
<br>
year         = {2018},
<br>
url          = {https://doi.org/10.1109/QRS.2018.00048},
<br>
doi          = {10.1109/QRS.2018.00048},
<br>
timestamp    = {Wed, 16 Oct 2019 14:14:57 +0200},
<br>
biburl       = {https://dblp.org/rec/conf/qrs/GhrairiKBPK18.bib},
<br>
bibsource    = {dblp computer science bibliography, https://dblp.org}
<br>
}
      </div>
      <div class="alert alert-success" role="alert" id="abstract-2018-1" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
Virtual Reality (VR) is a computer technology that holds the promise of revolutionizing the way we live. The release in 2016 of new-generation headsets from Facebook-owned Oculus and HTC has renewed the interest in that technology. Thousands of VR applications have been developed over the past years, but most software developers lack formal training on this technology. In this paper, we propose descriptive information on the state of practice of VR applications' development to understand the level of maturity of this new technology from the perspective of Software Engineering (SE). To do so, we focused on the analysis of 320 VR open source projects from Github to determine which are the most popular languages and engines used in VR projects, and evaluate the quality of the projects from a software metric perspective. To get further insights on VR development, we also manually analyzed nearly 300 questions from Stack Overflow. Our results show that (1) VR projects on GitHub are currently mostly small to medium projects, and (2) the most popular languages are JavaScript and C#. Unity is the most used game engine during VR development and the most discussed topic on Stack Overflow. Overall, our exploratory study is one of the very first of its kind for VR projects and provides material that is hopefully a starting point for further research on challenges and opportunities for VR software development.
      </div>
   </div>

## Posters and Short Papers
### 2024

- **Best Practices for Scalable and Efficient Distributed Machine Learning with Serverless Architectures**
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	A. Barrak <br>
	<i class="fa-solid fa-location-dot"></i>  The 38th IEEE International Parallel & Distributed Processing Symposium (IPDPS 2024). <br>
	</font>
	    <i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://aminebarrak.github.io/assets/pdfs/2024_ipdps_phd_forum_poster.pdf">Pre-print</a>
   </div>

- **Incorporating Serverless Computing into P2P Networks for ML Training: In-Database Tasks and Their Scalability Implications (Student Abstract)** <br>
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Amine Barrak <br>
	<i class="fa-solid fa-location-dot"></i>  The 38th Annual AAAI Conference on Artificial Intelligence. <br>
	</font>
	<i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://ojs.aaai.org/index.php/AAAI/article/view/30419/32488">Pre-print</a>
	<br>
      <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2024-2', 'abstract-2024-2')">Citation</button>
      <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2024-2', 'citation-2024-2')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2024-2" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
    @inproceedings{DBLP:conf/aaai/Barrak24a,
   <br>
   author       = {Amine Barrak},
   <br>
   editor       = {Michael J. Wooldridge and
                  Jennifer G. Dy and
                  Sriraam Natarajan},
   <br>
   title        = {Incorporating Serverless Computing into \'{P2P} Networks for \'{ML} Training:
                  In-Database Tasks and Their Scalability Implications (Student Abstract)},
   <br>
   booktitle    = {Thirty-Eighth \'{AAAI} Conference on Artificial Intelligence, \'{AAAI}
                  2024, Thirty-Sixth Conference on Innovative Applications of Artificial
                  Intelligence, \'{IAAI} 2024, Fourteenth Symposium on Educational Advances
                  in Artificial Intelligence, \'{EAAI} 2014, February 20-27, 2024, Vancouver,
                  Canada},
   <br>
   pages        = {23439--23440},
   <br>
   publisher    = {\'{AAAI} Press},
   <br>
   year         = {2024},
   <br>
   url          = {https://doi.org/10.1609/aaai.v38i21.30419},
   <br>
   doi          = {10.1609/AAAI.V38I21.30419},
   <br>
   timestamp    = {Tue, 02 Apr 2024 16:32:10 +0200},
   <br>
   biburl       = {https://dblp.org/rec/conf/aaai/Barrak24a.bib},
   <br>
   bibsource    = {dblp computer science bibliography, https://dblp.org}
   <br>
   }
      </div>
      <div class="alert alert-success" role="alert" id="abstract-2024-2" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
Distributed ML addresses challenges from increasing data and model complexities. Peer to peer (P2P) networks in distributed ML offer scalability and fault tolerance. However, they also encounter challenges related to resource consumption, and communication overhead as the number of participating peers grows. This research introduces a novel architecture that combines serverless computing with P2P networks for distributed training. Serverless computing enhances this model with parallel processing and cost effective scalability, suitable for resource-intensive tasks. Preliminary results show that peers can offload expensive computational tasks to serverless platforms. However, their inherent statelessness necessitates strong communication methods, suggesting a pivotal role for databases. To this end, we have enhanced an in memory database to support ML training tasks.
      </div>
   </div>

- **The Promise of Serverless Computing within Peer-to-Peer Architectures for Distributed ML Training** <br>
   <div> 
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Amine Barrak <br>
	<i class="fa-solid fa-location-dot"></i>  The 38th Annual AAAI Conference on Artificial Intelligence - DOCTORAL CONSORTIUM. <br>
	</font> 
	<i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://ojs.aaai.org/index.php/AAAI/article/view/30392/32459">Pre-print</a>
	<br>
      <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2024-1', 'abstract-2024-1')">Citation</button>
      <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2024-1', 'citation-2024-1')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2024-1" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
@inproceedings{DBLP:conf/aaai/Barrak24a,
<br>
author       = {Amine Barrak},
<br>
editor       = {Michael J. Wooldridge and
                  Jennifer G. Dy and
                  Sriraam Natarajan},
<br>
title        = {Incorporating Serverless Computing into \'{P2P} Networks for \'{ML} Training:
                  In-Database Tasks and Their Scalability Implications (Student Abstract)},
<br>
booktitle    = {Thirty-Eighth \'{AAAI} Conference on Artificial Intelligence, \'{AAAI}
                  2024, Thirty-Sixth Conference on Innovative Applications of Artificial
                  Intelligence, {IAAI} 2024, Fourteenth Symposium on Educational Advances
                  in Artificial Intelligence, \'{EAAI} 2014, February 20-27, 2024, Vancouver,
                  Canada},
<br>
pages        = {23439--23440},
<br>
publisher    = {\'{AAAI} Press},
<br>
year         = {2024},
<br>
url          = {https://doi.org/10.1609/aaai.v38i21.30419},
<br>
doi          = {10.1609/AAAI.V38I21.30419},
<br>
timestamp    = {Tue, 02 Apr 2024 16:32:10 +0200},
<br>
biburl       = {https://dblp.org/rec/conf/aaai/Barrak24a.bib},
<br>
bibsource    = {dblp computer science bibliography, https://dblp.org}
<br>
}</div>
      <div class="alert alert-success" role="alert" id="abstract-2024-1" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
My thesis focuses on the integration of serverless computing with Peer to Peer (P2P) architectures in distributed Machine Learning (ML). This research aims to harness the decentralized, resilient nature of P2P systems, combined with the scalability and automation of serverless platforms. We explore using databases not just for communication but also for indatabase model updates and gradient averaging, addressing the challenges of statelessness in serverless environments.
      </div>
   </div>

### 2022


- **On securing the communication in IoT infrastructure using elliptic curve cryptography** <br>
   <div>
	<font size="3"> 
	<i class="fa-solid fa-people-line"></i>
	Hugo Bourreau, Emeric Guichet, Amine Barrak, Benoît Simon, Fehmi Jaafar <br>
	<i class="fa-solid fa-location-dot"></i>  2022 IEEE 22nd International Conference on Software Quality, Reliability, and Security Companion (QRS-C). <br>
	</font> 
	<i class="fa-solid fa-book"></i>
   <a class="btn btn--info btn--small" target="_blank" href="https://qrs22.techconf.org/download/webpub2022/pdfs/QRS-C2022-6ZV0KHtj9FyqYCij5lnlun/199100a758/199100a758.pdf">Pre-print</a>
	<br>
      <i class="fa-solid fa-quote-left"></i>  <button class="btn btn--success btn--small" onclick="toggleText('citation-2022-3', 'abstract-2022-3')">Citation</button>
      <i class="fa-solid fa-paperclip"></i>  <button class="btn btn--success btn--small" onclick="toggleText('abstract-2022-3', 'citation-2022-3')">Abstract</button>
      <div class="alert alert-success" role="alert" id="citation-2022-3" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
@inproceedings{DBLP:conf/qrs/BourreauGBSJ22,
<br>
author       = {Hugo Bourreau and
                  Emeric Guichet and
                  Amine Barrak and
                  Beno{\^{\i}}t Simon and
                  Fehmi Jaafar},
<br>
title        = {On Securing the Communication in IoT Infrastructure using Elliptic
                  Curve Cryptography},
<br>
booktitle    = {22nd \'{IEEE} International Conference on Software Quality, Reliability,
                  and Security, \'{QRS} 2022 - Companion, Guangzhou, China, December 5-9,
                  2022},
<br>
pages        = {758--759},
<br>
publisher    = {\'{IEEE}},
<br>
year         = {2022},
<br>
url          = {https://doi.org/10.1109/QRS-C57518.2022.00121},
<br>
doi          = {10.1109/QRS-C57518.2022.00121},
<br>
timestamp    = {Sat, 22 Apr 2023 17:02:06 +0200},
<br>
biburl       = {https://dblp.org/rec/conf/qrs/BourreauGBSJ22.bib},
<br>
bibsource    = {dblp computer science bibliography, https://dblp.org}
<br>
}
   </div>
      <div class="alert alert-success" role="alert" id="abstract-2022-3" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
Internet of Things (IoT) is widely present nowadays, from businesses to connected houses, and more. IoT is considered a part of the Internet of the future and will comprise billions of intelligent communication. These devices transmit data from sensors to entities like servers to perform suitable responses. The problem of securing these data from cyberattacks increases due to the sensitive information it contains. In addition, studies have shown that most of the time data transiting in IoT devices does not apply encrypted communication. Thus, anyone has the ability to listen to or modify the information. Encrypting communications seems mandatory to secure networks and data transiting from sensors to servers. In this paper, we propose an approach to secure the transmission and the storage of data in IoT using Elliptic Curve Cryptography (ECC). The proposed method offers a high level of security at a reasonable computational cost. Indeed, we present an adequate architecture that ensures the use of a state-of-the-art cryptography algorithm to encrypt sensitive data in IoT.
      </div>
   </div>
