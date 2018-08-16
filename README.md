# STM32_Flash
This project was made based on STM32CubeMx and built for STM32 Nucleo board, NUCLEO-L031K6.

The compiler IDE is Keil 5.

Please follow the intructions to setup your hardware environment. 

If using low voltage flash, such as SST26WF040B (1.8V), please modify the power source in Nucleo board.

The Nucleo board default operation voltage is 3.3V.

  remove SB14

  apply 1.8v to jp1. make sure all VDD. AVDD, +3V3 are 1.8V
  
Connect flash to Nucleo board.

  pin1 (CE#) to PA4
  
  pin2 (SO) to PA6
  
  pin3 (WP#) 10K pull high to 1.8v
  
  pin4 (VSS) to gnd
  
  pin5 SI to PA7
  
  pin6 SCK to PA5
  
  pin7 HOLD 10K pull high to 1.8V
  
  pin8 to 1.8V
  
Have Fun...

Patrick Lin.

2018/08/15

Taipei, Taiwan
