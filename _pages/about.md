---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm currently an undergraduate student at [Shanghai Jiao Tong University](https://en.sjtu.edu.cn/), majoring in Computer Science and Technology (IEEE Pilot Class). I'm now a research intern in [Machine Vision and Intelligence Group](https://www.mvig.org/) (MVIG), under the supervision of Prof. [Cewu Lu](https://www.mvig.org/) and Prof. [Lixin Yang](https://lixiny.github.io/). My research interests revolve around the intersection between Computer Vision and Robotics, and I welcome any invitation for collaboration or discussion.

I intend to gain some experience as an intern in a company or research institution while prepare my MS applications in Fall 2025. If you are interested, please drop me an email!


# 🔥 News
- *2024.6*: I will work as an intern in the AI department of [bilibili](https://www.bilibili.com) this summer.
- *2023.12*: One paper **FAVOR** was accepted by [AAAI 2024](https://aaai.org/aaai-conference/)
- *2023.07*: I have spent wonderful two weeks attending the summer course [IDS2301](https://datascience.hku.hk/2023/07/idss-2301-immersing-oneself-in-a-very-meaningful-vacation-through-the-hku-ids-summer-course-stay-proud-as-our-first-batch-of-potential-data-scientists/) at [HKU-IDS](https://datascience.hku.hk/#).
- *2023.03*: &nbsp;🎉🎉 I joined MVIG and began exploring the field of Computer Vision.

# 📝 Publications 

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <img src="images/POEM-v2.png" alt="sym" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>Multi-view Hand Reconstruction with a Point-Embedded Transformer</strong></p>

    <p>Arxiv | <a href="https://arxiv.org/abs/2408.10581">Paper</a> | <a href="https://github.com/JubSteven/POEM-v2">Code</a></p>

    <p><a href="https://lixiny.github.io/">Lixin Yang</a>, <a href="https://colmar-zlicheng.github.io/">Licheng Zhong</a>, <b><u>Pengxiang Zhu</u></b>, Xinyu Zhan, Junxiao Kong, Jian Xu, <a href="http://mvig.org">Cewu Lu</a> </p>
  
  <p>POEM is a generalizable multi-view hand mesh reconstruction model which embeds a static basis point within the multi-view stereo space. To infer accurate 3D hand mesh from multi-view images, POEM introduce a point-embedded transformer decoder. By employing a combination of five large-scale multi-view datasets and sufficient data augmentation, POEM demonstrates superior generalization ability in real-world applications.  </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <img src="images/FAVOR.png" alt="sym" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>FAVOR: Full-body AR-driven Virtual Object Rearrangement Guided by Textual Instructions</strong></p>
    <p><strong>AAAI 2024</strong> | <a href="https://ojs.aaai.org/index.php/AAAI/article/view/28097">Paper</a></p>

    <p><a href="https://kailinli.top/">Kailin Li</a>*, <a href="https://lixiny.github.io/">Lixin Yang</a>*, Zenan Lin, Jian Xu, Xinyu Zhan, Yifei Zhao, <b><u>Pengxiang Zhu</u></b>, Wenxiong Kang, Kejian Wu, <a href="http://mvig.org">Cewu Lu</a></p>    
  
  <p>FAVOR is a novel dataset for Full-body AR-driven Virtual Object Rearrangement that uniquely employs motion capture systems and VR. A pipeline for producing digital human rearrangement motion sequences is also presented.</p>
  </div>
</div>

# 💻 Undergraduate Projects


<div class="paper-box">
  <div class="paper-box-image">
  <div>
  <div class="badge">AI3603</div>
  <img src="images/AI3603.png" width="100%"></div>
  </div>
  <div class="paper-box-text">
    <p><a href="https://github.com/JubSteven/AI3603-Final-Project">CUT++: Image Style Transfer</a></p>
    <p><i class="fab fa-fw fa-github" aria-hidden="true"></i> <a href="https://github.com/JubSteven/AI3603-Final-Project"> GitHub</a>｜<svg t="1697827825990" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="7835" width="16" height="16"><path d="M645.071238 97.52381L828.952381 281.258667V414.47619h48.761905v390.095239h-48.761905v48.761904a73.142857 73.142857 0 0 1-73.142857 73.142857H268.190476a73.142857 73.142857 0 0 1-73.142857-73.142857v-48.761904H146.285714V414.47619h48.761905V170.666667a73.142857 73.142857 0 0 1 73.142857-73.142857h376.880762zM755.809524 804.571429H268.190476v48.761904h487.619048v-48.761904zM368.274286 520.94781H299.154286v174.445714h43.885714v-53.101714h10.971429a177.493333 177.493333 0 0 0 31.597714-2.852572 103.619048 103.619048 0 0 0 16.237714-4.827428c4.534857-2.048 8.777143-4.461714 12.726857-7.241143 7.168-5.412571 12.507429-12.141714 16.018286-20.187429 3.364571-8.484571 5.046857-17.334857 5.046857-26.550857a72.338286 72.338286 0 0 0-4.388571-23.698286 56.441905 56.441905 0 0 0-13.604572-19.968 62.025143 62.025143 0 0 0-23.917714-12.726857 116.784762 116.784762 0 0 0-25.453714-3.291428z m140.434285 0h-61.44v174.445714h61.44c6.875429-0.146286 13.750857-0.731429 20.626286-1.755429 6.144-1.024 12.141714-2.56 17.993143-4.608 5.266286-2.194286 10.313143-4.754286 15.140571-7.68 4.388571-3.218286 8.411429-6.875429 12.068572-10.971428 3.510857-4.388571 6.582857-9.069714 9.216-14.043429a110.689524 110.689524 0 0 0 6.144-16.896c2.194286-10.24 3.364571-20.626286 3.510857-31.158857a176.37181 176.37181 0 0 0-1.755429-21.284571 113.249524 113.249524 0 0 0-4.608-18.432 90.599619 90.599619 0 0 0-7.68-15.579429 78.214095 78.214095 0 0 0-10.532571-12.507429 77.994667 77.994667 0 0 0-13.604571-9.435428 93.42781 93.42781 0 0 0-16.457143-6.363429 139.702857 139.702857 0 0 0-30.061715-3.730285z m213.504 0h-116.736v174.445714h43.885715v-65.828572h63.414857v-34.011428h-63.414857v-39.497143h72.850285v-35.108571z m-206.482285 35.108571c4.973714 0.146286 9.654857 1.536 14.043428 4.169143 4.534857 3.072 8.265143 7.021714 11.190857 11.849143 3.218286 5.851429 5.485714 11.995429 6.802286 18.432 1.024 5.997714 1.609143 11.995429 1.755429 17.993143-0.146286 6.144-0.731429 12.214857-1.755429 18.212571a62.22019 62.22019 0 0 1-6.802286 18.212571c-2.925714 4.681143-6.656 8.557714-11.190857 11.629715a28.038095 28.038095 0 0 1-14.043428 3.730285h-24.576v-104.228571h24.576z m-151.625143 0c3.949714 0.146286 7.826286 0.877714 11.629714 2.194286 3.364571 1.316571 6.363429 3.218286 8.996572 5.705143 4.681143 5.12 7.021714 11.117714 7.021714 17.993142 0 7.314286-2.706286 13.385143-8.118857 18.212572a28.525714 28.525714 0 0 1-9.874286 5.485714 47.88419 47.88419 0 0 1-12.068571 1.536h-18.651429v-51.126857h21.065143z m217.307428-385.414095L268.190476 170.666667v243.809523h487.619048v-49.956571h-174.372572L581.412571 170.666667z m73.142858 39.740952v80.993524h81.042285l-81.042285-80.993524z" p-id="7836"></path></svg> <a href="/blob/main/Report.pdf">PDF</a></p>
    <p>In this project, we build our CUT++ model for image style transfer on the renowned CUT model. By introducing attention into the GAN-based model and modifying the PatchNCE loss, we achieve decent result on the given dataset.</p>
  </div>
</div>



<div class="paper-box">
  <div class="paper-box-image">
  <div>
  <div class="badge">CS3602</div>
  <img src="images/CS3602.jpg" width="100%"></div>
  </div>
  <div class="paper-box-text">
    <p><a href="https://github.com/JubSteven/CS3602-Final-Project">Chinese Slot Language Understanding</a></p>
    <p><i class="fab fa-fw fa-github" aria-hidden="true"></i> <a href="https://github.com/JubSteven/CS3602-Final-Project"> GitHub</a>｜<svg t="1697827825990" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="7835" width="16" height="16"><path d="M645.071238 97.52381L828.952381 281.258667V414.47619h48.761905v390.095239h-48.761905v48.761904a73.142857 73.142857 0 0 1-73.142857 73.142857H268.190476a73.142857 73.142857 0 0 1-73.142857-73.142857v-48.761904H146.285714V414.47619h48.761905V170.666667a73.142857 73.142857 0 0 1 73.142857-73.142857h376.880762zM755.809524 804.571429H268.190476v48.761904h487.619048v-48.761904zM368.274286 520.94781H299.154286v174.445714h43.885714v-53.101714h10.971429a177.493333 177.493333 0 0 0 31.597714-2.852572 103.619048 103.619048 0 0 0 16.237714-4.827428c4.534857-2.048 8.777143-4.461714 12.726857-7.241143 7.168-5.412571 12.507429-12.141714 16.018286-20.187429 3.364571-8.484571 5.046857-17.334857 5.046857-26.550857a72.338286 72.338286 0 0 0-4.388571-23.698286 56.441905 56.441905 0 0 0-13.604572-19.968 62.025143 62.025143 0 0 0-23.917714-12.726857 116.784762 116.784762 0 0 0-25.453714-3.291428z m140.434285 0h-61.44v174.445714h61.44c6.875429-0.146286 13.750857-0.731429 20.626286-1.755429 6.144-1.024 12.141714-2.56 17.993143-4.608 5.266286-2.194286 10.313143-4.754286 15.140571-7.68 4.388571-3.218286 8.411429-6.875429 12.068572-10.971428 3.510857-4.388571 6.582857-9.069714 9.216-14.043429a110.689524 110.689524 0 0 0 6.144-16.896c2.194286-10.24 3.364571-20.626286 3.510857-31.158857a176.37181 176.37181 0 0 0-1.755429-21.284571 113.249524 113.249524 0 0 0-4.608-18.432 90.599619 90.599619 0 0 0-7.68-15.579429 78.214095 78.214095 0 0 0-10.532571-12.507429 77.994667 77.994667 0 0 0-13.604571-9.435428 93.42781 93.42781 0 0 0-16.457143-6.363429 139.702857 139.702857 0 0 0-30.061715-3.730285z m213.504 0h-116.736v174.445714h43.885715v-65.828572h63.414857v-34.011428h-63.414857v-39.497143h72.850285v-35.108571z m-206.482285 35.108571c4.973714 0.146286 9.654857 1.536 14.043428 4.169143 4.534857 3.072 8.265143 7.021714 11.190857 11.849143 3.218286 5.851429 5.485714 11.995429 6.802286 18.432 1.024 5.997714 1.609143 11.995429 1.755429 17.993143-0.146286 6.144-0.731429 12.214857-1.755429 18.212571a62.22019 62.22019 0 0 1-6.802286 18.212571c-2.925714 4.681143-6.656 8.557714-11.190857 11.629715a28.038095 28.038095 0 0 1-14.043428 3.730285h-24.576v-104.228571h24.576z m-151.625143 0c3.949714 0.146286 7.826286 0.877714 11.629714 2.194286 3.364571 1.316571 6.363429 3.218286 8.996572 5.705143 4.681143 5.12 7.021714 11.117714 7.021714 17.993142 0 7.314286-2.706286 13.385143-8.118857 18.212572a28.525714 28.525714 0 0 1-9.874286 5.485714 47.88419 47.88419 0 0 1-12.068571 1.536h-18.651429v-51.126857h21.065143z m217.307428-385.414095L268.190476 170.666667v243.809523h487.619048v-49.956571h-174.372572L581.412571 170.666667z m73.142858 39.740952v80.993524h81.042285l-81.042285-80.993524z" p-id="7836"></path></svg> <a href="https://github.com/JubSteven/CS3602-Final-Project/blob/final/LM_Report.pdf">PDF</a></p>
    <p>In this project, we build a BERT-based pipeline for Chinese slot understanding. We incorporated Lexicon information into the BERT backbone and achieved descent result on the given noisy dataset. </p>
  </div>
</div>

# 📇 Experiences
<div class="paper-box-right">
  <div class="paper-box-text">
    <p><a href="https://www.mvig.org/">Machine Vision and Intelligence Group</a></p>
    <p>Undergraduate Research Intern, <em>2023.3 - (now)</em></p>
    <p>Advisor: <a href="https://lixiny.github.io/">Lixin Yang</a>, <a href="https://www.mvig.org/">Cewu Lu</a></p>
  </div>
  <div class="paper-box-image">
    <div>
      <a href="https://www.mvig.org/">
      <img src="images/mvig.png" alt="sym" width="100px" style="padding: 10px">
      </a>
    </div>
  </div>
</div>
  <!-- <div class="paper-box-image">
    <div>
      <a href="https://www.mvig.org/">
      <img src="images/SJTU_logo.png" alt="sym" width="80px" style="padding: 10px">
      </a>
    </div>
  </div> -->
<div class="paper-box-right">
  <div class="paper-box-text">
    <p>Department of AI Technology, <a href="https://www.bilibili.com/">bilibili</a></p>
    <p>Algorithm Intern, <em>2024.6 - (now)</em></p>
    <p>Video Understanding and Machine Reviews</p>
  </div>
  <div class="paper-box-image">
    <div>
      <a href="https://www.bilibili.com/">
      <img src="images/bilibili.jpg" alt="sym" width="100px" style="padding: 10px">
      </a>
    </div>
  </div>
</div>

# 🎖 Honors and Awards
- *2023* Academic Excellence Scholarship of SJTU (top 10%)
- *2022* Academic Excellence Scholarship of SJTU (top 10%)
- *2022.3* Finalist of Mathematical Contest of Modeling (top 5%)

# 📖 Educations
- *2021.09 - (now)*, Shanghai Jiao Tong University, Shanghai, China.
- *2018.09 - 2021.06*, Shanghai High School, Shanghai, China (Outstanding Graduate).

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

