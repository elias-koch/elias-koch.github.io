---
layout: page
permalink: /CV/
title: CV
nav: true
nav_order: 5
cv_pdf: CV_Koch.pdf
#description: This is a description of the page. You can modify it in '_pages/cv.md'. You can also change or remove the top pdf download button.
#toc:
#  sidebar: left
---
<h1 class="post-title">{{ page.title }}</h1>
{% if page.cv_pdf %}
  <a
    href="{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url }}"
    target="_blank"
    rel="noopener noreferrer"
    style="float: right; font-size: 1.5rem; color: red;"
    title="Download CV"
    download
  >
    <i class="fa-solid fa-file-pdf"></i>
  </a>
{% endif %}

<iframe src="/assets/pdf/CV_Koch.pdf" width="100%" height="700" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>