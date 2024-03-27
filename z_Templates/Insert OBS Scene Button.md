---
next_scene: _scene
---
```meta-bind-button
label: Change to _scene
hidden: false
class: ""
tooltip: ''
id: _btn
style: default
actions:
  - type: updateMetadata
    bindTarget: next_scene
    evaluate: false
    value: _scene
  - type: sleep
    ms: 200
  - type: js
    file: z_js/obs-button.js
```
