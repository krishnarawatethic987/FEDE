# Fundamental of Electrical and Digital Electronics: Lecture Topic 1.1.1

## Types of Circuits
- **Closed Circuit**: Allows electric current to flow in a complete path.
- **Open Circuit**: Breaks the path, stopping the current flow.
  - Example: A flashlight turned off is an open circuit.
- **Short Circuit**: Direct connection between two unintended points, causing current to bypass its intended path, potentially leading to overheating or damage.

## Open Circuits
- Created intentionally (e.g., light switches) or by accident (e.g., disconnection of components).
- Accidental open circuits can hinder circuit functionality.

## Short Circuits
- Occur when current takes an unintended, low-resistance path.
- Can cause heat buildup, fire, or damage to power supplies.

## Electric Potential and Potential Difference
- **Electric Potential**: Measure of potential energy per unit charge at a specific point in a circuit.
- **Potential Difference (Voltage)**: Drives the current through the circuit, representing the work needed to move a charge from one point to another.

# Fundamental of Electrical and Digital Electronics: Lecture Topic 1.1.2

## Basic Electrical Elements
- **Resistance (R)**: Opposes the flow of charge; unit: ohm (Ω).
- **Inductance (L)**: Opposes changes in current; stores energy as a magnetic field; unit: henry (H).
- **Capacitance (C)**: Stores energy as an electric field; unit: farad (F).

## Types of Elements
1. **Active and Passive Elements**
   - *Active*: Have their own energy source (e.g., voltage and current sources).
   - *Passive*: Require an external energy source (e.g., resistance, inductance, capacitance).

2. **Linear and Non-linear Elements**
   - *Linear*: Follow Ohm’s Law (e.g., resistance, inductance, capacitance).
   - *Non-linear*: Do not follow Ohm’s Law (e.g., diodes, transistors).

3. **Unilateral and Bilateral Elements**
   - *Unilateral*: Current flows in one direction only (e.g., diodes, rectifiers).
   - *Bilateral*: Current flows in both directions (e.g., resistors, inductors, capacitors).

## Ohm’s Law
- States that voltage (V) is directly proportional to current (I) in a closed circuit, provided physical conditions like temperature remain constant.
- **Applications**:
  - Applicable to linear circuits.
  - Used for determining current and voltage relationships in circuits.

## Kirchhoff’s Laws
1. **Kirchhoff’s Voltage Law (KVL)**
   - In a closed loop, the sum of all voltage drops is zero: ΣV = 0.
   - Algebraic sum of voltage drops and EMF sources in a loop equals zero: ΣV + Σemf = 0.

2. **Kirchhoff’s Current Law (KCL)**
   - At any node, the sum of incoming currents equals the sum of outgoing currents: ΣI_in = ΣI_out.

# Fundamental of Electrical and Digital Electronics: Lecture Topic 1.1.3

## AC Circuits with Pure Components

### Purely Resistive Circuit
- **Definition**: A circuit with negligible inductance; primarily resists current flow.
- **Properties**:
  - No inductance or capacitance present.
  - Voltage and current are in phase (sine waveform).
  - Resistor converts electrical energy into heat.
  
### Purely Inductive Circuit
- **Definition**: A circuit with zero resistance, focusing on self-inductance.
- **Properties**:
  - Current and voltage are 90° out of phase.
  - Current peaks occur when voltage is zero.
  - Power alternates between positive and negative values.

### Purely Capacitive Circuit
- **Definition**: Circuit where the capacitor charges and discharges with alternating voltage.
- **Properties**:
  - Current leads voltage by 90°.
  - Current flow is zero when voltage is at maximum.
  - Current flows when voltage decreases to a negative value.

# Fundamental of Electrical and Digital Electronics: Lecture Topic 1.1.4

## Series RL Circuit
- **Components**: Resistor (R) and Inductor (L) connected in series.
- **Key Properties**:
  - Current lags the voltage across the inductor by 90°.
  - Voltage across the resistor is in phase with the current.
  - Impedance (Z) combines resistance (R) and inductive reactance (XL).

