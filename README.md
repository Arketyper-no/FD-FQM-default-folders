## How to use this folder set
1. Download the zip file and extract to the local folder containing form building projects. OneDrive can be used for this.
2. Rename the folder "FD-FQM-default-folders-main" to your project name
3. Edit `fileserver.config`, replacing the default value of the "name" element with your project name
4. Add the path to the folder where you extracted the zip file, to the "Home folder" setting of Form Designer, and to the "Working directory" setting of Form Quality Manager
5. If using a git repository for the project, open a terminal and run
```
git init --initial-branch=main
git add .
git commit -m "my commit"
git remote add origin [url to git repository]
git push origin main
```

# !Project name!

## About

!Short description of the project!

## Version log

### 0.1 !description of the version!
