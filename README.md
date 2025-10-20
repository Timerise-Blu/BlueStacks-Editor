BlueStacks-Editor v1.2:
I used Python 3.10.5 and Customtkinter 5.2.2 in development of BlueStacks-Editor v1.2
Main Script: BlueStacks-Editor.py
Additional Assets:
-menu.json -> Used by BlueStacks-Editor.py to build the menu and map it to patches
-patches.json -> The Patches available
-config.json -> General Config, mostly holds path metadata
-exe.json -> Self manifest for assets
-project.conf -> Small Configuration file, unimportant for usage
-project.manifest -> Manifest file of the project
-additional-properties.json -> Contains additional build properties, currently empty

Known Issues:
Patch ADs tries to get input from the user due to a dumb implementation (it treats empty input as empty output for some reason which shouldn't be handled the same)
Spoof Device Info fails due to a issue with the "ids" instead of "id" field, from what i have seen it's related to a customtkinter callback issue

Requirements:
Needs same (or better) requirements as used by me in the build process

How to Use:
Simply execute the script via a python interpreter (if you meet the requirements)

How to Install:
1. Install Python 3.10.5+
2. Install customkinter: 'pip install customkinter==5.2.2' or if it doesn't work: 'py -m pip install customtkinter==5.2.2' or 'python -m pip install customkinter==5.2.2'
3. Donwload and extract the zip
4. Run: 'python BlueStacks-Editor.py'
