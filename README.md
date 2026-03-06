# PCBForge Agent

**AI agent for PCB design, schematic generation, and layout automation.**

PCBForge aims to turn design intent — expressed in natural language, structured constraints, or reusable templates — into **schematics, PCB layouts, and manufacturable designs**.

This project explores how AI agents can assist or automate the workflow of PCB designers, from early concept to layout generation.

---

## Vision

Modern PCB design still requires a large amount of manual work:

- writing schematics
- placing components
- routing traces
- checking design rules
- iterating layouts

PCBForge explores a different approach:

> describe the circuit you want, and let an AI agent help construct the design.

The long-term goal is to enable **programmable PCB design**, where design intent can be expressed through:

- natural language
- structured design constraints
- reusable templates
- domain-specific design rules

---

## Project Status

🚧 **Early prototype**

PCBForge is currently in the early development stage.  
The repository focuses on building the core foundations:

- PCB design data model
- design intent parsing
- schematic generation
- KiCad project export
- AI agent workflow

APIs and architecture may change frequently.

---

## Planned Features

- Natural language → schematic generation
- Component library and reusable circuit blocks
- Automated component placement
- Constraint-aware routing assistance
- KiCad project generation
- Design rule validation
- AI agent workflow orchestration

---

## Example Workflow (Concept)

```text
User Input:
"Design a STM32 microcontroller board with USB and a voltage regulator."

↓

AI Agent:
- selects components
- generates schematic
- assigns footprints
- creates initial PCB layout

↓

Output:
KiCad project with schematic and PCB
