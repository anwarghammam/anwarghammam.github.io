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


- **Build Code Needs Maintenance Too: A Study on Refactoring and Technical Debt in Build Systems**
  <div style="margin-top:5px;">

    <span style="font-size:14px;">
      <i class="fa-solid fa-people-line"></i>
      Anwar Ghammam, Dhia Elhaq Rzig, Mohamed Almukhtar, Rania Khalsi, Foyzul Hassan, Marouane Kessentini
      <br>
      <i class="fa-solid fa-location-dot"></i> Mining Software Engineering (MSR 2025)
    </span>

    <div style="margin-top:8px; display:flex; gap:8px; align-items:center; flex-wrap:wrap;">
      <i class="fa-solid fa-book"></i>
      <a class="btn btn--info btn--small" target="_blank" href="https://arxiv.org/pdf/2504.01907">Pre-print</a>

      <i class="fa-solid fa-quote-left"></i>
      <button class="btn btn--success btn--small" onclick="toggleText('citation-2025', 'abstract-2025')">Citation</button>

      <i class="fa-solid fa-paperclip"></i>
      <button class="btn btn--success btn--small" onclick="toggleText('abstract-2025', 'citation-2025')">Abstract</button>
    </div>
  </div>

  <div class="alert alert-success" role="alert" id="citation-2025" style="padding: 15px; background-color: #e0e0e0; color: #333; border: 1px solid #ccc; border-radius: 5px; margin: 15px 0; font-size: 16px; max-width: 700px; display: none;">
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

<div class="alert alert-success" role="alert" id="abstract-2025" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
In modern software engineering, build systems play the crucial role of facilitating the conversion of source code into software artifacts. Recent research has explored high-level causes of build failures, but has largely overlooked the structural properties of build files. Akin to source code, build systems face technical debt challenges that hinder maintenance and optimization. While refactoring is often seen as a key tool for addressing technical debt in source code, there is a significant research gap regarding the specific refactoring changes developers apply to build code and whether these refactorings effectively address technical debt.In this paper, we address this gap by examining refactorings applied to build scripts in open-source projects, covering the widely used build systems of Gradle, Ant, and Maven. Additionally, we investigate whether these refactorings are used to tackle technical debts in build systems. Our analysis was conducted on 725 examined build-file-related commits. We identified 24 build-related refactorings, which we divided into 6 main categories. These refactorings are organized into the first empirically derived taxonomy of build system refactorings. Furthermore, we investigate how developers employ these refactoring types to address technical debts via a manual commitanalysis and a developer survey. In this context, we identified 5 technical debts addressed by these refactorings and discussed their correlation with the different refactorings. Finally, we introduce BuildRefMiner, an LLM-powered tool leveraging GPT40 to automate the detection of refactorings within build systems. We evaluated its performance and found that it achieves an F1 score of 0.76 across all build systems.This study will serve as a foundational building block for guiding future research and practice in the maintenance and optimization of build systems. BuildRefMiner and the replication package for this study are available at [1]
</div>



- **Efficient management of containers for software defined vehicles**
  <div style="margin-top:5px;">

    <span style="font-size:14px;">
      <i class="fa-solid fa-people-line"></i>
      Anwar Ghammam, Rania Khalsi, Marouane Kessentini, Foyzul Hassan
      <br>
      <i class="fa-solid fa-location-dot"></i> ACM Transactions on Software Engineering and Methodology (TOESM)
    </span>

    <div style="margin-top:8px; display:flex; gap:8px; align-items:center; flex-wrap:wrap;">
      <i class="fa-solid fa-book"></i>
      <a class="btn btn--info btn--small" target="_blank" href="https://deepblue.lib.umich.edu/bitstream/handle/2027.42/198681/3672461.pdf?sequence=1">Pre-print</a>

      <i class="fa-solid fa-quote-left"></i>
      <button class="btn btn--success btn--small" onclick="toggleText('citation-2025', 'abstract-2025')">Citation</button>

      <i class="fa-solid fa-paperclip"></i>
      <button class="btn btn--success btn--small" onclick="toggleText('abstract-2025', 'citation-2025')">Abstract</button>
    </div>
  </div>

  <div class="alert alert-success" role="alert" id="citation-2025" style="padding: 15px; background-color: #e0e0e0; color: #333; border: 1px solid #ccc; border-radius: 5px; margin: 15px 0; font-size: 16px; max-width: 700px; display: none;">
