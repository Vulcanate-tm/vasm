
# VASM: Vulcanate Assembly Language

VASM (Vulcanate Assembly Language) is a robust, low-level assembly language designed for efficient programming of custom virtual or physical CPU architectures. It features a versatile syntax for defining operations, control flow, loops, and function definitions, enabling developers to write precise and efficient code.

---

## Features

- **Low-level Control**: Direct manipulation of registers, memory, and program flow.
- **Rich Instruction Set**: Includes arithmetic, logic, control flow, stack manipulation, and system calls.
- **Access Modifiers**: Support for `PUBLIC`, `PRIVATE`, and `PROTECTED` for scoped labels and functions.
- **Control Structures**: Native `IF`, `ELIF`, `ELSE`, and `LOOP` constructs.
- **Functionality**: Label-based function definitions and calls with return statements.
- **Customizability**: Extensible for specialized architectures, including support for vector and control registers.

---

## Getting Started

### Prerequisites

To work with VASM, you need:

- A basic understanding of assembly language and low-level programming concepts.
- A text editor or IDE capable of handling `.vasm` files.
- (Optional) An assembler or emulator for compiling and running VASM programs.

---

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/vasm.git
   cd vasm
   ```

2. Follow the instructions in the documentation for assembling and testing your VASM programs.

---

### Writing Your First Program

1. Create a `.vasm` file with your desired program. Example:

   ```vasm
   PUBLIC start:
       MOV GPR0, 10
       ADD GPR1, GPR0
       CALL print
       HALT

   PRIVATE print:
       PUSH GPR1
       RET
   ```

2. Use the provided tools to assemble and run the program.

3. Explore the [VASM Specification](./Specification.md) for the full grammar and features.

---

## Contributing

We welcome contributions to VASM! Here's how you can help:

1. Fork this repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add new feature"`.
4. Push to your branch: `git push origin feature-name`.
5. Open a pull request.

Please ensure your contributions adhere to the project's guidelines and include relevant documentation.

---

## License

This project is licensed under the **Vulcanate License**. Please review the [LICENSE](./LICENSE) file for details. By using this project, you agree to the terms outlined in the Vulcanate License.

---

## Community and Support

- [Discord](https://discord.gg/invite/arr7cDwUTe): Join the Vulcanate community for discussions, support, and updates.
- [Wiki](vulcanate.com/vasm/wiki): Access the project's detailed documentation and examples.
