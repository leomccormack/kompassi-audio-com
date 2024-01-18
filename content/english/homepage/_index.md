---
# Banner
banner:
  title: "Kompassi Renderer"
  content: ""
  image: "/images/kompassi_banner.png"
  button:
    enable: true
    label: "Download"
    link: "https://github.com/zeon-studio/hugoplate"

# Features
features:
  - title: "Advanced Spatial Audio Codec"
    image: "/images/kompassi_renderer_GUI.png"
    content: "An spatial sound scene reproduction plugin:"
    bulletpoints:
      - "Supports Ambisonics and arbitrary microphone array recordings as input"
      - "The plugin can output signals for binaural or arbitrary loudspeaker array based listening"
      - "Processing is separated into dedicated encoder and decoder blocks"  
      - "Supports loading SOFA files containing head-related impulse responses (HRIRs/HRTFs) for personalised headphone listening."
    button:
      enable: false
      label: "Find out more"
      link: "https://leomccormack.github.io/sparta-site/"

  - title: "Highly Customisable"
    image: "/images/kompassi_renderer_GUI_adv.png"
    content: "Many of the internal parameters can be exposed to the user in the advanced tab:"
    bulletpoints:
      - "Supports loading SOFA files containing microphone array impulse responses, if using a custom array configuration for which there is no preset in the plugin."
      - "hhh"
    button:
      enable: false
      label: "Get Started Now"
      link: "https://github.com/zeon-studio/hugoplate"

  - title: "Supports Spatial Audio Effects"
    image: "/images/kompassi_translation.png"
    content: "Due to the decoupling of the encoder and decoder, many spatial audio effects can be achieved:"
    bulletpoints:
      - "Spatial metadata outputted by the encoder can be intercepted and modified prior to reproducing the scene (e.g. for enabling 3DoF/6DoF support)" 
    button:
      enable: false
      label: ""
      link: ""
---
