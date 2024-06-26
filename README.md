# LandUAVSafe 

## Description
LandUAVSafe Dataset, for estimating surface inclination angle from images 
## Structure
The dataset is organized in the following structure:

- **Data Directory**: Contains the raw data files. RBG images
- **Ground Truth**: Contains labels (inclination angle of surface in the image), As of now folders have been named according to inclination angle.
- **Documentation Directory**: Contains documentation files providing additional information about the dataset : To be updated
- **Examples Directory**: Contains example scripts or notebooks demonstrating how to use the dataset: To be updated
- **Folders**: House1_wood_45 (wood as surface material and 45 degree inclination), House2_brick_15 (Brick as surface material and 15 degree inclination), House2_wood_60 (Wood as surface meterial and 60 degree inclination), hut_tiled_30 (two inclinations 30 degree each), Mixed (contains all surface inclinatons and multiple objects in single frame) 

## ContentS
- [List of objects](./data/data_file_1.csv): 3 different type objects have been used, House1(small), House2(big) and Hut
- [height of UAV](./data/data_file_2.xlsx): UAV captures images using downward facing camera at different heights 
- [Documentation](./dataset_details.csv): Additional documentation and metadata.
- #[Examples](./examples): Example scripts and notebooks.

## Usage
To use the dataset, simply clone or download this repository to your local machine. Refer to the documentation files for information on how to access and preprocess the data. You can also explore the provided examples to get started with using the dataset in your projects.

## License
This dataset is provided under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/). Please see the [LICENSE](./LICENSE) file for more details.

## Citation
If you use this dataset in your research or projects, please cite it as follows:





## Contributing
Contributions to this dataset repository are welcome! If you have additional data or improvements to existing data, please feel free to open a pull request.

## Issues
If you encounter any issues with the dataset or have suggestions for improvements, please [open an issue](../../issues). We appreciate your feedback!


