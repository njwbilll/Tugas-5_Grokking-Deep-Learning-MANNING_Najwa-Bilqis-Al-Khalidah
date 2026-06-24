# Grokking Deep Learning

Repositori ini berisi reproduksi kode dan penjelasan teori dari buku
**"Grokking Deep Learning"** karya Andrew Trask (Manning Publications).

Setiap chapter direpresentasikan sebagai satu Jupyter Notebook terpisah,
lengkap dengan penjelasan konsep dalam Bahasa Indonesia, reproduksi kode,
implementasi menggunakan NumPy, visualisasi hasil, dan pembahasan teori secara mendalam.

---

## Identifikasi

| Field | Detail |
|---------|---------|
| Nama | Najwa Bilqis Al Khalidah |
| NIM | 101032300186 |
| Kelas | TK-46-GAB |
| Mata Kuliah | Deep Learning |
| Referensi | Grokking Deep Learning by Andrew Trask (Manning Publications) |

---

## Deskripsi Proyek

Tugas ini merupakan bagian dari enrichment course Deep Learning.

Tujuan utama proyek ini adalah memperdalam pemahaman konsep Deep Learning melalui reproduksi kode, implementasi algoritma dari nol menggunakan NumPy, serta penjelasan teori yang terstruktur berdasarkan isi buku Grokking Deep Learning.

Repository ini mencakup seluruh 16 chapter dari buku Grokking Deep Learning dan disusun mengikuti urutan pembelajaran yang direkomendasikan oleh penulis.
- Penjelasan teori dalam Bahasa Indonesia
- Reproduksi kode dari buku referensi
- Implementasi algoritma menggunakan NumPy
- Visualisasi hasil eksperimen
- Ringkasan chapter
- Latihan dan eksplorasi tambahan

---

## Struktur Repository

```text
GrokkingDeepLearning/

|
|-- 01_Introducing_Neural_Networks.ipynb
|-- 02_Making_a_Prediction_with_Multiple_Inputs.ipynb
|-- 03_Making_a_Prediction_with_Multiple_Outputs.ipynb
|-- 04_How_Do_Neural_Networks_Learn.ipynb
|-- 05_Generalizing_Gradient_Descent.ipynb
|-- 06_Building_your_first_deep_neural_network.ipynb
|-- 07_How_Do_Neural_Networks_Really_Learn.ipynb
|-- 08_Learning_Signal_and_Generalization.ipynb
|-- 09_Modeling_Probabilities_and_Nonlinearities.ipynb
|-- 10_Neural_Learning_About_Edges_and_Corners.ipynb
|-- 11_Neural_Networks_That_Understand_Language.ipynb
|-- 12_Recurrent_Layers_for_Variable_Length_Data.ipynb
|-- 13_Introducing_Automatic_Optimization.ipynb
|-- 14_Long_Short_Term_Memory_Networks.ipynb
|-- 15_Introducing_Federated_Learning.ipynb
|-- 16_Where_To_Go_From_Here.ipynb
|-- README.md
```

---

# Deskripsi Setiap Chapter

## Chapter 1: Introducing Neural Networks

**File:** `01_Introducing_Neural_Networks.ipynb`

Chapter pembuka yang memperkenalkan konsep dasar neural network dan bagaimana komputer dapat melakukan prediksi menggunakan bobot sederhana.

Topik utama:

- Apa itu Artificial Intelligence
- Machine Learning dan Deep Learning
- Konsep neuron buatan
- Input, weight, dan output
- Forward propagation
- Prediksi sederhana menggunakan NumPy
- Intuisi dasar neural network

---

## Chapter 2: Making a Prediction with Multiple Inputs

**File:** `02_Making_a_Prediction_with_Multiple_Inputs.ipynb`

Membahas bagaimana neural network menangani banyak fitur input sekaligus.

Topik utama:

- Multiple input prediction
- Weighted sum
- Dot product
- Vector operations
- NumPy arrays
- Forward propagation dengan banyak input
- Interpretasi bobot

---

## Chapter 3: Making a Prediction with Multiple Outputs

