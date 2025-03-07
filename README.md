# 🪙 Coin Year Detector - My First ML Experiment! 🎉  

Hey there! 👋 This is my first attempt at building a machine learning model, and I’m super excited to dive into the world of AI! I watched a few YouTube videos about CNNs and wanted to apply what I learned in a **fun and engaging way**.

## 💡 The Idea  
Since I couldn't find an existing dataset for **Algerian 5DZ coins**, I decided to create my own and train a **Coin Year Detector**!

## 📸 Collecting the Dataset  
At first, I thought gathering coin images would be easy—just snap photos of all the years from **1962 to 2025**. Turns out, some years were missing (e.g., 1999, 2000, 2001, etc.), but no big deal!

## 🏗️ Building the Dataset  
- Captured **multiple images per coin** using my **Redmi 9 Power** 📱  
- Experimented with different lighting (flash/no flash) and zoom levels  
- Final dataset split: **70% train / 15% validation / 15% test**  

## 🛠️ Model v0.1  
A simple **CNN using TensorFlow & Keras**, but my first attempt failed hard—**7% accuracy after 60 epochs** 😅. My **10-year-old laptop (i3-3110M, no GPU) struggled**, but I kept pushing forward!

## 🔥 Model v0.2 - Learning from Mistakes  
- Switched to **grayscale images (500x500)**  
- Increased dataset size (50+ images per class)  
- Improved preprocessing  
- Results? **83% accuracy after 40 epochs** – still not great, but better!  

## 🏆 Next Steps  
- 📈 Collect more data (different lighting, angles, zoom levels)  
- 🏗️ Improve model architecture  
- 🔄 Try **Transfer Learning (ResNet-50)**  
- 🔍 Fine-tune preprocessing & augmentations  
- 🚀 Share dataset & code for others to use!  
## 📂 Download Dataset  
You can download the dataset from **Google Drive**:  
🔗 [Click here to download](https://drive.google.com/drive/folders/19L55dXjF10Y5bbWJr7lOWsVC7aHImf1D?usp=drive_link)  

I’m documenting my progress here—feel free to check it out and drop any tips! 😊

