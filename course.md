```mermaid
graph LR
    ACC5(Accounting F5)
    ACC6(Accounting F6)
    ART5(Art F5)
    BEA4(Business Studies Economics Accounting F4)
    CON5(Trades and Construction F5)
    CON6(Trades and Construction F6)
    DAD6(Digital Art Design F6)
    DAR5(Digital Art F5)
    DES6(Design F6)
    DES7(Design F7)
    ESD4(Engineering Systems and Design F4)
    ESD5(Engineering Systems and Design F5)
    FAR5(Fine Art F5)
    GRA4(Graphics F4)
    VIS4(Visual Art F4)
   

    ESD4 --> ESD5
    CON5 --> CON6
    ACC5 --> ACC6
    VIS4 --> ART5
    VIS4 -.->|One| DAR5
    VIS4 -.->|One| FAR5
    DAR5 --> DES6
    FAR5 --> DES6
    DAR5 --> DAD6
    FAR5 --> DAD6
    DES6 --> DES7

```
