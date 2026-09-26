---
layout: about
title: about
permalink: /
subtitle: PhD Student, Computer Science, <a href='https://tulane.edu'>Tulane University</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p><b>Uptown Campus</b></p>
    <p>411 Stanley Thomas Hall</p>
    <p>New Orleans, LA 70118</p>
    <p>&nbsp;</p>
    <p><b>Downtown Campus</b></p>
    <p>Triad, School of Medicine</p>
    <p>New Orleans, LA 70112</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

I am a PhD student in Computer Science at Tulane University, advised by [Dr. Jihun Hamm](https://www.cs.tulane.edu/~jhamm3/). My research focuses on Medical AI, Multimodal Deep Learning, Medical Imaging, and Generative AI, with an emphasis on modeling complex multimodal clinical data. I am particularly interested in medical world models that simulate disease trajectories, forecast future clinical states, and learn directly from medical imaging.

Before joining Tulane, I completed my MS in Computer Science at Old Dominion University, where I worked on genomic modeling and DNA foundation models. I earned my Bachelor's degree in Software Engineering from the National University of Sciences and Technology (NUST), Islamabad.

<style>
  .social {
    background-color: #f2f2f2;
    border-radius: 12px;
    padding: 2rem 1rem;
    margin-top: 1.5rem;
  }
  .social .contact-icons a i::before,
  .social .contact-note {
    color: #333333 !important;
  }

  /* Capitalize the "news" section heading */
  h2 a[href$="/news/"] {
    text-transform: capitalize;
  }

  /* News list: bold accent date column + colored accent bar per entry */
  .news table {
    border-collapse: separate;
    border-spacing: 0 0.9rem;
  }
  .news th {
    font-weight: 700;
    color: var(--global-theme-color);
    white-space: nowrap;
    padding-right: 1.5rem;
    vertical-align: top;
  }
  .news td {
    border-left: 3px solid var(--global-theme-color);
    padding-left: 1rem;
    vertical-align: top;
  }
</style>
