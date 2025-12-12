# Python Environment Setup

This README provides a step-by-step guide to setting up a Python virtual environment for your project.

## Table of Contents

1. [Creating a Virtual Environment](#creating-a-virtual-environment)
2. [Activating the Virtual Environment](#activating-the-virtual-environment)
3. [Upgrading pip](#upgrading-pip)
4. [Installing Packages](#installing-packages)
5. [Deactivating the Virtual Environment](#deactivating-the-virtual-environment)
6. [Managing Dependencies with Requirements Files](#managing-dependencies-with-requirements-files)

## Creating a Virtual Environment

To create a virtual environment, navigate to your project directory and run the following command:

```bash
python -m venv .venv
```

##Activating the Virtual Environment
Before you can use the packages installed in your virtual environment, you need to activate it. The activation command varies depending on your operating system:

```bash
.venv\Scripts\activate
```

##Upgrading pip
After activating your virtual environment, it's a good practice to upgrade

```bash
pip install --upgrade pip
```

##Installing Packages
To install packages within your virtual environment, use the following command:

```bash
pip install package_name
```

To instal package from a requirements file use the below command:

```bash
pip install -r requirements.txt
```

##Deactivating the Virtual Environment
When you are done working in your virtual environment, you can deactivate it by running:

```bash
deactivate
```

##Managing Dependencies with Requirements Files

To keep track of the packages you have installed in your virtual environment, you can create a
```bash
pip freeze > requirements.txt
```
