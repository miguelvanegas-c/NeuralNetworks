# NeuralNetworks

Workshop on a boot camp for agents and artificial intelligence.

## 📖 Learning Objectives

- Understand neural network fundamentals
- Implement backpropagation manually
- Design and justify CNN architectures
- Analyze the role of inductive bias
- Compare different architectural choices

## 🎯 Topics Covered

- Artificial neurons and activation functions
- Forward and backward propagation
- Loss functions and optimization
- Convolutional layers and pooling
- Translation equivariance and weight sharing
- Receptive fields and hierarchical features

## 📊 Datasets Used

- MNIST: Handwritten digit recognition (28×28 grayscale)
- CIFAR-10: Object classification (32×32 RGB, 10 classes)

## 👨‍💻 Author

Miguel Vanegas

## Summary and Conclusions

### What We Learned:

1. **Neural networks are not black boxes**—architectural choices encode assumptions

2. **Convolutional layers introduce inductive bias** for spatial data:
   - Locality
   - Stationarity
   - Compositionality

3. **This bias improves performance** on images:
   - Fewer parameters
   - Better generalization
   - Faster convergence

4. **Design choices matter**:
   - Kernel size affects receptive field and parameter count
   - Smaller kernels (3×3) often outperform larger ones
   - Depth builds hierarchical representations

5. **Convolution is not universal**:
   - Fails on tabular data, graphs, unstructured sets
   - Only works when spatial structure exists
