
# 🧠 Image Classification using Transfer Learning

This project implements an **Image Classification model using Transfer Learning** in Python.  
It leverages pre-trained deep learning architectures to achieve high accuracy with limited training data.

The model is trained and evaluated in the notebook **`image_classification_TL.ipynb`**.

---

## 🚀 Features

- 🔗 Transfer Learning with pretrained CNN (e.g., ResNet, VGG, MobileNet etc.)
- 📂 Custom dataset loading using `torchvision.datasets`
- 📊 Training, validation loops with accuracy tracking
- 🧪 Model evaluation & predictions on new images
- 💾 Model saving for deployment

---

## 🛠 Tech Stack

| Component | Technology |
|----------|------------|
| Language | Python 3 |
| Framework | PyTorch |
| Visualization | Matplotlib, Seaborn |
| Model | Pretrained CNN (TorchVision Models) |
| Environment | Jupyter Notebook / Google Colab |

---

## 📦 Installation

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

pip install -r requirements.txt
```

If you're using **Google Colab**, simply upload the notebook and start running.

---

## 📁 Folder Structure

```
├── image_classification_TL.ipynb
├── data/            # training images (optional)
├── saved_model/     # exported weights
└── README.md
```

---

## ▶️ How to Run

### **1️⃣ Open Notebook**

```bash
jupyter notebook image_classification_TL.ipynb
```

### **2️⃣ Train the Model**
Run all cells to train the model.  
Make sure your dataset path is configured correctly.

### **3️⃣ Test on New Images**

Use the prediction section inside the notebook to classify custom images.

---

## 📉 Training Results

| Metric | Value |
|--------|-------|
| Training Accuracy | ~87% |
| Validation Accuracy | ~82% |
| Loss | Reduced significantly across epochs |


---

## 📌 Example Predictions

| Input Image | Prediction |
|-------------|------------|
| 🐶 Dog.jpg | **Dog** |
| 🚗 Car.png | **Car** |

---

## 💾 Save & Load Model

```python
torch.save(model.state_dict(), "model.pth")
```

```python
model.load_state_dict(torch.load("model.pth"))
model.eval()
```

---

## 🧑‍💻 Author

**Rakesh Suru**  
📍 India  

---

## ⭐ Contribute

Pull requests are welcome!  
If you like this repo, consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is licensed under the **MIT License**.
