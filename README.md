# Strong Prime Number Theorem - Astrolabe Template

[![Astrolabe](https://img.shields.io/badge/Visualize%20with-Astrolabe-purple)](https://github.com/Xinze-Li-Bryan/Astrolabe)
[![Original Project](https://img.shields.io/badge/Original-math--inc%2Fstrongpnt-blue)](https://github.com/math-inc/strongpnt)

An Astrolabe visualization template for the Strong Prime Number Theorem formalization in Lean 4.

## About This Template

This repository is an [Astrolabe](https://github.com/Xinze-Li-Bryan/Astrolabe) template based on the [Strong PNT project](https://github.com/math-inc/strongpnt) by Math Inc.

**What's included:**
- Lean 4 source code (25k+ lines, 1.1k theorems/definitions)
- Pre-configured `.astrolabe/` directory with canvas layout and node positions

**What's removed:**
- Blueprint LaTeX files
- Home page / documentation build scripts

## Acknowledgments

Thanks to [Math Inc.](https://www.math.inc/) and the original contributors ([@augustepoiroux](https://github.com/augustepoiroux) and others) for creating this formalization using the Gauss autoformalization agent. See the [original repository](https://github.com/math-inc/strongpnt) for full details.

## Usage with Astrolabe

1. **Get Astrolabe** from [GitHub](https://github.com/Xinze-Li-Bryan/Astrolabe)

2. **Clone this template:**
   ```bash
   git clone https://github.com/Xinze-Li-Bryan/astrolabe-template-strongpnt.git
   cd astrolabe-template-strongpnt
   ```

3. **Build the Lean project** (requires [Lean 4](https://docs.lean-lang.org/lean4/doc/quickstart.html)):
   ```bash
   lake build
   ```

4. **Open in Astrolabe** - Launch Astrolabe and open this folder

## Project Structure

```
astrolabe-template-strongpnt/
├── .astrolabe/           # Astrolabe configuration
│   ├── canvas.json       # Node positions, camera state
│   ├── meta.json         # Node styles, notes
│   └── graph.json        # Parsed dependency cache
├── StrongPNT/            # Lean source files
├── lakefile.toml         # Lake build config
└── lean-toolchain        # Lean version
```

## Feedback

We welcome everyone to explore Lean 4 projects with Astrolabe! If you have any issues or suggestions, please report them to the [Astrolabe main repository](https://github.com/Xinze-Li-Bryan/Astrolabe/issues).

## License

See original project for license details.
