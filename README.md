# Digital Scanner (mpi 2021 Spring)
This repository contains all my files for the Digital Scanner project. This project was my semester project for the Microprocessors and Interfacing Course 2021 (Spring).  
>The problem statement was to design a microprocessor based scanner which will scan a black and white image and store it as binary data.  

The project was not physically implemented, however all connections and pinouts have been provided and all market available chips alone have been used. The 8086 is encoded using assembly language code. The simulation is done in _Proteus 7_. Emu 8086 was used to generate the necessary _.bin_ files for simulation.  
</br>
_Proteus 7_ has certain limitations and the project could not be simulated exactly according to the hardware design and hence certain changes have been made for the _Proteus_ simulation.

## File Description:  
1. **Digital Scanner Project Report.pdf** : Detailed description of components used, logic, methodology
2. **Hardware Design and Pinouts.pdf** : Complete hardware design with connections to all the chips used
3. **scanner_code.asm** : Source Code(exactly according to the hardware design) 
4. **scanner.dsn** : _Proteus_ file  
5. **scanner_emu.asm** : Source Code(considering _Proteus_ limitations) 
6. **scanner_emu.bin** : Binary file generated after assembly using EMU8086 (_scanner_emu.asm_ was used to generate _.bin_ file)
7. **Manuals:**  
    contains the datasheets of all the components used in the hardware design  
    
    - ADC0808 (analog to digital converter)
    - FDS010 (Si Photodiode)
    - NEMA17 stepper motor
    - ULN2003A (7 darlington pairs)
    - LM 324 (Quad Operational Amplifiers)
    - AlInGaP LED
