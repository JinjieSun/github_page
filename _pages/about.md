---
layout: about
title: about
permalink: /
subtitle: 孙进杰 | M.Sc. in Computer Science at the University of Toronto | Robot Learning and Surgical Robotics
# nav: true
# nav_order: 1
profile:
  align: right
  image: my_image.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>Toronto, Canada</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

selected_projects: true
announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts

---

I recently completed my M.Sc. in Computer Science at the University of Toronto, supervised by
Prof. Jessica Burgner-Kahrs and Prof. Lueder A. Kahrs. My research focuses on robot learning,
vision-based control, imitation learning, diffusion policies, and sim-to-real transfer for
autonomous surgical robotics.

I develop complete robotic systems spanning simulation, synthetic data generation, visual
perception, policy learning, ROS 2 integration, and real-world evaluation. I am interested in
robotics and embodied AI roles involving visuomotor learning, sim-to-real transfer, and deployment
on physical systems.

Selected projects

Privileged Multimodal Distillation for RGB-Only Diffusion Policy

Ongoing research · 2025–2026

<!-- Place the video at assets/video/diffusion-policy-demo.mp4. -->

<video width="100%" controls muted playsinline preload="metadata">
  <source src="{{ '/assets/video/diffusion-policy-demo.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support embedded video.
</video>

<!-- An RGB-only diffusion policy for autonomous liquid removal, trained through privileged
multimodal distillation from teachers with access to segmentation and depth during training. The
project studies whether privileged visual representations improve robustness across tissue scenes,
liquid visibility conditions, and the simulation-to-real transition.

My contributions: teacher-student policy design, distillation objectives, Unity data pipeline,
PyTorch and LeRobot training, ROS 2 deployment, and simulation and physical-robot evaluation. -->

[View all projects]({{ '/projects/' | relative_url }})