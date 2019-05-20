# Learning-pytorch
## 1. tensor和ndarray的转换
### (1) a为ndarray，转换为tensor类型
b = torch.from_numpy(a)
### (2) a为tensor，转换为ndarray类型
b = a.numpy()
### (3) weights为requires_grad=True的tensor，转换为ndarray类型
weights.detach().numpy()


## 2. PyTorch之保存加载模型
  https://www.jianshu.com/p/4905bf8e06e5  官网翻译
  https://ldzhangyx.github.io/2018/11/19/pytorch-1119/  PyTorch模型加载与保存的最佳实践
