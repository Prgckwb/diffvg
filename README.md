# Diffvg
Diffvg Wheel of Python 3.10 + PyTorch 2.6.0+cu124

## Setup
```bash
# Create Environment
uv venv -p 3.10
source .venv/bin/activate

# Install diffvg wheel
uv pip install https://github.com/Prgckwb/diffvg/releases/download/v0.0.1/diffvg-0.1.0-cp310-cp310-linux_x86_64.whl
uv pip install matplotlib
```

## Citation
This repo is folk of https://github.com/BachiLi/diffvg/tree/master

```bibtex
@article{Li:2020:DVG,
    title = {Differentiable Vector Graphics Rasterization for Editing and Learning},
    author = {Li, Tzu-Mao and Luk\'{a}\v{c}, Michal and Gharbi Micha\"{e}l and Jonathan Ragan-Kelley},
    journal = {ACM Trans. Graph. (Proc. SIGGRAPH Asia)},
    volume = {39},
    number = {6},
    pages = {193:1--193:15},
    year = {2020}
}
```
