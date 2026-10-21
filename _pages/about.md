---
permalink: /
title: "Matteo Salvino"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<p>
  <strong>Location: </strong> Department of Computer Science, Sapienza University of Rome, Viale Regina Elena 295, 00161, Rome.<br>
  <strong>Office: </strong> Office G48, Third floor, Building G<br>
  <strong>Email: </strong> salvino at di.uniroma1.it<br>
  <a href="https://scholar.google.com/citations?user=2K5X2R0AAAAJ&hl=en"><i class="ai ai-google-scholar ai-lg"></i>Scholar</a> 
  - 
  <a href="https://dblp.org/pid/336/4723.html"><i class="ai ai-dblp ai-lg"></i>dblp</a> 
  - 
  <a href="https://orcid.org/0009-0008-8722-0634"><span style="color: #b2c046"><i class="ai ai-orcid ai-lg"></i></span>ORCID</a>
</p>
<hr>

<h3 id="about-me">About me</h3>
<p>Since November 2025 I have been a PhD student in the Department of Computer, Control and Management Engineering at Sapienza University of Rome, under the supervision of Prof. <a href="https://dventuri83.github.io">Daniele Venturi</a>.
  <br>
  I earned my MSc in Engineering in Computer Science in January 2022 from Sapienza University of Rome.
</p>


<hr>

<h3 id="research-interests"> Research Interests</h3>
<p>My primary research interests lie in theoretical cryptography, with a main focus on secret sharing schemes and foundational cryptographic primitives. I am particularly motivated by bridging theory and practice, leveraging secret sharing mechanisms to design efficient protocols for practical applications such as secure multi-party computation (MPC).</p>

<hr>

<h3 id="news">News</h3>
<div class="news-list">
  {% for item in site.data.news limit:5 %}
  <div class="news-item">
    <div class="news-date">[{{ item.date }}]</div>
    <div class="news-text">{{ item.text | markdownify | remove: '<p>' | remove: '</p>' }}</div>
  </div>
  {% endfor %}
</div>