**File:** `03_Making_a_Prediction_with_Multiple_Outputs.ipynb`

Membahas neural network yang menghasilkan lebih dari satu output.

Topik utama:

- Multiple output prediction
- Matrix multiplication
- Layer representation
- Weight matrices
- Vectorized computation
- Prediksi multi target

---

## Chapter 4: How Do Neural Networks Learn?

**File:** `04_How_Do_Neural_Networks_Learn.ipynb`

Memperkenalkan konsep pembelajaran melalui error dan optimisasi.

Topik utama:

- Error calculation
- Loss function
- Hot and cold learning
- Gradient intuition
- Single weight optimization
- Learning from mistakes

---

## Chapter 5: Generalizing Gradient Descent

**File:** `05_Generalizing_Gradient_Descent.ipynb`

Membahas perluasan gradient descent pada berbagai parameter.

Topik utama:

- Gradient descent
- Learning rate
- Multiple weights
- Error minimization
- Optimization process
- Numerical intuition

---

## Chapter 6: Building Your First Deep Neural Network

**File:** `06_Building_your_first_deep_neural_network.ipynb`

Chapter penting yang membahas pembangunan neural network multilayer pertama.

Topik utama:

- Hidden layers
- Deep neural networks
- Matrix operations
- Forward propagation
- Backpropagation
- Training process
- NumPy implementation

---

## Chapter 7: How Do Neural Networks Really Learn?

**File:** `07_How_Do_Neural_Networks_Really_Learn.ipynb`

Mendalami mekanisme pembelajaran neural network secara matematis.

Topik utama:

- Chain rule
- Partial derivatives
- Backpropagation detail
- Gradient flow
- Error propagation
- Parameter updates

---

## Chapter 8: Learning Signal and Generalization

**File:** `08_Learning_Signal_and_Generalization.ipynb`

Membahas kemampuan model untuk melakukan generalisasi.

Topik utama:

- Overfitting
- Underfitting
- Generalization
- Signal vs noise
- Validation concepts
- Training behavior

---

## Chapter 9: Modeling Probabilities and Nonlinearities

**File:** `09_Modeling_Probabilities_and_Nonlinearities.ipynb`

Memperkenalkan fungsi aktivasi non linear dan probabilitas.

Topik utama:

- Sigmoid
- Softmax
- Probability modeling
- Binary classification
- Multi class classification
- Cross entropy loss

---

## Chapter 10: Neural Learning About Edges and Corners

**File:** `10_Neural_Learning_About_Edges_and_Corners.ipynb`

Chapter yang memperkenalkan Convolutional Neural Networks.

Topik utama:

- CNN fundamentals
- Convolution operation
- Local receptive field
- Weight sharing
- Kernel
- Filter
- Feature map
- Edge detection
- Multiple filters
- Stride
- Padding
- CNN implementation using NumPy

---

## Chapter 11: Neural Networks That Understand Language

**File:** `11_Neural_Networks_That_Understand_Language.ipynb`

Membahas bagaimana neural network memahami hubungan antar kata.

Topik utama:

- Natural Language Processing
- One Hot Encoding
- Word Embedding
- Semantic space
- Cosine similarity
- Similarity search
- Word vectors
- King minus Man plus Woman equals Queen
- CBOW
- Skip Gram
- Word2Vec intuition

---

## Chapter 12: Recurrent Layers for Variable Length Data

**File:** `12_Recurrent_Layers_for_Variable_Length_Data.ipynb`

Membahas neural network untuk data sekuensial.

Topik utama:

- Sequential data
- Hidden state
- Recurrent Neural Network
- Weight sharing
- Sequence modeling
- Backpropagation Through Time
- RNN implementation using NumPy
- NLP applications

---

## Chapter 13: Introducing Automatic Optimization

**File:** `13_Introducing_Automatic_Optimization.ipynb`

Membahas pembangunan mini deep learning framework.

Topik utama:

- Tensor
- Computational graph
- Automatic differentiation
- Autograd
- Layer abstraction
- Embedding layer
- Cross entropy layer
- Optimizer
- Mini deep learning framework
- Framework design concepts

