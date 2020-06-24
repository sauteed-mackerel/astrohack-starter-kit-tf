# AstroHack - Tensorflow + Keras Example

A tutorial that demonstrates how to predict galaxy M/L ratios using a simple convolutional neural network with the Keras API of TensorFlow 2.0.

This tutorial is written and tested with Python 3.6.


## How to Use

### Local Environment

This would the the preferred option if you already have a local Python environment configured and your machine has a descent GPU.

1. Clone this repository to your local environment
2. Install and serve a [Jupyter notebook host](https://jupyter.readthedocs.io/en/latest/install.html) from the cloned directory
3. Download the AstroHack datasets to `./data` directory. Unzip any .zip packages there as well.
4. Run the `astrohack_tf_example.ipynb` notebook and enjoy the fun!


### Using a AWS SageMaker Notebook Server

If you are unfamiliar with Python configurations or your local machine does not have a GPU ready for Deep Learning, then you could use a ready-to-go AWS SageMaker notebook instance to get started with. 

1. Create an account with [AWS](http://aws.com/) if you do not have one yet, and navigate to your [AWS console](https://console.aws.amazon.com/).
2. Select or search for `SageMaker` service in the AWS services section.
3. On the navigation panel to the left, find the `Notebook` section and then select `Notebook instances`
4. Create a notebook instance    
    - You can leave most options to their default values
    - In the optional `Git repositories` section, select `clone a public Git repository to this notebook instance only` and enter the URI of this repository.
    - Confirm and create a notebook instance
    - It may take a few minutes before your notebook instance is ready    
    
    
5. Once the notebook instance is ready, click on `Open Jupyter` and then open the `astrohack_tf_example.ipynb` notebook.
6. Follow the notebook instructions and have fun!
