 
# qBraid Platform Guide

## 🧠 What is qBraid?

[qBraid](https://www.qbraid.com) is a cloud-based platform designed for quantum computing development. It provides a unified environment for programming with popular quantum software frameworks like **Qiskit**, **Cirq**, **PennyLane**, and more. With integrated Jupyter Notebooks, GPU/CPU backends, and quantum hardware access, qBraid makes it easy for users to build, simulate, and deploy quantum applications all in one place.

---

## 📝 How to Create a qBraid Account

Follow these steps to create an account on the qBraid platform:

1. Visit the official site: [https://www.qbraid.com](https://www.qbraid.com)
2. Click on **“Sign Up”** in the upper-right corner.
3. Choose to sign up using:
   - Your **email and password**, or
   - A **Google** or **GitHub** account
4. Verify your email if prompted.
5. After registration, log in at [app.qbraid.com](https://app.qbraid.com) to access the development environment.

---

## ⚛️ Running Qiskit on qBraid

Once you're logged in, follow these steps to use Qiskit on qBraid:

### Step 1: Open a JupyterLab Workspace
- From the qBraid dashboard, click **“Launch Lab”**.
- This opens a JupyterLab environment in your browser.

### Step 2: Create a New Notebook
- In JupyterLab, click **File > New > Notebook**.
- Select **Python 3 (ipykernel)** as your kernel.

### Step 3: Import and Use Qiskit
qBraid comes with Qiskit pre-installed. You can start using it immediately.

Here's a sample code snippet to verify:

```python
from qiskit import QuantumCircuit, transpile, Aer, execute

# Create a simple circuit
qc = QuantumCircuit(2)
qc.h(0)
qc.cx(0, 1)
qc.measure_all()

# Run the circuit on the qasm simulator
simulator = Aer.get_backend('qasm_simulator')
result = execute(qc, simulator, shots=1024).result()
counts = result.get_counts()

print("Measurement results:", counts)
````

### Step 4: (Optional) Use Real Quantum Hardware

* To run on real IBM quantum hardware, you can set your IBMQ account token:

  ```python
  from qiskit import IBMQ
  IBMQ.save_account('YOUR_IBM_TOKEN', overwrite=True)
  IBMQ.load_account()
  ```
* qBraid also supports hardware access via integrated providers (depending on your plan).

---

## 📚 Resources

* [qBraid Docs](https://docs.qbraid.com/)
* [Qiskit Documentation](https://qiskit.org/documentation/)
* [qBraid GitHub](https://github.com/qBraid)

---

## ✅ Summary

qBraid provides a ready-to-use quantum development environment that simplifies the process of working with frameworks like Qiskit. From account creation to executing real quantum circuits, it's a powerful platform for developers, researchers, and learners alike.

```
 
