---
title: 'Input/Output'

layout: nil
---

### Blink example

* Set the mode of the pin using the `pinMode(pinNumber, mode)` function. In this case the mode is `OUTPUT`.

<p><iframe src="https://create.arduino.cc/editor/andreabianchi/35da6784-f487-4488-95e4-d84bcd37fbe4/preview?embed " height="510px" width="100%"  frameborder="0"></iframe></p>


### Input and output examples

<p><iframe src="https://create.arduino.cc/editor/andreabianchi/f6c9af64-b212-43e7-88ee-8adc7b5bdabc/preview?embed" height="510px" width="100%"  frameborder="0"></iframe></p>

* The pinMode function is not needed in the **analog** case.
* For input you should use either an internal (e.g., pinMode set to `INPUT_PULLUP`) or external pull-up resistor.

An alternative to pull-up the internal resistor is to use the following code

```pinmode(pin, INPUT);
digitalWirte (pin, HIGH);
```

### Exercise

![schematics](images/w5_ex1.jpg)

