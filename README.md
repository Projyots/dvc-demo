 Create Environement

 '''bash
conda create -n wineq python=3.7 -y
'''

activate env
'''bash
conda activate wineq
'''

create Requirements.txt
'''bash
touch requirements.txt
'''

Installed Requirements.txt

'''bash
pip install requirements.txt
'''

Dowload the data

'''GDrive link'''

git init

dvc init -- It will create certain folders like dvcIgnore and others.

dvc add data_given/winequality.csv

git add . --This will add everything in the folder to GitHub

git commit - m "First Commit" -- this will commit the changes with message in double quotes.




