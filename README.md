# Lab 1: Quantum Algorithms

Welcome to **Lab 1: Quantum Algorithms**! This hands-on lab will guide you through the practical implementation of several essential quantum algorithms using **Qiskit**. Whether you're new to quantum computing or have some experience, this lab provides an interactive environment to learn and experiment with key quantum algorithms.

---

## 🚀 What You Will Learn

This lab introduces both **basic** and **intermediate** quantum algorithms that leverage the power of quantum mechanics. By the end of the lab, you will have practical experience coding quantum algorithms in Python using the **Qiskit framework**.

**This repository contains a collection of quantum algorithms adapted from the [Qiskit Community Tutorials](https://github.com/qiskit-community/qiskit-community-tutorials). The original implementations can be found in the following sections of the community repository:**

* [Coding with Qiskit](https://github.com/qiskit-community/qiskit-community-tutorials/tree/master/Coding_With_Qiskit)
* [Algorithms](https://github.com/qiskit-community/qiskit-community-tutorials/tree/master/algorithms)

These algorithms have been **modified to work with the latest version of Qiskit** and tested to ensure compatibility with recent updates.


### 🧠 Topics Covered:

---

### **Basic Quantum Algorithms**

1. **Quantum Random Number Generator (QRNG)**
   Explore how quantum mechanics can be used to generate truly random numbers. In this section, you will learn about the inherent randomness in quantum systems and how it differs from classical random number generation.
   Learn more:

   * [Creating a Quantum Random Number Generator with IBM’s Qiskit (medium)](https://zach1020.medium.com/creating-a-quantum-random-number-generator-with-ibms-qiskit-48a90383490c)

2. **Deutsch's Algorithm**
   Learn how **Deutsch's Algorithm** demonstrates a quantum advantage by determining whether a Boolean function is constant or balanced with a single quantum query. This foundational algorithm highlights how quantum computing can solve certain problems more efficiently than classical computers.
   Learn more:

   * [Quantum query algorithms](https://learning.quantum.ibm.com/course/fundamentals-of-quantum-algorithms/quantum-query-algorithms)

3. **Bell State Generation**
   Discover **entanglement**, one of the most profound phenomena in quantum mechanics. You will learn how to create **Bell states**, which are maximally entangled quantum states of two qubits. These states are a core resource for many quantum communication and computation protocols.
   Learn more:

   * [Introduction to Bell States](https://quantumcomputinguk.org/tutorials/introduction-to-bell-states)

---

### **Intermediate Quantum Algorithms**

4. **Deutsch-Jozsa Algorithm**
   This algorithm demonstrates how quantum computers can outperform classical ones in determining whether a function is constant or balanced with exponential speed-up. You will explore the power of quantum parallelism and how this algorithm uses quantum states to test multiple possibilities at once.
   Learn more:

   * [Quantum query algorithms](https://learning.quantum.ibm.com/course/fundamentals-of-quantum-algorithms/quantum-query-algorithms)

5. **Bernstein-Vazirani Algorithm**
   Learn how the **Bernstein-Vazirani Algorithm** allows quantum computers to extract a hidden bit string from a black-box function, solving the problem exponentially faster than classical computers.
   Learn more:

   * [Bernstein-Vazirani Algorithm on IBM Quantum](https://docs.quantum.ibm.com/api/qiskit/0.31/qiskit.aqua.algorithms.BernsteinVazirani)

6. **Quantum Teleportation**
   Get introduced to the concept of **quantum teleportation**, which allows the transfer of quantum states across space, without physically moving the qubits themselves. This fascinating application demonstrates the non-local nature of quantum entanglement.
   Learn more:

   * [Entanglement in action](https://learning.quantum.ibm.com/course/basics-of-quantum-information/entanglement-in-action)

---

## 🧑‍💻 How to Use the Notebooks

You can easily run the notebooks in this repository directly on **Google Colab**. Just follow these simple steps:

### 1. **Open the Notebooks in Google Colab**

Click the links below to open each notebook in **Google Colab**:

Created using Colab
* [Quantum Random Number Generator (QRNG)](https://colab.research.google.com/github/v2rinku/Lab-1-Quantum-Algorithm/blob/main/QRNG_Algo.ipynb)
* [Deutsch's Algorithm](https://colab.research.google.com/github/v2rinku/Lab-1-Quantum-Algorithm/blob/main/Deutsch_algo.ipynb)
* [Bell State Generation](https://colab.research.google.com/github/v2rinku/Lab-1-Quantum-Algorithm/blob/main/Create_Bell_states.ipynb)
* [Deutsch-Jozsa Algorithm](https://colab.research.google.com/github/v2rinku/Lab-1-Quantum-Algorithm/blob/main/DJ_algo.ipynb)
* [Bernstein-Vazirani Algorithm](https://colab.research.google.com/github/v2rinku/Lab-1-Quantum-Algorithm/blob/main/Bernstein_Vazirani_Algorithm.ipynb)
* [Quantum Teleportation](https://colab.research.google.com/github/v2rinku/Lab-1-Quantum-Algorithm/blob/main/Quantum_Teleportation.ipynb)

### 2. **Set Up Qiskit in Google Colab**

When you open a notebook for the first time, run the following cell to install the **Qiskit** package and set up your environment:

```python
!pip install qiskit qiskit_aer qiskit-ibm-runtime matplotlib pylatexenc 
 
```

This will install the required quantum programming tools for running the algorithms.

### 3. **Run the Cells**

Each notebook contains cells with code to implement and execute the quantum algorithms. Simply click "Run All" in Google Colab to execute all the cells and observe the results.

### 4. **Explore and Modify**

Feel free to modify the code, change parameters, or experiment with different quantum circuits. Google Colab makes it easy to collaborate with others or share your results with a single link.

---

## 🛠️ Requirements

* **Google Colab** (No installation needed, as everything runs in the cloud)
* **Qiskit** (Automatically installed in Colab using `!pip install`)

---
## Explore More

To discover additional algorithms and quantum programming examples, visit the [Qiskit Community Tutorials – Algorithms](https://github.com/qiskit-community/qiskit-community-tutorials/tree/master/algorithms) section.

## 🌐 Additional Resources

* [IBM Quantum - Learn Quantum Computing](https://quantum-computing.ibm.com)
* [Qiskit Documentation](https://qiskit.org/documentation/)
* [Quantum Computing Fundamentals](https://www.ibm.com/blogs/5-quantum-computing-fundamentals/)

---
  
## 🤝 Acknowledgments

* **IBM Quantum** for providing the tools and resources for quantum computing.
* **Qiskit** for the open-source quantum programming framework.
* All the resources and tutorials from IBM Quantum to help understand quantum algorithms.

---
 
Happy coding, and enjoy your quantum journey! 🚀👩‍💻👨‍💻

--- 
