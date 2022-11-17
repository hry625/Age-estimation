# Age-estimation

A toy model for age estimationn using Opencv.

# Image file

You need download the image files from [kaggle/UTKFace](https://www.kaggle.com/datasets/jangedoo/utkface-new?resource=download).

Then unzip the image folder to the root folder of this repo.

# Setup with conda

After you installed [conda](https://www.anaconda.com/products/distribution), you can use ```conda create -f env.yml``` to install all required package. Please do note that this .yml file is supposed to be used for Apple's Mac with ARM processor. If you have a Mac with Intel processor or a PC, you need to edit the env.yml file yourself in order to have all  packages are correctly installed.
Then use ```conda activate age-estimator``` in your terminal to activate dedicated python environment.

# Follow the tutorial

Now you can follow [this tutroial](https://www.thepythoncode.com/article/predict-age-using-opencv) to play around.
You don't need to install any packages, all packages are provided within env.yml

# Test with UTKFace

Now we can test the pre-trained model with downloaded UTKFace images.
In your terminal with activated conda environment, you can use ```python predict_age.py '/archive/utkface_aligned_cropped/crop_part1/20_0_0_20170104020603909.jpg.chip.jpg'``` to test the model with pre-trained model.
