# W55RP20_Ethernet3

This repository enables the use of the Ethernet3 Library on W55RP20 using PIO SPI.

## Overview

This library is a combination of:
- [sstaub's Ethernet3](https://github.com/sstaub/Ethernet3)
- [jpiat's PIOSpi](https://github.com/jpiat/PIOSpi)

It allows you to use Ethernet functionality on the W55RP20 microcontroller by leveraging the PIO (Programmable I/O) peripheral for SPI communication.

## Usage

Instead of using `#include <Ethernet3>`, use:

```cpp
#include <W55RP20_Ethernet3.h>
```

## Credits

- [sstaub/Ethernet3](https://github.com/sstaub/Ethernet3) - Original Ethernet3 library
- [jpiat/PIOSpi](https://github.com/jpiat/PIOSpi) - PIO SPI implementation

## License

See [license.txt](license.txt) for license information.