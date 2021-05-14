# Evaluating-the-Robustness-of-Self-Supervised-Learning-in-Medical-Imaging


Source code for our paper "Evaluating-the-Robustness-of-Self-Supervised-Learning-in-Medical-Imaging"

Authors: Fernando Navarro, Christopher Watanabe, Suprosanna Shit, Anjany Sekuboyina,  Jan Peeken , Stephanie E. Combs, and Bjoern H. Menze.

<img src="./model_architecture_transfer.png"/>

## Getting Started
### Pre-requisites

You need to have following in order for this library to work as expected

1. python >= 3.6.5
2. pip >= 18.1
3. tensorflow-gpu = 1.9.0
4. tensofboard = 1.9.0
4. numpy >= 1.15.0
5. dipy >= 0.14.0
6. matplotlib>= 2.2.2
7. nibabel >= 1.15.0
8. pandas >= 0.23.4
9. scikit-image >= 0.14.0
10. scikit-learn >= 0.20.0
11. scipy >= 1.1.0
12. seaborn >= 0.9.0
13. SimpleITK >= 1.1.0
14. tabulate >= 0.8.2
15. xlrd >= 1.1.0

### Install requirements
Run `pip install -r requirements.txt`


## How to use the code for training
### Convert your data-set to npz


### Start the training
Run the python script `train_val.py`. Make sure to change file paths for tfrecord files according to your configuration.


## How to use the code for inference

Run the python script `inference.py`. Follow the commends in the script to change variables according to your training model and file paths.


## License and Citation

Please cite our paper if it is useful for your research:

## Code Authors

* **Fernando Navarro**  - [ferchonavarro](https://github.com/ferchonavarro)
* **Christopher Watanabe** - []
## Help us improve
Let us know if you face any issues. You are always welcome to report new issues and bugs and also suggest further improvements. And if you like our work hit that start button on top. Enjoy :)