## Impedance in RL Circuit
- **Impedance (Z)**: Z = R + jX_L
- **Magnitude**: |Z| = \sqrt{R^2 + X_L^2}
- **Phase Angle**: \Phi = \tan^{-1} \left( \frac{X_L}{R} \right)

## Series RC Circuit
- **Components**: Resistor (R) and Capacitor (C) connected in series.
- **Key Properties**:
  - Current leads the voltage across the capacitor by 90°.
  - Voltage across the resistor is in phase with the current.
  - Impedance (Z) combines resistance (R) and capacitive reactance (XC).

## Impedance in RC Circuit
- **Impedance (Z)**: Z = R - jX_C
- **Magnitude**: |Z| = \sqrt{R^2 + X_C^2}
- **Phase Angle**: \Phi = \tan^{-1} \left( \frac{-X_C}{R} \right)

## Series RLC Circuit
- **Components**: Resistor (R), Inductor (L), and Capacitor (C) in series.
- **Key Properties**:
  - Voltage vectors for R, L, and C are out-of-phase with each other.
  - Current amplitude depends on the frequency and impedance (Z).
  - Impedance (Z) combines all three components.

## Impedance in RLC Circuit
- **Impedance (Z)**: Depends on the relative values of XL and XC.
- **Impedance Triangle**: Combines resistance (R), inductive reactance (XL), and capacitive reactance (XC).
- **Resonance**: Occurs when X_L = X_C, resulting in purely resistive impedance.

## Phase Angle and Current
- The phase angle (\theta) indicates whether the circuit behaves more inductively or capacitively.
- Positive angle (\theta) means the circuit is inductive (current lags voltage).
- Negative angle (\theta) means the circuit is capacitive (current leads voltage).

# Fundamental of Electrical and Digital Electronics: Lecture Topic 1.2.1

## Introduction to Digital Electronics
- **Digital Electronics**: Deals with the representation and manipulation of data in digital form using devices like transistors, diodes, and microcontrollers.
- **Key Concepts**: Boolean algebra, logic gates, digital filters, and flip-flops.

## Types of Digital Circuits
1. **Combinational Circuits**: Output depends only on current input values (e.g., decoders, multiplexers).
2. **Sequential Circuits**: Output depends on current input values and previous outputs (e.g., registers, counters).
3. **State Machines**: Output depends on current state and input values.
4. **Synchronous Circuits**: Operate using clock signals to synchronize components.
5. **Asynchronous Circuits**: Operate without clock signals, controlled by data flow.

## Digital Logic Types
1. **Boolean Logic**: Uses AND, OR, and NOT gates for logical operations.
2. **K-map Logic**: Simplifies Boolean expressions using Karnaugh maps.
3. **Arithmetic Logic**: Performs arithmetic operations using adders and subtractors.
4. **Memory Circuits**: Store and retrieve data using components like flip-flops.
5. **Microprocessor Circuits**: Act as CPUs for executing instructions.

## Applications of Digital Electronics
1. **Computing**: Used in CPUs, memory, and data processing.
2. **Communication**: Used in cell phones, satellite systems, and internet technology.
3. **Entertainment**: Found in TVs, video game consoles, and music players.
4. **Transportation**: Used in vehicle control systems and traffic management.
5. **Industrial Control**: Automates and controls manufacturing processes.
6. **Medical Equipment**: Used in x-ray machines and patient monitoring.
7. **Military**: Employed in radar and missile guidance systems.
8. **Home Appliances**: Found in devices like refrigerators and washing machines.
9. **Environmental Monitoring**: Measures air and water quality.
10. **Security Systems**: Used in alarms and surveillance cameras.

## Advantages of Digital Electronics
1. More accurate and reliable than analog.
2. Easier to store, process, and transmit data.
3. More precise and capable of complex operations.
4. Easier to design and manufacture.
5. More energy-efficient.

## Disadvantages of Digital Electronics
1. Requires a power source to operate.
2. Susceptible to quantization errors.
3. May need hardware to convert between analog and digital signals.
4. Can be more expensive to produce.
5. May have higher latency than analog systems.

## Difference Between Digital and Analog Electronics
- **Analog Electronics**: Use continuous signals for processing; ideal for applications requiring a continuous range of values.
- **Digital Electronics**: Use discrete signals; more precise and better suited for complex data processing.

