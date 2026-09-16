# PROJECT-02 Requirement Inventory — INITIAL

Canonical prefix: `CAN-`
Allowed statuses: OPEN, IN_PROGRESS, IMPLEMENTED, VERIFIED, BLOCKED, NOT_APPLICABLE. VERIFIED requires evidence.

| ID | Title | Requirement | Source | Verification | Status |
|---|---|---|---|---|---|
| CAN-001 | MCU | Use STM32H573RIT6 only after peripheral capability and package/pin feasibility are independently verified. | JOB-02 | Reference manual/datasheet evidence | OPEN |
| CAN-002 | Dual CAN FD | Provide two independent CAN/CAN FD channels. | JOB-02 | Peripheral/pin mapping + schematic evidence + later traffic logs | OPEN |
| CAN-003 | USB-C | Provide USB-C device connectivity with correct CC implementation. | JOB-02 | Schematic review + USB evidence when available | OPEN |
| CAN-004 | USB/UART | Provide USB and UART engineering/debug interfaces as defined by final architecture. | JOB-02 | Interface control review | OPEN |
| CAN-005 | SWD | Provide SWD programming/debug access. | JOB-02 | Schematic/pin review | OPEN |
| CAN-006 | Termination | Define selectable 120-ohm termination per channel where architecture requires it. | Engineering requirement derived from CAN network needs | Schematic review + resistance/traffic evidence later | OPEN |
| CAN-007 | Protection | Address ESD, common-mode behavior and connector protection. | JOB-02 + engineering derivation | Protection design review | OPEN |
| CAN-008 | Voltage Measurement | Provide protected voltage measurement with scaling/limits documented. | JOB-02 | Calculation + schematic review | OPEN |
| CAN-009 | Board Constraint | Treat approximately 80 x 50 mm and two-layer construction as targets, not verified constraints, until layout feasibility is shown. | JOB-02 | Layout evidence | OPEN |
| CAN-010 | Isolation Decision | Record galvanic isolation as an explicit architectural tradeoff/decision rather than assuming it. | Handoff investigation list | Decision register | OPEN |
