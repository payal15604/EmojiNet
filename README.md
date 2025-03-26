# 🚀 EmojiNet: Object Localization with TensorFlow  

🔍 **EmojiNet** is a deep learning project that uses **Convolutional Neural Networks (CNNs)** to detect and localize emojis within images. Built with **TensorFlow & Keras**, this model predicts both **emoji type and position**, enabling exciting applications in **AR filters, smart emoji suggestions, and AI-powered chat assistants**.  

---

## 🎯 Project Overview  
### 🔹 What does EmojiNet do?  
EmojiNet is trained on an **emoji dataset** to:  
✅ **Identify** different types of emojis in an image.  
✅ **Predict their precise location** using object localization techniques.  
✅ **Enhance AI-driven emoji applications** with real-time localization.  

### 🔥 Real-World Impact  
This project demonstrates **multi-output CNNs** for object localization, a technique used in:  
💬 **AI-powered emoji keyboards** (auto-suggest emojis based on image context).  
📱 **Augmented Reality (AR) emoji filters** (like Snapchat & Instagram).  
🤖 **Smart chatbots** (suggesting emojis dynamically).  
🎥 **Video editing apps** (auto-placing stickers & reactions).  

---

## 🏗️ Tech Stack  
🚀 **Deep Learning** – TensorFlow, Keras  
🎨 **Dataset** – Custom Emoji Dataset  
📊 **Metrics** – IoU (Intersection over Union) for localization accuracy  
🖥️ **Training** – Multi-output CNN  

---

## ⚡ Model Architecture  
EmojiNet is a **custom CNN model** that predicts:  
1️⃣ **Emoji class** (classification output)  
2️⃣ **Emoji bounding box** (localization output: x, y, width, height)  

**Loss Function:** Categorical Cross-Entropy (for emoji type) + Mean Squared Error (for bounding box)  
**Metric:** Custom IoU (Intersection over Union)  

---

## 🚀 Getting Started  

### 1️⃣ Clone the Repo  
```bash
git clone https://github.com/payal15604/EmojiNet.git
cd emojinet

