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

1. **Before or During the Course:** Fill in your details in this [**Shared Feedback Table**](https://pad.shoplatein.de/p/ErumHub_2026_FeedbackPad)

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

**👉 [Open the Feedback Table Here](https://pad.shoplatein.de/p/ErumHub_2026_FeedbackPad)**

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

## 🚀 Core Learning Path: Master Deep Learning & FCNNs (Recommended)

### **Follow This Order: FCNN → CNN → Additional Self-Study**

This is the **best path** to understand **Fully Connected Neural Networks (FCNNs)** and **Convolutional Neural Networks (CNNs)** completely. It takes about **12-15 hours** and builds from applications to deeper theory.

---

## What Exercises Are Here?

### **PHASE 1: Real-World FCNN Applications**
**Location:** `/code/FCNN/`

#### **Exercise 04A: Wine Classification with TensorFlow** 🍷
**File:** `code/FCNN/04_Wine_Classification_Tensorflow.ipynb`

**What it's about:**
- Classify wine into 3 types using TensorFlow/Keras
- Real dataset with 178 wine samples and 13 features
- Learn practical model building and evaluation
- Understand confusion matrices and accuracy scores

**What you'll learn:**
- ✅ **Keras model creation:** Sequential API and Dense layers
- ✅ **One-hot encoding:** Convert labels to neural network format
- ✅ **Data preprocessing:** StandardScaler normalization
- ✅ **Train-test splitting:** Stratified data splitting
- ✅ **Model compilation:** Optimizers and loss functions
- ✅ **Training:** Fitting models on real data
- ✅ **Predictions:** Converting probabilities to class labels
- ✅ **Model evaluation:** Confusion matrix and accuracy metrics

**Time:** 1-2 hours | **Outcome:** Build and evaluate real classification models! 📦

---

#### **Exercise 04B: MNIST Classification with TensorFlow** 🔢
**File:** `code/FCNN/04_mnist_classification_tensorflow.ipynb`

**What it's about:**
- Classify handwritten digits (MNIST - 60,000 images!)
- Use TensorFlow/Keras framework
- Real deep learning on a large dataset
- Achieve 97%+ accuracy

**What you'll learn:**
- ✅ **TensorFlow/Keras workflow:** Load, build, train, evaluate
- ✅ **Large datasets:** Handle thousands of training samples
- ✅ **Image preprocessing:** Flatten and normalize pixel values
- ✅ **Professional evaluation:** Accuracy, loss curves, predictions
- ✅ **Real performance:** See your model work on complex data

**Time:** 1-2 hours | **Outcome:** Build your first real production model! 🚀

---

#### **Exercise 08A: MNIST with PyTorch** 🔢
**File:** `code/FCNN/08_MNIST_classification_Pytorch.ipynb`

**What it's about:**
- Use **PyTorch** (the professional deep learning framework)
- Classify handwritten digits (MNIST dataset - 60,000 images!)
- Real deep learning on real data with production-ready patterns
- Learn how researchers build neural networks

**What you'll learn:**
- ✅ **PyTorch syntax:** Tensors, models, loss functions, optimizers
- ✅ **Network architecture:** Define models with nn.Module
- ✅ **Batch training:** Process samples in batches (more efficient!)
- ✅ **Data loaders:** Efficient data pipeline with automatic batching
- ✅ **GPU acceleration:** 10-100x faster training on GPU (if available)
- ✅ **Professional training loop:** Forward → loss → backward → optimizer.step()
- ✅ **Optimization algorithms:** SGD, Adam, Momentum - when to use each
- ✅ **Real performance:** Achieve 97-99% accuracy on MNIST

**Key insight:** "PyTorch is what researchers and engineers use. Now you understand what's under the hood!" 🚀

**Time:** 2-3 hours | **Outcome:** Ready to use professional deep learning tools! ✨

---

#### **Exercise 08B: Wine Classification with PyTorch** 🍷
**File:** `code/FCNN/08_WINE_classification_Pytorch_Exercise.ipynb`

**What it's about:**
- Practice PyTorch on the wine classification task
- Build a complete PyTorch pipeline for classification
- Exercise to reinforce learning

**What you'll learn:**
- ✅ **PyTorch for tabular data:** Working with non-image datasets
- ✅ **Custom dataset classes:** DataLoader integration
- ✅ **Model training patterns:** Complete training loop
- ✅ **Evaluation:** Metrics and analysis with PyTorch

**Time:** 1-2 hours | **Outcome:** Master PyTorch on real problems! 💪

---

### **PHASE 2: Advanced - Convolutional Neural Networks**
**Location:** `/code/CNN/`

#### **Exercise 09: AlexNet - CIFAR10** 🎨
**File:** `code/CNN/09_alexnet_cifar10.ipynb`

**What it's about:**
- Build **AlexNet** architecture for image classification
- Classify CIFAR10 images (32×32 color images, 10 classes)
- Learn about convolutional layers and filters
- Understand how CNNs work for image data

**What you'll learn:**
- ✅ **Convolutional layers:** How filters detect features in images
- ✅ **Pooling layers:** Reduce spatial dimensions efficiently
- ✅ **AlexNet architecture:** Classic deep CNN design
- ✅ **Image preprocessing:** Normalization and augmentation
- ✅ **Transfer of learning concepts:** From FCNN to CNN

**Time:** 2-3 hours | **Outcome:** Understand how CNNs revolutionized computer vision! 📸

---

#### **Exercise 10: VGG - CIFAR10** 🎨
**Files:** 
- `code/CNN/10_vgg_cifar10.ipynb` (Solution)
- `code/CNN/10_vgg_cifar10_exercise.ipynb` (Exercise to practice)

**What it's about:**
- Build **VGG architecture** with multiple convolutional blocks
- Advanced CNN design patterns
- Practice implementing modern neural network architectures
- Achieve high accuracy on CIFAR10

**What you'll learn:**
- ✅ **VGG architecture:** Multiple conv blocks, systematic design
- ✅ **Deep networks:** Stacking many layers effectively
- ✅ **Feature extraction:** How networks learn hierarchical features
- ✅ **Architecture patterns:** Templates for building modern networks
- ✅ **Comparison:** VGG vs AlexNet - improvements in CNN design

**Key insight:** "Modern architectures follow clear patterns. Learn them and you can design anything!" 🏗️

**Time:** 2-3 hours | **Outcome:** Master modern CNN architectures! 🚀

---

### **PHASE 3: Foundation - Understanding Neural Networks from Scratch**
**Location:** `/code/Additional_code_self_study/`

#### **Exercise 01: Building Blocks - Binary Classification** 🧱
**File:** `01_Building_Blocks_Binary_Classification_solution.ipynb`

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
**File:** `code/Additional_code_self_study/02_Activation_Functions_Theory.ipynb`

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
**File:** `code/Additional_code_self_study/03_Simple_NN_Iris_Classification_solution.ipynb`

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

#### **Exercise 04: Networks as Code - Penguin Classification** 🐧
**File:** `code/Additional_code_self_study/04_Networks_as_Code_Penguin_Classification_solution.ipynb`

**What it's about:**
- Use **Keras/TensorFlow** (real deep learning framework)
- Build a **2-layer neural network** on real datasets
- Classify penguin species with Keras

**What you'll learn:**
- ✅ **Keras syntax:** Layers, Sequential models, compile, fit
- ✅ **Real datasets:** Penguin data
- ✅ **One-hot encoding:** Convert labels for neural networks
- ✅ **Data preprocessing:** Scaling and normalization
- ✅ **Model evaluation:** Confusion matrices and accuracy scores
- ✅ **Predictions:** Converting probabilities to class labels

**Time:** 1-2 hours | **Outcome:** Build real models with Keras! 📦

---

#### **Exercise 05: Feedforward - Squirrel Classification** 🐿️
**File:** `code/Additional_code_self_study/05_Feedforward_Squirrel_Classification_solution.ipynb`

**What it's about:**
- Practice **feedforward networks** on real squirrel data
- Build networks with 2-3 hidden layers
- Learn architecture design patterns
- Classify squirrels into 2 species

**What you'll learn:**
- ✅ **Deeper architectures:** Design multi-layer networks
- ✅ **Network structure:** Input → Hidden(s) → Output
- ✅ **Hyperparameter tuning:** Neurons, layers, activation functions
- ✅ **Real data handling:** Feature scaling and train/test split
- ✅ **Evaluation metrics:** Accuracy and error analysis

**Time:** 1-2 hours | **Outcome:** Design and tune networks like a pro! 🎯

---

#### **Exercise 06: Building NN From Scratch - Advanced** 🔧
**File:** `code/Additional_code_self_study/06_Building_NN_From_Scratch_Advanced_solution.ipynb`

**What it's about:**
- Build a **complete neural network** without any frameworks
- Use only NumPy for matrix operations
- Advanced backpropagation with multiple layers
- Understand every mathematical detail

**What you'll learn:**
- ✅ **Complete network implementation:** Forward + backward pass
- ✅ **Matrix operations:** Efficient batch processing with NumPy
- ✅ **Advanced backpropagation:** Chain rule with multiple layers
- ✅ **Numerical stability:** Overflow/underflow prevention
- ✅ **Optimization:** Gradient descent with momentum

**Time:** 2-3 hours | **Outcome:** Master the complete neural network mathematics! 🧮

---

#### **Exercise 07: Monitoring Training - Weather Regression** 🌡️
**File:** `code/Additional_code_self_study/07_Monitor_Training_Weather_Regression_solution.ipynb`

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


## 🔗 Learning Paths Depending on Your Goals

### **FCNN Master Path (Focus on Fully Connected Networks)**
**Recommended exercises:** 01 → 02 → 03 → 04(Additional) → 05 → 06 → 07 → 04-08(FCNN)
**Time:** 8-10 hours
**Outcome:** Expert-level understanding of FCNNs
**Use case:** Tabular data, time series, non-image problems

---

### **Complete Deep Learning Path (FCNN + CNN)**
**Recommended exercises:** 01 → 02 → 03 → 04(Additional) → 05 → 06 → 07 → 04-08(FCNN) → 09-10(CNN)
**Time:** 12-15 hours
**Outcome:** Understand both FCNNs and CNNs
**Use case:** Comprehensive deep learning foundation

---

### **Quick Start Path (Just the essentials)**
**Recommended exercises:** 01 → 02 → 03 → 04(Wine-FCNN) → 08(FCNN-PyTorch)
**Time:** 4-5 hours
**Outcome:** Practical knowledge to build neural networks
**Use case:** Learn quickly and start building

---

### **CNN Specialist Path (Image focus)**
**Prerequisites:** Complete exercises 01-07 first  
**Then:** 09-10 (CNN exercises)
**Time:** 4-5 hours additional
**Outcome:** Master convolutional neural networks for images
**Use case:** Computer vision, image classification, object detection

---

## Repository Structure

```
erumhub_deep-learning_2026/
├── README.md                                       # This file
├── LICENSE                                         # License info
├── Lecture_Materials/
│   └── ErumHub_2026_FCNN_CNN.pdf                  # Lecture slides
└── code/                                           # All exercises
    ├── FCNN/                                       # FULLY CONNECTED NEURAL NETWORKS
    │   ├── 04_mnist_classification_tensorflow.ipynb        (TensorFlow/Keras version)
    │   ├── 04_Wine_Classification_Tensorflow.ipynb         (Wine classification with Keras)
    │   ├── 08_MNIST_classification_Pytorch.ipynb           (Deep Learning with PyTorch)
    │   └── 08_WINE_classification_Pytorch_Exercise.ipynb   (Wine classification with PyTorch)
    │
    ├── CNN/                                        # CONVOLUTIONAL NEURAL NETWORKS
    │   ├── 09_alexnet_cifar10.ipynb                (AlexNet architecture)
    │   ├── 10_vgg_cifar10.ipynb                    (VGG architecture - solution)
    │   └── 10_vgg_cifar10_exercise.ipynb           (VGG architecture - exercise)
    │
    └── Additional_code_self_study/                 # FOUNDATION MATERIALS (Start learning here!)
        ├── 01_Building_Blocks_Binary_Classification_solution.ipynb
        ├── 02_Activation_Functions_Theory.ipynb
        ├── 03_Simple_NN_Iris_Classification_solution.ipynb
        ├── 04_Networks_as_Code_Penguin_Classification_solution.ipynb
        ├── 05_Feedforward_Squirrel_Classification_solution.ipynb
        ├── 06_Building_NN_From_Scratch_Advanced_solution.ipynb
        └── 07_Monitor_Training_Weather_Regression_solution.ipynb
```

Each `.ipynb` file is a **notebook** - a file with code, formulas, and detailed explanations.

**📌 Important:** Although `Additional_code_self_study/` appears last in the folder structure, **start learning from here first!** These are the foundation exercises (01-07) that teach you the basics before moving to FCNN and CNN applications.

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

- **[Machine Learning with Scikit-Learn (The Carpentries)](https://carpentries-incubator.github.io/machine-learning-novice-sklearn/)** - A beginner-friendly tutorial on machine learning fundamentals using scikit-learn. Great for understanding classical ML before diving into deep learning! 📊

- **[Introduction to Deep Learning (The Carpentries Lab)](https://carpentries-lab.github.io/deep-learning-intro/)** - An introductory deep learning course with hands-on exercises. Perfect complement to understand different perspectives on neural networks! 🧠

- **[Introduction to Image Classification with CNNs (The Carpentries)](https://carpentries-incubator.github.io/intro-image-classification-cnn/images.html)** - A comprehensive guide to image classification using convolutional neural networks. Excellent resource after you complete the CNN exercises! 📸

These resources complement the exercises in this repository and will help you build a stronger understanding of deep learning concepts.

---

## License

This project is open source. See LICENSE file for details.

---

**Happy Learning! 🎉**  
**Master neural networks step by step!** 🧠✨
