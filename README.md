# 🐚 Ammonite-model 🦕  
  
This is an Ultralytics YOLO V6.0 machine vision model for detecting fossil ammonites. It was created by labeling 300 images of ammonites, totaling over 800 annotations, using Datature's online free trial version. This dataset was used to build a machine vision YOLO model through deep (transfer) learning.  
  
## 🎥 Demo Video  
To see the model in action, check out this demo video:  
[Ammonite Model Demo](https://github.com/bsab/Ammonite-model/raw/refs/heads/patch-1/Smartphone_ammonite_detector_video.mov)

## 🌟 Features  
- 📱 Detects fossil ammonites in real-time using your smartphone camera.  
- 🧠 Educates children and adults about Geology and AI.  
- 👁️‍🗨️ Potentially useful for the visually impaired.  
  
## 🚀 Installation and Setup  
  
### Step 1: 📥 Download the Vision Detector App  
1. Go to the [App Store](https://apps.apple.com/it/app/vision-detector/id6443729650?platform=iphone) on your smartphone.  
2. Search for **Vision Detector** and download the app.  
  
### Step 2: 🔄 Download the Ammonite Model  
1. Download the model file from the provided link (ensure the link is accessible and updated).  
2. Save the model file to a location on your smartphone where it can be easily accessed.  
  
### Step 3: 📂 Load the Model into the Vision Detector App  
1. Open the **Vision Detector** app.  
2. Navigate to the model loading section (refer to the app's documentation if needed).  
3. Load the downloaded Ammonite model file into the app.  
  
### Step 4: 📸 Using the Model  
1. Point your smartphone camera at objects you want to analyze.  
2. The app will detect and highlight ammonites in real-time.  
  
> **Note:** The accuracy of the model varies depending on the object and environment. The Vision Detector App does not allow setting a confidence threshold, so it may detect low-probability ammonites as high-confidence detections (e.g., 1.0).  
  
### Step 5: 🛠️ Advanced Usage (Optional)  
For those who want more control over the detection process, you can build your own smartphone app or use Python to apply the model to photographs. This allows setting custom confidence cutoffs and other advanced features.  
  
## 📱 Vision Detector App Features  
The Vision Detector app performs real-time image processing using a CoreML model on Mac. Here’s how to use it:  
  
- **Input Devices:** The app searches for input devices in the following order: external video inputs connected to your Mac, the MacBook's FaceTime camera, and nearby iPhones. You can switch input devices via the camera menu.  
- **Model Selection:** Select your CoreML machine learning model from the app's open menu or control panel buttons, or drag and drop it onto the Vision Detector app icon in Finder or Dock.  
- **Processing:** Start or stop processing by pressing the 'Play' button or hitting the space bar.  
- **Supported Models:** Includes image classification, object detection, and style transfer. Models lacking a non-maximum suppression layer, or those that use MultiArray for input/output data, are not supported.  
    
Enjoy exploring the fascinating world of Geoscience with the power of AI! 🦑💡  

