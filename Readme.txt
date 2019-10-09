This project contains three parts:
1. Voltage measurement by STM internal ADC (no calibration included)
1.1 Polling ADC + PWM write 
1.2 Change LED brightness with respect to value measured 

2. Keystroke implementation (2 key for this version)
2.1 GPIO callback initiates 1ms timer 
2.2 Timer interrupt for dealing keystoke operations
2.3 Multi_Click operation
2.4 Button idle period: 25ms

3. FreeRTOS 
3.1 Periodic task (vTaskDelayUntil)
3.2 Suspended task + interrupt 
3.2 Continuous Task
 