### 1. Boolean Algebra

Boolean algebra is a branch of mathematics that deals with binary values: true and false, or 1 and 0. It's the foundation of digital logic and computer science.

**Basic Operations:**

- **AND:** Returns true only if both inputs are true.
- **OR:** Returns true if at least one input is true.
- **NOT:** Inverts the input.

**Truth Tables:** A truth table is a table that shows the output of a Boolean expression for all possible combinations of input values.

| A    | B    | A AND B | A OR B | NOT A |
| ---- | ---- | ------- | ------ | ----- |
| 0    | 0    | 0       | 0      | 1     |
| 0    | 1    | 0       | 1      | 1     |
| 1    | 0    | 0       | 1      | 0     |
| 1    | 1    | 1       | 1      | 0     |

Export to Sheets

**Boolean Expressions:** Boolean expressions are formed using Boolean variables and operators. For example:

```
(A AND B) OR (NOT C)
```

**Applications in Programming:**

- **Conditional statements:** `if-else` statements.
- **Logical operators:** `&&`, `||`, `!` in many programming languages.
- **Digital circuits:** Designing logic gates and circuits.

### 2. Number Systems

**Binary Number System:**

- Base-2 system, using only 0s and 1s.
- Each digit's position represents a power of 2.
- Example: 1011 (binary) = 11 (decimal)

**Hexadecimal Number System:**

- Base-16 system, using digits 0-9 and letters A-F.
- Often used as a shorthand for binary numbers.
- Example: A2 (hexadecimal) = 162 (decimal)

**Decimal Number System:**

- Base-10 system, the most common number system.
- Each digit's position represents a power of 10.

### 3. Floating-Point Numbers

Floating-point numbers represent real numbers with a decimal point. They are stored in a computer's memory in a specific format, which can lead to rounding errors.

**IEEE 754 Standard:** The IEEE 754 standard defines how floating-point numbers are represented in computers. It specifies the format for single-precision (32-bit) and double-precision (64-bit) floating-point numbers.

**Precision and Range:**

- **Precision:** The number of significant digits.
- **Range:** The range of values that can be represented.

**Rounding Errors:** Due to the finite representation of floating-point numbers, calculations can sometimes produce inaccurate results.

### 4. Logarithms

Logarithms are the inverse of exponentiation. They are used to solve equations involving exponents and to analyze the growth of functions.

**Common Logarithm:** The logarithm base 10.

**Natural Logarithm:** The logarithm base e (approximately 2.71828).

**Properties of Logarithms:**

- `log(a * b) = log(a) + log(b)`
- `log(a / b) = log(a) - log(b)`
- `log(a^b) = b * log(a)`

### 5. Set Theory

Set theory is the study of sets, which are unordered collections of distinct objects.

**Basic Set Operations:**

- **Union:** Combines elements from two sets.
- **Intersection:** Finds elements common to both sets.
- **Difference:** Finds elements in one set but not the other.
- **Complement:** Finds elements not in a given set.

**Venn Diagrams:** Venn diagrams are visual representations of sets and their relationships.

### 6. Combinatorics

Combinatorics is the study of counting, permutations, and combinations.

**Permutations:** The number of ways to arrange a set of objects in a specific order.

**Combinations:** The number of ways to choose a subset of objects from a larger set, without regard to order.

**Binomial Coefficient:** The number of ways to choose k items from a set of n items.

### 7. Graph Theory

Graph theory is the study of graphs, which are mathematical structures used to model relationships between objects.

**Basic Concepts:**

- **Vertex:** A node in a graph.
- **Edge:** A connection between two vertices.
- **Degree:** The number of edges incident to a vertex.

**Graph Types:**

- **Directed graphs:** Edges have a direction.
- **Undirected graphs:** Edges have no direction.
- **Weighted graphs:** Edges have associated weights.

**Graph Algorithms:**

- **Breadth-first search (BFS):** Explores all neighbors at the current depth before moving to the next depth.
- **Depth-first search (DFS):** Explores as deep as possible along a branch before backtracking.
- **Dijkstra's algorithm:** Finds the shortest path between two nodes in a weighted graph.

### 8. Complexity Theory

Complexity theory analyzes the efficiency of algorithms. Big O notation is used to describe the time and space complexity of algorithms.

**Common Time Complexities:**

- **Constant time (O(1)):** Operations that take the same amount of time regardless of input size.
- **Logarithmic time (O(log n)):** Operations that halve the problem size in each step.
- **Linear time (O(n)):** Operations that take time proportional to the input size.
- **Quadratic time (O(n^2)):** Operations that involve nested loops.
- **Exponential time (O(2^n)):** Operations that double the work for each additional input.

### 9. Statistics

Statistics is the science of collecting, analyzing, interpreting, and presenting data.

**Descriptive Statistics:**

- **Mean:** The average of a set of numbers.
- **Median:** The middle value in a sorted set of numbers.
- **Mode:** The most frequent value in a set of numbers.
- **Standard deviation:** Measures the dispersion of data points.

**Inferential Statistics:**

- **Hypothesis testing:** Making inferences about a population based on a sample.
- **Confidence intervals:** Estimating a population parameter with a certain level of confidence.

### 10. Linear Algebra

Linear algebra is the study of linear equations and their solutions. It's fundamental to many areas of computer science, including computer graphics, machine learning, and data science.

**Key Concepts:**

- **Vectors:** Ordered lists of numbers.
- **Matrices:** Arrays of numbers arranged in rows and columns.
- **Matrix operations:** Addition, subtraction, multiplication, and inversion.
- **Determinants:** A scalar value associated with a square matrix.
- **Eigenvalues and eigenvectors:** Used to analyze the behavior of linear transformations.

By understanding these fundamental math concepts, you'll be better equipped to tackle complex programming challenges and write more efficient and elegant code.
