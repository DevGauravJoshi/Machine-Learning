<div align="center">
  <img src="https://github.com/DevGauravJoshi/Machine-Learning/assets/93304640/6180d408-452c-4c80-8a67-7524c830a01b" alt="Machine Learning" width="700px">

  <h1>
    Introduction to Machine Learning Essentials
  </h1>

  <p>A comprehensive repository designed for seamless model development and analysis. Harness the power of PyTorch, NumPy, Pandas, and Matplotlib in one unified framework. </p>
</div>

## Table of Contents
1. [Get Started](#Get-Started)
   1. [Set up a Virtual Environment](#Set-up-a-Virtual-Environment)
   2. [Install PyTorch](#Install-PyTorch)
   3. [Confirm PyTorch Installation](#Confirm-PyTorch-Installation)

## Get Started

Follow these steps to set up and run the project on your local machine.

### 1. Set up a Virtual Environment

#### Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

#### Windows

```bash
python -m venv venv
.\venv\Scripts\activate
```

#### macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 2. Install PyTorch

Visit the [official PyTorch website](https://pytorch.org/get-started/locally/) to find the installation command for your specific operating system and package manager.

### 3. Confirm PyTorch Installation

Create a Python script (e.g., `check_pytorch.py`) and add the following code:

```python
import torch
x = torch.rand(5, 3)
print(x)
```

Run the script:

```bash
python check_pytorch.py
```

The output should resemble the following:

```plaintext
tensor([[0.3380, 0.3845, 0.3217],
        [0.8337, 0.9050, 0.2650],
        [0.2979, 0.7141, 0.9069],
        [0.1449, 0.1132, 0.1375],
        [0.4675, 0.3947, 0.1426]])
```

If you see this output, PyTorch is successfully installed.

---
