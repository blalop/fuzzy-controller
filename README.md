# fuzzy-controller
The aim of this practice was to implement a fuzzy control system in an Arduino Uno. We choose [eFFL](https://github.com/zerokol/eFLL).

## Fuzzy things
The inputs are an ultrasonic sensor and a LDR. The output is a LED. We define the variables of distance, ldr and brightness. The fuzzy rules are:

if distance is small and ldr is low then brightness is high
if distance is small and ldr is high then brightness is off
if distance is mid then brightness is midb
if distance is big then brightness is low
if distance is verybig then brightness is off
