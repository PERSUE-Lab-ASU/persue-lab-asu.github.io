---
title: "Persue Lab - Publications"
layout: gridlay
excerpt: "Persue Lab -- Publications."
sitemap: false
permalink: /publications/ 
---


# Publications
**At the end of this page, you can find the [full list of publications and patents](#full-list-of-publications).**


{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/img/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>



## Full List of publications

  Exploring Privacy and Security Concerns of EdTech Users: A Qualitative Analysis of User Written Reviews
  *Waqar Hassan Khan, Protik Bose Pranto, Tianyi Yang, Rakibul Hasan*
  year: 2023
  venue_full_name: Nineteenth Symposium on Usable Privacy and Security
  venue_short_name: SOUPS'23
  paper_link: "[../Publications/Exploring.pdf](../Publications/Exploring.pdf)"
  poster_link: "[../Publications/Exploring.pdf](../Publications/Exploring.pdf)"
  poster_image_link: "[../Publications/Exploring.jpg](../Publications/Exploring.jpg)"

  Understanding the Effect of Private Data in Disinformation Propagation
  *Protik Bose Pranto, Waqar Hassan Khan, Sahar Abdelnabi, Rebecca Weil, Mario Fritz, Rakibul Hasan*
  year: 2023
  venue_full_name: Nineteenth Symposium on Usable Privacy and Security
  venue_short_name: SOUPS'23
  paper_link: "[../Publications/Understanding.pdf](../Publications/Understanding.pdf)"
  poster_link: "[../Publications/Understanding.pdf](../Publications/Understanding.pdf)"
  poster_image_link: "[../Publications/understanding.jpg](../Publications/understanding.jpg)"


 From Bad to Worse: Using Private Data to Propagate Disinformation on Online Platforms with a Greater Efficiency
 *Protik Bose Pranto, Waqar Hassan Khan, Sahar Abdelnabi, Rebecca Weil, Mario Fritz, Rakibul Hasan*
  year: 2023
  venue_full_name: 'Designing Technology and Policy Simultaneously: Towards A Research Agenda and New Practice'
  venue_short_name: CHI'23 Workshop
  paper_link: "[../Publications/CHI_23_Design_Policy_misinfo.pdf](../Publications/CHI_23_Design_Policy_misinfo.pdf)"

 A Psychometric Scale to Measure Individuals' Value of Other People's  Privacy (VOPP)
 *Rakibul Hasan, Rebecca Weil, Rudolf Siegel, Katharina Krombholz* 
  year: 2023
  venue_full_name: Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems
  venue_short_name: CHI'23
  paper_link: "[https://publications.cispa.saarland/3930/1/VOPP_Hasan_et_al_2023.pdf](https://publications.cispa.saarland/3930/1/VOPP_Hasan_et_al_2023.pdf)"

 Understanding the Perception and Awareness of Education Technologies' Privacy and Security Issues
 *Rakibul Hasan* 
  year: 2023
  venue_full_name: The 23rd Privacy Enhancing Technologies Symposium
  venue_short_name: PETS 23
  paper_link: "[https://www.petsymposium.org/2023/files/papers/issue4/popets-2023-0110.pdf](https://www.petsymposium.org/2023/files/papers/issue4/popets-2023-0110.pdf)"


  Developing a Psychometric Scale to Measure One’s Valuation of Other People’s Privacy
  *Rakibul Hasan, Rudolf Siegel, Rebecca Weil, Katharina Krombholz*
  year: 2022
  venue_full_name: The Eighteenth Symposium on Usable Privacy and Security
  venue_short_name: SOUPS 2022
  paper_link: "[https://www.usenix.org/system/files/soups2022-poster57_hasan_abstract_final_1.pdf](https://www.usenix.org/system/files/soups2022-poster57_hasan_abstract_final_1.pdf)"
  poster_link: "[https://www.usenix.org/system/files/soups2022-poster57_hasan_final_1.pdf](https://www.usenix.org/system/files/soups2022-poster57_hasan_final_1.pdf)"
 

 The Impact of Viral Posts on Visibility and Behavior of Professionals: A Longitudinal Study of Scientists on Twitter
 *Rakibul Hasan, Cristobal Cheyre, Yong-Yeol Ahn, Roberto Hoyle, Apu Kapadia*
  year: 2022
  venue_full_name: Proceedings of the International AAAI Conference on Web and Social Media
  venue_short_name: AAAI 22
  paper_link: "[../Publications/aaai-paper-22.pdf](../Publications/aaai-paper-22.pdf)"

 Understanding Utility and Privacy of Demographic Data in Education Technology by Causal Analysis and Adversarial-Censoring
 *Rakibul Hasan, Mario Fritz*
  year: 2022
  venue_full_name: The 22nd Privacy Enhancing Technologies Symposium
  venue_short_name: PETS 22
  paper_link: "[https://petsymposium.org/popets/2022/popets-2022-0044.pdf](https://petsymposium.org/popets/2022/popets-2022-0044.pdf)"

 Open-domain, content-based, multi-modal fact-checking of out-of-context images via online resources
 *Sahar Abdelnabi, Rakibul Hasan, Mario Fritz*
  year: 2022
  venue_full_name: Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition
  venue_short_name: IEEE/CVF 22
  paper_link: "[https://openaccess.thecvf.com/content/CVPR2022/papers/Abdelnabi_Open-Domain_Content-Based_Multi-Modal_Fact-Checking_of_Out-of-Context_Images_via_Online_Resources_CVPR_2022_paper.pdf](https://openaccess.thecvf.com/content/CVPR2022/papers/Abdelnabi_Open-Domain_Content-Based_Multi-Modal_Fact-Checking_of_Out-of-Context_Images_via_Online_Resources_CVPR_2022_paper.pdf)"

 Your photo is so funny that i don’t mind violating your privacy by sharing it: effects of individual humor styles on online photo -sharing behaviors
 *Rakibul Hasan, Bennett I Bertenthal, Kurt Hugenberg, Apu Kapadia*
  year: 2021
  venue_full_name: Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems
  venue_short_name: CHI 21
  paper_link: "[https://dl.acm.org/doi/pdf/10.1145/3411764.3445258](https://dl.acm.org/doi/pdf/10.1145/3411764.3445258)"

  Automatically detecting bystanders in photos to reduce privacy risks
 *Rakibul Hasan, David Crandall, Mario Fritz, Apu Kapadia*
  year: 2020
  venue_full_name: IEEE Symposium on Security and Privacy 2020
  venue_short_name: IEEE S & P 20
  paper_link: "[https://publications.cispa.saarland/3051/1/bystander-oakland-2020.pdf](https://publications.cispa.saarland/3051/1/bystander-oakland-2020.pdf)"

 Influencing photo sharing decisions on social media: A case of paradoxical findings
 *Mary Jean Amon, Rakibul Hasan, Kurt Hugenberg, Bennett I Bertenthal, Apu Kapadia*
  year: 2020
  venue_full_name: IEEE Symposium on Security and Privacy 2020
  venue_short_name: IEEE S & P 20
  paper_link: "[https://par.nsf.gov/servlets/purl/10183400](https://par.nsf.gov/servlets/purl/10183400)"

 Reducing Privacy Risks in the Context of Sharing Photos Online
 *Rakibul Hasan*
  year: 2020
  venue_full_name: Extended Abstracts of the 2020 CHI Conference on Human Factors in Computing Systems
  venue_short_name: CHI'20 (EA)
  paper_link: "[https://drive.google.com/file/u/0/d/1bbDJc8BD0yg2EdLWjkW_AyWZJFfZDiJn/view](https://drive.google.com/file/u/0/d/1bbDJc8BD0yg2EdLWjkW_AyWZJFfZDiJn/view)"

 Can privacy be satisfying? on improving viewer satisfaction for privacy-enhanced photos using aesthetic transforms
 *Rakibul Hasan, Yifang Li, Eman Hassan, Kelly Caine, David J Crandall, Roberto Hoyle, Apu Kapadia*
  year: 2019
  venue_full_name: Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems
  venue_short_name: CHI'19
  paper_link: "[https://dl.acm.org/doi/pdf/10.1145/3290605.3300597](https://dl.acm.org/doi/pdf/10.1145/3290605.3300597)"

 Viewer experience of obscuring scene elements in photos to enhance privacy
 *Rakibul Hasan, Eman Hassan, Yifang Li, Kelly Caine, David J Crandall, Roberto Hoyle, Apu Kapadia*
  year: 2018
  venue_full_name: Proceedings of the 2018 CHI Conference on Human Factors in Computing Systems
  venue_short_name: CHI'18
  paper_link: "[https://dl.acm.org/doi/pdf/10.1145/3173574.3173621](https://dl.acm.org/doi/pdf/10.1145/3173574.3173621)"

  Cartooning for enhanced privacy in lifelogging and streaming videos
 *Rakibul Hasan, Patrick Shaffer, David Crandall, Eman T Apu Kapadia* 
  year: 2017
  venue_full_name: Proceedings of the IEEE conference on computer vision and pattern recognition workshops
  venue_short_name: CVPR 17
  paper_link: "[https://openaccess.thecvf.com/content_cvpr_2017_workshops/w16/papers/Kapadia_Cartooning_for_Enhanced_CVPR_2017_paper.pdf](https://openaccess.thecvf.com/content_cvpr_2017_workshops/w16/papers/Kapadia_Cartooning_for_Enhanced_CVPR_2017_paper.pdf)"

 A novel approach for constructing emulator for Microsoft Kinect XBOX 360  Sensor in the. NET platform
 *Mohammad Raihanul Islam, Sazzadur Rahaman, Rakibul Hasan, Ridwan Rashid Noel, Asif Salekin, Hasan Shahid Ferdous* 
  year: 2013
  venue_full_name: 2013 4th International Conference on Intelligent Systems, Modelling and Simulation
  venue_short_name: ISMS 13
  paper_link: "[../Publications/ISMS2013.pdf](../Publications/ISMS2013.pdf)"

{% for publi in site.data.publist %}

{{ publi.title }} 
{{ publi.authors }} 
{{ publi.link.display }}

{% endfor %}