# Semiconductor Physics: Lecture Topic 1.2.2

## Half-Wave Rectifier

### Introduction
- A half-wave rectifier allows only one half of the AC input cycle to pass, converting it into a pulsating DC.
- During the positive half-cycle, the diode is forward-biased and conducts.
- During the negative half-cycle, the diode is reverse-biased and does not conduct.

### Working of Half-Wave Rectifier
- Positive half-cycle: Generates a positive voltage at the output.
- Negative half-cycle: No output, as the diode blocks the current.

### Characteristics of Half-Wave Rectifier

1. **Ripple Factor**
   - Measures the amount of AC ripple present in the output DC.
   - Given by the formula: \gamma = \sqrt{(\frac{V_{rms}}{V_{DC}})^2 - 1}.

2. **DC Current**
   - DC current is calculated as: I_{DC} = \frac{I_{max}}{\pi}.

3. **DC Output Voltage**
   - DC output voltage is: V_{DC} = \frac{V_{Smax}}{\pi}.

4. **Form Factor**
   - The ratio of RMS value to DC value for a half-wave rectifier is 1.57.

5. **Rectifier Efficiency**
   - Efficiency of a half-wave rectifier is 40.6%.

### Advantages
- Simple design and connections.
- Affordable with fewer components.

### Disadvantages
- High ripple production and low efficiency.
- Generates harmonics and poor transformer utilization.

### Applications
1. **Power Rectification**: Used with transformers for power supply conversion.
2. **Signal Demodulation**: Used to demodulate AM signals.
3. **Signal Peak Detection**: Detects the peak of incoming waveforms.

# Fundamental of Electrical and Digital Electronics: Lecture Topic 1.2.3

## Introduction to Logic Gates
- Logic gates are the basic building blocks of digital systems.
- Each gate has one or more inputs and a single output, with the output depending on the logic applied.

## Types of Logic Gates
1. **AND Gate**
   - Output is high (1) only if all inputs are high.
   - Expression: Y = A \cdot B

2. **OR Gate**
   - Output is high (1) if at least one input is high.
   - Expression: Y = A + B

3. **NOT Gate**
   - Produces an inverted output (complement of the input).
   - Expression: Y = \overline{A}

4. **NAND Gate**
   - Combination of AND gate followed by a NOT gate.
   - Output is low (0) only if all inputs are high.
   - Expression: Y = \overline{A \cdot B}

5. **NOR Gate**
   - Combination of OR gate followed by a NOT gate.
   - Output is high (1) only if all inputs are low.
   - Expression: Y = \overline{A + B}

6. **Ex-OR (XOR) Gate**
   - Output is high (1) if only one of the inputs is high.
   - Expression: Y = A \oplus B

7. **Ex-NOR (XNOR) Gate**
   - Output is high (1) if both inputs are the same.
   - Expression: Y = \overline{A \oplus B}

## Validation of Logic Gates
- Logic gates can be validated using truth tables, which show the output for every possible input combination.

## Implementation Techniques
- Logic gates can be constructed using different technologies like RTL (Resistor-Transistor Logic) and DRL (Diode-Resistance Logic).

# Fundamental of Electrical and Digital Electronics: Lecture Topic 1.2.4

## Binary Operations

### 1. Binary Addition
- **Rules**:
  - 0 + 0 = 0
  - 0 + 1 = 1
  - 1 + 0 = 1
  - 1 + 1 = 0 (carry 1)

### 2. Binary Subtraction
- **Rules**:
  - 0 - 0 = 0
  - 1 - 0 = 1
  - 1 - 1 = 0
  - 0 - 1 = 1 (borrow 1)

### 3. Binary Multiplication
- **Rules**:
  - 0 × 0 = 0
  - 0 × 1 = 0
  - 1 × 0 = 0
  - 1 × 1 = 1

- **Example**: Multiplying (1010)₂ by (101)₂
  - The result is (110010)₂.

### 4. Binary Division
- **Rules**:
  - 0 / 0 = ∞ (undefined)
  - 0 / 1 = 0
  - 1 / 0 = ∞ (undefined)
  - 1 / 1 = 1

