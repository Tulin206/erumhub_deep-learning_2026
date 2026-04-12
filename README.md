# Deep Learning Exercises for Beginners

Welcome! 👋 This is a **learning repository** with simple exercises about **neural networks** (AI that learns from data).

## What Will You Learn?

In this repository, you will learn:

- **What is a Neural Network?** - How computers learn to make decisions.
- **How to Build a Network** - Create networks using Python and TensorFlow.
- **How to Train a Network** - Teach the network to learn from examples.
- **How to Use Networks** - Use networks to classify data (like recognizing animals).
- **Basic Concepts** - Learn activation functions, loss, and optimization.

---

## 📋 Participant Feedback & Learning Tracking

We would love to hear from you! **After completing this course**, please share your experience and feedback:

### **How to Participate:**

1. **Before or During the Course:** Fill in your details in this [**Shared Feedback Table**](https://notes.desy.de/L43d4d93TOWYpuDy-EcBkA?both)

2. **Information to Share:**
   - **Your Name:** Your first and last name
   - **Your Profession:** What do you do? (e.g., Software Engineer, Data Scientist, Student, etc.)
   - **ML Experience Level:** Your experience with machine learning (e.g., Beginner, Intermediate, Advanced, None)

3. **At the End of the Course:** Return to the same table and add:
   - **Your Feedback:** What did you learn? What was helpful? What could be improved?
   - **Exercises Completed:** Which exercises did you complete?
   - **Any Additional Comments:** Questions, suggestions, or ideas for improvement

### **Why Your Feedback Matters:**

- 📊 **Help us improve:** Your feedback helps us create better learning materials
- 🎯 **Track your progress:** See how far you've come from start to finish
- 🤝 **Build community:** Connect with other learners on the same journey
- 💡 **Make it better:** Your suggestions shape future versions of these exercises

**👉 [Open the Feedback Table Here](https://notes.desy.de/L43d4d93TOWYpuDy-EcBkA?both)**

---

## 🚀 Core Learning Path: Master Deep Learning & FCNNs (Recommended)

### **Follow This Order: 01 → 02 → 03 → 05 → 07 → 08**

This is the **best path** to understand **Fully Connected Neural Networks (FCNNs)** completely. It takes about **6-8 hours** and builds from basic concepts to professional tools.

---

## What Exercises Are Here? (Learn in Order 👇)

Follow the numbers from **01 → 10**. Each lesson builds on the previous one!

| # | Exercise | Topic | What You Learn |
|---|----------|-------|----------------|
| 1️⃣ | 01_Building_Blocks_Binary_Classification | Basic Concepts | Learn what a neuron is and how it works (simple flower classification) |
| 2️⃣ | 02_Activation_Functions_Theory | Activation Functions | Understand WHY we need activation functions and how they work |
| 3️⃣ | 03_Simple_NN_Iris_Classification | Multi-Class with NumPy | Build a network from scratch using only NumPy (Iris flowers - 3 types) |
| 4️⃣ | 04_Networks_as_Code_Penguin_Classification & Wine_Classification | Real Project with Keras | Use TensorFlow/Keras to classify real penguin data (3 species) and wine data |
| 5️⃣ | 05_Feedforward_Squirrel_Classification | More Practice | Classify squirrels using a feedforward network (2 types) |
| 6️⃣ | 06_Building_NN_From_Scratch_Advanced | Advanced From Scratch | Write complete network code without using Keras |
| 7️⃣ | 07_Monitor_Training_Weather_Regression | Training Monitoring | Learn regression and watch how the network learns over time |
| 8️⃣ | 08_Deep_Learning_With_PyTorch_MNIST | Deep Learning | Learn PyTorch and build deeper networks (MNIST digit recognition) |
| 9️⃣ | 09_AlexNet_CIFAR10 | CNN Architectures | Build an AlexNet-style convolutional neural network to classify CIFAR10 images |
| 🔟 | 10_VGG_CIFAR10 | Advanced CNNs | Implement a VGG-like network with multiple convolutional blocks for image classification |

---

## 📚 Detailed Learning Path Breakdown

### **PHASE 1: Foundation - Understanding Neural Networks from Scratch**

#### **Exercise 01: Building Blocks - Binary Classification** 🧱
**File:** `01_Building_Blocks_Binary_Classification_exercise.ipynb`

**What it's about:**
- Build the **simplest neural network** possible: Just 1 neuron!
- Classify flowers into 2 types (Iris-Setosa vs Iris-Versicolor)
- Completely from scratch using **only NumPy** (no frameworks)
- Dataset: 8 flower samples with petal measurements

**What you'll learn:**
- ✅ **Neurons:** How do they work? (weights, bias, input, output)
- ✅ **Forward propagation:** How to make predictions
- ✅ **Sigmoid activation:** Why squash outputs to 0-1?
- ✅ **MSE loss function:** How to measure if you're wrong
- ✅ **Backpropagation:** How neurons learn from mistakes
- ✅ **Gradient descent:** How to adjust weights to reduce errors
- ✅ **Training loop:** Repeat forward pass → loss → backprop → update 100 times

**Key formulas:**
- Weighted sum: `z = (w₀ × x₀) + (w₁ × x₁) + bias`
- Sigmoid: `σ(z) = 1 / (1 + e^(-z))`
- MSE Loss: `Loss = mean((y_true - y_pred)²)`
- Weight update: `w = w + learning_rate × gradient`

**Time:** 1-2 hours | **Outcome:** Understand the core building block of all neural networks! 🎯

---

#### **Exercise 02: Activation Functions Theory** ⚡
**File:** `02_Activation_Functions_Theory.ipynb`

**What it's about:**
- Deep dive into **WHY** activation functions exist
- Compare **Sigmoid, ReLU, Tanh** and understand when to use each
- Visual demonstrations and mathematical explanations
- Understand the **vanishing gradient problem**

**What you'll learn:**
- ✅ **Sigmoid:** `σ(x) = 1 / (1 + e^(-x))` → Range: 0 to 1 (good for probabilities)
- ✅ **ReLU:** `f(x) = max(0, x)` → Range: 0 to ∞ (no vanishing gradient!)
- ✅ **Tanh:** Range -1 to 1 (centered, often better than sigmoid)
- ✅ **Vanishing gradient problem:** Why deep networks struggle with sigmoid
- ✅ **When to use each:** Output layer vs hidden layers, binary vs multi-class
- ✅ **ReLU advantage:** Modern networks use ReLU in hidden layers because it's faster

**Key insight:** "Activation functions make networks non-linear. Without them, deep networks are just linear math!" 🧠

**Time:** 1 hour | **Outcome:** Understand why ReLU is better than sigmoid for hidden layers!

---

#### **Exercise 03: Multi-Class Classification with NumPy** 🌸
**File:** `03_Simple_NN_Iris_Classification_exercise.ipynb`

**What it's about:**
- Build a **2-layer neural network** from scratch (1 hidden + 1 output layer)
- Classify 3 iris species (3-class problem, not binary!)
- Still using **only NumPy** - understand every detail
- Dataset: 150 iris flowers, 4 features (sepal/petal measurements)

**What you'll learn:**
- ✅ **One-hot encoding:** Convert labels to vectors `[1,0,0]`, `[0,1,0]`, `[0,0,1]`
- ✅ **Data preprocessing:** Min-max scaling to 0-1 range (networks learn faster!)
- ✅ **Network architecture:** Input(4) → Hidden(6) → Output(3)
- ✅ **Forward propagation through 2 layers:** With sigmoid then softmax
- ✅ **Softmax activation:** Convert to probabilities that sum to 1.0
- ✅ **Cross-Entropy loss:** Better than MSE for multi-class classification
- ✅ **Backpropagation through 2 layers:** Chain rule with matrix operations
- ✅ **Matrix multiplication:** Efficient computation with @ operator

**Key formulas:**
- One-hot: `y = [1 if i==label else 0 for i in range(num_classes)]`
- Softmax: `P = e^z / sum(e^z)`
- Cross-Entropy: `L = -mean(y × log(P))`
- Magic gradient: `dL/dz = P - y`

**Time:** 2-3 hours | **Outcome:** Understand hidden layers + multi-class + backpropagation! 🔄

---

### **PHASE 2: Real-World Challenges**

#### **Exercise 05: Feedforward Advanced - Squirrel Classification** 🐿️
**File:** `05_Feedforward_Squirrel_Classification_exercise.ipynb`

**What it's about:**
- Use **Keras/TensorFlow** (real deep learning framework)
- Build **deeper networks** (3+ layers, more neurons)
- Real dataset with more complexity
- Classify squirrels into 2 species

**What you'll learn:**
- ✅ **Keras syntax:** Layers, Sequential models, compile, fit
- ✅ **Deeper networks (3+ layers):** Why go deep? Better representations!
- ✅ **Vanishing gradient problem in practice:** When networks stop learning
- ✅ **Choosing architecture:** Layers vs neurons - the trade-offs
- ✅ **Overfitting & underfitting:** Detect from train/validation gap
- ✅ **Regularization techniques:** L1/L2, Dropout, Early stopping
- ✅ **Data handling in Keras:** Train/validation/test split and batching

**Time:** 1-2 hours | **Outcome:** Build deeper networks with real frameworks! 📦

---

#### **Exercise 07: Monitoring Training - Weather Regression** 🌡️
**File:** `07_Monitor_Training_Weather_Regression_exercise.ipynb`

**What it's about:**
- Switch from **classification** to **regression** (predict continuous values)
- Predict weather temperature instead of categories
- Learn to **monitor** network training properly
- Detect overfitting/underfitting from learning curves

**What you'll learn:**
- ✅ **Classification vs Regression:** Discrete classes vs continuous numbers
- ✅ **Output layers for regression:** Use **Linear activation** (no squashing!)
- ✅ **Loss functions:** MSE vs MAE - when to use each
- ✅ **Metrics to monitor:** Training loss, validation loss, accuracy
- ✅ **Learning curves interpretation:** Underfitting vs overfitting vs healthy training
- ✅ **Early stopping:** Stop training when validation loss plateaus
- ✅ **Data splitting:** Train (60-70%), Validation (15-20%), Test (15-20%)

**Key insight:** "The learning curve is your window into the network's learning process!" 📊

**Time:** 1-2 hours | **Outcome:** Know when networks work, when they fail, and how to fix it! 🔧

---

### **PHASE 3: Professional Deep Learning Tools**

#### **Exercise 08: Deep Learning with PyTorch - MNIST** 🔢
**File:** `08_Deep_Learning_With_PyTorch_MNIST_exercise.ipynb`

**What it's about:**
- Use **PyTorch** (the professional deep learning framework)
- Classify handwritten digits (MNIST dataset - 60,000 images!)
- Real deep learning on real data
- Learn production-ready code patterns

**What you'll learn:**
- ✅ **PyTorch syntax:** Tensors, models, loss functions, optimizers
- ✅ **Network architecture:** Define models with nn.Module
- ✅ **Batch training:** Process 32/64/128 samples together (more efficient!)
- ✅ **Data loaders:** Efficient data pipeline with automatic batching
- ✅ **GPU acceleration:** 10-100x faster training on GPU
- ✅ **Professional training loop:** Forward → loss → backward → optimizer.step()
- ✅ **Optimization algorithms:** SGD, Adam, Momentum - when to use each
- ✅ **Real performance:** Achieve 97-99% accuracy on MNIST

**Key insight:** "PyTorch is what researchers and engineers use. Now you understand what's under the hood!" 🚀

**Time:** 2-3 hours | **Outcome:** Ready to use professional deep learning tools!

---

## 🔗 Optional Advanced Exercises

These exercises are **not required** for FCNN mastery, but great if you want to go deeper:

### **Exercise 04: Networks as Code - Keras Projects** (Optional)
**Files:** `04_Networks_as_Code_Penguin_Classification_solution.ipynb`, `04_Networks_as_Code_Wine_Classification_solution.ipynb`

**Good if:** You want more Keras practice before PyTorch  
**Can skip if:** You're comfortable with frameworks  
**Topics:** Real datasets, preprocessing, model evaluation

---

### **Exercise 06: Building NN From Scratch - Advanced** (Optional)
**File:** `06_Building_NN_From_Scratch_Advanced_Exercise.ipynb`

**Good if:** You want to master NumPy implementation  
**Can skip if:** NumPy exercises 01-03 are thorough enough  
**Topics:** Advanced backpropagation, matrix operations, numerical stability

---

### **Exercises 09-10: CNN Architectures** (Different Topic)
**Files:** `09_alexnet_cifar10.ipynb`, `10_vgg_cifar10.ipynb`

**Note:** These are **Convolutional Neural Networks (CNNs)**, not FCNNs!  
**Learn after:** You complete exercises 01-08  
**Topics:** Convolutions, filters, feature maps, modern CNN architectures

---

## Repository Structure

```
erumhub_deep-learning_2026/
├── README.md                                      # This file
├── LICENSE                                        # License info
└── code/                                          # All exercises
    ├── 01_Building_Blocks_Binary_Classification_exercise.ipynb
    ├── 01_Building_Blocks_Binary_Classification_solution.ipynb
    ├── 02_Activation_Functions_Theory.ipynb
    ├── 03_Simple_NN_Iris_Classification_exercise.ipynb
    ├── 03_Simple_NN_Iris_Classification_solution.ipynb
    ├── 05_Feedforward_Squirrel_Classification_exercise.ipynb
    ├── 05_Feedforward_Squirrel_Classification_solution.ipynb
    ├── 07_Monitor_Training_Weather_Regression_exercise.ipynb
    ├── 07_Monitor_Training_Weather_Regression_solution.ipynb
    ├── 08_Deep_Learning_With_PyTorch_MNIST_exercise.ipynb
    ├── 08_Deep_Learning_With_PyTorch_MNIST_solution.ipynb
    ├── 09_alexnet_cifar10.ipynb
    ├── 10_vgg_cifar10_exercise.ipynb
    └── 10_vgg_cifar10.ipynb

Note: Optional advanced exercises (04, 06) and CNN materials (09, 10) are in optional_code/
```

Each `.ipynb` file is a **notebook** - a file with code, formulas, and detailed explanations.

---

## How to Use These Exercises

### Option 1: Run on Google Colab (Easiest!) ✨

Google Colab lets you run code **for free** without installing anything.

**Steps:**

1. Go to this repository on GitHub: [erumhub_deep-learning_2026](https://github.com/Tulin206/erumhub_deep-learning_2026)
2. Open any `.ipynb` file (like `01_Building_Blocks_Binary_Classification_exercise.ipynb`)
3. Click the **"Open in Colab"** button at the top of the notebook
4. The notebook opens in Google Colab automatically
5. Click the "Play" button (▶️) to run each code block
6. Read the explanation and play with the code!

### Option 2: Run Locally (On Your Computer)

1. Download this repository (click "Code" → "Download ZIP")
2. Install Python 3.8+ on your computer
3. Install required libraries: `pip install numpy tensorflow pandas seaborn matplotlib scikit-learn torch`
4. Open the `.ipynb` files with Jupyter Notebook or JupyterLab
5. Run the code and learn!

---

## Requirements

- Python 3.9 or higher (tested with Python 3.14.2)
- NumPy (for math)
- TensorFlow/Keras (for neural networks)
- PyTorch (for deep learning)
- Pandas (for data)
- Scikit-learn (for data tools)
- Matplotlib & Seaborn (for pictures/graphs)

**Note:** If you use Google Colab, everything is already installed!

---

## Questions or Need Help?

If you have questions:
- Check the detailed code comments in each exercise
- Look at the hints provided in the notebooks
- Compare your work with the solution notebooks
- Experiment and play with the code!

The best way to learn is by doing! 🚀

---

## 📚 Additional Resources for Learning at Home

Want to dive deeper into deep learning? Check out these excellent resources:

### **Recommended Learning Materials:**

- **[Sebastian Raschka's Deep Learning Course](https://sebastianraschka.com/blog/2021/dl-course.html)** - A comprehensive deep learning tutorial with step-by-step explanations and code examples. Perfect for learning at your own pace! 🎓

These resources complement the exercises in this repository and will help you build a stronger understanding of deep learning concepts.

---

## License

This project is open source. See LICENSE file for details.

---

**Happy Learning! 🎉**  
**Master neural networks step by step!** 🧠✨
