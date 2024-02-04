---
# Banner
banner:
  title: "KOMPASSI-Renderer"
  content: ""
  image: ""
  button:
    enable: true
    label: "Download"
    link: "https://github.com/leomccormack/kompassi-audio-com/releases"

# Features
features:
  - title: "An Advanced Spatial Audio Codec"
    image: "/images/kompassi_renderer_GUI.png"
    content: "Our most advanced parametric rendering algorithms all re-written and intergrated into a highly configurable encoder and decoder. The renderer plugin, which serves as a demo of the codec, currently supports:"
    bulletpoints:
      - "Ambisonics or tetrahedral/A-format microphone array recordings as input"
      - "Binaural playback"
      - "A SOFA loader, allowing for personalised binaural listening"
    button:
      enable: false
      label: "Find out more"
      link: "https://github.com/leomccormack/kompassi-audio-com/releases"

  - title: "Sound Scene Modifications"
    image: "/images/kompassi_translation.png"
    content: "Optionally, the spatial parameter stream produced by the encoder, may be intercepted and augmented before being passed onto the decoder. Currently, this is conducted by the renderer plugin to enable:"
    bulletpoints:
      - "Six-degrees of Freedom (6DoF) support (i.e., accounting for both listener head-rotations and translations away from the recording point)"
      - "Biasing the reproduction to give more prominence to either the ambience in the scene or directional sounds"
    button:
      enable: false
      label: ""
      link: ""
---
