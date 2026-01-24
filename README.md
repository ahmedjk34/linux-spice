# linux-spice

A high-performance, native Linux circuit simulator inspired by LTspice.

## Development Philosophy

**This project is built with ZERO AI-generated code.** Every line is written by hand, with intention and understanding. This ensures code quality, maintainability, and deep domain knowledge throughout the codebase.

## Vision

This project aims to create a **fully native LTspice alternative for Linux** - no Wine, no compromises. 

After using PySpice extensively in my graduate project, I realized there's a massive gap in the Linux EDA ecosystem: there's no modern, performant, native GUI circuit simulator that matches the workflow and speed that LTspice users are accustomed to. This project exists to fill that gap.

## Why linux-spice?

- **Native Linux experience** - Built for Linux, from the ground up
- **High performance** - C++ and Qt for maximum speed and responsiveness  
- **LTspice-inspired workflow** - Familiar schematic capture and analysis tools
- **Powered by ngspice** - Leveraging the robust, open-source ngspice simulation engine
- **Open source** - GPL v3, community-driven development

## Planned Architecture

### Tech Stack
- **GUI Framework:** Qt 6.x (C++)
- **Simulation Engine:** libngspice (C library)
- **Language:** C++17
- **Build System:** CMake
