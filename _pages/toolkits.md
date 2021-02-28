---
title: BootCamps and Toolkits
layout: default
bodyClass: page-services-list
permalink: /toolkits
---
<!-- Wat betekenen voor jullie werking?-->
<div class="intro">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h1>Aim of the Toolkits</h1>
        <p>
          The project team will develop three toolkits for educators and organize three bootcamps to introduce young girls to a broad range of STEM subjects, in particular robotics, programming, electronics. A mentoring programme will be also implemented to provide further support after the mobilities, specifically to assist girls who want to deepen some topics, improve their competences or undertake STEM related studies. 
        </p>
      </div>
    </div>
  </div>
</div>

<div class="container pb-6">
  <div class="row">
    {% for service in site.services %}
    <div class="col-12 col-md-4 mb-1">
      <div class="service service-summary">
        <div class="service-content">
          <h2 class="service-title">
            <a href="{{site.baseurl}}{{ service.url }}">{{ service.title }}</a>
          </h2>
          {{ service.shortcontent | markdownify | strip_html | truncate: 100 }}
        </div>
      </div>
    </div>
    {% endfor %}
  </div>
</div>
  <!-- Interesse, contacteer ons-->

<!--div class="intro-med">
 <div class="container pt-6 pt-md-1">
    <div class="row">
      <div class="col-12 ">
        <h1>Interesse in dit project, maar je hebt nog vragen?</h1>
          <div class="call-box-bottom">
        <a href="mailto:{{ site.data.contact.email }}" class="button">Contacteer ons!</a>   
    </div>
       </div>
   </div>
  </div>
</div-->

