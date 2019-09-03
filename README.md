# core-mem-pcb

PCB design files for 64-bit core memory board, in KiCad format. 

## Known issues

Pull-downs are needed on all of the {X,Y}n_EN_{F,R} FET gates to avoid shoot-through currents when the FPGA is unconfigured. The unconfigured FPGA pins have a substantial pull-up current that will turn on the drivers. 

![CoreMem PCB](core-mem-pcb.jpg?raw=true "PCB Photo")