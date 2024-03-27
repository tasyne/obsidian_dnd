---
next_scene: night_scene
---

[asdf](dnd://testing_this)

```meta-bind-button
label: Change to derg_scene
hidden: false
class: ""
tooltip: ''
id: derg_btn
style: default
actions:
  - type: updateMetadata
    bindTarget: next_scene
    evaluate: false
    value: derg_scene
  - type: sleep
    ms: 200
  - type: js
    file: z_js/obs-button.js
```
```meta-bind-button
label: Change to night_scene
hidden: false
class: ""
tooltip: ''
id: night_btn
style: default
actions:
  - type: updateMetadata
    bindTarget: next_scene
    evaluate: false
    value: night_scene
  - type: sleep
    ms: 200
  - type: js
    file: z_js/obs-button.js
```


