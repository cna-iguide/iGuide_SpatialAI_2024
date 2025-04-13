# iGuide_SpatialAI_2024

## Overview

**iGuide_SpatialAI_2024** is a project focused on spatial artificial intelligence. The project comprises three main Jupyter notebooks: [`main.ipynb`](main.ipynb), [`utils.ipynb`](utils.ipynb), and [`unet.ipynb`](unet.ipynb). The primary workflow is executed from the [`main.ipynb`](main.ipynb) notebook, which leverages utility functions and a U-Net model for spatial data processing.

## Repository Structure

```
iGuide_SpatialAI_2024/
|-- main.ipynb
|-- utils.ipynb
|-- unet.ipynb
|-- requirements.txt
|-- README.md
|-- Datasets
|-- models
|-- resources

```


- **main.ipynb**: The entry point for the project. This notebook coordinates the overall workflow, calling functions and models defined in the other notebooks.
- **utils.ipynb**: Contains utility functions that support data preprocessing, visualization, and other auxiliary tasks.
- **unet.ipynb**: Implements the U-Net model, a convolutional neural network designed for image segmentation tasks.

## Getting Started

### Prerequisites

To run the notebooks, you need to have the following software and libraries installed:
#### Development Environment
- [**Python 3.11.x**](https://www.python.org/downloads/release/python-3110/)
- [**Jupyter Notebook**](https://jupyter.org/)

#### Standard library imports
- [**os**](https://docs.python.org/3/library/os.html)
- [**sys**](https://docs.python.org/3/library/sys.html)
- [**Pathlib**](https://docs.python.org/3/library/pathlib.html)
- [**warnings**](https://docs.python.org/3/library/warnings.html)
- [**import_ipynb**](https://pypi.org/project/import-ipynb/)

#### Third-party libraries
- [**NumPy**](https://numpy.org/)
- [**TensorFlow**](https://www.tensorflow.org/)
- [**Matplotlib**](https://matplotlib.org/)
- [**Scikit-Learn**](https://scikit-learn.org/)
- [**PIL (Pillow)**](https://pillow.readthedocs.io/en/stable/index.html)

#### Python 3.x built-in libraries
Note that these libraries should not need to be manually installed, but they are included here for reference.
- [**shutil**](https://docs.python.org/3/library/shutil.html)
- [**re (Regular Expressions)**](https://docs.python.org/3/library/re.html)
- [**typing**](https://docs.python.org/3/library/typing.html)
- [**random**](https://docs.python.org/3/library/random.html)

**Note:** You can install these libraries using the **requirements.txt** in this repository.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/cna-iguide/iGuide_SpatialAI_2024.git
    cd iGuide_SpatialAI_2024
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Project

1. Open the Jupyter Notebook server:
    ```bash
    jupyter notebook
    ```

2. Navigate to the [`main.ipynb`](main.ipynb) notebook and open it.

3. Execute the cells in [`main.ipynb`](main.ipynb) to run the project. This notebook will call functions from [`utils.ipynb`](utils.ipynb) and use the U-Net model from [`unet.ipynb`](unet.ipynb) to process spatial data.

## Usage

### [`main.ipynb`](main.ipynb)

This notebook is the main entry point for the project. It orchestrates the data loading, preprocessing, model training, and evaluation steps.

### [`utils.ipynb`](utils.ipynb)

Contains utility functions for various tasks such as:
- Data loading and preprocessing
- Data augmentation
- Visualization of results
- Data saving

### [`unet.ipynb`](unet.ipynb)

Implements the U-Net model, which is used for image segmentation. This notebook defines the architecture, training loop, and evaluation metrics for the model. This notebook also contains utility functions specifically for U-Net tasks such as:
- Preparing the U-Net model
- Visualization of results
- Data saving

## License

The code and notebooks associated with this project are licensed under the MIT License. See the [LICENSE](LICENSE.txt) for more details.

## Acknowledgements

- The authors would like to thank the contributors and the open-source community for their valuable tools and libraries.