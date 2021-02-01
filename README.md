# practicedjango

Practicing django with docker on my virtual machine.

Steps Required to create a Django App On Visual Studio Code.


-- Downloaded Python by specifying the pathto be in my \C drive when installing.

( On Windows, make sure the location of your Python interpreter is included in your PATH environment variable. You can check the location by running path at the command prompt. If the Python interpreter's folder isn't included, open Windows Settings, search for "environment", select Edit environment variables for your account, then edit the Path variable to include that folder).

-- Downloaded and install Git, check git is enabled from settings.

-- Created a directory (A folder on Desktop called practiceddjango)

-- In the folder created, i activated the environment using gitbash with this command(python -m venv env) by right clicking and  using the the GitBash GUI.

-- Also added the path on VS code by selecting Python interpreter using (ctrl+shift+p) 

-- Then selected the activated environment into Vscode

End goal -- The python path has been mapped to my VScode and also the virtual environment has been activated:

Creating the Django App

-- I launched the terminal on VS code and ran:
 -- python -m pip install Django

-- In the activated virtual environment, I  ran the below cmd: 
-- django-admin startproject web_project 

-- The new web-project was in the same directory with manage.py file. To verify the new created django project, i cd into web_project then run
-- python manage.py runserver


-- This command below stops whatever site your local host is running

-- netstat -ano| finstr :8000
-- taskkill /PID 3244 /F

