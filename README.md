# Mixed Signal Hardware 3D Model with Kicad

<img width="1010" alt="Picture" src="https://github.com/republicofmakers/MixedSignalHardware/assets/114834611/c065a555-b0a6-479c-8f63-004c0e68844c">

* You can download and check the project in Kicad.
* You can order this board (incl. SMT assembly) at https://www.jlcpcb.com. 
* Gerber and assembly files are in the relevant repo folders.

# With this project you can learn how to design:
* Switching voltage regulator and Low-dropout regulator
* STM32 MCU that using USB & SPI interface
* ADC / DAC intergration
* A kalman filter for noise
* Also how to isolate the part with PCB cutouts.

NOTE:If you are an employer , you can check out my skills...

# Where can you use it?
* If you need many ADC or DAC readings, STM32 have limited ADC/DAC converters, such as if you design an SDD tester etc. 
* If you need more accurate readings, I used 14-Bit for ADC and 12-Bit for DAC but you can go 16-BIT or more...
* ADC => (ADC141S626 14-Bit, 50 kSPS to 250 kSPS)
* DAC => (DAC7563SDGSR 12-Bit, 0 to 3.3V)
* I used these parts because I had at my invertory, but I think you get the idea.
* If you need filtering for noise, kalman filters are so common in industry. Drones etc.





* Take the project, adapt it , use it. I hope it helps you...












  STM32F1 based ADC / DAC signal analyzer <br />
  Mixed Signal Hardware Design with Kicad. <br />
  Created By Ceyhun Pempeci <br />
