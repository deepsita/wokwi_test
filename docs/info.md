<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The circuit is a full adder with IN1,IN2,CIN inpus and sum, cout as outputs which follow the below logic.
    sum=IN1 ^ IN2 ^ CIN
    cout = (IN1&IN2)|(IN1&CIN)|(CIN&IN2)

| IN1 | IN2 | CIN | sum | cout |
|-----|-----|-----|-----|------|
| 0   | 0   | 0   | 0   | 0    |
| 0   | 0   | 1   | 1   | 0    |
| 0   | 1   | 0   | 1   | 0    |
| 0   | 1   | 1   | 1   | 1    |
| 1   | 0   | 0   | 1   | 0    |
| 1   | 0   | 1   | 0   | 1    |
| 1   | 1   | 0   | 0   | 1    |
| 1   | 1   | 1   | 1   | 1    |

## How to test

Trigger the inputs according to the truth table to observe the output changes.

## External hardware

NA
