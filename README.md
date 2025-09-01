# 2025_Deep_Challenge


```
conda create -n qwen25 python=3.10 -y
conda activate qwen25

pip install --upgrade pip setuptools wheel

pip install --index-url https://download.pytorch.org/whl/cu121 torch==2.4.1 torchvision==0.19.1
pip install -r requirements.txt
```

## 0. 학습 데이터에서 train/val 데이터 분리

## 1. Qwen2.5-VL-7B 모델 LoRA fine-tuning

## 2. Fine-tuned model로 task 수행



