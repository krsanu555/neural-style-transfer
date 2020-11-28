# Neural Style Transfer

In this project, we have implemented neural style transfer Algorithm. Neural style transfer is an optimization technique used to take two images—a 
content image and a style reference image (such as an artwork by a famous painter)—and blend them together so the output image looks like the content image, 
but “painted” in the style of the style reference image.

### Project description

We have used [VGG-19](https://www.kaggle.com/teksab/imagenetvggverydeep19mat), a 19-layer version of the VGG network(https://github.com/opencv)  and [TensorFlow](https://www.tensorflow.org/) Deep Learning Framework for developing Neural Style Transfer Algorithm.
Link to the [Notebook](https://github.com/krsanu555/neural-style-transfer/blob/master/Art_Generation_with_Neural_Style_Transfer.ipynb)


### Set up

1. Clone the repository
```
git clone https://github.com/krsanu555/neural-style-transfer.git
```
2. Move inside the newly created repository
```
cd neural-style-transfer
```
3. Create a virtual environment and install necessary dependecies
```
conda create --name my-env --file requirements.txt
```

### Run Application

1. Go to the root directory of the project
2. Activate virtual environment
```
conda activate my-env
```
3. Start jupyter
```
jupyter notebook
```
4. Run jupyter files you want
Art_Generation_with_Neural_Style_Transfer.ipynb

5. Deactivate environment
```
conda deactivate
```
