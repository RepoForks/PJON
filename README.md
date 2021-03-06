
![PJON](http://www.gioblu.com/PJON/PJON-github-header-tiny.png)
## PJON v8.1
PJON™ (Padded Jittering Operative Network) is an Arduino compatible, multi-master, multi-media communications bus system. It proposes a Standard, it is designed as a framework and implements a totally software-emulated network protocol stack that can be easily cross-compiled on many architectures like ATtiny, ATmega, ESP8266, Teensy, Raspberry Pi and Windows X86 machines. It is a valid tool to quickly and comprehensibly build a network of devices. Visit [wiki](https://github.com/gioblu/PJON/wiki) and [documentation](https://github.com/gioblu/PJON/wiki/Documentation) to know more about the PJON Standard.

[![Get PJON bus id](https://img.shields.io/badge/GET-PJON%20bus%20id-lightgrey.svg)](http://www.pjon.org/get-bus-id.php)
[![Video introduction](https://img.shields.io/badge/PJON-video%20introduction-blue.svg)](https://www.youtube.com/watch?v=vjc4ZF5own8)
[![Join the chat at https://gitter.im/gioblu/PJON](https://badges.gitter.im/gioblu/PJON.svg)](https://gitter.im/gioblu/PJON?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Donate](https://img.shields.io/badge/DONATE-Paypal-green.svg)](https://www.paypal.me/PJON)

#### Features
- Supports cross-compilation with [interfaces](interfaces) abstraction to system calls
- Multi-media support with the data link layer abstraction or [Strategy](strategies) framework
- Master-slave or multi-master [dynamic addressing](specification/PJON-dynamic-addressing-specification-v0.1.md)
- Configurable synchronous and/or asynchronous [acknowledgement](specification/PJON-protocol-acknowledge-specification-v0.1.md) of correct packet sending
- Configurable 2 level addressing (device and bus id) for scalable applications
- Configurable 1 or 2 bytes packet length (max 255 or 65535 bytes)
- Collision avoidance to enable multi-master capability
- Configurable CRC8 or CRC32 table-less cyclic redundancy check
- Packet manager to handle, track and if necessary retransmit a packet sending in background
- Optional ordered packet sending
- Error handling

#### PJON (Padded Jittering Operative Network) Protocol specification
- PJON [v1.1](specification/PJON-protocol-specification-v1.1.md)
- PJON Acknowledge [v0.1](specification/PJON-protocol-acknowledge-specification-v0.1.md)
- PJON Dynamic addressing [v0.1](specification/PJON-dynamic-addressing-specification-v0.1.md)

#### PJDL (Padded Jittering Data Link) specification
- PJDL [v1.1](strategies/SoftwareBitBang/specification/PJDL-specification-v1.1.md)
- PJDLR [v1.1](strategies/OverSampling/specification/PJDLR-specification-v1.1.md)

#### Compliant tools
- [ModuleInterface](https://github.com/fredilarsen/ModuleInterface) by Fred Larsen
- [PJON-piper](https://github.com/Girgitt/PJON-piper) by Zbigniew Zasieczny
- [PJON-python](https://github.com/Girgitt/PJON-python) by Zbigniew Zasieczny
- [saleae-pjon-protocol-analyzer](https://github.com/aperepel/saleae-pjon-protocol-analyzer) by Andrew Grande

PJON™ is a self-funded, no-profit open-source project created (in 2010) and maintained by Giovanni Blu Mitolo with the support of the internet community if you want to see the PJON project growing with a faster pace, consider a donation at the following link: https://www.paypal.me/PJON

PJON™ and its brand are unregistered trademarks, property of Giovanni Blu Mitolo gioscarab@gmail.com
