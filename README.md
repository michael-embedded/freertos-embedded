# FreeRTOS from Zero to Hero - Companion Code Repository



This repository contains practical code examples from the book **Real-Time Operating Systems for Embedded Engineers: FreeRTOS from Zero to Hero** (© 2025).

The book teaches FreeRTOS-based design from fundamentals to production-grade systems on real hardware (STM32, ESP32, RP2040). Examples are purposeful, hands-on, and designed to run on common development boards.




## Hardware Recommendations
- **STM32**: Nucleo-F407ZG or Discovery board (examples use HAL)



- **ESP32**: ESP32-S3 DevKitC (for SMP examples)



- **RP2040**: Raspberry Pi Pico or Pico 2



## Chapters with Code
- **Chapter 2**: Tasks, Priorities, and Preemption – Blinking LEDs, stack monitoring, starvation demo
- **Chapter 3**: Queues, Semaphores, Mutexes, Event Groups – Producer-consumer, ISR-safe queues
- **Chapter 4**: Timer and Interrupt Management – Software timers, deferred processing
- **Chapter 5**: Memory Allocation – heap_4 stress tests, monitoring
- **Chapter 6**: Porting to STM32/ESP32/RP2040 – Platform-specific configs and demos (including SMP on ESP32/RP2040)
- **Chapter 7**: Production-Grade Projects – Architecture outlines and key code for 8 real-world systems (full details in book)
- **Appendices**: Recommended FreeRTOSConfig.h

Each chapter folder contains runnable examples (import into STM32CubeIDE, ESP-IDF, or Pico SDK).

## How to Use
1. Clone the repo: `git clone https://github.com/YOUR-USERNAME/freertos-zero-to-hero-book.git`
2. Open the desired chapter/project in your IDE.
3. Build and flash to your board.
4. Use a logic analyzer/scope for timing verification as described in the book.

Conceptual chapters (e.g., Chapter 1) have no code – focus is on building mental models.

## License
Code examples are for educational use. See LICENSE file.

The book text is © 2025 by the Author – excerpts here for companion purposes only.

Star the repo if you find it useful! 🚀
