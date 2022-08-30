# Dual CR2032 Retro Battery

![PCB image](https://github.com/chadr/Dual-CR2032-Retro-Battery/blob/main/img/dual_cr2032_pcb.jpg)

This is a CMOS backup power source for vintage computers that use a standard dupont-style header for external batteries.

## Setting Output Voltage

Each CR2032 battery produces 3V. They are arranged in series for a total of 6V. The two 1N4148 diodes are in a series arrangement. They provide about a 0.6V drop each. Use zero-ohm jumper links in place of the diode(s) to adjust output voltage. For example, one diode and one jumper link would yield an output voltage of about 5.4V. 
