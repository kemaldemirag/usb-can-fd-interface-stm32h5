# PROJECT-02 Architecture — Initial

**Architecture status:** OPEN / not yet verified.

## Candidate chain

```
USB-C + SWD -> STM32 -> FDCAN A/B -> Transceiver A/B -> CAN-A / CAN-B
```

## Must investigate
- MCU peripheral capability and pin mapping
- USB device implementation and USB-C CC implementation
- Transceiver voltage compatibility
- CAN FD data rates
- Selectable termination
- ESD / common-mode behavior and connector strategy
- Galvanic isolation tradeoff
- Protected voltage measurement
