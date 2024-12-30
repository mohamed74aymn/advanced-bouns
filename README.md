# Image Compression and Preview

A simple web application that allows users to upload an image, compress it to different sizes, and preview both the original and compressed versions. Users can also download the compressed images.

## Features
- Upload an image with a size greater than 2 MB.
- Preview the original image and its size.
- Compress the image to 25%, 50%, and 75% of its original size.
- Download compressed images.
- User-friendly alerts for unsupported actions (e.g., images smaller than 2 MB).

## Technologies Used
- **HTML5**: For structuring the webpage.
- **CSS3**: For styling the user interface.
- **JavaScript**: For image processing and dynamic functionality.

## How It Works
1. **Upload Image**: The user uploads an image using the file input.
2. **Validate Size**: If the image size is less than 2 MB, an alert is shown.
3. **Generate Previews**:
   - Displays the original image and its size.
   - Compresses the image to different levels using `canvas` and `toBlob`.
4. **Download Option**: Provides downloadable links for compressed images.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/image-compression-preview.git
