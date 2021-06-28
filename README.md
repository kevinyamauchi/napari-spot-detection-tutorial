# napari-spot-detection-tutorial
A tutorial on performing spot detection using napari, scikit-image, and scipy

# Setup
To perform this tutorial, we first need to set up our environment. To do so, please clone the repository containing the tutorial materials to your computer. We recommend cloning the materials into your Documents folder, but you can choose another suitable location. First, open your Terminal navigate to you the folder you will download the course materials into

```bash
cd ~/Documents
```
and then clone the repository. This will download all of the files necessary for this tutorial.

```bash
git clone https://github.com/kevinyamauchi/napari-spot-detection-tutorial.git
```
Then, navigate to the directory you just cloned.

```bash
cd napari-spot-detection-tutorial
```

We have provided an anaconda environment file to set up your python environment for this tutorial. To install the dependencies, please enter the following. This may take 5-10 minutes, so feel free to take a break and grab a coffee.

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

You can test to make sure napari was installed correctly launching napari from the command line using the command below. Launching napari this first time will take some extra time because it will download the cellpose image segmentation models that we will use during this tutorial.

```bash
napari
```

You are now ready to start the tutorial! We will perform the analysis using Jupyter Notebook. To start Jupyter Notebook, enter

```bash
jupyter notebook
```

Jupyter Notebook will open in a browser window and you will see three notebooks:

- `spot_detection_tutorial_beginner.ipynb`: this is the activity notebook for people new to image processing with python
- `spot_detection_tutorial_advanced.ipynb`: this is the activity notebook for people with experience performing image processing with python
- `spot_detection_tutorial_solution.ipynb`: this is the solution to the activity.

All of the notebooks cover the same activities, they just require you to fill in more or less of the solution. Choose one of the notebooks and begin the tutorial!


