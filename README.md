# Image Classificaiton of BCCD

# Directory Structure

### Dataset BCCD

BCCD from here : https://github.com/Shenggan/BCCD_Dataset
This was found using Kaggle
Images are .jpg and they have associated annotation files which has also been converted to a .csv to make reading them into a dataframe easier.

This has been supplied in BCCD.zip and will need to be unzipped to BCCD at the root level of this project.

Moving it to another location will impact the python notebooks ability to read the data.

### BCCD_small

Contains a .csv that uses a smaller list of images.

### Images

The output from runs, file name convention is

<number of epochs>_epcochs_over_<number of images>
example
one_epoch_over_50.jpg

### Root

The pyton notebooks live in the root directory to make referencing other files easier.
