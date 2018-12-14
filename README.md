# stm32f1_ds1307

Important procedure : 
1. Initialize with CubeMX : 
   - RCC, SYS
   - I2C with RX Interrupt
   - EXTI line to load default date time into DS1307
   - Config NVIC
2. Include "ds1307.h" and add existing "ds1307.c".
3. Create variable with DateTime_TypeDef in "main.c" and call functions.

Figure out more in included CubeMX and KeilC project.
