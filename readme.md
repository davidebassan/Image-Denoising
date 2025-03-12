# Exploration of Methods for Noise Reduction in Medical Images

## Overview
This project explores techniques for reducing noise in medical images using both traditional and deep learning approaches. The goal is to improve image quality for more accurate diagnosis and analysis. The methodologies employed include noise analysis, noise addition, and various denoising techniques, culminating in two deep learning models for effective noise reduction.

## Author
- **Davide Bassan**

## System Requirements
- **CPU**: AMD Ryzen 5 3600  
- **GPU**: NVIDIA RTX 3060 12GB  
- **RAM**: 48GB  
- **OS**: Linux Ubuntu 20.04.6 LTS  

## Dependencies
The following libraries are required to run the project:

```bash
pip install tensorflow pandas numpy matplotlib pillow scikit-image scipy tqdm seaborn opencv-python pywavelets
```

## Dataset
The dataset used in this project consists of medical images with artificially added noise for evaluation purposes. The images are processed using various noise reduction techniques and deep learning models.

## Code Structure
- `notebook.ipynb`: Jupyter Notebook containing the full pipeline for noise reduction.
- `data/`: Directory containing the medical images used for testing. (not shared)
- `models/`: Pretrained models for noise reduction. (not shared)

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/davidebassan/Exploration-of-Methods-for-Noise-Reduction-in-Medical-Images.git
   cd yourrepository
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Davide_Bassan.ipynb
   ```

## Methodologies
### 1. Traditional Denoising Techniques
- **Gaussian Smoothing**
- **Median Filtering**
- **Wavelet Denoising**
- **Bilateral Filtering**

### 2. Deep Learning Models
- **Convolutional Neural Networks (CNNs)** for denoising
- **Autoencoders** for noise reduction

## Evaluation Metrics
The effectiveness of noise reduction techniques is assessed using the following metrics:
- **Peak Signal-to-Noise Ratio (PSNR)**
- **Mean Squared Error (MSE)**
- **Structural Similarity Index (SSIM)**

## Results
The project evaluates different noise reduction techniques and compares them against deep learning-based approaches to determine the best performing model for medical image enhancement.

## Future Work
- Exploring transformer-based models for denoising
- Enhancing training with larger datasets
- Optimizing models for real-time medical imaging applications

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, contact **Davide Bassan**.