---

## Chapter 14: Long Short Term Memory Networks

**File:** `14_Long_Short_Term_Memory_Networks.ipynb`

Membahas LSTM sebagai solusi terhadap keterbatasan RNN.

Topik utama:

- Vanishing gradient
- Memory cell
- Forget gate
- Input gate
- Output gate
- Cell state
- Hidden state
- LSTM architecture
- NumPy implementation
- Sequence learning

---

## Chapter 15: Introducing Federated Learning

**File:** `15_Introducing_Federated_Learning.ipynb`

Membahas paradigma pelatihan model terdistribusi yang menjaga privasi data.

Topik utama:

- Federated Learning
- Distributed training
- Privacy preserving AI
- Local model updates
- Aggregation methods
- Collaborative learning
- Modern AI applications

---

## Chapter 16: Where To Go From Here

**File:** `16_Where_To_Go_From_Here.ipynb`

Chapter penutup yang merangkum perjalanan pembelajaran Deep Learning serta memberikan arahan mengenai topik lanjutan yang dapat dipelajari setelah menyelesaikan buku Grokking Deep Learning.

Topik utama:

- Review seluruh konsep Deep Learning
- Neural Network Roadmap
- Computer Vision
- Natural Language Processing
- Reinforcement Learning
- Generative Models
- Deep Learning Frameworks
- Research Directions
- Industry Applications
- Continuous Learning Strategy
- Future of Artificial Intelligence

Pada chapter ini pembaca diajak memahami bagaimana seluruh konsep yang telah dipelajari saling terhubung dan bagaimana melanjutkan pembelajaran menuju topik Deep Learning yang lebih lanjut.

---

# Library yang Digunakan

| Library | Kegunaan |
|----------|----------|
| Python | Bahasa pemrograman utama |
| NumPy | Operasi numerik dan matriks |
| Matplotlib | Visualisasi data |
| Pandas | Manipulasi data |
| Jupyter Notebook | Dokumentasi dan eksperimen |
| Scikit Learn | Dataset dan utilitas pendukung |

---

# Cara Menjalankan

## Prasyarat

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

## Menjalankan Notebook

```bash
git clone https://github.com/njwbilll/Tugas-5_Grokking-Deep-Learning-MANNING_Najwa-Bilqis-Al-Khalidah.git

cd Tugas-5_Grokking-Deep-Learning-MANNING_Najwa-Bilqis-Al-Khalidah

jupyter notebook
```

Kemudian buka notebook sesuai urutan chapter.

---

## Urutan yang Disarankan

```text
01 Introducing Neural Networks
    |
    v
02 Multiple Inputs
    |
    v
03 Multiple Outputs
    |
    v
04 Neural Networks Learn
    |
    v
05 Gradient Descent
    |
    v
06 Deep Neural Networks
    |
    v
07 Backpropagation
    |
    v
08 Generalization
    |
    v
09 Probabilities and Nonlinearities
    |
    v
10 CNN
    |
    v
11 NLP and Embeddings
    |
    v
12 RNN
    |
    v
13 Automatic Optimization
    |
    v
14 LSTM
    |
    v
15 Federated Learning
    |
    v
16 Where To Go From Here
```

---
# Ringkasan Keseluruhan Buku

Grokking Deep Learning memperkenalkan konsep Deep Learning secara bertahap mulai dari neural network sederhana hingga topik yang lebih kompleks seperti:

- Forward Propagation
- Backpropagation
- Gradient Descent
- Deep Neural Networks
- Convolutional Neural Networks
- Word Embeddings
- Recurrent Neural Networks
- Long Short Term Memory Networks
- Automatic Differentiation
- Federated Learning

Melalui pendekatan berbasis implementasi NumPy dari nol, pembaca memperoleh pemahaman mendalam mengenai cara kerja algoritma Deep Learning tanpa bergantung pada framework tingkat tinggi seperti TensorFlow atau PyTorch.

---
# Referensi

Trask, A. (2019).

*Grokking Deep Learning.*

Manning Publications.

ISBN: 9781617293702
