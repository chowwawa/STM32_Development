This project contains three parts:
1. Voltage measurement by STM internal ADC (no calibration included)
1.1 Polling ADC 

2. Keystroke implementation (2 key for this version)
2.1 GPIO callback initiates 1ms timer 
2.2 Timer interrupt for dealing keystoke operations
2.3 Multi_Click operation
2.4 Button idle period: 25ms

3. FreeRTOS 
3.1 continuous + periodic task (vTaskDelayUntil)
3.2 Task + interrupt 