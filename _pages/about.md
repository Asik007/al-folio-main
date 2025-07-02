---
layout: about
title: about
permalink: /
subtitle: Research focused around...

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <div style="display: grid; width: 100%; grid-template-rows: auto auto; row-gap: 1em;">
    <h3 style="margin: 0;"><b>Principal Investigator</b></h3>
  
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 2em;">
    <div>
      <strong>David T. Eddington, PhD</strong><br>
      Professor of Bioengineering<br>
      Department of Bioengineering<br>
      University of Illinois Chicago<br><br>

      <h5 style="margin: 0 0 0.5em 0;"><b>Office</b></h5>
      201 SEO<br>
      851 S Morgan St.<br>
      Chicago, IL 60607<br>
      <a href="https://maps.google.com/?q=851+S+Morgan+St,+Chicago,+IL+60607" target="_blank">Google Maps</a>
    </div>
    <div>
      <strong>Lab Address:</strong><br>
      E-603 MSB<br>
      835 S Wolcott St.<br>
      Chicago, IL 60607<br>
      <a href="https://maps.google.com/?q=835+S+Wolcott+St,+Chicago,+IL+60607" target="_blank">Google Maps</a>
    </div>
    </div>
    </div>


    

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

# latest_posts:
#   enabled: true
#   scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
#   limit: 3 # leave blank to include all the blog posts

carousel:
  images:
    - src: "assets/img/1.jpg"
      # title: "Research Lab"
      # text: "Our state-of-the-art research facility"
      # position: "align-center-middle"
    - src: "assets/img/2.jpg"
      title: "Our Team"
      text: "Dedicated researchers and students"
    - src: "assets/img/3.jpg"
      title: "Equipment"
      text: "Advanced scientific instruments"
  
---


{% include carousel.liquid images=page.carousel.images height="500px" autoplay=true ken_burns=true %}

Some text about your lab and research...

Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.
