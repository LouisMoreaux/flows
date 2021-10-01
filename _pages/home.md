---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
  actions:
    - label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Try now'
      url: "https://apex.oracle.com/pls/apex/mtflows/r/flowsforapex"
      target: "_blank"
    - label: '<i class="fas fa-cloud-download-alt" aria-hidden="true" style="padding-right: 5px;"></i>Download'
      url: "https://github.com/mt-ag/apex-flowsforapex/releases/download/v21.1/FLOWSFORAPEX_APEX201_984339_UTF8.sql"
    - label: "Learn more"
      url: "/docs/getting-started"
excerpt: >
  Oracle APEX extension for BPMN based workflows<br />
  <small><a href="https://github.com/mt-ag/apex-flowsforapex/releases/tag/v21.1" target="_blank">Latest release v21.1</a></small>
row1:
  - title: "100% Open Source"
    excerpt: "Flows for APEX is open source. You can share and/or modify it, always under the adherence of the MIT-license. Flows for APEX ist cost free and was created by passionate developers."
    url: "https://github.com/mt-ag/apex-flowsforapex"
    target: "_blank"
    btn_class: "btn--info"
    btn_label: '<i class="fab fa-github" aria-hidden="true" style="padding-right: 5px;"></i>Browse code'
row2:
  - title: "Expense Claims Sample App"
    excerpt: 'Test Flows for APEX with the sample app "Expense Claims", which is also included in the software.'
    url: "https://apex.oracle.com/pls/apex/mtflows/r/flowsforapexdemo"
    target: "_blank"
    btn_class: "btn--info"
    btn_label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Try now'
    image_path: "/assets/images/demo-app.png"
---
{% include feature_row id="row1" type="center"%}
{% include feature_row id="row2" type="left"%}