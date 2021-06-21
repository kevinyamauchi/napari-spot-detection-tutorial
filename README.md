# napari-spot-detection-tutorial
A tutorial on performing spot detection using napari, scikit-image, and scipy

# Setup
To perform this tutorial, we first need to set up our environment. To do so, please clone the repository containing the tutorial materials to a location of your choice on your computer.

```bash
git clone https://github.com/kevinyamauchi/napari-spot-detection-tutorial.git
```
Then, navigate to the directory you just cloned.

```bash
cd napari-spot-detection-tutorial
```

We have provided an anaconda environment to set up your python environment for this tutorial. To install the dependencies, please enter the following:

```bash
conda env create -f environment.yaml
```

Follow the instructions for installation. When the installation completes successfully, you should see the following

```bash
done
#
# To activate this environment, use
#
#     $ conda activate napari-tutorial
#
# To deactivate an active environment, use
#
#     $ conda deactivate
```

Once the installation has been completed, activate your tutorial environment

```bash
conda activate napari-tutorial
```

You are now ready to start the tutorial! We will perform the analysis using Jupyter Notebook. To start Jupyter Notebook, enter

```bash
jupyter notebook
```

Jupyter Notebook will open in a browser window and you will see two notebooks

- `napari_spot_detection_tutorial.ipynb`: this is the activity notebook
- `napari_spot_detection_tutorial_solution.ipynb`: this is the solution to the activity.

Select `napari_spot_detection_tutorial.ipynb` and begin the tutorial!


