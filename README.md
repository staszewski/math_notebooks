# Math Learning Repository

A repository for learning mathematics through interactive Python notebooks.

## Structure

- `probability/` - Probability theory and statistics concepts

## Setup

### Local Development (with uv)

This project uses [uv](https://github.com/astral-sh/uv) for fast, reliable dependency management.

1. **Install uv** (if not already installed):
   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```

2. **Create and activate virtual environment**:
   ```bash
   uv venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   uv pip install -r requirements.txt
   ```

4. **Launch Jupyter**:
   ```bash
   jupyter lab
   ```
   or
   ```bash
   jupyter notebook
   ```

### Kaggle

To use these notebooks on Kaggle:

1. Upload the notebook file (`.ipynb`) to Kaggle
2. The required packages (numpy, scipy, matplotlib, pandas, etc.) are pre-installed on Kaggle
3. For any additional dependencies, use:
   ```python
   !pip install -r requirements.txt
   ```

## Dependencies

- **numpy** - Numerical computing
- **scipy** - Scientific computing and statistics
- **sympy** - Symbolic mathematics
- **matplotlib** - Plotting and visualization
- **seaborn** - Statistical data visualization
- **plotly** - Interactive plots
- **pandas** - Data manipulation and analysis
- **jupyter/jupyterlab** - Interactive notebook environment

## Usage

Each topic folder contains numbered notebooks that can be worked through sequentially. The notebooks include:
- Theoretical explanations
- Code examples
- Visualizations
- Practice exercises

## Contributing

This is a personal learning repository, but suggestions and corrections are welcome!

