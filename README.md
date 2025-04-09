# 📚 MATH2015 Final Project – Image Compression using SVD

This project is part of the **MATH UN2015: Linear Algebra and Probability** course at Columbia University. It demonstrates the use of **Singular Value Decomposition (SVD)** for image compression and evaluates the performance using PSNR and SSIM metrics.

## 🧠 Project Objective

To apply SVD (a key concept from linear algebra) to compress high-resolution images, visualize the impact of different rank approximations, and evaluate the quality using quantitative metrics.

---

## 🔧 Technologies Used

- Python 3
- NumPy
- Matplotlib
- Jupyter Notebook / JupyterLab
- scikit-image (for PSNR & SSIM)
- PIL (Python Imaging Library)

---

## 📂 Files Included

| File Name              | Description                                 |
|------------------------|---------------------------------------------|
| `MATH_Project.ipynb`   | Main notebook with all the code & analysis  |
| `MATH_Project.html`    | Exported HTML version of the notebook       |
| `README.md`            | This project description file               |

---

## 📸 Methodology

1. Load a high-resolution color image and convert it to grayscale.
2. Apply **SVD decomposition**: `A ≈ U_k S_k V_k^T` for different values of `k`
3. Visualize:
   - Original vs Compressed images
   - Singular values decay
   - Compression quality as `k` increases
4. Calculate metrics:
   - PSNR (Peak Signal-to-Noise Ratio)
   - SSIM (Structural Similarity Index)
   - Compression Ratio (CR)

---

## 📊 Sample Output

| Rank (k) | PSNR (dB) | SSIM  | Compression Ratio |
|----------|-----------|-------|-------------------|
| 10       | 18.42     | 0.68  | 0.19              |
| 50       | 27.60     | 0.89  | 0.47              |
| 100      | 31.27     | 0.94  | 0.74              |

---

## 📝 How to Run

Clone the repo and run:

```bash
jupyter lab MATH_Project.ipynb
