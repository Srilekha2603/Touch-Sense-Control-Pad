# Touch-Sense-Control-Pad
STM32 FreeRTOS project controlling LEDs using multiple tasks. Buttons trigger events via interrupts and a timer. Event groups activate one task while suspending others, with a high-priority emergency task. Mutex ensures safe GPIO access, and UART displays task status.
