MODBUS-RTU STM32F303 NANOMODBUS 

This repository contains an efficient Modbus RTU protocol implementation for the STM32F303 microcontroller, 
leveraging the built-in Hardware Receiver Timeout (RTO) peripheral of the USART.

Key Features

• ⚡ Hardware Receiver Timeout (RTO): Native detection of Modbus RTU end-of-frame boundaries via USART_CR2->RTOEN and USART_CR1->RTOIE registers.

• 🪶 Powered by NanoModbus: Integrates the popular, compact, and highly compliant nanomodbus library to handle protocol parsing and code execution.

• 🛡️ Resource Efficient: Frees up microcontroller Timers; all silent interval timing happens autonomously within the USART hardware block.