@article{ghammam2024efficient,
<br>
  title={Efficient management of containers for software defined vehicles},
  <br>
  author={Ghammam, Anwar and Khalsi, Rania and Kessentini, Marouane and Hassan, Foyzul},
  <br>
  journal={ACM Transactions on Software Engineering and Methodology},
  <br>
  volume={33},
  <br>
  number={8},
  <br>
  pages={1--36},
  <br>
  year={2024},
  <br>
  publisher={ACM New York, NY}
  <br>
}
  </div>

<div class="alert alert-success" role="alert" id="abstract-2025" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
Containerization technology, such as Docker, is gaining in popularity in newly established software-defined
vehicle architectures (SDVA). However, executing those containers can quickly become computationally
expensive in constrained environments, given the limited CPU, memory, and energy resources in the Electric
Control Units (ECU) of SDVA. Consequently, the efficient management of these containers is crucial for
enabling the on-demand usage of the applications in the vehicle based on the available resources while
considering several constraints and priorities, including failure tolerance, security, safety, and comfort. In this article, we propose a dynamic software container management approach for constrained environments such
as embedded devices/ECUs in SDVA within smart cars. To address the conflicting objectives and constraints
within the vehicle, we design a novel search-based approach based on multi-objective optimization. This
approach facilitates the allocation, movement, or suspension of containers between ECUs in the cluster.
Collaborating with our industry partner, Ford Motor Company, we evaluate our approach using different
real-world software-defined scenarios. These scenarios involve using heterogeneous clusters of ECU devices
in vehicles based on real-world software containers and use-case studies from the automotive industry. The
experimental results demonstrate that our scheduler outperforms existing scheduling algorithms, including
the default Docker scheduler -Spread- commonly used in automotive applications. Our proposed scheduler
exhibits superior performance in terms of energy and resource cost efficiency. Specifically, it achieves a
35% reduction in energy consumption in power-saving mode compared to the scheduler employed by Ford
Motor Company. Additionally, our scheduler effectively distributes workload among the ECUs in the cluster,
minimizing resource usage, and dynamically adjusts to the real-time requirements and constraints of the car
environment. This work will serve as a fundamental building block in the automotive industry to efficiently
manage software containers in smart vehicles, considering constraints and priorities in the real world.
</div>


- **Mind the gap: The disconnect between refactoring criteria used in industry and refactoring recommendation tools**
  <div style="margin-top:5px;">

    <span style="font-size:14px;">
      <i class="fa-solid fa-people-line"></i>
      James Ivers, Anwar Ghammam, Khouloud Gaaloul, Ipek Ozkaya, Marouane Kessentini, Wajdi Aljedaani
      <br>
      <i class="fa-solid fa-location-dot"></i> 2024 IEEE International Conference on Software Maintenance and Evolution (ICSME)
    </span>

    <div style="margin-top:8px; display:flex; gap:8px; align-items:center; flex-wrap:wrap;">
      <i class="fa-solid fa-book"></i>
      <a class="btn btn--info btn--small" target="_blank" href="https://ieeexplore.ieee.org/abstract/document/10795000">Pre-print</a>

      <i class="fa-solid fa-quote-left"></i>
      <button class="btn btn--success btn--small" onclick="toggleText('citation-2025', 'abstract-2025')">Citation</button>

      <i class="fa-solid fa-paperclip"></i>
      <button class="btn btn--success btn--small" onclick="toggleText('abstract-2025', 'citation-2025')">Abstract</button>
    </div>
  </div>

  <div class="alert alert-success" role="alert" id="citation-2025" style="padding: 15px; background-color: #e0e0e0; color: #333; border: 1px solid #ccc; border-radius: 5px; margin: 15px 0; font-size: 16px; max-width: 700px; display: none;">
