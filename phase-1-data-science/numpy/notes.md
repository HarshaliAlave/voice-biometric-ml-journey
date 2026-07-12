# 📊 NumPy — Notes

## What is NumPy?
NumPy (Numerical Python) is the core library for numerical computing in Python.
It provides powerful N-dimensional array objects and mathematical functions.

## Why NumPy for This Project?
In our Voice Biometric system, NumPy will be used to:
- Store and manipulate MFCC feature vectors
- Perform matrix operations on audio data
- Handle large arrays of voice samples efficiently

## Key Concepts

### 1. Arrays
- NumPy arrays are faster and more memory efficient than Python lists
- All elements must be of the same data type
- Supports N-dimensional arrays (1D, 2D, 3D...)

### 2. Array Operations
- Vectorized operations — no need for loops
- Broadcasting — operations between arrays of different shapes
- Slicing and indexing — similar to Python lists but more powerful

### 3. Mathematical Functions
- Linear algebra — dot product, matrix multiplication
- Statistical — mean, std, min, max
- Trigonometric — sin, cos (used in audio processing)

## Important Functions to Remember
| Function | Purpose |
|---|---|
| np.array() | Create array |
| np.zeros() | Array of zeros |
| np.ones() | Array of ones |
| np.reshape() | Change shape |
| np.mean() | Calculate mean |
| np.std() | Standard deviation |
| np.dot() | Dot product |
| np.concatenate() | Join arrays |

## Connection to Project
MFCC features extracted from voice are stored as NumPy arrays.
Each audio sample produces a feature vector of shape (39,) as a NumPy array.

## Status
⏳ Coming Soon — will update with code examples after completing this topic!

---
*Harshali | Kankavli, Sindhudurg, Maharashtra | 2026*
