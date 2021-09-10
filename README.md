# pcv

## Code from "Programming Computer Vision" by Jan Erik Solem

Selected code from [**Programming Computer Vision**](http://programmingcomputervision.com/) by *Jan Erik Solem*.

Code has been modified to work with Python 3.x and also cleaned up use standarding aliases for numpy and matplotlib. Other minor changes here and there.

## Environment Setup

If you are using Anaconda, you set up a new conda environment as follows:

```
conda env create -f env.yml
```

This creates a new conda environment called **pcv**. To add this as a kernel to Jupyter, use the following command:
```
python -m ipykernel install --user --name pcv --display-name "Python (pcv)"
```

## Image Data

Download the [zip file](https://github.com/jesolem/PCV/zipball/master) from http://programmingcomputervision.com/ and unzip into a directory called `data`. You may also need to unzip some of the contained zip files into their own subdirectories under data.
