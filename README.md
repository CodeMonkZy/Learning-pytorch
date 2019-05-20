# Learning-pytorch
## 1.tensor和ndarray的转换
#### a为ndarray，转换为tensor类型
b = torch.from_numpy(a)
#### a为tensor，转换为ndarray类型
b = a.numpy()
#### weights为requires_grad=True的tensor，转换为ndarray类型
weights.detach().numpy()
