# Hooks: add the main qml file imported by Qml engine and all its hidden imports

* This Pull Request searches all the python files in the analysis folder (i.e. folder
in which the main py file used by pyinstaller can be found) and extracts any qml file url used in it.

* Then reads each qml file to extract all other imports, including hidden imports,
.js files and folders.

