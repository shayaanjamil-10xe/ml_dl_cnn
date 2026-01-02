The goals of this assignment
are as follows:

- understand the architecture of **Convolutional Neural Networks**
- gain an understanding of how a modern deep learning library (PyTorch) works
  and gain practical experience using it to train models.

## Setup
Same as Assignment 1.
Copy the deeplearning folder from your Assignment 1.
It will contain functions which might be needed in this assignment.

**Download data:**
Once you have the starter code, you will need to download the CIFAR-10 dataset.
Run the following from the `assignment2` directory:

```bash
cd deeplearning/datasets
./get_datasets.sh
```

If you are on Mac, this script may not work if you do not have the wget command 
installed, but you can use curl instead with the alternative script.
```bash
cd deeplearning/datasets
./get_datasets_curl.sh
```

**Compile the Cython extension:** Convolutional Neural Networks require a very
efficient implementation. We have implemented of the functionality using
[Cython](http://cython.org/); you will need to compile the Cython extension
before you can run the code. From the `deeplearning` directory, run the following
command:

```bash
python setup.py build_ext --inplace
```

### Submitting your work:
You will need to create a private fork of this repository and add your SME as a collaborator to the repoistory.

### Q1: ConvNet
In the IPython Notebook `ConvolutionalNetworks.ipynb` you will implement several
new layers that are commonly used in convolutional networks as well as implement
a small convolutional network.

### Q2: Train a model on CIFAR10 using Pytorch!
Now that you've implemented and gained an understanding for many key components 
of a basic deep learning library, it is time to move on to a modern deep learning
library: Pytorch. Here, we will walk you through the key concepts of PyTorch, and
you will use it to experiment and train a model on CIFAR10. We highly recommend 
you use Google Colab (https://colab.research.google.com/) for this notebook, as it
comes with Pytorch installed and provides access to GPUs.

If you use Colab for this notebook, make sure to manually download the completed 
notebook and place it in the assignment directory before submitting. Also remember 
to download required output file and place it into submission_logs/ directory.


