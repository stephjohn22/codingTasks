<a id="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#project-description">Project Description</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a>
      <ul>
        <li><a href="#neuron-activation-functions">Neuron Activation Functions</a></li>
        <li><a href="#logic-gates-modelling">Logic Gates Modelling</a></li>
        <li><a href="#matrix-computations">Matrix Computations</a></li>
      </ul>
    </li>
    <li><a href="#credits">Credits</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Welcome to the "Exploring Neural Networks" project repository! This repository hosts a Jupyter Notebook titled "Exploring Neural Networks.ipynb" that serves as a practical exploration into fundamental concepts of neural networks using Python and NumPy.

**Exploring Neural Networks**

### Project Description

The "Exploring Neural Networks" project dives deep into the foundational principles of neural networks. It covers topics such as neuron activation functions, modelling of logic gates using neurons, and matrix computations for network layers. Understanding these concepts is crucial for anyone interested in delving into machine learning and artificial intelligence.

**Key Features**

* **Neuron Activation Functions:** Understand how neurons process inputs using activation functions like the sigmoid function.
* **Logic Gates Modelling:** Implement neural networks to mimic behaviour of basic logic gates such as OR, AND, NOR, and NAND gates.
* **Matrix Computations:** Explore how neural networks are represented and manipulated using matrix computations for efficient processing.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

Make sure you have the following installed:

Python: Ensure Python is installed on your system. You can download it from python.org if not already installed.

JypterNotebook: Ensure JypterNotebook is installed. to download it:
   ```sh
   pip install notebook
   ```
Install the libraries:
   ```sh
   pip install numpy
   pip intall matplotlib
   ```

### Installation

1. Clone the Repository:
   ```sh
   git clone https://github.com/stephjohn22/codingTasks.git
   ```
2. Navigate to the Directory:
   ```sh
   cd codingTasks
   ```
3. Create a Virtual Environment (Optional but Recommended):
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Explore the Jupyter Notebook "Exploring Neural Networks.ipynb" to learn and experiment with neural network concepts firsthand. Follow along with detailed explanations, code examples, and visualizations provided in the notebook. Below are examples of how you can use and experiment with the concepts covered in the notebook.

### Neuron Activation Functions

Explore how different activation functions affect neuron outputs. Run the code cells provided in the notebook to visualise the sigmoid function and its impact on neuron activation.

**Visualise the Sigmoid Function:**<br>
The sigmoid function is commonly used in neural networks as an activation function. It maps any input value to a range between 0 and 1, which helps in normalising the output of each neuron. The diagrams below show the sigmoid function is plot and how it transforms different input values. This visualisation helps in understanding how the sigmoid function behaves and its role in neural networks.

![Screenshot 2024-06-30 164707](https://github.com/stephjohn22/codingTasks/assets/163042398/0927a3c1-fc82-4220-9b7a-e1fc71bba98b)
![Screenshot 2024-06-30 164733](https://github.com/stephjohn22/codingTasks/assets/163042398/90957204-9693-43da-87cb-aad97884ff0d)

### Logic Gates Modelling

Demonstrate how neurons can be used to model logic gates such as OR, AND, NOR, and NAND gates. Run the code cells provided in the notebook to see the implementation of logic gates

**Implement Neurons as Logic Gates:**<br>
Logic gates like OR, AND, NOR, and NAND can be simulated using neurons by setting appropriate weights and biases. The diagrams below show how a logic gate is cretated and how its weights and bias are used to verify thier truth tables.

![Screenshot 2024-06-30 183045](https://github.com/stephjohn22/codingTasks/assets/163042398/c0601b27-790f-4de5-9203-73a7e0217601)
![Screenshot 2024-06-30 183201](https://github.com/stephjohn22/codingTasks/assets/163042398/28cbe452-1b3a-45c6-8d47-ea01d45528cb)
![image](https://github.com/stephjohn22/codingTasks/assets/163042398/960df30e-a150-4992-8e5c-4f8a0e9cee15)


### Matrix Computations

Understand the role of matrix computations in neural networks. Implement network layers using matrix multiplication and activation functions to see how inputs are processed and transformed through multiple layers.

Implement Network Layers Using Matrix Multiplication:
Instead of handling individual neurons, neural networks often work with layers of neurons. Each layer performs matrix multiplication of the input vector with a weight matrix, adds a bias vector, and applies an activation function. The diagrams below show how to implement these layers and how inputs are processed through the network. Experimenting with different weight matrices and biases affect the output of the network.

![image](https://github.com/stephjohn22/codingTasks/assets/163042398/fba7eeb3-a298-4b68-9763-1418d0c164e9)
![image](https://github.com/stephjohn22/codingTasks/assets/163042398/b3d110a7-bb8e-4aef-b866-93f5fcf78536)
![image](https://github.com/stephjohn22/codingTasks/assets/163042398/0e74a632-e673-4eb9-bdbd-1d502a73bae8)

### Additional Resources

For more examples and detailed explanations, refer to these links:<br>
[Exploring Neural Networks](https://www.kdnuggets.com/exploring-neural-networks)
[Neural Networks: Exploring the Basics and Building from Scratch](https://www.pullrequest.com/blog/deep-dive-into-neural-networks-building-and-training-from-scratch/)
[Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)<br>
[Activation Functions in Neural Networks](https://towardsdatascience.com/activation-functions-neural-networks-1cbd9f8d91d6)<br> [Logic Gates – Definition, Types, Uses](https://www.geeksforgeeks.org/logic-gates/?ref=header_search)<br>
[Neural Representation of AND, OR, NOT, XOR and XNOR Logic Gates (Perceptron Algorithm)](https://medium.com/@stanleydukor/neural-representation-of-and-or-not-xor-and-xnor-logic-gates-perceptron-algorithm-b0275375fea1)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CREDITS -->
## Credits

- Developed by [Stephanie Johnson](https://github.com/stephjohn22)


<p align="right">(<a href="#readme-top">back to top</a>)</p>
