# Introduction #

The warning "avrdude: please define PAGEL and BS2 signals in the configuration file" is harmless and can be ignored.


# Details #

When using the STK500v1 protocol (e.g. ArduinoISP), avrdude loads and validates the PAGEL and BS2 parameters.  These parameters are only relevant to Parallel Programming.  They do not apply when using the STK500v1 protocol.  The warning is harmless and can be ignored.