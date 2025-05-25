# BQ25703A
Define all the registers for the [BQ25703A component](https://www.ti.com/product/BQ25703A).

This repository is platform independant code.

You must declare an implementation of the I2C functions :
- i2c_readDatam: read some data from the I2C line
- i2c_writeData: write some data to the I2C line


Based on [LawMate implementation](https://github.com/Lawmate/BQ25703A/tree/master), with data read & write corrections.