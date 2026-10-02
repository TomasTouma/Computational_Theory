# Computational Theory

Assessment repository for the Computational Theory module at ATU Fourth Year 2026/2027.

The work in this repository is based on the [Secure Hash Standard (FIPS 180-4)](https://doi.org/10.6028/NIST.FIPS.180-4). The main goal is to implement the SHA-256 hash function from scratch in Python and explain each step along the way.

## Contents

| File                | Description                                                  |
| ------------------- | ------------------------------------------------------------ |
| `problems.ipynb`    | Jupyter notebook containing my solutions to the problems     |
| `AGENTS.md`         | Instructions for AI coding agents, as required by the module |
| `requirements.txt`  | Python packages needed to run the notebook                   |
| `.gitignore`        | Files and folders excluded from version control              |

## Problems

| # | Problem                            | Status      | Issue                                                              |
| - | ----------------------------------- | ----------- | ------------------------------------------------------------------- |
| 1 | Representing SHA-256 Data           | ✅ Complete | [#1](https://github.com/TomasTouma/Computational_Theory/issues/1) |
| 2 | SHA-256 Bitwise Operations          | 🔄 In progress | [#2](https://github.com/TomasTouma/Computational_Theory/issues/2) |
| 3 | Generating the SHA-256 Constants    | ⏳ Not started | [#3](https://github.com/TomasTouma/Computational_Theory/issues/3) |
| 4 | Padding and Parsing Messages        | ⏳ Not started | [#4](https://github.com/TomasTouma/Computational_Theory/issues/4) |
| 5 | The SHA-256 Compression Function    | ⏳ Not started | [#5](https://github.com/TomasTouma/Computational_Theory/issues/5) |
| 6 | Complete SHA-256                    | ⏳ Not started | [#6](https://github.com/TomasTouma/Computational_Theory/issues/6) |


## Setup

You will need Python 3 and Git installed.

```bash
# 1. Clone the repository
git clone https://github.com/TomasTouma/Computational_Theory.git
cd Computational_Theory

# 2. Install the dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook problems.ipynb
```

### Using uv (optional)

If you use [uv](https://docs.astral.sh/uv/):

```bash
uv venv
uv pip install -r requirements.txt
uv run jupyter notebook problems.ipynb
```

## Author

Tomasz Touma (G00439630)