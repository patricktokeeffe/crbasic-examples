## Model 205 Dual Beam Ozone Monitor

The model 205 is a research grade trace gas analyzer for ozone (O<sub>3</sub>).
It supports analog voltage output and RS-232 bidirectional communication for
configuration, diagnostics and improved data acquisition. 

### Wiring

The rear RS-232 port is a male DB9 jack wired as Data Terminal Equipment (DTE):

| Pin # | Signal                 | CR6 terminal |
|:-----:|------------------------|:------------:|
|   3   | data receive (input)   |      U5      |
|   2   | data transmit (output) |      U6      |
|   5   | signal ref/ground      |   &#x23da;   |

### Configuration

To use with the example program, the model 205 must satisfy the following
configuration:

* Baud rate of 19200: <kbd>Cfg</kbd>&rarr;<kbd>I/O</kbd>&rarr;<kbd>Bdr</kbd>&rarr;<kbd>19200</kbd>
* Temperature units of Celsius: <kbd>Cfg</kbd>&rarr;<kbd>Unt</kbd>&rarr;<kbd>T</kbd>&rarr;<kbd>C</kbd>
* Pressure units of millibars: <kbd>Cfg</kbd>&rarr;<kbd>Unt</kbd>&rarr;<kbd>P</kbd>&rarr;<kbd>mbar</kbd>
* *(recommended optional)* fast reporting rate: <kbd>Avg</kbd>&rarr;<kbd>10s</kbd>

