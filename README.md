# MY-FIRST-PBL-PROJECT
FILE HANDELING PYTHON PG

MOVE DIFFRENT FILE USING OS MOULES IN EXTENSION WISE

First import os and shutil modules  these are inbuilt modules
then create a path variable which takes the input of the base path of the directories that you want to organize 
then create variable name file which consist the files name  uisng (os.listdirs(path))

now create loop in file to tracerse through all the files, then split the file in file name and in extension wise using (os.splitext(file))
now to get the files we need only extension so we remove (.) from extension.

then check the condition that id the  exrension file already exists then move it to that directory .... else  create that extension file folder using osmethod and move the file to perticular directory.
