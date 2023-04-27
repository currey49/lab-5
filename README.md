# lab-5

MATTHEW CURREY
3/23/2023


Lab 5:


Please fill in the blanks in the following code. Please see me or use the TI resource explorer along with the data sheet and user manual for for help.
/**********************************
 * ADC Controlled LED
 *
 * Example which controls the LED Brightness via PWM which is varied based on an ADC Reading
 *
 *
 * Change Log:
 *  - Changed LED Pin to 6.0 to allow for control by Timer3B module
 *  - Using Pin 1.1 for being connected to Grove Connector Analog Channel 1
 *
 *
 * Pin Map:
 *               MSP430FR2355
 *            -----------------
 *        /|\.  |                             |
 *         |.    |                               |
 *         --   |RST                       |
 *               |                               |
 *       >---|P1.1/A1      P6.0|--> LED --> Wired to LED 2 through external wire to P6.6
 *
 *       ****WARNING****
 *       Please disconnect J11 and connect to Pin 6.0 to the lower part of the jumper
 *
 *       ____
 *      | NC | <-- Keep this Disconnected
 *      |----  |
 *      | **    | <-- Connect to this part of J11
 *      |____. |
 *
 *
 * Peripherals Used:
 *      ADC12 - Channel 1 (Pin 1.1)
 *      GPIO - Pin 6.0
 *      TimerB0 - UP Mode, CCR1 for PWM Control, controls Pin 6.0
 */
