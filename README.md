# ChatGPT Clone
feel free to improve the code / suggest improvements

<img width="1470" alt="image" src="https://user-images.githubusercontent.com/98614666/232768610-fdeada85-3d21-4cf9-915e-a0ec9f3b7a9f.png">


## Getting Started
To get started with this project, you'll need to clone the repository and set up a virtual environment. This will allow you to install the required dependencies without affecting your system-wide Python installation.

### Prequisites
Before you can set up a virtual environment, you'll need to have Python installed on your system. You can download Python from the official website: https://www.python.org/downloads/

### Cloning the Repository
Run the following command to clone the repository:
```
git clone https://github.com/rahul-scad/py_chat.git
```

### Setting up a Virtual Environment
To set up a virtual environment, follow these steps:

1. Navigate to the root directory of your project.
```
cd py_chat
```
2. Run the following command to create a new virtual environment:
```
python -m venv venv
```
3.  Activate the virtual environment by running the following command:
```
 on Windows, the command will be :
```
venv\Scripts\activate
```
4. Install the required dependencies by running the following command:
```
pip install -r requirements.txt
```

### Configure the Application
Go this path and updated your own API_KEY   "app\static\js\config.js"


### Running the Application
To run the application, make sure the virtual environment is active and run the following command:
```
python manage.py runserver
```



