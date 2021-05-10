## **Introduction**

This repository is comprising of adder circuits, both combinational as well as sequential along with a full adder made up off two half adders.

## **Pre-requisites**

- [Logisim](http://www.cburch.com/logisim/download.html) Software
- [Icarus Verilog](http://bleyer.org/icarus/) Simulator
- [GitHub](https://github.com/)

## **Instructor**

- [Zeeshan Rafique](https://github.com/zeeshanrafique23)

## **Implementation** ##

First, a simple adder circuit has been implemented to have hands on practice on verilog. To get better understanding, both the combinational as well sequential circuit has been implemented. Then, by using the concept of digital logic design circuits of half adder and full adder have been created on logisim software. Lastly, in light of both the softwares, two half adders are used to make a full adder on the verilog software.

### ***Full Adder*** ###

This circuit, as the name describes is the modified form of half adder that is actually been implemented by two half adders allowing three inputs and displays complete result in two bit numbers.

## **Execution** ##

### ***Verilog Terminal*** ###

When the code has been written, then its time to execute it and check the result it on another simulator i.e. gtkwave which displays the waveforms. Gtkwave is basically the part of Icarus Verilog comes along with the package when downloaded.

_Since, all the working has been done on ubantu.

```
iverilog -o file_name_tb.vvp file_name_tb.v
vvp file_name_tb.vvp
gtkwave
```

### ***Gtkwave Simulator*** ###

When the window of gtkwave appears, select the vcd file by:
File -> Open New Tab -> file_name_tb.vcd

Now, select all the inputs and outputs to check the waveform and analyse the results.
