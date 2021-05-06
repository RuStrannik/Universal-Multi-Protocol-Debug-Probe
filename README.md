# Universal Multi-Protocol Debug Probe

### Introduction
There are many ways to develop for bare metal.
Among them
- J-Link (JTAG)
- ST-LInk (SWD)
- DAP-Link (CMSIS-DAP)

Each requires special adapter, and most require proprietary software with multiple restrictions.
However, debugger is rather simple essential tool. 
I decided to create a compilation of available probes and thier cons and pros implemented on $2 BluePill board
