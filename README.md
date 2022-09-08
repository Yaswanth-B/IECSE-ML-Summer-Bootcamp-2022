# IECSE-ML-Summer-2022

## The Summer Domain Bootcamp for Machine Learning project of IECSE 2022

**Instructions:**
## Format and Tracks of Summer Bootcamp

<br>
The project is divided into 3 parts as 4 weeks of content. We have 2 tracks one for those who have done Winter bootcamp (Track 1) and one for those who are starting off with ML (Track 2). <br>
For <b>Track 1 : </b>first 3 weeks contains 2 courses that you need to complete on Coursera and submit its Programming Assignment in your branch. <br>
<br>https://www.coursera.org/learn/neural-networks-deep-learning/home/welcome
<br>https://www.coursera.org/learn/deep-neural-network/home/welcome
<br><b>These 2 courses are from deeplearning.ai for Track 1</b>.
<br><br><br>For <b>Track 2 : </b>first 3 weeks will be 3 courses that they need to complete.<br>
<br>https://www.coursera.org/learn/python-for-applied-data-science-ai?specialization=ibm-data-science
<br> https://www.coursera.org/learn/data-analysis-with-python?specialization=ibm-data-science
<br>https://www.coursera.org/learn/machine-learning-with-python?specialization=ibm-data-science
<br><b>These are course 4, 7, and 9 of IBM data science course for Track 2.</b>
<br><br><b>For both the tracks the last week will have two projects that you need to submit.</b> 
Feel free to ask doubts, if any. 
<br>
Also make your submissions in your branch and not in main.<br> 

## Configure Tooling
#### Configure user information for all local repositories

Sets the name you want attached to your commit transactions:

 ```$ git config --global user.name "[name]"``` 

Sets the email you want attached to your commit transactions:

  ```$ git config --global user.email "[email address]"``` 

This will be required to be done for any github processes over the net. You have to do it only once.

- Clone the IECSE ML Winter Project repository
```git clone https://github.com/Yaswanth-B/IECSE-ML-Summer-Bootcamp-2022.git```

- Initialize a repository in the directory(this is just for information, you won't need this for any task) ```git init <Project Name>```

- Type ```cd IECSE-ML-Summer-Bootcamp-2022```

- Create a new branch with your name using the command ```git checkout -b <branch-name>```, with branch name in format ```<full name and track number 
with '-' for space>. eg.- git checkout -b John-Doe-1 ;;;  if John Doe is from Track 1```

- All commits should be made to your own branch, **Never commit to main.** To prevent this always check what branch you're on before committing any changes, command to check current branch ```git branch```, command to checkout(change to) a branch, ```git checkout <branch-name>```.

- To pull solutions after they are uploaded to main, change branch to main and do a git pull.
```git checkout main```
```git pull origin main```

- Steps to submit your code. (Only for WC)
* Add files to be committed using the command ```git add .``` (the "." after add means all files in the current directory will be added)
* Add a descriptive commit message for the same. Command- ```git commit -m "<msg>"```.
Format - ```Task #<task-no.> : description```. Mention any errors or issues in the code in the commit message, if any.

- Finally, push your code. command - ```git push origin <branch-name>``` <br>
**Note:** While pushing your code, the above git command might ask your GitHub Id and password, enter the same, and then after successful verification only will git push your branch onto GitHub

## Summary 
### Initial Setup
 ```
 git config --global user.name "[name]"
 git config --global user.email "[email address]"
 git clone https://github.com/Yaswanth-B/IECSE-ML-Summer-Bootcamp-2022.git
 cd IECSE-ML-Winter-2020
 ```

### Creating your own branch
```
git checkout -b [your-full-name-with-track-number] // no square brackets in actual command, use - for spaces
eg: git checkout -b John-Doe-1
```
### Submitting your work
``` 
git checkout [your-full-name-with-track-number]	// to make sure you are in your own branch
git add .	// adds all files and subfolders to be committed in the current directory
git commit -m "Task #0: description"
git push origin John-Doe-1 
```

### Downloading the solutions once they are uploaded
```
git checkout main
git pull origin main
```

- All solutions will be uploaded to main.

- All tasks will be posted on the [wiki](https://github.com/Yaswanth-B/IECSE-ML-Summer-Bootcamp-2022.git).
