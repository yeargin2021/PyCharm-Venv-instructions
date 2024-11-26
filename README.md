# Setting up a Virtual Environment in PyCharm

To add a virtual environment to your project in PyCharm, you can follow the steps below:

1. Open the `PyCharm Preferences` dialog. You can access this by clicking `PyCharm` in the menubar, then selecting `Preferences...`.
2. In the sidebar, under the `Project` section, select `Python Interpreter`.
3. Click on the `+` symbol located at the top-right of the `Python Interpreter` pane.
4. In the pop-up window, choose `Virtualenv Environment`.
5. Then, specify the location of the new virtual environment in your project. Do not inherit global packages from the system interpreter (unless there's a specific requirement) and use whatever Python interpreter you’d like. Then, click `OK`.

Your virtual environment is now set up. You can select it from the interpreter's list under 'Python Interpreter' to use in your project.

> **Remember:** Always activate the project's virtual interpreter before installing any package to ensure it's not installed on your global Python interpreter. These local packages are isolated from the global Python interpreter making it easier to manage dependencies and avoid conflicts between packages.

> **Note:** These steps apply specifically to PyCharm Professional Edition.