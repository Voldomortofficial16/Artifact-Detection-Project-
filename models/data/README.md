data_readme = """# Dataset

This project works with histopathology images for artifact segmentation.

The artifact categories considered in this project are:

1. Tissue folds
2. Ink
3. Air bubbles
4. Dust
5. Marker
6. Out-of-focus

The medical image dataset is not included in this repository.

Please obtain the dataset from the corresponding publicly available source
and place the processed data in this directory before running the notebook.
"""

with open("/content/WSI_Artifact_Detection/data/README.md", "w") as f:
    f.write(data_readme)

print("data/README.md created")
