# MicromouseRev.3-
CSUChico IEEE MicroMouse Code

IMPORTANT INFO FOR CONVERTING YOUR KIEL TO A C++ COMPILER
1. Open "Options for Target" menu (there is a button on the task bar that looks like a wand with a circuit)
2. Open the "C/C++" tab in that menu
3. On the bottom of that tab there are 3 lines you can fill in. The middle one labeled "Misc Controls" should say
   something like "--C99". Change this to "--cpp". 
4. Your compiler is now compiling C++. Congrats.


PINOUT FOR THE STM32L432KC EVAL BOARD

 1 *   USB   * 30
 2 *         * 29
 3 *         * 28
 4 *         * 27
 5 *         * 26
 6 *         * 25
 7 *         * 24
 8 *         * 23
 9 *         * 22
10 *         * 21
11 *         * 20
12 *         * 19
13 *         * 18
14 *         * 17
15 *         * 16

*******************************************************
# :NAME         :CURRENT USE              :TEST BENCH
*******************************************************
1 :PA9          :PWM motor A1             :LED 1
2 :PA10         :PWM motor A2             :LED 2
3 :RST          :                         :
4 :GND          :GND                      :GND
5 :PA12         :Button 1 input           :Button 1
6 :PB0          :encoder right A input    :Button 2
7 :PB7          :Switch 2 input           :Switch 1
8 :PB6          :switch 1 input           :Switch 2
9 :PB1          :encoder right B input    :Button 3
10:PC14         :                         :
11:PC15         :                         :
12:PA8          :PWM motor B1             :LED 3
13:PA11         :PWM motor B2             :LED 4
14:PB5          :encoder left B input     :Button 4
15:PB4          :encoder left A input     :Button 5
16:PB3          :                         :
17:3V3          :                         :
18:AREF         :                         :
19:PA0          :IR_BL                    :Potentiometer 5
20:PA1          :IR_FL                    :Potentiometer 4
21:PA3          :IR_M                     :Potentiometer 3
22:PA4          :IR_FR                    :Potentiometer 2
23:PA5          :IR_BR                    :Potentiometer 1
24:PA6          :LED 1                    :LED 6
25:PA7          :LED 2                    :LED 5
26:PA2          :LED 3                    : // NOTE: Is not connected, should be mapped to LED 7 
27:5V           :Power input              :Power Rail
28:RST          :                         :
29:GND          :GND                      :
30:VIN          :                         :


****************************************************************************************
                                 Testing Checklist
****************************************************************************************

PWM Output Works    :
ADC Input Checks out:
EXTI Interupts Occur:
DIP Switch Works    :
ADC readings from IR:
GPIO init works     :
Button works        :
LEDs work           :


