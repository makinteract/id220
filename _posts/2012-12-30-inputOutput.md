---
title: 'Input/Output'

layout: nil
---

### Blink

<p><iframe src="https://create.arduino.cc/editor/uaiti/f0b14f3d-f497-447b-b50a-f56bd629e991/preview?embed" height="510px" width="100%" frameborder="0"></iframe></p> 

### Input with internal PULLUP

* In this case the mode should be `INPUT_PULLUP`.
  
<p><iframe src="https://create.arduino.cc/editor/uaiti/f0b14f3d-f497-447b-b50a-f56bd629e991/preview?embed" height="510px" width="100%" frameborder="0"></iframe></p> 

An alternative to achieve the same result is to use the following code

```pinmode(pin, INPUT);
digitalWirte (pin, HIGH);```

