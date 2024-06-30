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
        - text: Partial Solutions to Exercises from Nelsen's Copula Book (2nd Edition)
          icon: academicons/obp
          url: uploads/intro_copula.pdf
        - text: An Excellent Chinese TV Series: Ming Dynasty 1566
          icon: fab/imbd
          url: https://www.imdb.com/title/tt6424870/ 
---
