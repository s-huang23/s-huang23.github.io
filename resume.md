---
layout: default
title: Resume
wide: true
---

{% assign resume_file = site.static_files | where: "path", "/assets/files/Si-Qin-Huang-Resume.pdf" | first %}

<div class="resume-page" markdown="1">

# Resume

<p class="resume-updated">
  <span class="eyebrow">Resume last updated</span>
  {{ resume_file.modified_time | date: "%B %Y" }}
</p>

<a class="download-btn" href="{{ '/assets/files/Si-Qin-Huang-Resume.pdf' | relative_url }}" download>Download PDF</a>

<div class="resume-embed">
  <iframe src="{{ '/assets/files/Si-Qin-Huang-Resume.pdf' | relative_url }}#view=FitH" title="Resume"></iframe>
</div>

</div>
