## Computer Science Fundamentals - The Building Blocks of Computation

**Turning Machine:** A theoretical device that manipulates symbols on a tape according to a table of rules. It's a foundational model for understanding the limits and capabilities of computation. While it's a simplified model, it's powerful enough to simulate any algorithm.

**CPU (Central Processing Unit):** The "brain" of a computer, executing instructions and performing calculations. It consists of:

- **Control Unit (CU):** Coordinates the activities of the CPU.
- **Arithmetic Logic Unit (ALU):** Performs arithmetic and logical operations.
- **Registers:** High-speed storage locations for data and instructions.

**Transistor:** A semiconductor device that amplifies or switches electronic signals. It's the fundamental building block of modern electronics, enabling the miniaturization of computers.

**Bits and Bytes:**

- **Bit:** The smallest unit of data, representing a 0 or a 1.
- **Byte:** A group of 8 bits, often used to represent a character.

**Character Encoding (ASCII):** A standard mapping of characters to numerical values, allowing computers to store and manipulate text. ASCII is a common character encoding standard, but there are others like Unicode, which supports a wider range of characters.

**Number Systems:**

- **Binary:** A base-2 number system, using only 0s and 1s. It's the foundation of digital computers.
- **Hexadecimal:** A base-16 number system, using digits 0-9 and letters A-F. It's often used as a shorthand for binary numbers.
- **Nibble:** A group of 4 bits, half a byte.

**Machine Code:** The lowest-level programming language, directly understood by the CPU. It's a sequence of binary instructions.

### Memory and Storage

**RAM (Random Access Memory):** Volatile memory used to store data and instructions while a program is running. It's faster than other storage types but loses its contents when the power is turned off.

**Memory Address:** A unique identifier for a location in memory.

**I/O (Input/Output):** The process of transferring data between a computer and external devices. This includes input devices like keyboards and mice, and output devices like monitors and printers.

**Operating System Components:**

- **Kernel:** The core component, managing hardware and software resources. It handles tasks like memory management, process scheduling, and file system operations.
- **Shell:** A user interface for interacting with the operating system. It can be a command-line interface or a graphical user interface.

**Command Line Interface:** A text-based interface for interacting with a computer. It allows users to input commands directly, providing a powerful way to control the system.

**SSH (Secure Shell):** A network protocol for secure communication over an insecure network. It's commonly used for remote login and file transfer.

**Mainframe:** A large, powerful computer system, often used for critical applications like banking and airline reservations. They are characterized by their high processing power and ability to handle large amounts of data.

### Programming Paradigms and Languages

**Programming Language:** A formal language used to write computer programs. Different languages have different syntax and semantics, but they all follow fundamental principles of computation.

**Abstraction:** The process of simplifying complex systems by focusing on relevant details. It allows programmers to work at a higher level of abstraction, making code more readable and maintainable.

**Interpreted vs. Compiled Languages:**

- **Interpreted:** Executed line by line without being compiled into machine code. Python and JavaScript are examples of interpreted languages.
- **Compiled:** Translated into machine code before execution. C and C++ are examples of compiled languages.

**Data Types:** Categories of data, such as integers, floating-point numbers, and strings. Data types determine how data is stored and manipulated in memory.

**Variables:** Named storage locations for data. They can hold different types of values, and their values can change during program execution.

**Dynamic vs. Static Typing:**

- **Dynamic Typing:** Data types are determined at runtime.
- **Static Typing:** Data types are declared before execution.

**Pointers:** Variables that store the memory address of another variable. They are used to manipulate memory directly and create complex data structures.

**Garbage Collector:** A program that automatically reclaims memory that is no longer in use. This helps prevent memory leaks and improves program performance.

**Primitive Data Types:**

- **int:** Integer numbers.
- **float/double:** Floating-point numbers.
- **char:** Single characters.
- **string:** Sequences of characters.

**Endianness:** The order in which bytes are stored in memory. Big-endian systems store the most significant byte first, while little-endian systems store the least significant byte first.

### Data Structures

**Arrays:** Ordered collections of elements, accessed by an index. They are efficient for storing and accessing data in sequential order.

**Linked Lists:** Linear data structures where elements are connected by pointers. They are flexible for insertions and deletions, but accessing elements can be less efficient than arrays.

**Sets:** Unordered collections of unique elements. They are useful for membership testing and eliminating duplicates.

**Stacks:** LIFO (Last-In-First-Out) data structures. They are used for tasks like function calls and expression evaluation.

**Queues:** FIFO (First-In-First-Out) data structures. They are used for tasks like task scheduling and breadth-first search.

**Hashes:** Data structures that map keys to values. They provide efficient key-based access to data.

**Trees:** Non-linear data structures with hierarchical relationships. They are used to represent hierarchical data, such as file systems and organizational structures.

**Graphs:** Non-linear data structures consisting of nodes and edges. They are used to model relationships between objects, such as social networks and transportation networks.

### Algorithms and Problem-Solving

**Algorithms:** Step-by-step procedures for solving problems. They are the foundation of computer science and are used to design efficient solutions to a wide range of problems.

**Functions:** Reusable blocks of code that perform specific tasks. They promote modularity and code reusability.

**Conditional Logic:** Controlling the flow of execution based on conditions. It allows programs to make decisions and respond to different inputs.

**Loops:**

- **While Loop:** Repeats a block of code while a condition is true.
- **For Loop:** Repeats a block of code a specific number of times.

**Recursion:** A programming technique where a function calls itself. It's often used to solve problems that can be broken down into smaller, self-similar subproblems.

**Big-O Notation:** A way to measure the efficiency of algorithms. It describes how the runtime of an algorithm grows with input size.

**Common Algorithm Design Techniques:**

- **Brute Force:** Trying all possible solutions.
- **Divide and Conquer:** Breaking problems into smaller subproblems.
- **Dynamic Programming:** Storing solutions to subproblems to avoid redundant calculations.
- **Greedy Algorithms:** Making locally optimal choices.
- **Dijkstra's Algorithm:** Finding shortest paths in graphs.
- **Backtracking:** Systematically exploring all possible solutions.

### Programming Paradigms

**Declarative vs. Imperative:**

- **Declarative:** Specifies *what* to compute.
- **Imperative:** Specifies *how* to compute.

**Functional Programming:** Emphasizes functions as the primary building block. It promotes pure functions, immutability, and higher-order functions.

**Object-Oriented Programming (OOP):** Models real-world entities as objects with properties and methods. It promotes code reusability, modularity, and encapsulation.

### Concurrency and Parallelism

**Threads:** Units of execution within a process. They allow programs to perform multiple tasks concurrently.

**Parallelism:** Executing multiple tasks simultaneously. It's often achieved using multiple cores or processors.

**Concurrency:** Handling multiple tasks at the same time, even if not truly parallel. It's essential for responsive and efficient applications.

### Networking and Web Development

**IP Address:** A unique identifier for a device on a network. It's used to route data packets between devices.

**URL (Uniform Resource Locator):** A way to identify resources on the internet. It specifies the protocol, domain name, and path to a resource.

**DNS (Domain Name System):** Maps domain names to IP addresses. It allows users to access websites using human-readable names instead of IP addresses.

**TCP/IP:** Fundamental protocols for internet communication. TCP provides reliable data transmission, while IP handles packet routing.

**HTTP (Hypertext Transfer Protocol):** Protocol for transmitting data over the web. It's used to request and receive web pages.

**API (Application Programming Interface):** A set of rules for building software applications. It defines how different software components can interact with each other.