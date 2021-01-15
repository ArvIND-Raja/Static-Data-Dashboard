# Static-Data-Dashboard
A data visualisation dashboard that helps analyse the behavior of avocado prices and the number of avocados sold in the US between 2015 and 2018.

1. Install a stable version of python along with pip and include it in your PATH before installing this application. 
   I have used python version 3.8.6 to build this application.

2. Open a command prompt in the root directory.

3. Setup a virtual environment in the root directory.

   a) If you have already installed the virtualenv library using pip proceed to create a new virtual environment with the following command:

$python -m venv venv

   b) If you have not installed the library install the library using the following command and then carry out the previous instruction.

$pip install virtualenv

4. Initialise the virtual environment by entering the following command.

$venv\Scripts\activate.bat

5. Install all the libraries present in the requirements.txt file by entering the following command in the command prompt.
    
$pip install -r requirements.txt

6. Now that we have installed all the requisite libraries, let us run our application. Enter the following command in the prompt to start our server.

$python avocadoAnalytics.py

7. You can open the application on your web browser in this address : http://localhost:8050.
