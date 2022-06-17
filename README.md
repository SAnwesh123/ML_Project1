Machine Learning project





Creating conda environment
...

conda create -p venv python==3.7 -y
...

conda activate venv
....

OR
...
conda activate venv
....
pip install -r requirements.txt

...

To add file to git
.....

git add.

...
OR
...

git add <file_name>
....

To ignore file or folder from git we can write name of file/folder in .gitignore file

....
To send version/changes to github
...
git push origin main

...
To check remote URL
..
git remote -v



To check the git status
....
git status
...
To check all version maintained by git
...
git log
...
to create version/commit all changes by git
....
git commit -m "message"
...



To set CI/CD pipeline inHeroku we need 3 information

1. Heroku Email ID: anweshsahoo23@gmail.com
2. Heroku API_Key:6b0e428f-a4e8-4a38-abe0-836a5d48ebc5
3. Heroku_APP_Name:ml_project_apps


Build DOCKER IMAGE
....

docker build -t<image name>:<tagname>


note: Image name for docker must be lowercase


To list docker image
...
docker image
...

docker run -p 5000:5000 -e PORT = 5000