# ResNet：Deep Residual Learning for Image Recognition

![031.png](031.png)

理论上越深的层，如果看作在较浅层的神经网络的扩充，那么理论上可以做到完全的复制，但实际上并不能做到

之前的神经网络如果是想训练来拟合一个函数H(X)，那么残差神经网络是想训练来拟合函数F(X)=H(X)-X，这样训练出来的神经网络可以更容易做到恒等变换。H(X)就可以通过shortcut connection来计算