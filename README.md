# TvaraLLM

TvaraLLM aims to provide a high-performance, minimalistic framework that seamlessly integrates into various LLM workflows, ensuring speed and efficiency without compromising functionality.

Key Features:
- Rapid inference and advanced optimizations
- Streamlined training and fine-tuning of models
- Minimal abstraction layers for direct control and maximum performance
- Designed for ease of integration and use across diverse LLM applications

## Getting Started with Development

Create a new conda environment and install the dependencies:

```bash
conda create -n tvarallm python=3.12
conda activate tvarallm
```

Run the tests:

```bash
# install dependencies
pip install -e .[dev]

# run tests
cd tvarallm
pytest --cov=tvarallm tests/
```
