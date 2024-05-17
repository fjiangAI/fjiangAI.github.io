---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education/PostDoc
======
* B.S. in Computer Science and Technology, Jiangsu University of Science and Technology, 2016
* M.S. in Computer Science and Technology, Soochow University, 2019
* Ph.D in Computer Science and Technology, Soochow University, 2022
* PostDoc in Computer Science and Technology, The Chinese University of Hong Kong, Shenzhen, 2024 (expected)

Work experience
======
* Summer 2018: Algorithm Engineer (Intern)
  * Microsoft 
  * Responsible for the research on the more natural conversation experience with dialogue act
  * As a key member in building a dialogue process description and control prototype system
  * The system contains four dimensions contexts based on Dialogue Interpretation Theory (DIT++), leveraging dialog act and beliefs to make the robot more natural, politer, more active, and longer memory
  * Supervisor: Yue Pan
  
Research Project
======
* Research on discourse structure analysis driven by micro and macro nuclearity (NSFC)
* Fifth participant 
* Responsible for the research on the Chinese macro discourse resources construction and discourse analysis methods
* As the main member in constructing a representation schema of Chinese macro discourse structure
* As one of the main leaders in the annotation of the Macro Chinese Discourse TreeBank (MCDTB)
* Proposed two discourse parsers based on global reverse reading and topic segmentation, according to the characteristics of Chinese macro discourse structure
* Proposed three neural models, which enhance the semantic representation of discourse units, indirectly and directly modeling discourse relations separately, to recognize implicit discourse relations

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Competition
======
* [NLPCC Share Task 2023](http://tcci.ccf.org.cn/conference/2023/cfpt.php) 
    * Chinese Grammatical Error Correction track (TOP 3, Second Prize)
    * The task  aims to automatically correct grammatical errors that violate language rules and convert the noisy input texts to cleaned output texts. This task focuses on correcting grammatical errors made by Chinese native speakers.
    * As the leader of the team (collaborate with 1 postgraduate student).
    * Proposed a human-machine hybrid data construction method and an error-invariant data enhancement method for the no-training dataset setup.
    * Based on our Phoenix model,  we trained GrammarGPT to achieve better performance than the SOTA model, only using data of 1/1200.
      
 * [CAIL 2022](http://cail.cipsc.org.cn/task_summit.html?raceID=4&cail_tag=2022) (Challenge of AI in Law)
    * Summarization track (TOP 1, First Prize)
    * The task aims to generate a summary of law-related public opinion news with an average length of 1600 words.
    * As the leader of the team (collaborate with 1 postgraduate student).
    * Proposed a two-stage (extracted-generating) judicial summary model, including a Hi-XLNET to extract the summary of long documents and a T5 model to polish the summary.
  
Teaching
======
  * Operating System (National Excellent Course, Online Course) (2019)
      * Teaching Assistant 
      * Tutored undergraduate students' assignments and answered their questions. 
   
  * Python Programming (Lab) (2017)
      * Teaching Assistant 
      * Assisted in solving the problems students met in the lab and tutored the students' assignments. 
  
Service and leadership
======
* As the Senior Area Chair (SAC) in ACL ARR 2024.
* As the Area Chair (AC) in NAACL 2024 and ACL 2024.
* As the Virtual Infrastructure Chair and Area Chair in EMNLP 2023.
* As a PC member in NeurIPS 2023/2024, ACL2019/2020/2023, AAAI2021/2022/2023/2024, EMNLP2020/2021, COLING2022. 
* As a member of the China Computer Federation (CCF). 
