# Mixed Signal Hardware Design

![Picture-Front1](https://github.com/user-attachments/assets/5b0512be-3641-4ee9-8448-70b26a146de4)

 <br />
Image generated with Kicad 3D viewer.
  <br />
* You can download and check the project in Kicad.
* You can order this board (incl. SMT assembly) at https://www.jlcpcb.com. 
* Gerber and assembly files are in the relevant repo folders.

# With this project you can learn how to design:
* Switching voltage regulator and Low-dropout regulator
* STM32 MCU that using USB & SPI interface
* ADC / DAC integration
* Creating kalman filter for noise
* Also how to isolate the part with PCB cutouts for noise

NOTE:If you are an employer , you can check out my skills...

# Where can you use it?
* If you need many ADC or DAC readings, STM32 have limited number of ADC/DAC , such as if you design an SDD tester etc. 
* If you need more accurate readings, I used 14-Bit for ADC and 12-Bit for DAC but you can go 16-BIT or more...
* ADC => (ADC141S626 14-Bit, 50 kSPS to 250 kSPS)
* DAC => (DAC7563SDGSR 12-Bit, 0 to 3.3V)
* I used these parts because I had at my invertory, but I think you get the idea.
* If you need filtering for noise, kalman filters are so common in industry. Drones etc.<br />
Don't forget the test with LTSPICE.
<br />
<br />
* Take the project, adapt it , use it. I hope it helps you...

<br />
<br />
<br />
<br />
<br />

 **STM32F1 based ADC / DAC signal analyzer** <br />
 **Mixed Signal Hardware Design with Kicad** <br />
 **Created By Ceyhun Pempeci** <br />
