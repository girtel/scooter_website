---
widget: slider
weight: 1
active: false
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '500px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 5000

content:
  slides:
    - title: Insert some slider title here
      content: Insert some descripcion here and change the image.
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.3
        media: GIRTEL-FIRST.jpg
    - title: Insert some slider title here
      content: Insert some descripcion here and change the image. 
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.3
        media: GIRTEL-SECOND.jpg
    - title: Insert some slider title here
      content: Insert some descripcion here and change the image.
      align: right
      background:
        position: center
        color: '#555'
        brightness: 0.3
        media: GIRTEL-THIRD.jpg
      #link:
      #  icon: graduation-cap
      #  icon_pack: fas
      #  text: Join Us
      #  url: ../contact/
---
