# 🧠 Crack Detection using U-Net

This project focuses on detecting cracks in images of concrete surfaces using a **U-Net** deep learning model. The model performs pixel-level segmentation to identify regions containing cracks with high accuracy.

---

## 🚀 Overview

* Built and trained a **U-Net convolutional neural network** for image segmentation.
* Achieved around **96% accuracy** on the crack detection dataset.
* The trained model can be used to process new images or videos to highlight cracked areas.

---

## 🧩 Model Architecture

The project uses a **U-Net** architecture with:

* An **encoder** that captures features using convolution and pooling layers.
* A **decoder** that reconstructs the segmentation mask using upsampling and concatenation.

**Loss Function:** Binary Crossentropy
**Optimizer:** Adam

---

## ⚙️ Workflow

1. **Dataset Preparation**

   * Load images and their corresponding crack masks.
   * Resize and normalize all images to 128×128 pixels.

2. **Model Training**

   * Train the U-Net model on 80% of the dataset and validate on the remaining 20%.
   * Save the trained model as `unet_crack_localization.h5`.

3. **Inference**

   * Load the trained model.
   * Apply it to new images or videos for crack segmentation.
   * The output highlights the detected crack regions.

---

## 📦 Dependencies

Install the required libraries:

```bash
pip install tensorflow numpy opencv-python matplotlib scikit-learn tqdm
```

---

## 📈 Results

| Metric      | Value              |
| ----------- | ------------------ |
| Accuracy    | ~96%               |
| Model       | U-Net              |
| Application | Crack Segmentation |

---

## 👨‍💻 Author

**Sudhanshu Songire**
GitHub: [github.com/yourusername](https://github.com/yourusername)
LinkedIn: [linkedin.com/in/sudhanshu-songire](https://linkedin.com/in/sudhanshu-songire)
