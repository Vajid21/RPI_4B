# RPI_4B
Reference for kernel bug fix spi_bug0
1)Load default kernel
2)compile the source code with spi as built in driver
3)Load the compiled driver
4)Add log to verify that compiled driver is loaded or not
5)Load the driver
6)test spi driver with spi cmds exposed to user space
7)kernel hang will come fix that issue
