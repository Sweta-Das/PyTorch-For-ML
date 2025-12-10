# PyTorch-For-ML

Learning basics and advanced concepts of PyTorch

---

## About this repository

This repo collects interactive notebooks and examples that follow the LearnPyTorch.io style of practical, hands‑on PyTorch tutorials. The materials are organized to start from fundamentals (tensors, dtypes, devices) and progress to model building, training loops, data pipelines, and common deep learning workflows.

LearnPyTorch.io (https://www.learnpytorch.io) is a concise practical guide to PyTorch — the site provides step‑by‑step notebooks and explanations to help you build intuition and working knowledge of PyTorch APIs and common ML patterns. This repo contains companion notebooks you can run locally or in Colab.

---

## Recommended learning path

1. Fundamentals — tensors, shapes, datatypes, device handling, basic ops.  
2. Models & Layers — torch.nn, building simple networks.  
3. Training — loss, optimizers, training loop, metrics.  
4. Data — Dataset, DataLoader, transforms.  
5. Transfer learning & vision tasks — prebuilt models, finetuning.  
6. Projects & deployment — end‑to‑end examples.

Start with: Fundamentals/0_pytorch_fundamentals.ipynb

---

## Run the notebooks (macOS)

1. Create and activate a virtual environment:
   ```
   python3 -m venv .venv
   source .venv/bin/activate
   ```
2. Upgrade pip and install essentials:
   ```
   pip install -U pip
   pip install jupyterlab
   ```
3. Install PyTorch (follow official selector at https://pytorch.org/get-started/locally for the best command for your macOS/Apple Silicon/CPU/GPU):
   ```
   # Example (CPU): adjust per instructions on pytorch.org
   pip install torch torchvision torchaudio
   ```
4. Launch JupyterLab / Notebook:
   ```
   jupyter lab
   ```
   or
   ```
   jupyter notebook Fundamentals/0_pytorch_fundamentals.ipynb
   ```

You can also open notebooks directly in VS Code or run them in Google Colab (many notebooks include a Colab badge/link).

---

## Notes & tips

- When debugging PyTorch errors, check: shape, dtype, device (CPU vs GPU/MPS).  
- Use small reproducible examples when experimenting with new operations.  
- Refer to the official PyTorch docs for API details: https://pytorch.org/docs

---

## Credits & resources

- Primary learning resource: https://www.learnpytorch.io (use the site for tutorials and up‑to‑date examples).  
- Official PyTorch docs: https://pytorch.org/docs

---

## Contributing

Add notebooks, exercises, or fixes via pull requests. Keep notebooks small and focused; include a short description at the top of each notebook.

--- 

## License

This repository is for personal learning. Check licensing of any upstream materials.