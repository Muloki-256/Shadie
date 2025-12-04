# Shadie
Shadie heart website by Derick
# Heart for Shadie 💖

A beautiful, interactive digital heart created with love for Shadie by Derek. This is a personalized web page featuring photos, a special video message, and romantic animations that can be opened on any smartphone.

## 🌟 Features

- **Animated Beating Heart** - A beautiful heart that pulses with love
- **Photo Gallery** - Showcase of special memories together
- **Portrait Video Player** - Special video message optimized for vertical viewing
- **Interactive Elements**:
  - Secret love message that reveals with animations
  - Photo gallery with lightbox viewing
  - Video controls (play, pause, restart)
  - Floating hearts and confetti effects
- **Responsive Design** - Works perfectly on all mobile devices
- **Romantic Animations** - Hearts, sparkles, and celebration effects
- **Personalized Content** - Custom messages and photos

## 📱 How to Use

### For Derek (Setting Up):
1. **Prepare Your Files**:
   - Save all photos in an `images/` folder (named: `shadie.jfif`, `shadiie.jfif`, etc.)
   - Save your video as `shadie.mp4` in the main folder
   - Save the HTML file as `heart-for-shadie.html`

2. **Folder Structure**:
   ```
   project-folder/
   ├── heart-for-shadie.html
   ├── shadie.mp4
   └── images/
       ├── shadie.jfif
       ├── shadiie.jfif
       └── shadiee.jfif
   ```

3. **Customization Options**:
   - Edit the title and messages in the HTML
   - Change colors by modifying CSS variables at the top
   - Add more photos by duplicating gallery items
   - Update the video source if needed

### For Shadie (Viewing):
1. **On iPhone**:
   - Tap the HTML file in Messages/Files
   - It will open in Safari
   - Tap "Allow" if asked about media permissions

2. **On Android**:
   - Tap the HTML file in WhatsApp/File Manager
   - Choose "Chrome" or "Browser" to open
   - Allow media permissions if prompted

3. **Interactive Elements**:
   - **Heart's Secret Button**: Reveals a romantic message with animations
   - **View Our Memories**: Shows photo gallery below the button
   - **Watch Our Special Video**: Plays your video message below the button
   - **Click Photos**: Opens them in fullscreen lightbox
   - **Click Video**: Tap to play/pause, double-tap for fullscreen

## 🎨 Design Elements

- **Color Scheme**: Romantic pinks and reds with gradient backgrounds
- **Heart Animation**: Realistic beating heart with glow effect
- **Photo Display**: Heart-shaped photo frame with rotating photos
- **Video Player**: Optimized for portrait videos with custom controls
- **Animations**: Floating hearts, sparkles, confetti bursts
- **Typography**: Elegant fonts with gradient text effects

## 🔧 Technical Details

- **Pure HTML/CSS/JavaScript** - No external dependencies (except Font Awesome icons)
- **Mobile-First Design** - Optimized for smartphone viewing
- **Portrait Video Support** - Special handling for vertical videos
- **Touch-Friendly** - All interactions work with touch gestures
- **Lightweight** - Fast loading even on slower connections

## 💝 Personalization Tips

1. **Add More Photos**:
   ```html
   <div class="gallery-item" onclick="openLightbox(this)">
       <img src="images/your-photo.jpg" alt="Our Memory" class="gallery-photo">
   </div>
   ```

2. **Change Messages**:
   - Edit text in the `message` and `secret-message` sections
   - Update the title to include special dates or nicknames

3. **Update Video**:
   - Replace `shadie.mp4` with your new video
   - Update the video poster image if needed

## 🚀 Sharing Options

### Option 1: Direct File Share
- Compress all files into a ZIP folder
- Send via WhatsApp/Telegram/Email
- She extracts and opens the HTML file

### Option 2: Online Deployment (Free)
1. Upload to GitHub Pages, Netlify, or Vercel
2. Share the live URL with her
3. She can open it directly in her browser

### Option 3: QR Code
1. Generate a QR code for the HTML file or URL
2. Send the QR code image
3. She scans it with her phone camera

## 📝 Notes

- **Video Format**: MP4 works best (H.264 codec)
- **Photo Sizes**: Square photos (1:1 ratio) look best in the gallery
- **File Names**: Use lowercase with no spaces for compatibility
- **Testing**: Open the HTML file on your own phone first to test

## ❤️ Special Features

1. **Heartbeat Animation**: The heart actually beats like a real heart
2. **Surprise Effects**: Confetti and floating hearts when opening secrets
3. **Memory Gallery**: Photos can be tapped for fullscreen viewing
4. **Video Celebration**: Special effects when video starts and ends
5. **Dark Mode Support**: Automatically adapts to phone's theme

## 🛠️ Troubleshooting

**Video doesn't play?**
- Ensure it's MP4 format
- Check file name matches HTML code
- Try a shorter video (under 2 minutes)

**Photos don't show?**
- Check file paths in the HTML
- Ensure photos are in the `images/` folder
- Verify file names are correct

**Animations not working?**
- Make sure JavaScript is enabled
- Try opening in Chrome/Safari
- Check for any error messages in browser console

## 📄 File List

- `heart-for-shadie.html` - Main HTML file
- `shadie.mp4` - Your special video
- `images/shadie.jfif` - Main photo
- `images/shadiie.jfif` - Additional photo
- `images/shadiee.jfif` - Additional photo

## 💌 Final Message

This digital heart is more than just code - it's a container for your love, memories, and special moments together. Every animation, every effect, every line of code was written with Shadie in mind. May it bring a smile to her face every time she opens it!

Made with ❤️ by Derek for Shadie
