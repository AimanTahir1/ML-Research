# 🚀 Unleashing Neural Network Potential: A Deep Dive into Activation Functions

## 📚 Overview

In this exploration, I delve into the performance of various activation functions within a 3-layer neural network. The network architecture includes:

- **Input Layer**: 728 neurons
- **Hidden Layer**: 128 neurons
- **Output Layer**: 10 neurons

We evaluated three distinct activation functions to understand their impact on network performance:

1. **Sigmoid** 🌟
2. **Tanh** 🌟
3. **Tanh + Sin** 🌟

## 🔍 Activation Functions and Their Performance

- **Sigmoid**: Maps inputs to a range between 0 and 1. While it offers smooth gradients, it can suffer from vanishing gradients during training.

- **Tanh**: Transforms inputs to a range between -1 and 1. This function generally provides better performance due to its zero-centered output and wider range.

- **Tanh + Sin**: Combines `tanh` and `sin` functions to introduce additional non-linearity, potentially capturing more complex patterns in the data.

## 📊 Results

Testing accuracies for each activation function:

- **Sigmoid**: 77.75% 📉
- **Tanh**: 83.36% 📈
- **Tanh + Sin**: 84.35% 🏆

The combination of `tanh` and `sin` yields the highest accuracy, showcasing its ability to model intricate patterns more effectively than individual functions.

## 📈 Visual Analysis

To complement our performance evaluation, we created visualizations of these activation functions and their derivatives:

- **Tanh and Sin Functions**: Plots of `np.tanh` and `np.sin`, including their sum and the differences in their derivatives.

- **Tanh and Cosh Functions**: Analysis of `np.tanh` and `np.cosh`, focusing on their sum and differential.

- **Tanh and Sinh Functions**: Examination of `np.tanh` and `np.sinh`, their combined output, and the differential of their sum.

These plots provide insight into how these functions transform inputs and how their derivatives change, which is crucial for understanding their impact on neural network training dynamics.

## 🧠 Conclusion

Our analysis underscores the critical role of activation functions in optimizing neural network performance. The `tanh` + `sin` combination stands out, achieving superior accuracy and capturing complex data patterns more effectively. Choosing the right activation function is essential for enhancing model efficiency and learning capabilities.

---

Feel free to explore the visualizations and results to deepen your understanding of activation functions in neural networks!
