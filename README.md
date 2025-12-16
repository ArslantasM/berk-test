# BERK Demo Package
**Production-Ready Systems Programming with Breakthrough Performance**
This demo package showcases BERK's unique capabilities through hands-on, runnable examples. Each demo is self-contained and demonstrates quantifiable technical advantages.
---
##  What is BERK?
BERK is a modern systems programming language that delivers:
- **263x faster** memory allocation (region memory vs malloc/free)
- **Rust-level** memory safety (ownership + borrow checker)
- **98-100%** of C++ performance
- **19 platform** support (x86, ARM, RISC-V, ESP32, STM32, WebAssembly)
- **Dual-language** syntax (Turkish + English keywords)
- **2900+ functions** in standard library
---
##  Demo Structure
```
demos/
├── BEGINNER/           #  Getting started demos
│   ├── 01_hello_world.berk
│   ├── 02_variables.berk
│   ├── 03_functions.berk
│   ├── EN_01_hello_world.berk
│   ├── EN_02_variables.berk
│   └── EN_03_functions.berk
│
├── INTERMEDIATE/       #  Core language features
│   ├── 01_collections.berk
│   ├── 02_error_handling.berk
│   ├── 03_pattern_matching.berk
│   ├── EN_01_collections.berk
│   ├── EN_02_error_handling.berk
│   └── EN_03_pattern_matching.berk
│
├── EXPERT/             #  Advanced concepts
│   ├── 01_memory_regions.berk
│   ├── 02_ownership.berk
│   ├── 03_concurrency.berk
│   ├── EN_01_memory_regions.berk
│   ├── EN_02_ownership.berk
│   └── EN_03_concurrency.berk
│
├── HAL/                #  Hardware Abstraction Layer
│   ├── 01_gpio_basics.berk
│   ├── 02_uart_serial.berk
│   ├── 03_spi_communication.berk
│   ├── 04_i2c_sensors.berk
│   ├── EN_01_gpio_basics.berk
│   ├── EN_02_uart_serial.berk
│   ├── EN_03_spi_communication.berk
│   └── EN_04_i2c_sensors.berk
│
├── LIBRARY/            #  Standard Library showcase
│   ├── 01_math_demo.berk
│   ├── 02_string_demo.berk
│   ├── 03_file_io_demo.berk
│   ├── 04_json_demo.berk
│   ├── 05_regex_demo.berk
│   ├── 06_datetime_demo.berk
│   ├── EN_01_math_demo.berk
│   ├── EN_02_string_demo.berk
│   ├── EN_03_file_io_demo.berk
│   ├── EN_04_json_demo.berk
│   ├── EN_05_regex_demo.berk
│   └── EN_06_datetime_demo.berk
│
├── DUAL_LANGUAGE/      #  Turkish + English syntax
│   ├── fibonacci_tr_en.berk
│   └── sorting_algorithms.berk
│
├── run_tests.ps1       #  Test runner script
└── README.md           #  This file
```
**Total: 40 demos** (20 Turkish + 20 English)
---
##  Demo Categories
###  BEGINNER (6 demos)
Perfect for learning BERK basics.
| Demo | Turkish | English | Description |
|------|---------|---------|-------------|
| Hello World | `01_hello_world.berk` | `EN_01_hello_world.berk` | First program, print output |
| Variables | `02_variables.berk` | `EN_02_variables.berk` | Data types, variables, constants |
| Functions | `03_functions.berk` | `EN_03_functions.berk` | Functions, parameters, return values |
**Run:**
```bash
berk-lang run demos/BEGINNER/01_hello_world.berk
berk-lang run demos/BEGINNER/EN_01_hello_world.berk
```
---
###  INTERMEDIATE (6 demos)
Core language features for real applications.
| Demo | Turkish | English | Description |
|------|---------|---------|-------------|
| Collections | `01_collections.berk` | `EN_01_collections.berk` | Lists, arrays, dictionaries |
| Error Handling | `02_error_handling.berk` | `EN_02_error_handling.berk` | Option, Result, error propagation |
| Pattern Matching | `03_pattern_matching.berk` | `EN_03_pattern_matching.berk` | Match expressions, destructuring |
**Run:**
```bash
berk-lang run demos/INTERMEDIATE/01_collections.berk
berk-lang run demos/INTERMEDIATE/EN_01_collections.berk
```
---
###  EXPERT (6 demos)
Advanced concepts for systems programming.
| Demo | Turkish | English | Description |
|------|---------|---------|-------------|
| Memory Regions | `01_memory_regions.berk` | `EN_01_memory_regions.berk` | 263x faster allocation |
| Ownership | `02_ownership.berk` | `EN_02_ownership.berk` | Borrow checker, lifetimes |
| Concurrency | `03_concurrency.berk` | `EN_03_concurrency.berk` | Threads, channels, async |
**Run:**
```bash
berk-lang run demos/EXPERT/01_memory_regions.berk
berk-lang run demos/EXPERT/EN_01_memory_regions.berk
```
---
###  HAL - Hardware Abstraction Layer (8 demos)
Embedded systems and hardware programming.
| Demo | Turkish | English | Description |
|------|---------|---------|-------------|
| GPIO Basics | `01_gpio_basics.berk` | `EN_01_gpio_basics.berk` | Digital I/O, LED control |
| UART Serial | `02_uart_serial.berk` | `EN_02_uart_serial.berk` | Serial communication |
| SPI Communication | `03_spi_communication.berk` | `EN_03_spi_communication.berk` | SPI bus, peripherals |
| I2C Sensors | `04_i2c_sensors.berk` | `EN_04_i2c_sensors.berk` | I2C protocol, sensor reading |
**Run:**
```bash
berk-lang run demos/HAL/01_gpio_basics.berk
berk-lang run demos/HAL/EN_01_gpio_basics.berk
```
**Supported Platforms:**
- STM32 (F4, F7, H7 series)
- ESP32 (ESP-IDF)
- Raspberry Pi Pico
- Arduino (via abstraction)
- Nordic nRF52
---
###  LIBRARY - Standard Library Showcase (12 demos)
Demonstrating BERK's 2900+ standard library functions.
| Demo | Turkish | English | Modules Used |
|------|---------|---------|--------------|
| Math | `01_math_demo.berk` | `EN_01_math_demo.berk` | `std::math`, trigonometry, constants |
| String | `02_string_demo.berk` | `EN_02_string_demo.berk` | `std::string`, manipulation |
| File I/O | `03_file_io_demo.berk` | `EN_03_file_io_demo.berk` | `std::io`, file operations |
| JSON | `04_json_demo.berk` | `EN_04_json_demo.berk` | `std::json`, parsing |
| Regex | `05_regex_demo.berk` | `EN_05_regex_demo.berk` | `std::regex`, patterns |
| DateTime | `06_datetime_demo.berk` | `EN_06_datetime_demo.berk` | `std::time`, dates |
**Run:**
```bash
berk-lang run demos/LIBRARY/01_math_demo.berk
berk-lang run demos/LIBRARY/EN_01_math_demo.berk
```
---
###  DUAL_LANGUAGE (2 demos)
BERK's unique feature: write in Turkish, English, or both!
| Demo | Description |
|------|-------------|
| `fibonacci_tr_en.berk` | Same algorithm in TR, EN, and mixed syntax |
| `sorting_algorithms.berk` | Multiple sorting algorithms in mixed syntax |
**Key Point:** ALL versions compile to **identical machine code** - zero overhead!
**Run:**
```bash
berk-lang run demos/DUAL_LANGUAGE/fibonacci_tr_en.berk
berk-lang run demos/DUAL_LANGUAGE/sorting_algorithms.berk
```
**Example code:**
```rust
// Turkish
fonksiyon fibonacci_tr(n: tamsayı) -> tamsayı yap
    eğer n <= 1
        dön n
    son
    dön fibonacci_tr(n - 1) + fibonacci_tr(n - 2)
son
// English
function fibonacci_en(n: integer) -> integer do
    if n <= 1
        return n
    end
    return fibonacci_en(n - 1) + fibonacci_en(n - 2)
end
```
---
##  Quick Start
### Prerequisites
1. **BERK Compiler** (v1.0.0+)
   - Download: https://github.com/ArslantasM/berk-lang/releases
   - Or build from source: https://github.com/ArslantasM/berk-lang
