# Neural Network Implementation in Python

This repository contains the implementation of a two-layer perceptron neural network for function approximation, based on the research paper "Neural Network Programming in Python" by Primož Podržaj (2019) published in the International Journal of Innovative Technology and Exploring Engineering (IJITEE).

## 📑 Paper Reference
- **Title**: Neural Network Programming in Python
- **Author**: Primož Podržaj
- **Journal**: International Journal of Innovative Technology and Exploring Engineering (IJITEE)
- **Volume**: 8, Issue-6S4, April 2019
- **DOI**: 10.35940/ijitee.F1075.0486S419
- **Paper Link**: [Download PDF](https://www.ijitee.org/wp-content/uploads/papers/v8i6s4/F10750486S419.pdf)

## 🎯 Project Overview

This project implements a two-layer perceptron neural network that can be used for function approximation. The implementation follows the paper's methodology and includes:
- Creation of a feedforward neural network
- Training using backpropagation algorithm
- Function approximation demonstration
- Visualization of results
- Experimentation with different parameters

## 🛠️ Requirements

```
python >= 3.7
numpy
neurolab
matplotlib
```

## ⚙️ Installation

1. Clone this repository:
```bash
git clone https://github.com/agneya-1402/Neural_Network_v1.git
cd Neural_Network_v1
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## 📘 Usage

The implementation is available in two formats:
1. Jupyter/Google Colab notebook (`NeuralNetwork_1.ipynb`)

To use the Jupyter notebook:
1. Open Google Colab
2. Upload the notebook
3. Run cells sequentially

## 🔬 Experiments

The code allows for experimentation with various parameters:

1. Network Architecture:
   - Number of neurons in hidden layer
   - Input range
   - Transfer functions

2. Training Parameters:
   - Number of epochs
   - Learning goal
   - Number of training samples

3. Function Approximation:
   - Different target functions
   - Input data distribution
   - Training data size

## 📊 Results

The implementation produces two main visualizations:
1. Training error over epochs
2. Comparison between target function and network output

Key findings from the paper:
- Optimal performance with 15 neurons in hidden layer
- Training with 100 data points gives good results
- Both too few (<3) and too many (>200) neurons can lead to poor performance
- Training data quantity significantly impacts approximation quality

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🔎 Citation

If you use this implementation in your research, please cite the original paper:

```bibtex
@article{podrzaj2019neural,
  title={Neural Network Programming in Python},
  author={Podržaj, Primož},
  journal={International Journal of Innovative Technology and Exploring Engineering},
  volume={8},
  number={6S4},
  year={2019},
  publisher={Blue Eyes Intelligence Engineering & Sciences Publication}
}
```
