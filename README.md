# arduino-c-cpp-tinkercad

Foundational microcontrollers, electronics simulations, and C/C++ embedded programming in Autodesk Tinkercad.

## Description

arduino-c-cpp-tinkercad documents practical studies in basic electronics, microcontroller architecture, and firmware logic simulated via Autodesk Tinkercad. The repository details electrical fundamentals (Ohm's law, resistor sizing), sensor reading (analog and digital inputs), pulse-width modulation (PWM), and non-blocking state machine programming using `millis()`.

## Technologies

- **Simulation Platform:** Autodesk Tinkercad Circuits
- **Microcontroller:** Arduino Uno (ATmega328P)
- **Languages:** C, C++ (Arduino Core)
- **Circuit Design:** Schematic board layouts (`.brd`) and circuit wiring diagrams (`.png`)

## Project Structure

```text
arduino-c-cpp-tinkercad/
├── 01-Introducao-Microcontroladores/    # Ohm's law, LED circuits, and breadboard wiring
├── 02-Elementos-Sintaxe/                 # Data types, variables, and pin declarations
├── 03-Operacoes-Matematicas/             # Sensor value transformations and arithmetic
├── 04-Operacoes-Comparacao/              # Threshold comparisons and logical operators
├── 05-Estruturas-Decisao/                # Conditional branching (if/else, switch-case)
├── 06-Logica-Temporizador/               # Timing mechanisms and clock cycles
├── 07-Logica-Semaforo-SemDelay/          # Non-blocking traffic light state machine with millis()
├── 08-Entradas-Digital-Analogicas/       # ADC readings, potentiometers, and PWM output
├── 09-Estruturas-Repeticao/              # Iteration loops for pin sequencing
├── Projetos - Bonus/                     # Integrated multi-sensor simulation challenges
└── Sistema de Numeração Linguagens/      # Binary, hexadecimal, and digital logic reference
```

## Key Topics & Concepts

- **Ohm's Law & Electrical Safety:** Voltage, current, and resistance calculations to prevent component damage.
- **Digital vs. Analog I/O:** Reading discrete states (`digitalRead`) and continuous voltage ranges through the 10-bit Analog-to-Digital Converter (`analogRead`).
- **PWM (Pulse-Width Modulation):** Duty cycle control for LED fading and motor speed modulation (`analogWrite`).
- **Non-Blocking Architecture:** Implementing timed event loops using `millis()` elapsed-time checks instead of blocking `delay()` calls, maintaining system responsiveness.

## Setup & Simulation

### Prerequisites
- A modern web browser with access to [Autodesk Tinkercad](https://www.tinkercad.com/) (free account)

### Running a Circuit Simulation
1. Log into your Tinkercad account and open the **Circuits** workspace.
2. Assemble the components as illustrated in the circuit diagram (`.png`) for each lesson.
3. Open the **Code** panel, select **Text** mode (C/C++), and paste the code from the corresponding lesson script (`codigo.txt`).
4. Click **Start Simulation** to test the circuit behavior interactively.

## Developer

**Kauê Sérgio Campos**  
GitHub: [@EuKaueCMP](https://github.com/EuKaueCMP)