@inproceedings{ivers2024mind,
<br>
  title={Mind the gap: The disconnect between refactoring criteria used in industry and refactoring recommendation tools},
  <br>
  author={Ivers, James and Ghammam, Anwar and Gaaloul, Khouloud and Ozkaya, Ipek and Kessentini, Marouane and Aljedaani, Wajdi},
  <br>
  booktitle={2024 IEEE International Conference on Software Maintenance and Evolution (ICSME)},
  <br>
  pages={138--150},
  <br>
  year={2024},
  <br>
  organization={IEEE}

  <br>
}
  </div>

<div class="alert alert-success" role="alert" id="abstract-2025" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
Refactoring is a widely adopted practice that keeps code healthy and provides well known benefits like improving developer productivity. Developers routinely make decisions about how to refactor code (which specific refactoring changes to make), but the criteria that guide these decisions is not well studied. We conducted a multi-method study to understand the diversity of criteria that developers use in deciding what refactoring changes to make, the relative importance of different criteria, and the extent to which refactoring recommendation tools incorporate these criteria in their recommendation approaches. Our findings demonstrate that developers in industry situationally employ more than a dozen criteria when making refactoring decisions. However, no recommendation tool supports even half of those criteria and most criteria are supported by only a few tools. While research in refactoring recommendations tools is ripe, lack of support for criteria developers care about leaves industry without the kind of recommendation tools that they need. In this paper, we summarize findings from industry interviews, an industry survey, and an analysis of refactoring recommendation tools. We highlight gaps in refactoring recommendation tools that researchers and tool vendors should consider focusing on for successful practical application of refactoring recommendation tools at scale.
</div>



- **From boring to boarding: Transforming refactoring education with game-based learning**
  <div style="margin-top:5px;">

    <span style="font-size:14px;">
      <i class="fa-solid fa-people-line"></i>
      Wajdi Aljedaani, Anwar Ghammam, Mohamed Wiem Mkaouer, Marouane Kessentini
      <br>
      <i class="fa-solid fa-location-dot"></i> Proceedings of the ACM/IEEE 8th International Workshop on Games and Software Engineering, ISCE 2024

    <div style="margin-top:8px; display:flex; gap:8px; align-items:center; flex-wrap:wrap;">
      <i class="fa-solid fa-book"></i>
      <a class="btn btn--info btn--small" target="_blank" href="https://wajdialjedaani.com/publication/papers/paper44.pdf">Pre-print</a>

      <i class="fa-solid fa-quote-left"></i>
      <button class="btn btn--success btn--small" onclick="toggleText('citation-2025', 'abstract-2025')">Citation</button>

      <i class="fa-solid fa-paperclip"></i>
      <button class="btn btn--success btn--small" onclick="toggleText('abstract-2025', 'citation-2025')">Abstract</button>
    </div>
  </div>

  <div class="alert alert-success" role="alert" id="citation-2025" style="padding: 15px; background-color: #e0e0e0; color: #333; border: 1px solid #ccc; border-radius: 5px; margin: 15px 0; font-size: 16px; max-width: 700px; display: none;">
@inproceedings{aljedaani2024boring,
<br>
  title={From boring to boarding: Transforming refactoring education with game-based learning},
  <br>
  author={Aljedaani, Wajdi and Ghammam, Anwar and Mkaouer, Mohamed Wiem and Kessentini, Marouane},
  <br>
  booktitle={Proceedings of the ACM/IEEE 8th International Workshop on Games and Software Engineering},
  <br>
  pages={20--27},
  <br>
  year={2024}

  <br>
}
  </div>

