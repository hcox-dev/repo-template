# 🧰 Multi-Language Project Template

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive, ready-to-use template repository featuring multiple programming languages with their respective build systems and development environments. Perfect for polyglot projects, learning multiple languages, or quickly bootstrapping projects in your preferred language.

## 🚀 Quick Start

1. **Use this template** by clicking the "Use this template" button on GitHub
2. **Clone your new repository**
3. **Navigate to your preferred language directory**
4. **Follow the build instructions** for that specific language

## 🔧 Supported Languages

| Language | Build System | Version | Entry Point |
|----------|-------------|---------|-------------|
| **C** | Make | C99+ | `C/src/main.c` |
| **C++** | CMake | C++17+ | `Cpp/src/main.cpp` |
| **Go** | Go Modules | 1.24+ | `Go/cmd/` |
| **Node.js** | npm | Latest LTS | `Node/src/index.js` |
| **Rust** | Cargo | 2021 Edition | `Rust/src/main.rs` |

## 📂 Project Structure

```
📦 repo-template
├── 📁 C/                    # C project with Makefile
│   ├── Makefile
│   ├── include/hello.h
│   └── src/
│       ├── hello.c
│       └── main.c
├── 📁 Cpp/                  # C++ project with CMake
│   ├── CMakeLists.txt
│   ├── include/hello.hpp
│   └── src/
│       ├── hello.cpp
│       └── main.cpp
├── 📁 Go/                   # Go project with modules
│   ├── go.mod
│   └── cmd/
├── 📁 Node/                 # Node.js project with npm
│   ├── package.json
│   └── src/
├── 📁 Rust/                 # Rust project with Cargo
│   ├── Cargo.toml
│   └── src/main.rs
├── LICENSE                  # MIT License
└── README.md               # This file
```

## 🛠️ Build Instructions

### C Project
```bash
cd C/
make                    # Build the project
./app                   # Run the executable
make clean             # Clean build artifacts
```

**Requirements:** GCC, Make

### C++ Project
```bash
cd Cpp/
cmake .                # Generate build files
make                   # Build the project
./app                  # Run the executable
```

**Requirements:** CMake 3.10+, G++

### Go Project
```bash
cd Go/
go mod tidy           # Download dependencies
go build ./...        # Build all packages
go run ./cmd          # Run the main package (when available)
```

**Requirements:** Go 1.24+

### Node.js Project
```bash
cd Node/
npm install           # Install dependencies
npm start             # Run the application
```

**Requirements:** Node.js (Latest LTS), npm

### Rust Project
```bash
cd Rust/
cargo build           # Build the project
cargo run             # Build and run
cargo test            # Run tests
```

**Requirements:** Rust 2021 Edition

## 🎯 Use Cases

- **Learning Multiple Languages**: Compare implementations across different languages
- **Polyglot Projects**: Microservices or components in different languages
- **Quick Prototyping**: Start coding immediately without setup overhead
- **Teaching**: Demonstrate concepts across multiple programming paradigms
- **Benchmarking**: Compare performance across language implementations

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Customization

To adapt this template for your project:

1. **Update project names** in build configuration files
2. **Add dependencies** specific to your project requirements
3. **Remove unused languages** to keep your project lean
4. **Update this README** with your project-specific information

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with modern tooling and best practices for each language
- Designed for developer productivity and ease of use
- Inspired by the need for quick, reliable project bootstrapping
