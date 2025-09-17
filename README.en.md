# DaysOld - Photo Age Calculator

A simple web application that calculates people's ages based on EXIF timestamps from photos.\
No Pictures are transfered, only laoded in the Browser !

## 🎯 Features

- **People Management**: Add multiple people with names and birthdates
- **EXIF Data Analysis**: Automatic extraction of capture date from photo metadata
- **Age Calculation**: Precise calculation of age at the time the photo was taken / created
- **Pregnancy Mode** (BABY-Version): Special display for unborn babies
- **Photo Sharing**: Create and share polaroid-style images with age information
- **Responsive Design**: Optimized for desktop and mobile devices

## 🚀 Usage

1. **Add People**
   - Enter name and birthdate
   - Click "Add Person"
   - For unborn babies: Use a future date to enable pregnancy mode

2. **Upload Photo**
   - Select a photo with EXIF data
   - Age is automatically calculated and displayed

3. **Share Results**
   - Click "Share as Image" to create a shareable version
   - The generated image can be downloaded or shared

## 📋 Technical Details

- **Single-Page Application**: Entire application in one HTML file
- **No Installation Required**: Works directly in the browser
- **EXIF.js Integration**: Reads metadata directly from image files
- **Privacy**: All calculations are performed locally in the browser

## 📝 License

This project is open source and available under the MIT License.
