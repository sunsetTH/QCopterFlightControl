QCopterFC IMU Example
========
* Author  : [Hom](http://about.me/Hom)
* Update  : 2014/06/10

Description
========
QCopterFC IMU 的範例程式，以 500Hz 讀取感測器，並透過 RS232 將資料傳送至 PC 端的 VisualScope 做顯示。

Hardware
========
* LED  
PC13 - LED_B  
PC14 - LED_G  
PC15 - LED_R  

* KEY  
PB2  - KEY  

* UART  
PB10 - UART Tx  
PB11 - UART Rx  
> UARTx = USART3  
> BaudRate = 9600  
> ByteSize = 8  
> StopBits = 1  
> Parity = 'N'  
> HardwareFlowControl = None  

* SPI  
PB13 - SPI_SCK  
PB14 - SPI_SDO  
PB15 - SPI_SDI  
PC2  - SPI_CSM  
> SPIx = SPI2  
> Dir = 2Lines_FullDuplex  
> Mode = Slave  
> CPOL = High  
> CPHA = 2Edge  
> FirstBit = MSB  
> DataSize = 8 bits  
> BaudRate = Prescaler_256  
