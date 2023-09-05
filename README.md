This version of the je1rav code can be built simple with PlatformIO
which doesnt support the Seeed Xiao module but supports the standard RP2040 Pico.

That requires a moduled si5351 library as the Pico uses the i2c0 bus and the Seeed module uses i2c1 bus and pins.

There are some changes to improve the received audio and to control chips on the ADX module rather 
than the QP-7C module.
