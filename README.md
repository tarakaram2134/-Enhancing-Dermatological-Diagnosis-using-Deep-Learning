# Skin Lesion Prediction

A Convolutional Neural Network (CNN)–based project built with PyTorch/TensorFlow (Jupyter notebooks) to classify skin lesions into benign and malignant categories using a LeNet-inspired architecture.

---

## 📁 Project Structure

```text
Skin_Lesion_Prediction/
├── data/                    # (Optional) Place your image dataset here
│   ├── train/
│   └── test/
├── notebooks/
│   ├── lenetfinal.ipynb         # Original LeNet implementation
│   └── ModifiedLenetFinal.ipynb # Enhanced LeNet with custom layers/augmentation
├── models/                  # (Optional) Saved model weights/checkpoints
├── requirements.txt         # Python dependencies
└── README.md                # Project overview and instructions
```

---

## 🔍 Overview

This project demonstrates:

- **Data loading** and preprocessing for skin lesion images  
- **LeNet-based CNN** training and evaluation  
- **Model modifications**: added dropout, batch normalization, data augmentation  
- **Performance analysis**: accuracy, confusion matrix, ROC curve  

Aimed at researchers and students in medical image analysis and deep learning.

---

## ⚙️ Installation

1. **Clone or download** this folder to your local drive.  
2. Create and activate a Python virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate        # Linux / macOS
   venv\Scripts\activate         # Windows
   ```

3. Install dependencies:

   ```bash
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

---

## 🗂 Data Preparation

- Obtain the **HAM10000** or your chosen skin lesion dataset.  
- Unzip and organize images under `data/train/` and `data/test/`.  
- If your folder structure differs, update the paths in the notebooks accordingly.

---

## 🚀 Usage

1. Launch Jupyter Lab or Notebook in the project root:

   ```bash
   jupyter lab
   ```

2. Open and run:

   - `notebooks/lenetfinal.ipynb`  
   - `notebooks/ModifiedLenetFinal.ipynb`

3. Follow each cell’s instructions to train, validate, and visualize results.


## 📊 Results

After training, you’ll see:

- **Training & validation curves**  
- **Confusion matrix** and classification report  
- **ROC curve** and AUC score  

Feel free to tweak hyperparameters (learning rate, batch size, epochs) to improve performance.

---

## 🛠️ Customization

- Switch between PyTorch and TensorFlow by modifying the import blocks.  
- Add more augmentation (color jitter, random crops) in the data loader.  
- Swap out the LeNet backbone for deeper CNNs (e.g., ResNet, DenseNet).

---

## 🤝 Contributing

1. Fork this repository.  
2. Create a feature branch: `git checkout -b feature/YourFeature`  
3. Commit your changes: `git commit -m "Add awesome feature"`  
4. Push to your branch: `git push origin feature/YourFeature`  
5. Open a pull request—happy to review!

---

## 📄 License

This project is released under the [MIT License](LICENSE).

---

## 📬 Contact

**Taraka Ram**  
– Email: tarakaram2134@gmail.com  
– GitHub: [github.com/tarakaram2134](https://github.com/tarakaram2134)
