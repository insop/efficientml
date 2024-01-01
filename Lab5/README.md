# Lab5

## Overview

Apply quantization and other methods (loop unrolling, multithreading, SMID), so that LLM can run on local machine.

Lab description can be found at
- [MIT_Efficient_AI_Lab_5_Optimize_LLM_on_Edge.pdf](MIT_Efficient_AI_Lab_5_Optimize_LLM_on_Edge.pdf)

## Preparation

```

# prepare environment
brew install boost
brew install llvm

# checkout tinychat-tutorial
git clone --recursive https://github.com/mit-han-lab/tinychat-tutorial

# download model
cd tinychat-tutorial
python download_model.py --model LLaMA_7B_2_chat --QM QM_ARM

```


