# Replicator-GUI
In my time at infinite games I built an application in C# to make writing code more efficient.  This application saves hours of 
work by writing template code through server pipelines allowing for only minor changes to be made in special locations to get a 
new working endpoint from the end user to the server and back.  We called it a Replicator.

The template is a special file type made with template code and key words for the replicator to replace with.
A preview of changed files are displayed on the right when selected from the changed file list on the left.
The base name is the name for the new API function that you want to plumb through your system.
There is also a staging area that can also be previewed before writing out the code.
