# Color Compression Using K-means Clustering

## 📋 Project Overview
This project demonstrates **color compression** using the **K-means clustering algorithm** in Python. The goal is to reduce the number of colors in an image while preserving its visual quality. This technique can be used to efficiently compress images for storage or transmission, while maintaining an acceptable level of detail.

The project is based on an **annotated Jupyter notebook** which contains step-by-step instructions, code demonstrations, and additional information to help you understand the implementation of K-means for color compression.

## 📁 Data Source
The dataset used in this project is a **JPEG photograph of tulips**. The image data is accessed and processed directly within the notebook. No separate dataset download is required as the image is included in the notebook environment.

### Data Dictionary
- **Image**: A photograph in JPEG format that serves as the dataset for the compression task.
- **Color channels**: The RGB color channels of the image are used as features for clustering.
- **Compressed image**: The output image after applying K-means clustering to reduce the number of colors.

## 💡 Key Concepts
The notebook covers the following key concepts:

1. **Image Processing**:
   - Loading and visualizing the image using Python libraries like `matplotlib` and `PIL`.

2. **Feature Extraction**:
   - Extracting the RGB color values from the image pixels.

3. **K-means Clustering**:
   - Applying the K-means algorithm to group similar colors and reduce the total number of colors.

4. **Color Quantization**:
   - Creating a compressed image by replacing pixel colors with their respective cluster centroids.

5. **Visualization**:
   - Displaying the original and compressed images for comparison.

## 📝 Usage Notes
- The notebook provides a **follow-along guide** with detailed explanations of each code block.
- Additional tips and best practices are included throughout the notebook to help you understand the purpose of each step.

## 📊 Results
After running the notebook, you will see:

- The **original image** displayed with its full color range.
- The **compressed image**, which uses fewer colors, achieved through K-means clustering.

## 📂 Accessing the Data
If you are running the notebook in a Jupyter environment, you can download the image directly:

1. Navigate to the **Lab Files** dropdown menu at the top of the page.
2. Click into the `/home/jovyan/work` folder.
3. Select the relevant JPEG file and click **Download**.

## ⚠️ Notes
- The K-means clustering assumes the color values are normally distributed. While this may not always be the case, the method still yields good results for most natural images.
- The notebook uses a **pre-set random seed** for reproducibility.
