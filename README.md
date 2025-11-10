### Homework Assignments for ECGR-4105, Intro to Machine Learning
## Joshua Foster

All datasets taken from [Dr. Tabkhi's GitHub repo](https://github.com/HamedTabkhi/Intro-to-ML/tree/main/Dataset)

## Setup Instructions

### 1. Create the Shared Conda Environment

From this main directory, create the shared conda environment that will be used for all homework assignments:

```bash
conda env create -f environment.yml
```

This will create an environment named `ecgr4105` with all the necessary packages for the course.

### 2. Activate the Environment

```bash
conda activate ecgr4105
```

### 3. Working with Jupyter Notebooks

Once the environment is activated, you can start Jupyter from any homework folder:

```bash
cd homework1  # or homework2, etc.
jupyter notebook
```

The notebook will automatically use the `ecgr4105` environment.

### 4. Adding New Packages

If you need additional packages for future assignments, you can either:

- Install directly: `conda install package-name`
- Or update the `environment.yml` file and recreate the environment:
  ```bash
  conda env update -f environment.yml
  ```