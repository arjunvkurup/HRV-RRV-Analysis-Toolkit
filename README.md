# HRV-RRV-Toolkit
HRV-RRV-Toolkit is a Tkinter based application capable of processing and estimating Hear rate variability and respiratory rate variability parameters. The tools is entirely developed in python programming language. The tool was developed as part of an initial stage of research based on Autonomic dysfunction prediction based on HRV and RRV estimated features . A research journal article has been published as part of the research done at [Amrita Instutite of Medical Sciences and Research](https://amritahospitals.org).

__The article can be obtained from [International Journal of Online and Biomedical Engineering]__(https://online-journals.org/index.php/i-joe/article/view/22581).

## Features
* Capable of processing ECG data
* Capable of processing RRV data
* Currently supports .edf(European data format) format
* Visualization and analysis capability
* Removes noises
* Filter data
* Preview the signal data
* Estimate parameters such as RMSD, SDMM, Peak interval rate etc.

---
## Setting up

### __Linux / mac os__
1. A Python 3.6 and above version is required. You can install it from [Python's official website](https://www.python.org/downloads/) or can use the command provided below
    ```bash
    $ sudo apt install python3
    ```
2.  Setting up Virtual Environment
    ```bash
    # For Ubuntu
    $ sudo apt install python3-venv # Install virtual environment package
    ```
    ```bash
    $ python3 -m venv <virtual_env_name>  # Add virtual environment name
    ```
    Activating virtual environment
    ```bash
    $ source <virtual_env_name/bin/acivate>  # This will activate your virtual environment
    ```
    For deactivating virtual environment
    ```bash
    $ deactivate <virtual_env_name> # This will deactivate your virtual environment
    ```
3. Installing necessary packages
   
    Once the virtual environment is active, you can install the necessary packages required for the development and testing of the tool. For that you can use the requirement.txt which contains the package name and versions. To istall, type the pip command provided below:
    ```bash
    pip install -r requirement.txt # You will be able to see the installation
    ```
4. Running the tool

    The main file of the tool is hrvrrv.py, hence a command,
    ```bash
    python hrvrrv.py
    ```
    will start the tool and you will be able to see the Tkinter UI.
---

### __Windows__
1. A Python 3.6 and above version is required. You can install it from [Python's official website](https://www.python.org/downloads/).

2. Check whether python can be accessed from command prompt by typing "python" in the command prompt. If you get a python interactive shell, then proceed to the next step. Otherwise, you have to install python again and confirm the option for adding python to the "PATH".

3. Installing necessary packages

    Once you have the interactive shell, you can install the necessary packages required for the development and testing of the tool. For that you can use the requirement.txt which contains the package name and versions. To istall, type the pip command provided below:

    ```bash
    > pip install -r requirement.txt # You will be able to see the installation
    ```
4. Running the tool

    The main file of the tool is hrvrrv.py, hence a command,
    ```bash
    python hrvrrv.py
    ```
    will start the tool and you will be able to see the Tkinter UI.

---

## Contribution

The tools is currently in a beta version, hence the possibility of tool to have bugs are high. Also the tools is not quite secure, so feel free to report the bugs as well as pull requests to fix them.
