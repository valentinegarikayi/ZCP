---
layout: splash
classes: wide
permalink: /pdfs/
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