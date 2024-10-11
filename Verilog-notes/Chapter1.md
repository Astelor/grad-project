# Chapter 1, Overview

```
[Digital system designing methods]
                    |
        +-----------+-----------+
        |                       |
[Fully Customized IC]  [Semi Customized IC]
                                |
                +---------------+---+-----------+
                |                   |           |
            [Standard Cells]  [Gate Array]  [FPGA/PLD]

```

# Fully Customized IC

- Designed to fit perfectly to the customer's needs.
- Very manually optimized.
- Takes more time to design.
- Less widely implemented.
  - Time and labor = money
  - money = ouch

# Semi Customized IC

Including 3 categories:
1. `Standard Cells`
2. Mask Programmable Gate Array (`MPGA`) aka `Gate Array` (GA)
3. Field Programmable Gate Array (`FPGA`)

- `Standard Cells` and `Gate Array` can be customized by users but the finished IC *needs to be produced by IC factories*.
  - The prototype IC takes about 2~3 months to produce.
  - Not good for shortening design life cycles.
- `FPGA` is very reliant to CADs that came with it.
  - Used in prototyping.
- If circuits require larger surface area (run faster), `Fully Customized IC` will be more cost-effective

> Why SRAM Based, Antifuse, and Flash Based FPGA??
> https://www.electronicproducts.com/comparing-flash-and-sram-based-fpgas/

> Aster: the following are designing methods, come back later