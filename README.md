# Image ClusterLab – Image Segmentation Using K-Means & Hierarchical Clustering

Image ClusterLab is a Python-based image segmentation project that explores how clustering algorithms can group image pixels based on their color values.

The notebook demonstrates two unsupervised clustering techniques:

- **K-Means Clustering** – segments an image into a selected number of color clusters.
- **Hierarchical Clustering (Agglomerative)** – applies hierarchical clustering to image pixel values and visualizes the resulting hierarchy with a dendrogram.

## Project Workflow

1. Import the required Python libraries.
2. Load and display an image.
3. Read and convert the image using OpenCV.
4. Reshape image pixels into a dataset.
5. Apply K-Means clustering with different values of `K`.
6. Visualize the segmented images and cluster centers.
7. Resize the image for hierarchical clustering.
8. Apply Agglomerative Clustering.
9. Display the hierarchical clustering dendrogram.

## Technologies & Libraries

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- Scikit-learn
- SciPy

## Getting Started

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd Image-ClusterLab
```

### 2. Install dependencies

```bash
pip install numpy pandas matplotlib seaborn opencv-python scikit-learn scipy jupyter
```

### 3. Add the input image

The notebook currently loads an image named `Image.jpeg`. Place your image in the **same directory** as `Image_ClusterLab.ipynb` and name it exactly:

```text
Image.jpeg
```

> Note: The supplied ZIP contains the notebook but does not include `Image.jpeg`. Add an image before running the notebook.

### 4. Run the notebook

```bash
jupyter notebook
```

Open `Image_ClusterLab.ipynb` and run the cells in order.

## Repository Structure

```text
Image-ClusterLab/
│
├── Image_ClusterLab.ipynb
├── README.md
└── Image.jpeg                 # Add your input image here
```

## Learning Outcomes

- Understand image segmentation and unsupervised learning.
- Explore pixel-based image clustering.
- Compare K-Means and hierarchical clustering.
- Visualize segmented images and hierarchical relationships.

## Project Type

Machine Learning | Unsupervised Learning | Computer Vision

---

**Note:** This repository preserves the original notebook's implementation. The README and project naming are added for GitHub presentation; the notebook's existing code and workflow are otherwise unchanged.
