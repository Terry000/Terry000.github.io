---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am Terry Pei 😊, a researcher at the University of Sydney. I major in deep learning at the school of computer science.

**Research Field**: Data-centric deep learning. I also have rich experience on NLP and CV during the industry internship.

**Recent Work**: Update the AI search engine to automatic annotator via GPT models.

## News

<!-- * GPT is a good Annotator. -->
* <sub>**[Nov 2022]** Win the "Best Student Paper" awarded by ICDM as the first author. [[Award News]](https://twitter.com/icdm2022/status/1595243601545826304) </sub>


* <sub>**[Nov 2022]** Our work has been accepted by ICDM. ([Core Rank A*](http://portal.core.edu.au/conf-ranks/?search=mining&by=all&source=all&sort=arank&page=1)). [[Accepted News]](https://www.cse.fau.edu/~xqzhu/icdm2022/ICDM2022Program.pdf) </sub>


## Projects

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">

  {% for post in site.publications reversed%}
  <tr>
    <td style="border: none; padding:2.5%;width:25%;vertical-align:middle;max-width:100px;max-height:100px">
      <img src="/{{post.image}}" alt="project image" style="width:auto; height:auto; max-width:100%;" />
    </td>
    <td style="border: none; padding:2.5%;width:75%;vertical-align:middle">
      <h3>{{post.title}}</h3>
      {{post.authors}}
      <em>{{post.venue}}</em>, {{ post.date | date: "%Y" }}
      <br>
        {% if post.paperurl %}
          <a href="{{post.paperurl}}">paper</a> /
        {% endif %}
        {% if post.page %}
          <a href="{{post.page}}">website</a> /
        {% endif %}
        {% if post.video %}
          <a href="{{post.video}}">video</a> /
        {% endif %}
        {% if post.code %}
          <a href="{{post.code}}">code</a> /
        {% endif %}
        {% if post.poster %}
          <a href="{{post.poster}}">poster</a> /
        {% endif %}
        {% if post.slides %}
          <a href="{{post.slides}}">slides</a> /
        {% endif %}
        {% if post.dataset %}
          <a href="{{post.dataset}}">dataset</a> /
        {% endif %}
      <p></p>
      {{ post.excerpt }}
    </td>
  </tr>
  {% endfor %}
</table>
<!-- ## News

<!-- * <sub>**[April 2023]** GPT Self-Supervision for a Better Data Annotator </sub>
* <sub>**[Dec 2022]**  Win the "Best Student Paper" awarded by ICDM as the first author. [[Award News]](https://twitter.com/icdm2022/status/1595243601545826304).</sub>
* <sub>**[Nov 2022]** Our work has been accepted by ICDM ([Core Rank A*](http://portal.core.edu.au/conf-ranks/?search=mining&by=all&source=all&sort=arank&page=1)). [[Accepted News]](https://www.cse.fau.edu/~xqzhu/icdm2022/ICDM2022Program.pdf)</sub> --> 

<!-- * <sub>**[Nov 2022]** Beyond Neural Scaling Laws wins a Best Paper Award at NeurIPS 2022! [Press Release](https://blog.neurips.cc/2022/11/21/announcing-the-neurips-2022-awards/)</sub>
* <sub>**[Oct 2022]** New paper at the NeurIPS 2022 Self-Supervised Learning - Theory & Practice Workshop:  
  [Understanding contrastive versus reconstructive self-supervised learning of Vision Transformers](https://sslneurips22.github.io/paper_pdfs/paper_50.pdf)
* <sub>**[Sep 2022]** Life Update: I have relocated from the Bay Area back to Canada (Montreal).</sub>
* <sub>**[Aug 2022]** Beyond neural scaling laws paper accepted for oral presentation at the NeurIPS 2022 Conference.</sub>  
* <sub>**[June 2022]** New pre-print available: [Beyond neural scaling laws: beating power law scaling via data pruning](https://arxiv.org/abs/2206.14486).</sub>
* <sub>**[May 2022]** Awarded the University of Guelph Class of OAC'60 Award for Outstanding Teaching Assistant.
* <sub>**[March 2022]** Gave an invited talk at the Analogical Minds seminar on our Neural Structure Mapping paper. Talk available on [Analogical Minds YouTube channel](https://www.youtube.com/watch?v=v5al6mJKrHQ)</sub>
* <sub>**[Jan 2022]** Defended my master's thesis on "Inductive Biases in Higher-Order Visual Cognition."</sub>  -->
  
<!-- 
<details markdown=1><summary markdown="span"><b>Click here for older news</b></summary>
  
  * <sub>**[Nov 2021]** Invited to participate in the Breaking into AI: Industry Speaker Panel. Available on [University of Toronto Machine Intelligence Group YouTube channel](https://www.youtube.com/watch?v=y_JF5-adrCY&t=243s)</sub>
  * <sub>**[Nov 2021]** Our paper on Neural Structure Mapping was accepted to NeurIPS 2021 Shared Visual Representations in Humans and Machines Workshop</sub>
  * <sub>**[Oct 2021]** Our extended paper on Neural Response Time analysis was accepted to Applied AI Letters journal</sub> 
  * <sub>**[Sep 2021]** Started as an AI Resident at Facebook AI Reseach</sub> 
  * <sub>**[Aug 2021]** Our paper on generating scene graphs with transformers was accepted to the International Conference in Computer Vision 2021 for a poster presentation</sub>
  * <sub>**[April 2021]** Started as a Scientist in Residence for the NEXT AI startup accelerator</sub>  
  * <sub>**[Oct 2020]** Started as an instructor for LearnAI course at the University of Toronto</sub>   
  * <sub>**[Aug 2020]** Attended the MIT-CBMM Summer School on Brains, Minds and Machines 2020 virtually</sub>  
  * <sub>**[July 2020]** Attended the CIFAR Deep Learning and Reinforcement Learning Summer School 2020 virtually</sub>  
  * <sub>**[June 2020]** Our paper was accepted to CVPR 2020 Minds vs Machines Workshop for an oral presentation</sub>   
  * <sub>**[Jan 2020]** Joined the Machine Learning Research Group at University of Guelph as a graduate research assistant</sub>   
  * <sub>**[Nov 2019]** Volunteered and presented our work at the International Conference in Computer Vision 2019 in Seoul</sub>   
  * <sub>**[Sep 2019]** Started MASc in AI at the University of Guelph. Thankful to receive the Vector Scholarship and JN Tata Scholarship</sub>    
  * <sub>**[Aug 2019]** Attended the Bayesian Methods in Deep Learning Summer School 2019 in Moscow</sub>   
  * <sub>**[July 2019]** Attended the Machine Learning Summer School 2019 in London</sub>    

</details> -->


## Honors and Awards

 * <sub>  A Best Student Paper (2022) </sub>

 * <sub> Two Full-Scholarship (2019-2020, 2020-2021) </sub>

 * <sub> Outstanding Graduate (2019) </sub>

 * <sub> National Second Prize in Mathematics Competition (2018) </sub>

 * <sub> Provincial Prize in Blue Bridge Cup Programming C++ Competition (2018) </sub>

## Academic Services
* <sub> Program chair of NeurIPS. </sub>
 * <sub> Reviewer of ICML, NeurIPS, ICDM, AAAI. </sub>