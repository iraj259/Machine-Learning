# Day 6 – Tensors in Machine Learning

## What is a Tensor?
- A **tensor** is a multi-dimensional array that generalizes scalars, vectors, and matrices.  

### Tensor Dimensions (with Examples)
- **0D (Scalar):** Single number  
  ```python
  5
## 1D (Vector): Array of numbers

- python
- [1, 2, 3]

## 2D (Matrix): Rows × columns

- python
- [[1, 2],
- [3, 4]]
## 3D (Volume / RGB Image): Height × Width × Channels

python
- [[[255, 0, 0], [0, 255, 0]],
- [[0, 0, 255], [255, 255, 0]]]

## 4D (Batch of Images): Batch × Height × Width × Channels

- python
- batch_of_images = np.random.rand(32, 64, 64, 3)

## 5D (Video or Sequence of Image Batches): Batch × Time × Height × Width × Channels

- python
- video_batch = np.random.rand(16, 10, 64, 64, 3)

## Why Tensors are Important
- Fundamental data structure in ML frameworks (TensorFlow, PyTorch)

- Enable efficient computation on CPUs and GPUs

## Represent:

- Input data (images, videos, text sequences)

- Model parameters (weights, biases)

## Intermediate outputs in neural networks

- Tensor Operations
- Basic: Addition, subtraction, multiplication, division

- Matrix Operations: Dot product, transpose, matrix multiplication

- Reshaping & Slicing: Change shape without modifying data; extract parts of tensor

- Broadcasting: Operate on tensors of different shapes automatically

## Tensor Libraries
- NumPy: Basic tensor operations

- TensorFlow: Tensors for deep learning

- PyTorch: Tensors + autograd for ML

## Interview-style Q&A
- Q: What is a tensor and why is it used in ML?
- A: A tensor is a multi-dimensional array used to represent data and model parameters    efficiently. It enables fast computation and GPU acceleration.

## Q: Give examples of tensor dimensions.

- 0D: scalar → 5

- 1D: vector → [1, 2, 3]

- 2D: matrix → [[1,2],[3,4]]

- 3D: RGB image → height × width × channels

- 4D: batch of images → batch × height × width × channels

- 5D: video batch → batch × time × height × width × channels

## Q: Why are tensors preferred in frameworks like TensorFlow and PyTorch?
- A: They allow efficient storage and computation, support GPU acceleration, and represent complex multi-dimensional data for neural networks.









You said:
give me .md file


ChatGPT said:
Here’s the complete .md file content for Day 6 – Tensors with examples up to 5D. You can save it as Day6_Tensors.md in your repo:

markdown
Copy code
# Day 6 – Tensors in Machine Learning

## What is a Tensor?
- A **tensor** is a multi-dimensional array that generalizes scalars, vectors, and matrices.  

### Tensor Dimensions (with Examples)
- **0D (Scalar):** Single number  
  ```python
  5
1D (Vector): Array of numbers

python
Copy code
[1, 2, 3]
2D (Matrix): Rows × columns

python
Copy code
[[1, 2],
 [3, 4]]
3D (Volume / RGB Image): Height × Width × Channels

python
Copy code
[[[255, 0, 0], [0, 255, 0]],
 [[0, 0, 255], [255, 255, 0]]]
4D (Batch of Images): Batch × Height × Width × Channels

python
Copy code
batch_of_images = np.random.rand(32, 64, 64, 3)
5D (Video or Sequence of Image Batches): Batch × Time × Height × Width × Channels

python
Copy code
video_batch = np.random.rand(16, 10, 64, 64, 3)
Why Tensors are Important
Fundamental data structure in ML frameworks (TensorFlow, PyTorch)

Enable efficient computation on CPUs and GPUs

Represent:

Input data (images, videos, text sequences)

Model parameters (weights, biases)

Intermediate outputs in neural networks

Tensor Operations
Basic: Addition, subtraction, multiplication, division

Matrix Operations: Dot product, transpose, matrix multiplication

Reshaping & Slicing: Change shape without modifying data; extract parts of tensor

Broadcasting: Operate on tensors of different shapes automatically

Tensor Libraries
NumPy: Basic tensor operations

TensorFlow: Tensors for deep learning

PyTorch: Tensors + autograd for ML

Interview-style Q&A
Q: What is a tensor and why is it used in ML?
A: A tensor is a multi-dimensional array used to represent data and model parameters efficiently. It enables fast computation and GPU acceleration.

Q: Give examples of tensor dimensions.

0D: scalar → 5

1D: vector → [1, 2, 3]

2D: matrix → [[1,2],[3,4]]

3D: RGB image → height × width × channels

4D: batch of images → batch × height × width × channels

5D: video batch → batch × time × height × width × channels

Q: Why are tensors preferred in frameworks like TensorFlow and PyTorch?
A: They allow efficient storage and computation, support GPU acceleration, and represent complex multi-dimensional data for neural networks.