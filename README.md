# Hitchhiker's Guide to the Quantum Realm ⚛

My field notes on quantum computing with IBM's Qiskit...

<b>This repository is a work in progress.</b>

## Setup

### Prerequisites

You must have the following installed on your system to get started:

1. <a href="https://git-scm.com/">Git</a> version control system
2. <a href="https://www.python.org/">Python</a> (recommended to have a version greater than 3.9.0)

To setup this project locally on your machine, follow these steps:

### 1. Clone Project

Clone this repo to a desired location (folder) on your machine by opening up a terminal from the folder and entering the following command:

```shell
git clone https://github.com/ravi-aratchige/hitchhikers-guide-to-the-quantum-realm.git
```

Next, move into the project directory:

```shell
cd hitchhikers-guide-to-the-quantum-realm
```

### 2. Activate Virtual Environment

A virtual environment will help you keep the project's dependencies isolated from the global system of Python packages. To setup your virtual environment, first ensure that `virtualenv` is installed on your system:

```shell
pip install virtualenv
```

To create and activate a virtual environment, enter the following commands after moving into the `spacefarer` folder as done in the previous step:

```shell
# Create a virtual environment named 'env':
python -m venv env

# Activate the virtual environment (Windows):
env\Scripts\activate.bat

# Activate the virtual environment (MacOS / Linux):
source env/bin/activate
```

Your terminal will now include an `(env)` prefix, indicating a successful activation of the virtual environment:

```shell
# On Windows:
(env) drive:\folder\...spacefarer>

# On MacOS and Linux
(env) user@computer:~/...spacefarer$
```

To deactivate the virtual environment (and remove the `(env)` prefix):

```shell
deactivate
```

### 3. Install Dependencies

After activating the virtual environment, you can install all of the necessary dependencies with a single command:

```shell
pip install -r requirements.txt
```

<a href="https://github.com/ravi-aratchige/hitchhikers-guide-to-the-quantum-realm/blob/main/requirements.txt">`requirements.txt`</a> includes all of the project's dependencies and their respective versions.

### 4. Start Jupyter Server

You can start the Jupyter Server to view and run the notebooks after the dependencies have been successfully installed:

```shell
jupyter notebook
```

Jupyter Server will then start on <a href="http://localhost:8888/tree">http://localhost:8888/tree</a>.
