# Design-6-Labs
## Labs Completed by *Nate Dawson*

---

**Lab 1**
*GHDL and GTKWave*
- In this lab I downloaded the GHDL and GTKWAVE software to describe and simulate hardware examples
- This was completed with the tutorial by [Nerdy Dave](https://youtu.be/H2GyAIYwZbw?si=BPTJ1yH9rXGcyoHP)

1. Half Adder Example
   - I downloaded the half adder and half adder test bench vdhl code from the resources
   - These were opened through notepad to compile the code
   - There were no errors during this process
   - Through the windows terminal the following commands launched the compiled code through *GTKWAVE*
     
```
$ ghdl -a ha.vhdl
$ ghdl -a ha_tb.vhdl
$ ghdl -e ha_tb
$ ghdl -r ha_tb --vcd=ha.vcd
ha_tb.vhdl:47:5:@5ns:(assertion error): Reached end of test
$ gtkwave ha.vcd
```
![ha_results](ha_results.png)     

2. D Flip-Flop Example
   - For the second example I chose to use the D Flip-Flop
   - The codes were accessed and compiled using the same method
   - There were no errors during this process
   - Through the windows terminal the following commands launched the compiled code through *GTKWAVE*
```
$ ghdl -a dff.vhdl
$ ghdl -a dff_tb.vhdl
$ ghdl -e dff_tb
$ ghdl -r dff_tb --vcd=dff.vcd
$ gtkwave dff.vcd
```
![dff_results](dff_results.png)     



