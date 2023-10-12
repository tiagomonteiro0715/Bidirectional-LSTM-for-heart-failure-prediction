# Bidirectional LSTM(Long Short Term memory) model for heart failure prediction

https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction


### What this project does?

From 11 features(Age, Sex, Cholesterol...), predict the chance of heart failure in pacients.

Since there are many features, the mathametical function that describes it a non linear differencial equation

Neural networks can act as universial approximators for complex non linear differencial equations

Mathematically, this is called the [Universal approximation theorem](https://en.wikipedia.org/wiki/Universal_approximation_theorem)

In the notebooks, essecially, we are building an universally approximator based on those 11 features that predict the chance of heart failure.
 
### Why you used the technologies you used?

PyTorch lightning was the main library used, because of its simplicicy in scaling the size of the model

Addicionally, it allows very easily the creation of the training loop and evaluation loop

Making the full creation of the model and the functions that train and eavluate it in asingle python class, in a single cell

The last reason was that, as of 

### Some of the challenges you faced and features you hope to implement in the future?

Converting the dataset in tensors in the right format for training in the Bi direcional LSTM model

Finding the best Hyperparameters for the model

-----

# Table of Contents

### [ How to Install and Run the Project ](#How_to_install)

### [ How to Use the Project ](#How_to_use)

### [ Include Credits, Authors and acknowledgment for contributions ](#credits)


-----


<a name="How_to_install">

#### How to Install and Run the Project

#### Reserach depedencies

```
pip install pandas numpy ipykernel notebook scikit-learn torch lightning ipynbname
```

## To install Jupyter Notebook and associate it with your virtual environment in Python, follow these steps:

### 1. Create a Virtual Environment (if not already created):
If you haven't already created a virtual environment for your project, you can do so using virtualenv or venv. Here's an example using venv:

```
python -m venv myenv
```


Replace ```myenv``` with the desired name for your virtual environment.

### 2. Activate the Virtual Environment:
On Windows, activate the virtual environment using:

```
myenv\Scripts\activate
```


On macOS and Linux, use:
```
source myenv/bin/activate
```
Replace ```myenv``` with the name of your virtual environment.


### 3. Install Jupyter Notebook:
Once the virtual environment is activated, you can install Jupyter Notebook using pip:

```
pip install jupyter
```
This will install Jupyter Notebook within your virtual environment.

### 4. Verify Jupyter Installation:
To verify that Jupyter Notebook is installed in your virtual environment, you can run:


```
jupyter --version
```

This should display the version of Jupyter Notebook installed within your virtual environment.

### 5. Create a Jupyter Notebook Kernel for the Virtual Environment:
You need to create a Jupyter Notebook kernel that is associated with your virtual environment. This allows you to use the packages installed in your virtual environment within Jupyter Notebook.

#### a. First, activate your virtual environment (if it's not already activated).

#### b. Install the ipykernel package within the virtual environment:

```
pip install ipykernel
```
#### c. Now, you can create a Jupyter Notebook kernel for your virtual environment:


```
python -m ipykernel install --user --name=myenv --display-name="name"
```

Replace ```myenv``` with the name of your virtual environment and choose a suitable display name.

### 6. Start Jupyter Notebook:
Now, you can start Jupyter Notebook from within your virtual environment:

```
jupyter notebook
```
This will open a new Jupyter Notebook session in your web browser, and you should be able to select the "My Virtual Environment" kernel when creating a new notebook. This kernel will use the packages installed in your virtual environment.

</a>

<a name="How_to_use">


#### How to Use the Project

It can be used as foundation for other time series classification models.

With quantization, the model can be applied in sensores and small devices for IoT or microcontrolers

</a>


<a name="credits">

#### Include Credits, Authors and acknowledgment for contributions

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus feugiat fringilla eros nec mattis. Cras nec sagittis risus, vel mattis odio. Sed erat massa, commodo nec rutrum ac, tincidunt quis magna. Pellentesque non tristique ante. Phasellus convallis ante tincidunt lacus tempor aliquam. Donec quis ipsum laoreet, pretium ligula quis, pulvinar ante. Nam fringilla nunc in accumsan tempus. 

</a>

