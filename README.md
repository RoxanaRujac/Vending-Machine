# Vending-Machine
Vending Machine is a hardware-based project designed to simulate a vending machine using VHDL. The vending machine accepts coins of 5, 10, and 50 bani, calculating the total input and dispensing a soda can when the total reaches 1 leu. The system manages a variety of states, including coin validation, product availability, and rest calculation.

Key Features:
- **Coin Recognition**: Supports multiple coin denominations (5, 10, 50 bani) and rejects invalid inputs.
- **Automated Dispensing**: Delivers a soda can once the total amount of inserted money equals or exceeds 1 leu.
- **State-Based Control**: Implements various states such as idle, coin acceptance, dispense, and refund.
- **Error Handling**: Includes safeguards for invalid coins, empty stock, and refund situations.
- **VHDL Implementation**: Utilizes VHDL for the control and execution units, including submodules like adders, subtractors, comparators, multiplexers, and counters.
- **Modular Design**: Follows a top-down approach, with separate Control and Execution Units that manage the machine's operations and responses.
- **State Machine**: Designed using a finite state machine (FSM) to control the vending machine's logic flow.

Potential Improvements:
- Expanding to a wider range of products by adding a keypad for product selection.
- Adding inventory tracking for different products.
  
This project showcases advanced VHDL design principles, including FSMs, modular components, and hardware logic design. It also emphasizes resource efficiency and ease of future development.
