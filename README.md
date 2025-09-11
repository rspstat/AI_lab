# AI_lab

- **Name:** Gyu-Hyeon Kim (2021041017)  
- **Course:** 2025-2 Artificial Intelligence  

## Development Environment

### Hardware
- **GPU:** NVIDIA T4 (Google Colab)  
- **CUDA Support:** Available (1 device)  

### Software Stack
- **Python:** 3.13.7
- **PyTorch:** 2.8.0+cu126 (CUDA-enabled)  
- **Jupyter Notebook:** Configured and operational (via Google Colab)  

### Environment Status
- ✅ PyTorch successfully imported and functional  
- ✅ CUDA acceleration available  
- ✅ Tensor operations working correctly  
- ✅ GPU-accelerated deep learning ready  

## Quick Environment Check
- Run the first cell in **`week2.ipynb`** to verify PyTorch installation and CUDA availability.  

```python
import torch
print("PyTorch version:", torch.__version__)
print("CUDA available:", torch.cuda.is_available())
print("Device name:", torch.cuda.get_device_name(0) if torch.cuda.is_available() else "CPU")
