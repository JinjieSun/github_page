---
layout: about
title: about
permalink: /
subtitle: 孙进杰 | M.Sc. in Computer Science at the University of Toronto | Robot Learning and Surgical Robotics

# Enable these two lines if you want "about" to appear in the navigation bar.
# nav: true
# nav_order: 1

profile:
  align: right
  image: my_image.jpg
  image_circular: true
  more_info: >
    <p>Toronto, Canada</p>

selected_papers: true
social: true

announcements:
  enabled: false
  scrollable: false
  limit: 0

latest_posts:
  enabled: false
  scrollable: false
  limit: 0
---

I recently completed my M.Sc. in Computer Science at the University of Toronto, supervised by
Prof. Jessica Burgner-Kahrs and Prof. Lueder A. Kahrs. My research focuses on robot learning,
vision-based control, imitation learning, diffusion policies, and sim-to-real transfer for
autonomous surgical robotics. I received my B.Sc. in Computer Science from the University of
Toronto with High Distinction.

My research experience spans the Continuum Robotics Laboratory (CRL) and the Medical Computer
Vision and Robotics Laboratory (MedCVR). I develop complete robotic systems spanning simulation,
synthetic data generation, visual perception, policy learning, ROS 2 integration, and real-world
evaluation. I am interested in robotics and embodied AI roles involving visuomotor learning,
sim-to-real transfer, and deployment on physical systems.

## Selected projects

<div class="row mb-4">
  <div class="col-12">
    <div class="card hoverable">
      <div class="row g-0">
        <div class="col-md-5">
          <video class="w-100 h-100" style="object-fit: cover" controls muted playsinline preload="metadata">
            <source src="{{ '/assets/video/diffusion-policy-demo.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support embedded video.
          </video>
        </div>
        <div class="col-md-7">
          <div class="card-body">
            <h3 class="card-title">Privileged Multimodal Distillation for RGB-Only Diffusion Policy</h3>
            <p class="text-muted"><strong>Research project · 2025–2026</strong></p>
            <p class="card-text">
              An RGB-only diffusion policy for autonomous liquid removal, trained by distilling
              privileged segmentation and depth information from multimodal teacher policies. The
              project studies robustness across tissue scenes, liquid visibility conditions, and
              the simulation-to-real transition.
            </p>
            <p class="card-text">
              <strong>Contributions:</strong> teacher-student policy design, distillation
              objectives, Unity data generation, LeRobot training, ROS 2 deployment, and
              physical-robot evaluation.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="row mb-4">
  <div class="col-12">
    <div class="card hoverable">
      <div class="row g-0">
        <div class="col-md-7">
          <div class="card-body">
            <h3 class="card-title">Vision-Based Autonomous Liquid Removal with a Continuum Robot</h3>
            <div class="col-md-5 d-flex align-items-center">
            <video
              class="w-100"
              style="width: 100%; height: auto; object-fit: contain; object-position: center; background-color: #000"
              controls
              muted
              playsinline
              preload="metadata"
            >
              <source src="{{ '/assets/video/diffusion-policy-demo.mp4' | relative_url }}" type="video/mp4">
              Your browser does not support embedded video.
            </video>
          </div>
            <p class="text-muted"><strong>Published at CRV 2025</strong></p>
            <p class="card-text">
              A vision-based autonomous liquid-removal system for a concentric tube continuum
              robot, combining image-based targeting, differential inverse kinematics, and
              lookup-table recovery in simulation and on a physical platform.
            </p>
            <p class="card-text">
              <strong>Result:</strong> more than 99% liquid removal across 32 simulation trials,
              with 0.1 g or less typically remaining in the physical experiments.
            </p>
            <a href="https://crv.pubpub.org/pub/aw3sejjr">Paper</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<p class="text-right">
  <a href="{{ '/projects/' | relative_url }}">View all projects →</a>
</p>

