This pypanel will work without the markup, but if you want to see the pretty colours make sure that the pyEditorStylesheet.py is placed in your pythonpath

To install:
Save scripting_editor.pypanel to your houdini directory inside a folder called python_panels

Windows example:
C:\Users\{Username}\Documents\houdini19.0\python_panels

Linux example:
$HOME/houdini19.0/python_panels/scripting_editor.pypanel

Usage:
The script editor will always load the last text that was run in the text editor and will persist across open houdini sessions.
This is easier than working with multilines in the python shell

If you want to save your work, you can choose the save option from the dropdown, name your file and hit the 'Save' button. It will be added 
to your dropdown menu and set as the active script.

To clean up/remove an old script, make sure it's selected in the dropdown and you can run 'Delete'

To clear the text box, set the dropdown to "Load" and you'll be able to run the 'Clear' button

Yes yes, these buttons are a little bit awkward and I will revisit the layout to make it more user friendly