<div class="alert alert-success" role="alert" id="abstract-2025" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
Software Refactoring, a critical skill in software development, involves reorganizing code without altering its functionality. Despite its importance, many developers find refactoring complex and risky, often hesitating to adopt tools designed to assist in this process. To bridge this gap in this paper, we investigate the impact of gamification on the refactoring process and the usability of existing
refactoring tools. Our research introduces RefGame, an innovative game-based tool that aims to enhance the learning experience in identifying and applying refactoring techniques. We used RefGame in an exploratory study that involved 322 computer science students. Then, we collected the feedback provided by these students
via a survey. Our findings provide insight into the potential of gamification to make software refactoring education more accessible and effective, addressing the current challenges in teaching and learning refactoring techniques.
</div>


- **Dynamic software containers workload balancing via many-objective search**
  <div style="margin-top:5px;">

    <span style="font-size:14px;">
      <i class="fa-solid fa-people-line"></i>
      Anwar Ghammam, Thiago Ferreira, Wajdi Aljedaani, Marouane Kessentini, Ali Husain
      <br>
      <i class="fa-solid fa-location-dot"></i> IEEE Transactions on Services Computing (TSC)
    </span>

    <div style="margin-top:8px; display:flex; gap:8px; align-items:center; flex-wrap:wrap;">
      <i class="fa-solid fa-book"></i>
      <a class="btn btn--info btn--small" target="_blank" href="https://par.nsf.gov/servlets/purl/10450311#page=1.00&gsr=0">Pre-print</a>

      <i class="fa-solid fa-quote-left"></i>
      <button class="btn btn--success btn--small" onclick="toggleText('citation-2025', 'abstract-2025')">Citation</button>

      <i class="fa-solid fa-paperclip"></i>
      <button class="btn btn--success btn--small" onclick="toggleText('abstract-2025', 'citation-2025')">Abstract</button>
    </div>
  </div>

  <div class="alert alert-success" role="alert" id="citation-2025" style="padding: 15px; background-color: #e0e0e0; color: #333; border: 1px solid #ccc; border-radius: 5px; margin: 15px 0; font-size: 16px; max-width: 700px; display: none;">
@article{ghammam2023dynamic,
<br>
  title={Dynamic software containers workload balancing via many-objective search},
  <br>
  author={Ghammam, Anwar and Ferreira, Thiago and Aljedaani, Wajdi and Kessentini, Marouane and Husain, Ali},
  <br>
  journal={IEEE Transactions on Services Computing},
  <br>
  volume={16},
  <br>
  number={4},
  <br>
  pages={2575--2591},
  <br>
  year={2023},
  <br>
  publisher={IEEE}

  <br>
}
  </div>

<div class="alert alert-success" role="alert" id="abstract-2025" style="padding: 15px !important; background-color: #e0e0e0 !important; color: #333 !important; border: 1px solid #ccc !important; border-radius: 5px !important; margin-bottom: 15px !important; font-size: 16px !important; width: 700px !important; display: none;">
Software containers are becoming the new state of the art in the industry as they are extensively used to deploy systems. Indeed, the use of containers enables better modularity, reusability, and portability compared to other technologies. As the complexity of software systems is dramatically increasing, it is critical to enable optimal usage of the needed resources to execute them such as memory and CPU. Thus, different scheduling strategies are proposed to select the most suitable nodes to execute a set of containers. For instance, the default strategy in the Docker Swarm kit scheduling framework is based on an equal distribution of the containers between nodes independent of their sizes and consumed resources. However, balancing the containers’ workload is a complex problem due to the conflicting objectives of minimizing the number of selected nodes, minimizing the number of containers per node, the number of changes compared to the original schedule, and the coupling between containers allocated to different nodes. To deal with those conflicting scheduling objectives, we propose a scheduler based on a many-objective optimization approach for scheduling the execution of containers between multiple nodes. The proposed approach aims at finding the best allocation for containers in nodes that leads to efficient utilization of resources. To evaluate our approach, we compared the performance of multiple many and multi-objective techniques based on NSGA-II, NSGA-III, and IBEA algorithms using 48 Docker-related systems and the results show that NSGA-III outperforms the other algorithms in quality attributes as well as in CPU, Memory and Network usage.
</div>
