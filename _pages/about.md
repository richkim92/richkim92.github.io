---
layout: about
title: about
permalink: /
#subtitle: <a href='#'>Apple Inc</a>. Cupertino. <a href="mailto:enthusiakk@gmail.com">enthusiakk@gmail.com</a>

profile:
  align: center
  image: headshot_kim.png
  image_circular: true # crops the image to make it circular
  address: >
    <p>enthusiakk@gmail.com</p>
  #more_info:
            #<p> </p> 

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page



announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts

images:
  slider: true

---

I'm a sensing design enginner at `Apple`, under Advanced Technology Group. <br>
I was previously a postdoctoral fellow at Stanford under [Bao Research Group](https://baogroup.stanford.edu), and joint fellow at [Stanford Human Performance Alliance](https://humanperformance.stanford.edu). 

I specialize in the co-development of integrated `AI` and `hardware`for `wearable human-machine interfaces`, with a focus on VR/AR and healthcare applications. My research focuses on: 


<ul style="line-height: 1.8; padding-left: 2em;">
  <li>AI algorithms for time-series signal processing, enabling motion prediction and language translation from physiological signals</li>
  <li>User and Task-agnostic AI models to enhance and enrich wearable experiences in augmented environments</li>
  <li>Wearable electronics development for capturing motion, health, and language signals, including EMG, IMU, ECG, and strain sensors</li>
</ul>


<!-- >
Write your biography here. This is first page Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.
-->

<div style="margin-top: 50px;"></div>

<swiper-container style="width: 100%; height: auto; margin-bottom: 20px;" autoplay-delay="3500" keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true" loop="true" autoplay-disable-on-interaction="false">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/main_research/6.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/main_research/5.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/main_research/4.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/main_research/3.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/main_research/2.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-autoplay-progress slot="container-end"></swiper-autoplay-progress>
</swiper-container>

