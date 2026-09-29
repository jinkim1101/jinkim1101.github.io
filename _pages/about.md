---
layout: about
title: about
permalink: /
nav: false
nav_order: 2

profile:
  align: right
  image: jin_kim_headshot.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Electrical Engineering</p>
    <p>University of California, Los Angeles (UCLA)</p>
    <p><a href="mailto:jinkim04@ucla.edu">jinkim04@ucla.edu</a></p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # contact links are placed below the bio, before projects

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  @media (min-width: 992px) {
    .post .profile.float-right {
      margin-left: 2.5rem;
    }
  }
</style>

## Hi, I’m Jin Kim

I’m a second-year Electrical Engineering student at UCLA, with a growing interest in robotics. At UCLA’s Human–Computer Interaction Lab, I worked on an AI-assisted interface that helps researchers plan experiments. This past summer, I studied soft tactile sensors for robotics at Seoul National University’s Soft Robotics & Bionics Lab. Outside research, I’ve worked on startup consulting projects and explored venture capital through campus organizations and internships. I’m interested in building robotics technology and learning what it takes to bring it into the world. 

## Interests

I’m passionate about robotics and embedded systems: combining electronics, software, and physical design to make machines work. I’m also starting to explore power electronics and hardware–software co-design. You can find some of my projects below.

<div class="social">
  <div class="contact-icons">{% social_links %}</div>
</div>

<h2 style="margin-top: 3rem;">Projects</h2>

### [Inflatable Magnetic Soft Tactile Sensor]({{ '/projects/1_project/' | relative_url }})

Soft tactile sensing for force, orientation, and contact-state estimation.
