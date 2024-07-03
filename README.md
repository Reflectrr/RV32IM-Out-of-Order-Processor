# RV32IM Out-of-Order Processor

This repo contains our design of an out-of-order RISC-V processor using Tomasulo's organization. It features the basic components of Tomasulo's organization:
- Instruction Queue
- Reservation Stations
- Common Data Bus
- Reorder Buffer

In addition, we added a series of advanced features to boost the performance further:
- Banked Memory with Instruction/Data-Cache Subsystem
- GShare Branch Predictor
- Dadda Multiplier
- Memory Disambiguation (out-of-order load/in-order store)
- Sequential Divider (Synopsys IP)

The processor can be run at 444 MHz with an area of 197753 μm^2 and an average of 35 mW power usage.

## Credit
I want to thank my teammates Albert Wang and Cameron Choy. This project wouldn't be possible without them. Together we created this spectacular processor.
