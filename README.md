# Denoising Dirty Documents Image

---------------------------------------

This project/repo contains the code for Denoising Dirty Documents Image which is the kaggle problem.
Please check for the complete problem statements at kaggle website.
[click me for problem statements](https://www.kaggle.com/c/denoising-dirty-documents)

Installation
----------------------

### Download the data

* Clone this repo to your computer.
* Get into the folder using `cd Denoising-Dirty-Documents-kaggle`.
* Run `mkdir input`.
* Switch into the `input` directory using `cd input`.
* Download the data files from [here](https://www.kaggle.com/c/4406/download-all). into the `input` directory. 
* Extract all of the `.zip` files you downloaded.
* Remove all the zip files by running `rm *.zip`.
* Switch back into the `Denoising-Dirty-Documents-kaggle` directory using `cd ..`.
* Run `mkdir output`. This file will contain the output of your Dirty Document Image.
* Now train each model with if you want it from scratch or you can use it with traind model which is 
in `model` directory.
* Run `testautoencoder.ipynb` for output of you disired document image.

### Install the requirements
 
* Install the requirements using `pip install -r requirements.txt`.
    * Make sure you use Python 3.
