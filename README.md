<<<<<<< HEAD
# network-data-analysis
Daily Progress Log

network-data-analysis
Daily Progress Log
3.3

Read the task document to familiarize yourself with the task

3.4

Establishment of the basic framework and readiness to proceed with the completion of the tasks in task 1

3.5

Completion of the preamble to part 1 and code implementation of task A of part
=======
# 7CUSMNDA-2025
Official repository for 7CUSMNDA Network Data Analysis (24~25 SEM2)

## Getting started

To run Lab's notebooks, we encourage you to create a virtual environment and install all the packages that will be needed throughout  the course. For this, we provide a `requirements.txt` file so that you can easily set up your own environment from scratch.
> :warning: If you do not configure your environment properly, your notebooks will not run.

### Step 1: Check your conda setup
Open a terminal session and run `conda`. If the command is note recognised, this means that you do not have `conda` on your system, or that you local setup has not been configured well. In that case, please visit [this link](https://docs.conda.io/projects/conda/en/latest/user-guide/install/) and install a working version of `conda` (e.g. `Miniconda`).

### Step 2: Create the environment
Assuming that your conda installation works, you can now create your virtual environment. From a terminal session, run the commands below, one after the other.
```
conda create -n nda -c conda-forge --strict-channel-priority osmnx
conda activate nda
```
Now that your environment is created and activated, you can install all packages for this module by running:
```
pip install -r requirements.txt
```
Your environment should now be ready to run our notebooks.

## Running our notebooks

Running our coding notebooks require some familiarity with Python and Jupyter. Common ways to run the notebooks include:

- **Jupyterlab** (Recommended). An extended version of Jupyter notebooks (more info [here](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html)).

  Running:
  ```
  cd 7CUSMNDA-2025
  conda activate nda
  jupyter lab
  ```
  The server can be accessed at `http://localhost:8888/lab`.
- Running the notebook from a text editor (e.g. Visual Studio Code) or an IDE (e.g. PyCharm), and selecting `nda` when choosing the kernel/running environment.
- **Jupyter Notebook**. Just activate your environment using `conda activate nda` and run `jupyter notebook` from the same session.

If none of these options work, feel free to contact us. In the while, you can use the Colab version of our notebooks (see below).

---

## Colab notebooks and additional material

If you prefer to run notebooks on Colab, we will also update the links to notebooks here. You can open the link, save a copy to your own Google Drive then run it.

| Week # |   Date    |                                         Practical Lab                                          |                                              Exercise                                               |    Solution    |
|:------:|:---------:|:----------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------:|:--------------:|
|   1    | 13-Jan-25 |                                             No lab                                             |                                             No exercise                                             |       -        |                                                                                                      |
|   2    | 20-Jan-25 | [Lab 1](https://drive.google.com/file/d/1C04BzQ8bCwgfV3Amh6bjL_Uceh9Faczm/view?usp=share_link) | [Exercise 1](https://drive.google.com/file/d/1EMoncvZ7K-h1Zz9e0mqRg5l7eCTxUKIF/view?usp=share_link) | [Solution 1]() |  
|   3    | 27-Jan-25 |                                                                                                |                                                                                                     |                |  
|   4    | 03-Feb-25 |                                                                                                |                                                                                                     |                |  
|   5    | 10-Feb-25 |                                                                                                |                                                                                                     |                |  
|   6    | 17-Feb-25 |                                                                                                |                                                                                                     |                |  
|   7    | 24-Feb-25 |                                                                                                |                                                                                                     |                |  
|   8    | 03-Mar-25 |                                                                                                |                                                                                                     |                |  
|   9    | 10-Mar-25 |                                                                                                |                                                                                                     |                |  
|   10   | 17-Mar-25 |                                                                                                |                                                                                                     |                |  
|   11   | 24-Mar-25 |                                                                                                |                                                                                                     |                |  
>>>>>>> fc89736 (Task A)
