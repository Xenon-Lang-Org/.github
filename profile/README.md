<a id="readme-top"></a>

<!-- PROJECT HEADER -->
# Xenon

The goal of this project is to implement a programming language of our own design, in Haskell.

## Table of Contents
<details>
  <summary>Click to expand</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## Getting Started

### Dependencies/Requirements
- GHC: 9.6.6
- HLS: 2.9.0.1
- Cabal: 3.10.3.0
- Stack: 3.1.1
- Make: 4.3 (Optional, Linux Only)

### Supported Platforms
- Windows
- macOS
- Linux

### Build Instructions
#### Linux & macOS & Windows
1. Clone the Xenon repository:

2. Build the project:

using Make
```sh
make
```

using Stack
```
stack build
```

## Usage

**Compiler**
```sh
./xcc <source-file.xn> [-o <output-file.wasm>]
```

**Interpreter**
```sh
./xin [<file.xn>] [<file.xn>] [-e <file.xn>]
```

## Documentation

The documentation is available in the [docs repository](https://github.com/Xenon-Lang-Org/docs).
Use mdbook to open the documentation in your browser:

```sh
mdbook serve docs --open
```

## Contributors

- [Léo Wehrle - Rentmeister](https://github.com/leoWherle)
- [Théodore Magna](https://github.com/TheodoreMagna)
- [Lucien Pineau](https://github.com/mathematisse)
- [Alexis Hachemi](https://github.com/alexishachemi)
- [Karim Mohamed](https://github.com/Kuawhrime)

## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



![Xenopuff](https://github.com/user-attachments/assets/9e154317-0e0f-4516-afe4-bf429b57f2e0)
