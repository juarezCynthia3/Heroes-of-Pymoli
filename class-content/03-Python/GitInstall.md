* Creating and adding files to a github repository

No existing code
1. Go to github.com and create a new public repo
2. In git bash or terminal navigate to a desired path
e.g `cd ~/Desktop` in mac
3. git clone <github_url>
4. start creating files and adding to repo
`cat "Hello World!" >> README.txt`
`git add .`
`git commit -m "my first commit"`
`git push origin master`

Existing code
1. Navigate to your project
e.g `cd ~/Desktop/MyProject`
2. Initialize git repository
`git init`
3. Add files to git
`git add .`
4. Commit
`git commit -m "my first commit"`
5. Go to github.com and create a new repo there (name it whatever but best practice to keep it equal to the folder name, e.g MyProject)
6. After the github repo is created WITHOUT an initial README copy the second to last line
The below will alias the github url to origin
`git remote add origin https://github.com/manlara/MyProject.git`
7. Push to github from local git project
`git push -u origin master`