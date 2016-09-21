---
layout: post
title: "ML-India interview series - Dr. Mayank Vatsa, Professor, Indraprastha Institute of Information Technology-Delhi (IIIT-H), India"
excerpt: "Dr. Mayank Vatsa is an associate professor at Indraprastha Institute of Information Technology, Delhi (IIIT-D), India. He received the M.S. and Ph.D. degrees in computer science from West Virginia University, Morgantown, WV, USA, in 2005 and 2008, respectively. He has authored more than 150 publications in refereed journals, book chapters, and conferences. His research has been funded by the Unique Identification Authority of India and DIT. He was a recipient of the FAST Award Project by DST, India. His areas of interest are biometrics, image processing, machine learning, and information fusion.
"
tags: [india, machine learning, data science, interview, mayank, IIIT-D, indraprashtha institute of information technology delhi]
comments: true

tags_relevant: [interview]
---

<img src="https://media.licdn.com/mpr/mpr/shrinknp_200_200/AAEAAQAAAAAAAAIiAAAAJDk0MzYzYzA5LTc1N2QtNDBmMy1hM2JjLThmNzcyZDBkOWUzYg.jpg" align='left' style="margin-right:4px;width:30%">
[Dr. Mayank Vatsa](https://www.iiitd.edu.in/~mayank/){:target="_blank"} is an associate professor at Indraprastha Institute of Information Technology, Delhi (IIIT-D), India. He received the M.S. and Ph.D. degrees in computer science from West Virginia University, Morgantown, WV, USA, in 2005 and 2008, respectively. He has authored more than 150 publications in refereed journals, book chapters, and conferences. His research has been funded by the Unique Identification Authority of India and DIT. He was a recipient of the FAST Award Project by DST, India. His areas of interest are biometrics, image processing, machine learning, and information fusion.


<br>
Mayank on ..

 - <a href="#work_exp">His problem statements during PhD</a>
 - <a href="#ml_recog">his work on pattern recognition and Neuro-cognition</a>
 - <a href="#traits">Traits he looks for in a student</a>
 - <a href="#ml_eco">Current ML ecosystem in India</a>
 
<br>

**ML-India:** We’d like to start off by understanding how you got instigated into the field of machine learning?

**Mayank:** I remember I was watching The Terminator in 1998-1999, and I was intrigued by the technology applications depicted in the movie. It got me thinking about possible future applications of this technology. So I started exploring and came across a lot of ongoing projects on robotics. I began working towards building a robot that could meet and greet people with a personal touch. For example, it should recognize the face, language, and gestures to identify a person’s name and then greet them accordingly. Needless to say, robotics and machine learning are an integral part of this, but the problem of face recognition was a huge task in itself. To expand my knowledge base and work on this project, I worked with Prof [K.S. Venkatesh](http://home.iitk.ac.in/~venkats/){:target="_blank"}, as a summer intern, who introduced me to the field of computer vision and related subjects. Later, I joined IIT Kanpur in 2002 as a research associate with Prof [Phalguni Gupta](http://home.iitk.ac.in/~pg/){:target="_blank"}and he was very supportive of my research in this direction. So, I started with the intent of building a robot and then narrowed down to working on one particular aspect of it, recognizing people with their physiological traits such as face and iris. Over the years we have picked up machine learning techniques to see if we can solve this problem more efficiently. I believe if we can propose a good solution to this problem, it will automatically help solve other related problems. That’s how my research started. Then I got into West Virginia University which is more focused on biometric, forensics and identification technologies and worked on some really exciting projects with Prof. [Afzel Noore](http://www.statler.wvu.edu/faculty-staff/faculty/afzel-noore){:target="_blank"} and Prof. [Arun Ross](http://www.cse.msu.edu/~rossarun/){:target="_blank"}. This is where I realized that the core theory for these solutions would come from machine learning, pattern recognition, artificial intelligence and image processing.

  

**ML-India:** How did you come to be associated with IIIT Delhi?

**Mayank:** In the middle of 2008, I had started looking for jobs in India with a particular focus on academics. Dr. [Richa Singh](https://www.iiitd.edu.in/~richa/){:target="_blank"} and I were contacted by [Dr. Pankaj Jalote](https://www.iiitd.edu.in/~jalote/){:target="_blank"}, Director of IIITD and he wanted to have a meeting. The first batch of IIIT-Delhi hadn't even started then. He explained his vision for this new institution and the concept of IIIT-Delhi. I was excited at the opportunity but at the same time, I felt that it was a bit of a risk since everything was new and there’s always some degree of uncertainty associated with a new institution. However, I am glad I took it the leap of faith. The institute supported us with the seed money to start our lab and within 2-3 months, we started the [Image Analysis and Biometrics Lab](http://iab-rubric.org/){:target="_blank"}, which is the oldest research lab at IIIT-Delhi.

  
  
<a name="work_exp"></a>
**ML-India:** What were the problems statements you were working on during your PhD?

**Mayank:** During my PhD at [West Virginia University](http://www.wvu.edu/){:target="_blank"}, I was focusing on two research problems. One was machine learning oriented and the other was more computer vision driven. In the first contribution, the main question I tried answering is: How we can combine multiple sources of information which improve the performance compared to the ingredients. Let me explain it with respect to specific contributions in biometrics: Biometric fusion involves consolidating the output of two or more biometric matchers (Fingerprint and Iris – as in the case of Aadhaar) in order to render a decision about the identity of an individual. We consider the problem of designing a fusion scheme when (a) the number of training samples is limited, thereby undermining the use of a purely density-based scheme and the likelihood ratio test statistic; (b) the output of multiple matchers report conflicting results; and (c) the use of a single fusion rule may not be practical due to the diversity of scenarios encountered in the probe dataset. To address these issues, a learning based dynamic reconciliation scheme for fusion rule selection is proposed. The proposed approach follows no-free-lunch theorem which states that there is no one classification model that works best for every problem. My work was focused on building models which can learn to select different classifiers according to the situation. That’s how ML was involved in my research during my PhD. 

The other problem was more computer vision oriented which was focused on picking level 3 extended features in fingerprints. I was working on detecting pores and other deep rich features. I built an algorithm on level set approach to extract this meaningful information. 

  

**ML-India:** Did you have large data sets to train these classifiers? 

**Mayank:** The data set for some problem statements was not large since we were working on small-sample-size (also known as S<sup>3</sup>) problems. However, for problems involving fingerprint recognition, we had about 16 million fingerprints which were provided to us by the funding agencies. The data was both unlabeled and labeled and we had to devise some semi-supervised approaches to deal with it. Therefore, we worked on designing algorithms/models which would adapt themselves to the increasing number of inputs so that we do not have to revise and alter the algorithm repeatedly.

  

We started this work at WVU and continued it in India, solving India specific problems. The learning that happened at WVU helped us a lot in evolving our models and algorithms to address the problem statements unique to India.

  
<a name="ml_recog"></a>
**ML-India:** Some of your projects include work on the deep learning aspect of pattern recognition and Neuro-cognition. Could you elaborate on this?

**Mayank:** Yeah, during my PhD I did work on Neural Networks but never looked at it in a deeper fashion. If you look at our paper in ‘Image and vision and computing’, we do learn models using Gabor filters and neural networks. In late 2008-2009, we didn’t have enough resources to pursue deep learning and train the students. Later, we studied [Geoffrey Hinton](http://www.cs.toronto.edu/~hinton/){:target="_blank"}’s paper in [Science](http://www.sciencedirect.com/){:target="_blank"} where the idea of layer-by-layer greedy training was proposed. This motivated us to take a fresh look at it. A couple of students took it up and started studying it; though it took some time for them to wrap their heads around it. Once they learned it, we purchased some Tesla cards (thanks to our funded project from [Ministry of Electronics and Information Technology](http://meity.gov.in/){:target="_blank"}), as well as received some such cards as gifts from nVIDIA, so that we can work on deep learning related problems. The work is going on for about four years now. One of the problems we are working on is automatically recognizing faces which have aged a long period, 20 years for instance. So training the models using deep learning to modify relevant features with respect to time is a really engaging problem. A lot of factors come into picture while looking at this. Intentional and unintentional disguise is one of them. An example of intentional disguise would involve a person who used to stay clean shaven but started sporting a mustache and beard because the person may want to change the appearance to elude from law enforcement. Unintentional disguise would be a person starts wearing spectacles due to sight problem. Many people also go for cosmetic surgeries, which is another factor. We were recently given the best paper award at the Winter Conference on Applications of Computer Vision where we showed that if someone underwent a period of illicit drug abuse, a lot of changes could occur in the facial structure. It’s not only the age but many other environmental factors that contribute to changes in the face. The human brain, however, is really quick on picking these changes and identifying if it’s a known face or not. We have published 3-4 papers exploring the cognitive and behavioral aspect of the brain and how it responds when a modified face is shown to it. We recently studied MRI scans to see if the brain activity changes when an altered face is shown. We wanted to see if we can learn from the variations in the activity and inculcate these learning into our adaptive algorithms. ML: During your career, what were the general misconceptions that you’ve seen among new students of ML?The most common one is that they think ML is easy, which it obviously isn’t. An interesting misconception is that most students think ML won’t require much mathematics. We have our course spread over 2 semesters, and by the time they reach the second, they realize that ML is all about mathematics. Another misconception is that people believe that the machine learning classifier they just built would do wonders. They realize soon enough that it is not about doing wonders with these classifiers, it is about choosing the right problem, choosing the right data set for that problem, and choosing the right classifier for that particular dataset and problem.

<a name="traits"></a>
**ML-India:** What are the general traits that you look for in a student before working with them?

**Mayank:** Along with good background, we generally look at three characteristics. First is persistence. I can teach the student the mathematics, coding, and concepts, but the student needs to be persistent on solving the problems, overcoming failures, and be motivated to keep trying. Second quality I look for is the excitement towards a given problem statement. The student needs to treat it as his/her problem and be completely determined towards solving it. Many students just want to make projects to get credits, which does make them active in completing the project but does not help in coming up with strong publications and prototypes. The third quality is preparation. If the student already has knowledge on topics like data structures and other relevant subjects, it becomes easier to work with him/her. Students stay here as long as 3 years. For example, Prateekshit, a dedicated student, worked in our lab for ~3 years and then got admitted to UPenn. Thus, a keen interest in ML is an obvious prerequisite.   
  
**ML-India:** Like you mentioned you’re already working on many futuristic projects, are there any other research problems that you have in mind that you would like to take up later?

**Mayank:** I came across a lot of futuristic problems during the recent Harvard Fellowship that I attended varying from understanding brain to coming up novel sensing technology for faster medical diagnosis. Another, longer term aspect I would like to work on is to address the problem of water scarcity where cleaning rivers and preserving natural resources require the amalgamation of several engineering branches. I think there is a lot that can be achieved relating to this problem using computing approaches including Machine Learning; probably 10-15 years from now given we have decent developments in technology. 

<a name="ml_eco"></a>
**ML-India:** We still don’t see a lot of papers from India going to top conferences in spite of a lot of ML startups and researchers claiming to use ML concepts in their work. What’s your take on the current ecosystem of ML in India?

**Mayank:** A lot of buzz is already going around machine learning in India. A lot of people from the industry and research community are using ML. However, most of them are ‘using’ ML in their work and not building or generating new frameworks/models. A lot of extra effort goes into developing fresh research apart from the tools, coding etc. which is not happening in India. Most of us are utilizing and not innovating. China, as we know, have a significant number of papers every year in top-tier conferences because they spend more time in developing new technologies. Therefore, there is a need for all the Indian users of ML to switch to being the builders of ML. 

  

**ML-India:** How do you think can this be achieved?

**Mayank:** I have a two-fold answer to this. First is, as a leader, you need to become a role model to your followers. If they see you are putting in hard hours of work to get results, they will automatically try to match your efforts. It is inductive. That is how you can maintain persistency among the students and keep that drive toward research and development strong. The other aspect is nurturing the ecosystem itself. Fostering an ML environment by inculcating new courses and providing students the option of choosing the courses of their interest is an effective way of generating and maintaining a strong interest in the field. This will improve thing at the root level and help students in finding their path of interest early on in their careers.

**ML-India:** Thank you for your valuable time Mayank. All the best to you from ML-India.

