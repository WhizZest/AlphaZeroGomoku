# AlphaZeroGomoku
AlphaZeroGomoku

# 运行环境
1. python > 3.10
2. pytorch

# 环境安装步骤：
1. 创建conda环境：
   ```
   conda create -n py312_torch python=3.12
   ```
2. 激活conda环境：
   ```
   conda activate py312_torch
   ```
3. 检查NVIDIA CUDA版本：
   ```
   nvidia-smi
   ```
4. 根据CUDA版本修改这条命令：
   ```
   pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
   ```
5. 安装其他依赖：
   ```
   conda install matplotlib keyboard scipy joblib opencv pyautogui -y
   ```