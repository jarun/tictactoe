# TicTacToe
Checks the state of a Tic-Tac-Toe game

The board is represented by 3 bytes. Each row is represented by 6 MSBs of a byte. The 2 LSB bits are ignored.

Each square is represented using 2 bits. The meaning of the binary values are:

| Square State | Bit Value |
| --- |:---:|
| Empty square | `00` |
| Tick | `01` |
| Cross | `10` |
| Invalid | `11` |

# License & Copyright

GPLv3.0

Copyright (C) 2015 [Arun Prakash Jana](mailto:engineerarun@gmail.com)
