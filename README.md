# Learning-pytorch
## 1. tensor和ndarray的转换
### (1) a为ndarray，转换为tensor类型
b = torch.from_numpy(a)
### (2) a为tensor，转换为ndarray类型
b = a.numpy()
### (3) weights为requires_grad=True的tensor，转换为ndarray类型
weights.detach().numpy()
