# ImageFormatLab

Image Format Lab is a client-side web tool that converts a single image into multiple modern image formats and presents a clear, visual comparison of quality, size, and compression efficiency. All processing happens directly in the browser.

## 🚀 Features

### Core Functionality
- **Multiple Format Conversion**: Converts images to PNG, JPEG, WebP, and AVIF (where supported)
- **Canvas-Based Re-encoding**: Uses HTML5 Canvas API for accurate image conversion
- **Quality Control**: Adjustable quality slider for JPEG and WebP formats (1-100%)
- **Drag & Drop Interface**: Easy file upload with drag-and-drop support

### Visual Comparison Tools
- **File Size Display**: Shows compressed size for each format with original file size reference
- **Compression Ratio**: Calculates and displays compression efficiency for each format
- **Side-by-Side Preview**: View all formats simultaneously with zoomable previews
- **Pixel-Difference Heatmap**: Advanced view showing visual differences from original (optional)

### Output Options
- **Download Converted Images**: Save any converted format directly to your device
- **Format Recommendations**: Educational information about each format's best use cases

## 🎯 Why Use ImageFormatLab?

- **Helps developers and designers choose optimal formats** for web projects
- **Educational tool** to understand format differences and compression trade-offs
- **Practical utility** for quick image format conversion and comparison
- **Privacy-focused**: All processing happens client-side, no server uploads

## 🖼️ Supported Formats

### Input Formats
- JPEG/JPG
- PNG
- GIF
- BMP
- WebP

### Output Formats
- **PNG**: Lossless compression, best for graphics with transparency
- **JPEG**: Universal support, ideal for photographs
- **WebP**: Modern format with excellent compression and quality balance
- **AVIF**: Next-generation format with superior compression (browser support required)

## 🔧 How to Use

1. **Open the Application**: Open `index.html` in a modern web browser
2. **Upload an Image**: 
   - Click the upload area to browse for a file
   - Or drag and drop an image directly onto the upload area
3. **Adjust Quality** (optional): Use the slider to set JPEG/WebP quality (default: 85%)
4. **Enable Heatmap** (optional): Check the box to see pixel differences
5. **Convert**: Click "Convert Image" button
6. **Review Results**: 
   - Compare file sizes and compression ratios
   - View side-by-side previews (click to zoom)
   - Analyze pixel-difference heatmaps (if enabled)
7. **Download**: Save any converted format using the download buttons

## 📊 Understanding the Results

### File Size
The size of the converted file in KB or MB. Smaller files load faster on web pages but may have lower quality.

### Size Reduction
Percentage showing how much smaller (or larger) the converted file is compared to the original.

### Compression Ratio
Ratio of original size to compressed size. Higher values indicate better compression:
- `> 1.0x`: File was compressed (good)
- `< 1.0x`: File became larger (may indicate original was already optimized)

### Pixel-Difference Heatmap
Visual representation of quality loss:
- **Black areas**: No difference from original
- **Red areas**: Visible differences detected
- **Brighter red**: Greater pixel differences

## 🌐 Browser Compatibility

- **Chrome/Edge**: Full support (PNG, JPEG, WebP, AVIF)
- **Firefox**: Full support (PNG, JPEG, WebP, AVIF)
- **Safari**: PNG, JPEG, WebP supported; AVIF support varies by version
- **Requires**: Modern browser with Canvas API and Blob support

## 💡 Format Selection Guide

### When to Use Each Format

**PNG**
- Images requiring transparency
- Graphics, logos, and illustrations
- When lossless quality is essential
- Screenshots and UI elements

**JPEG**
- Photographs and complex images
- When some quality loss is acceptable
- Maximum compatibility needed
- File size is a concern

**WebP**
- Modern web applications
- Balance of quality and file size
- When browser support allows
- Both photos and graphics

**AVIF**
- Cutting-edge web projects
- Maximum compression needed
- When browser compatibility is not critical
- Future-proof web applications

## 🚀 Quick Start

Simply open the `index.html` file in your browser:

```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx serve

# Using PHP
php -S localhost:8080
```

Then navigate to `http://localhost:8080` in your browser.

## 📝 Technical Details

- **Pure HTML/CSS/JavaScript**: No dependencies or build process required
- **Client-Side Processing**: All conversions happen in your browser
- **Privacy-Focused**: Images never leave your device
- **Responsive Design**: Works on desktop and mobile devices

## 🤝 Contributing

Contributions are welcome! This project is open-source and available for improvements.

## 📄 License

See LICENSE file for details.

## 🎨 Screenshots

### Initial Upload Screen
Upload interface with drag-and-drop support.

### Conversion Results
Format comparison showing file sizes, compression ratios, side-by-side previews, and optional pixel-difference heatmaps.
