```mermaid
graph LR
    4BEA(Business Studies Economics Accounting F4)
    4ESD(Engineering Systems and Design F4)
    4GRA(Graphics F4)
    4VIS(Visual Art F4)
    5ACC(Accounting F5)
    5ART(Art F5)
    5BUS(Business Studies F5)
    5COM(Business Studies/Economics F5 NCEA1)
    5CON(Trades and Construction F5)
    5DAR(Digital Art F5)
    5ECO(Economics F5)
    5ESD(Engineering Systems and Design F5)
    5FAR(Fine Art F5)
    5GRA(Graphics/Graphic Products F5)
    6ACC-A(Accounting F6 AS)
    6ACC-N(Accounting F6 NCEA2)
    6CON(Trades and Construction F6)
    6DAD(Digital Art Design F6 AS)
    6DAP-A(Digital Art Photography F6 AS)
    6DES(Design F6 NCEA2)
    6IND(Industrial Design F6 NCEA2)
    6PHO-N(Photography F6 NCEA2)
    6PTG(Painting F6 NCEA2)
    7ACC-A(Accounting F7 A2)
    7ACC-N(Accounting F7 NCEA3)
    7CON(Trades and Construction F7 NCEA3)
    7DES-N(Design F7 NCEA3)
    7DES-A(Design F7 A2)
    7IND(Industrial Design F7 NCEA3)
    7PHO-N(Photography F7 NCEA3)
    7PHO-A(Photography F7 A2)
    7PTG-A(Painting F7 A2)
    7PTG-N(Painting F7 NCEA3)
    

    subgraph Art
        4VIS --> 5ART
        4VIS -.->|One| 5DAR
        4VIS -.->|One| 5FAR
        5DAR --> 6DES
        5FAR --> 6DES
        5DAR --> 6DAD
        5FAR --> 6DAD
        6DES --> 7DES-N
        6DAP-A --> 7PHO-A
        6DAD --> 7DES-A
        6PHO-N --> 7PHO-N
        6PTG --> 7PTG-N
    end

    subgraph Technology
        4GRA --> 5GRA
        4ESD --> 5ESD
        5CON --> 6CON
        6IND --> 7IND
    end

    subgraph Accounting
        5ACC --> 6ACC-A --> 7ACC-A
        5ACC --> 6ACC-N --> 7ACC-N
        4BEA --> 5BUS
        4BEA --> 5ECO
    end

```
