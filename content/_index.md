---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Subscribe to my newsletter
          icon: academicons/arxiv
          url: https://newsletter.easydata.dev/
        - text: Watch my new YouTube videos
          icon: brands/youtube
          url: https://www.youtube.com/channel/UCFublZ1-0cFcb6lKm_kVz0A
        - text: Connect with me on LinkedIn
          icon: brands/linkedin
          url: https://www.linkedin.com/in/czerwinskidev/
---