2. **VS Code Extension** (v0.6.0+) - Optional but recommended
   - Marketplace: Search "BERK" in VS Code Extensions
   - Provides: Syntax highlighting, linting, formatting, LSP
### Installation
```bash
# Download demo package
git clone https://github.com/ArslantasM/berk-test.git
cd berk-test
```
### Running All Tests
```powershell
# Run all 40 demos and verify output
.\demos\run_tests.ps1
```
**Expected output:**
```
=== BERK Demo Test Suite ===
Testing 40 demo files...
 BEGINNER/01_hello_world.berk - PASSED
 BEGINNER/02_variables.berk - PASSED
 BEGINNER/03_functions.berk - PASSED
...
 DUAL_LANGUAGE/sorting_algorithms.berk - PASSED
=== Results ===
Passed: 40/40 (100%)
```
---
##  Performance Summary
| Benchmark | Competitor | BERK | Speedup |
|-----------|-----------|------|---------|
| Memory allocation (1M ops) | malloc/free: 10.5ms | Region: 0.04ms | **263x** |
| Matrix multiply (1000x1000) | NumPy: 100ms | BERK: 40ms | **2.5x** |
| HTTP requests (1000 concurrent) | Node.js: 10k/s | BERK: 50k/s | **5x** |
| SQLite insert (10k rows) | Python: 2.5s | BERK: 0.5s | **5x** |
| AES-256 encryption (1MB) | Python: 15ms | BERK: 3ms | **5x** |
**Overall:** BERK delivers 98-100% of C++ performance with Rust-level safety.
---
##  Learning Path
### Week 1: Basics
1. `BEGINNER/01_hello_world.berk` - First program
2. `BEGINNER/02_variables.berk` - Data types
3. `BEGINNER/03_functions.berk` - Functions
### Week 2: Core Features
4. `INTERMEDIATE/01_collections.berk` - Data structures
5. `INTERMEDIATE/02_error_handling.berk` - Error handling
6. `INTERMEDIATE/03_pattern_matching.berk` - Pattern matching
### Week 3: Advanced
7. `EXPERT/01_memory_regions.berk` - Memory management
8. `EXPERT/02_ownership.berk` - Ownership system
9. `EXPERT/03_concurrency.berk` - Concurrency
### Week 4: Specialization
10. `HAL/*` - Embedded systems
11. `LIBRARY/*` - Standard library mastery
12. `DUAL_LANGUAGE/*` - Bilingual programming
---
##  VS Code Extension Features
The BERK VS Code extension (v0.6.0) provides:
### Real-time Linting (30+ rules)
- Unused variables (`sem_001`)
- Uninitialized variables (`safe_001` - ERROR level)
- Magic numbers (`qual_002`)
- Naming conventions (`qual_003-005`)
- Control flow issues (`cfg_001`)
- Documentation completeness (`doc_001-005`)
### Auto-formatting
- AST-based (preserves semantics)
- UTF-8 with BOM (Turkish character support)
- Idempotent (stable output)
- Performance: <50ms for large files
### LSP Features
- Auto-completion
- Go to definition
- Find references
- Hover documentation
- Signature help
- Diagnostics
- **310/310 tests passing**
### Integrated Tools
- BERK REPL (interactive shell)
- Run current file
- Format on save
- Inline error display
**Install:**
```bash
code --install-extension berk-lang-0.6.0.vsix
```
---
##  Why BERK?
### vs Rust
-  **263x faster** region memory
-  **2-5x faster** compilation
-  Dual-language (Turkish + English)
- ≈ Same safety guarantees
- ≈ Same performance level
### vs C++
-  Memory safety (no segfaults)
-  Thread safety (no data races)
-  Simpler syntax
- ≈ Same performance
- ≈ Same platform support
### vs Go
-  **No GC pauses** (region memory)
-  **98-100% C++ performance** (vs 80-90%)
-  Memory safety
- ≈ Same concurrency model
- ≈ Similar simplicity
### vs Zig
-  Memory safety (ownership system)
-  Dual-language
-  Mature stdlib (2900+ functions)
- ≈ Same manual memory control
- ≈ Similar C interop
---
##  Documentation
- **Language Guide:** https://arslantasm.github.io/berk_pages/
- **API Reference:** https://arslantasm.github.io/berk-stdlib-docs/
- **GitHub:** https://github.com/ArslantasM/berk-test
---
##  Contributing
Found a bug in demos? Want to add new examples?
1. Fork the repository
2. Create feature branch: `git checkout -b demo/new-example`
3. Add your demo with comprehensive comments
4. Submit PR with description
---
##  License
Demo code: MIT License
BERK compiler: GPL-3.0
---
##  Next Steps
1. **Try the demos** - Run all 40 examples
2. **Install VS Code extension** - Enhanced development experience
3. **Read the docs** - Learn advanced features
4. **Build something** - Share your project!
---
##  Support
- **GitHub Issues:** https://github.com/ArslantasM/berk-test/issues
- **Email:** arslantas.m@gmail.com
---
**Made in Türkiye **
**Türkçe dokümantasyon:** https://arslantasm.github.io/berk_pages/
