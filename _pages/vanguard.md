---
layout: splash
classes: wide
permalink: /vanguard/
title: "Vanguard Archive"
header:   
  overlay_image: /assets/images/harare-banner2.jpg
  text: "Vanguard Archive"
---

## Links to documents in pdf format

<table>
  <thead>
    <tr>
      <th>Title</th>
      <th>Description</th>
      <th>Link</th>
    </tr>
  </thead>
  <tbody>
    {% for pdf in site.pdfs %}
    <tr>
      <td>{{ pdf.title }}</td>
      <td>{{ pdf.description }}</td>
      <td><a href="{{ pdf.file }}" target="_blank">Download</a></td>
    </tr>
    {% endfor %}
  </tbody>
</table>

## About

The official journal of the Zimbabwe Communist Party is Vanguard. The object of Vanguard is to educate, agitate and organize the Party membership and those close to it. Its duty is to reflect the collective view of the Party as determined by the Founding Conference, future Congresses and the decisions of the leading organs. Views at variance with the collective decisions may, at times, be expressed through signed articles. 

Articles from other Communist Parties, other progressive organizations or even, on occasions, from reactionary sources, may be published so long as: 
1. The article is informative and thus assists our cadres in their political understanding. 
2. The origin of the article is clearly indicated. 