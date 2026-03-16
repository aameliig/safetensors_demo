# Safetensors: demonstartion

This is a short demonstartion of [safetensors library](https://github.com/huggingface/safetensors) by Hugging Face - a secure and fast format for storing ML-model weights.

The demonstration is made in `.ipynb` format. You can use Google Colab, Kaggle, Jupyter or any other preferred editor.

No special requirements (except `torch >= 2.0`) are needed.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aameliig/safetensors_demo/blob/main/safetensors_demo.ipynb)


## Notebook contents

1. Problem setup — why pickle is dangerous and what `.safetensors` actually is (explained)
2. DOS attack demo — how a `.pt` file executes arbitrary code on load
3. Basic safetensors usage — saving and loading weights
4. Metadata inspection — browsing file contents without loading tensors
5. Lazy loading — loading only the layers you need
6. Speed comparison — safetensors vs pickle on a ~200 MB file
7. Multi-framework support — save with NumPy, load with PyTorch

**Useful Links:** 
- [GitHub](https://github.com/huggingface/safetensors)
- [Documentation](https://huggingface.co/docs/safetensors)
- [Speed Comparison](https://huggingface.co/docs/safetensors/speed)
