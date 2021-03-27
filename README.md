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

'''bash
GDrive link
https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing
'''

'''bash
git init
'''

'''bash
dvc init -- It will create certain folders like dvcIgnore and others.
'''

'''bash
dvc add data_given/winequality.csv
'''

'''bash
git add . --This will add everything in the folder to GitHub
'''

'''bash
git commit - m "First Commit" -- this will commit the changes with message in double quotes.
'''

'''bash
git remote add origin https://github.com/Projyots/dvc-demo
'''

'''bash
git branch -M main -- Changes the brach name from "Master" to "Main"
'''

'''bash
git pull origin main --allow-unrelated-histories
'''

'''bash
git push origin main  -- This will push all the files/folders to GitHub 
'''





