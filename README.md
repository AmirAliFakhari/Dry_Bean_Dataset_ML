# Dry Bean Dataset Machine Learning Project

This project explores machine learning techniques applied to the Dry Bean Dataset, focusing on classifying seven different types of dry beans based on features extracted from their images.

## Dataset

The Dry Bean Dataset contains 13,611 instances, each representing a dry bean characterized by 16 features and a `Class` label indicating the bean type. The dataset has no missing values. The `Class` feature is categorical and is one-hot encoded for machine learning tasks.

### Features

- `Area`: Area of the bean.
- `Perimeter`: Perimeter of the bean.
- `MajorAxisLength`: Length of the major axis.
- `MinorAxisLength`: Length of the minor axis.
- `AspectRation`: Aspect ratio.
- `Eccentricity`: Eccentricity.
- `ConvexArea`: Convex area.
- `EquivDiameter`: Equivalent diameter.
- `Extent`: Extent.
- `Solidity`: Solidity.
- `roundness`: Roundness.
- `Compactness`: Compactness.
- `ShapeFactor1`: Shape factor 1.
- `ShapeFactor2`: Shape factor 2.
- `ShapeFactor3`: Shape factor 3.
- `ShapeFactor4`: Shape factor 4.
- `Class`: Type of bean (categorical).

## Files in this Repository

- `Dry_Bean_Dataset.xlsx - Dry_Beans_Dataset.csv`: CSV version of the Dry Bean Dataset.
- `Dry_Bean_Dataset.xlsx - Citation_Request.csv`: Citation information for the dataset.
- `main (7).ipynb`: Jupyter Notebook detailing data loading, exploration, and preprocessing.

## Usage

To run the analysis in the `main (7).ipynb` Jupyter Notebook:

1. **Dependencies**: Install the required Python libraries:

   - `pandas`
   - `numpy`
   - `scipy`
   - `matplotlib`
   - `seaborn`
   - `scikit-learn` (specifically `KMeans` and `TSNE`)

2. **Execution**: Open `main (7).ipynb` in a Jupyter environment (e.g., JupyterLab, Google Colab) and run the cells sequentially. The notebook covers:

   - Loading the dataset using pandas.
   - Checking for missing values.
   - One-hot encoding the `Class` feature.
   - Initial data exploration.

## Citation

If you use this dataset, please cite the original creators:

**Original Citation**:\
M. Koklu, and I. Tufekci, "Classification of Dry Beans Using Convolutional Neural Network (CNN) Based on Images," in Proceedings of the International Conference on Computer Vision and Image Analysis (ICCVIA), 2019, pp. 1-6.

**BibTeX**:

```bibtex
@inproceedings{koklu2019classification,
  title={Classification of Dry Beans Using Convolutional Neural Network (CNN) Based on Images},
  author={Koklu, Murat and Tufekci, Ilker},
  booktitle={International Conference on Computer Vision and Image Analysis (ICCVIA)},
  pages={1--6},
  year={2019},
  organization={IEEE}
}
```