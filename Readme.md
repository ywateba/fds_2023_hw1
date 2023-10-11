# FDS Hw1

## How to get the project 

To clone thr Git repository from a URL, such as the one you provided (https://github.com/ywateba/fds_2023_hw1.git), and work on the project, you can follow these steps:

**Prerequisites:**

1. Make sure you have Git installed on your computer. 

2. Nice to have an IDE  such as [VsCode](https://code.visualstudio.com/) installed on your computer or  use Jupyter Lab and in that case you will use git from your command line.

**Cloning the Repository:**

1. Open your terminal or command prompt on VScode.

2. Choose a directory on your computer where you want to store the repository. Navigate to that directory using the `cd` command. For example:

   ```bash
   cd /path/to/your/desired/directory
   ```

3. Clone the repository using the `git clone` command. Replace the repository URL with the one you provided:

   ```bash
   git clone https://github.com/ywateba/fds_2023_hw1.git
   ```

   This command will download the project files and create a local copy of the repository on your computer.

4. You may be prompted to enter your GitHub username and password or use a personal access token if the repository is private. If it's a public repository, you can clone it without authentication.

**Working on the Repository:**

Now that you have the repository cloned to your local machine, you can work on it:

1. Navigate into the project directory:

   ```bash
   cd fds_2023_hw1
   ```

2. Make your changes, edits, or additions to the project files.

3. After making changes, you can stage the modified files and commit them:

   ```bash
   git add .  # This stages all changes
   git commit -m "Your commit message here"
   ```

4. Push the changes back to the GitHub repository:

   ```bash
   git push
   ```

**Pulling Updates from the Remote Repository:**

If others are also working on the same project and have made changes to the remote repository, you can pull those changes to your local copy:

1. Navigate to your project directory (if you're not already there):

   ```bash
   cd /path/to/fds_2023_hw1
   ```

2. Pull the latest changes:

   ```bash
   git pull
   ```

This will synchronize your local copy with the latest changes from the remote repository.

Now, you can continue making changes, committing, and pushing to collaborate with others on the project.

## How to run the project 




### Setting up a Python 3.9 Environment with Conda or Miniconda

This README provides step-by-step instructions on how to set up a Python 3.9 environment using either Conda or Miniconda, depending on your preference.

#### Table of Contents

1. [Installing Conda or Miniconda](#installing-conda-or-miniconda)
2. [Creating a Python 3.9 Environment](#creating-a-python-39-environment)

---

## Installing Conda or Miniconda

Conda is a powerful package and environment manager for data science and scientific computing. Miniconda is a minimal installer for Conda that allows you to install only what you need. You can choose either Conda or Miniconda based on your requirements.

#### Installing Conda

 Visit the [Anaconda download page](https://www.anaconda.com/products/distribution) or [Miniconda download page](https://docs.conda.io/en/latest/miniconda.html).



#### Installing Miniconda

 Visit the [Miniconda download page](https://docs.conda.io/en/latest/miniconda.html).


---


### Creating a Python 3.9 Environment

After installing Conda or Miniconda, you can create a Python 3.9 environment by following these steps:

1. Open your terminal or command prompt.

2. To create a new Conda environment with Python 3.9, use the following command:

   ```bash
   conda create --name myenv python=3.9
   ```

   Replace `myenv` with your preferred environment name.

3. To activate your new environment, run the following command:

   ```bash
   conda activate myenv
   ```

   Replace `myenv` with the name you chose in step 2.

4. Your Python 3.9 environment is now active, and you can install packages and run Python scripts within it.

5. To deactivate the environment and return to your base Conda environment, use the following command:

   ```bash
   conda deactivate
   ```

---

That's it! You've successfully set up a Python 3.9 environment using Conda or Miniconda. You can now start working on your Python projects within this isolated environment.




## GIT Helper


After cloning your the project , you can create a branch which is a clean copy of the main branch.


      git branch branch_name main

Then to switch to your branch :

      git switch branch_name

Then after adding your modifications:

      git add .
      git commit -m "some_message"

To send everything on github:

      git push 



### PS
The folder resources contains code that can help 