- **Example**: Dividing (11011)₂ by (11)₂
  - The result is a quotient of 101 and a remainder of 0.

## Steps for Binary Multiplication and Division
- **Multiplication**:
  1. Multiply each bit of the multiplicand by the bits of the multiplier.
  2. Shift the results accordingly.
  3. Add the intermediate results using binary addition.

- **Division**:
  1. Compare parts of the dividend with the divisor.
  2. Subtract and bring down the next bit.
  3. Repeat until all bits are processed.
 
  4. # Fundamental of Electrical and Digital Electronics: Lecture Topic 1.2.5

## Binary Number Representation

### 1. Unsigned Binary Numbers
- Represents only positive numbers.
- Uses all n-bits to denote the magnitude.
- Range for n-bits: 0 to 2^n - 1.

### 2. Signed Binary Numbers
- Can represent both positive and negative numbers.
- MSB (Most Significant Bit) acts as the sign bit: 0 for positive, 1 for negative.
- Representations:
  1. **Signed Magnitude Form**
  2. **1's Complement**
  3. **2's Complement**

## 1's Complement
- Invert all bits (0s to 1s and 1s to 0s) to get the complement.
- Has two representations for zero.
- Range: -(2^{n-1} - 1) to 2^{n-1} - 1.

## 2's Complement
- Most commonly used method for signed numbers.
- To find 2's complement:
  1. Start with the binary representation of the number.
  2. Invert all bits after the first '1' from the LSB.
  3. Alternatively, find the 1's complement and add 1.
- Unique representation for zero.
- Range: -2^{n-1} to 2^{n-1} - 1.

## Gray Code
- Binary code where two successive values differ in only one bit.
- Used in error correction and to prevent ambiguities during transitions.

### Gray Code Example
| Decimal | Binary | Gray Code |
|---------|--------|-----------|
| 0       | 0000   | 0000      |
| 1       | 0001   | 0001      |
| 2       | 0010   | 0011      |
| ...     | ...    | ...       |
| 15      | 1111   | 1000      |

## Excess-3 Code
- A non-weighted, self-complementary code.
- Obtained by adding 3 to each digit in the BCD representation.
- Useful in arithmetic operations to handle numbers beyond decimal 9.

### Excess-3 Code Example
| Decimal | BCD    | Excess-3  |
|---------|--------|-----------|
| 0       | 0000   | 0011      |
| 1       | 0001   | 0100      |
| ...     | ...    | ...       |
| 9       | 1001   | 1100      |

## Self-Complementary Property
- Codes that automatically produce their complement when each bit is inverted.
- Useful in simplifying arithmetic operations and error detection.

# Semiconductor Physics: Lecture Topic 1.2.2

## Half-Wave Rectifier

### Introduction
- A half-wave rectifier allows only one half of the AC input cycle to pass, converting it into a pulsating DC.
- During the positive half-cycle, the diode is forward-biased and conducts.
- During the negative half-cycle, the diode is reverse-biased and does not conduct.

### Working of Half-Wave Rectifier
- Positive half-cycle: Generates a positive voltage at the output.
- Negative half-cycle: No output, as the diode blocks the current.

### Characteristics of Half-Wave Rectifier

1. **Ripple Factor**
   - Measures the amount of AC ripple present in the output DC.
   - Given by the formula: \gamma = \sqrt{(\frac{V_{rms}}{V_{DC}})^2 - 1}.

2. **DC Current**
   - DC current is calculated as: I_{DC} = \frac{I_{max}}{\pi}.

3. **DC Output Voltage**
   - DC output voltage is: V_{DC} = \frac{V_{Smax}}{\pi}.

4. **Form Factor**
   - The ratio of RMS value to DC value for a half-wave rectifier is 1.57.

5. **Rectifier Efficiency**
   - Efficiency of a half-wave rectifier is 40.6%.

### Advantages
- Simple design and connections.
- Affordable with fewer components.

### Disadvantages
- High ripple production and low efficiency.
- Generates harmonics and poor transformer utilization.

### Applications
1. **Power Rectification**: Used with transformers for power supply conversion.
2. **Signal Demodulation**: Used to demodulate AM signals.
3. **Signal Peak Detection**: Detects the peak of incoming waveforms.
