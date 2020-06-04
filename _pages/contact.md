---
title: Contact
layout: default
bodyClass: page-contact
permalink: /contact
---

<div class="intro intro-small">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h1>Contact</h1>
      </div>
    </div>
  </div>
</div>
<div class="container">
  <div class="row">
    <div class="col-12 col-md-8">
     <h3>For information about the project</h3>
        <p>Contact Cristina</p>
      <ul>
        <li>
            <strong>Tel: </strong>{{ site.data.contact.phone2 }}</li>
        <li><strong>Email: </strong><a href="mailto:{{ site.data.contact.email2 }}">
            {{ site.data.contact.email2 }}</a></li>
        {% if site.data.contact.address %}
        <li><strong>Adres: </strong>{{ site.data.contact.address }}</li>
        {% endif %}
      </ul>
     <h3>For information about activities</h3>
        <p>Contact Lennard</p>
      <ul>
        <li><strong>Email: </strong><a href="mailto:lennard@decreatievestem.be">
            lennard@decreatievestem.be</a></li>
        {% if site.data.contact.address %}
        <li><strong>Adres: </strong>{{ site.data.contact.address }}</li>
        {% endif %}
      </ul>
      <h4 class="mt-4">Office Hours</h4>
      <table class="table table-sm opening-hours-table">
        <tr>
          <td class="day font-weight-bold">Monday</td>
          <td class="opens">8:30</td>
          <td>-</td>
          <td class="closes">17:00</td>
        </tr>
        <tr>
          <td class="day font-weight-bold">Tuesday</td>
          <td class="opens">8:30</td>
          <td>-</td>
          <td class="closes">17:00</td>
        </tr>
        <tr>
          <td class="day font-weight-bold">Wednesday</td>
          <td class="opens">8:30</td>
          <td>-</td>
          <td class="closes">17:00</td>
        </tr>
        <tr>
          <td class="day font-weight-bold">Thursday</td>
          <td class="opens">8:30</td>
          <td>-</td>
          <td class="closes">17:00</td>
        </tr>
        <tr>
          <td class="day font-weight-bold">Friday</td>
          <td class="opens">8:30</td>
          <td>-</td>
          <td class="closes">17:00</td>
        </tr>
        <tr>
          <td class="day font-weight-bold">Saturday</td>
          <td class="opens">Closed</td>
          <td> </td>
          <td class="closes"> </td>
        </tr>
        <tr>
          <td class="day font-weight-bold">Sunday</td>
          <td class="opens">Closed</td>
          <td> </td>
          <td class="closes"> </td>
        </tr>
      </table>
    </div>
  </div>
</div>