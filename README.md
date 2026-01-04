# Zero Calculator(ZCalc)
A High-Precision Scientific Calculator Engineered for Extreme Computation

Live Demo: [https://zcalc.vercel.app](https://zcalc.vercel.app)

ZCalc is a browser-based scientific calculator built with TypeScript and React that delivers unprecedented numerical precision — supporting calculations with up to **500 fractional digits**. Unlike conventional calculators that fail at large computations, ZCalc handles massively intensive operations — such as factorial of 1,000,000 — accurately and efficiently.

## 🚀 What Makes ZCalc Unique
- **Extreme Precision**: Renders results with up to 500 decimal places, far beyond standard calculators.

- **Performance at Scale**: Computes enormous values (e.g., 1000000!) in seconds, not errors.

- **Reliable & Accurate**: Powered by the MPFR library compiled to WebAssembly for mathematically correct floating-point operations.

- **Clean Expression Parsing**: Uses Ohm.js for robust, unambiguous parsing of complex mathematical expressions.

## 🔬 Technical Highlights
- **Frontend**: React with TypeScript

- **Computation Core**: MPFR (via WebAssembly) for arbitrary-precision arithmetic

- **Parser**: Ohm.js for constructing AST and interpreting operations

- **Deployment**: Static hosting (Vercel) – no backend required

- **Interactive Features**:

  - Trigonometry (sin, cos, tan) and inverses

  - Logarithms (log, ln)

  - Factorials, powers, roots

  - Unit conversion (rad/deg)

  - Percentage and reciprocal operations

  - Scientific notation (e.g., 1e5) support

## 📊 Performance Examples

| Operation | Typical Calculator | ZCalc Result |
|:--:|:------------:|:--:|
| 10000! | Overflow/Infinity | 2.84625968... × 10^35659 (full precision) |
| √8 | 2.82842712475 | 2.8284271247461900976033774484... (500 digits)|
| 1000000! | Fails/crashes | 8.263931688... × 10^5565708 (~5 seconds on mobile) |


## 🛠️ Getting Started
Visit the [https://zcalc.vercel.app](https://zcalc.vercel.app) to start calculating with extreme precision — no installation required.


## License and AI Training
This project is licensed under the GNU General Public License v3.0 (GPLv3).

The authors of this software consider the use of this code, including its source code, documentation, and any other project artifacts, for the training of artificial intelligence (AI) systems (including but not limited to machine learning, large language models, and other AI technologies) to be creating a derivative work. As such, any entity using this code for such purposes must comply with the terms of the GPLv3. This includes, but is not limited to, making the entire source code of the AI system that uses this code available under the same GPLv3 license.

If you wish to use this code for AI training without being subject to the GPLv3, please contact the authors to negotiate a separate license.
