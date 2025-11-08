# HW3A Solution - Git and Version Control

## Part 1: Repository Cloning

I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to
`~/insy6500/class_repo`.

### Key Commands Used

- `git clone <url>` - Create local copy of remote repository
- `git log` - View commit history
- `git remote -v` - Check remote repository connections

## Part 2: Portfolio Repository Creation

I created my personal course repository with:

- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes

### Understanding Git Workflow

The three-stage workflow:

1. Working Directory: Where I edit files
2. Staging Area: Where I prepare commits with `git add`
3. Repository: Where commits are permanently stored with `git commit`

## Part 3: GitHub Publishing

Successfully published repository to GitHub:

- Used `git remote add origin` to connect local repo to GitHub
- Used `git push -u origin main` to upload commits
- Verified all files and commits are visible on GitHub

### The Remote Connection

My local repository is now connected to GitHub:

- `git remote -v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)

### Details

Complete this section with details from your setup:

- Repository URL: https://github.com/AbbyTucker0114/py4eda-work
- Output of `git remote -v`:
	origin  https://github.com/AbbyTucker0114/py4eda-work.git (fetch)
	origin  https://github.com/AbbyTucker0114/py4eda-work.git (push)

- The output of `git log --oneline`:
	fd95994 (HEAD -> master, origin/master) Add hw3a solution document
	6ddbe64 Intial commit: Add README and .gitignore

### Reflections

1a. I have had very limited experience with needing to keep different vesion of work. It would 
   usually consist of saving files with dates on them. The limited data analysis experience I have is 
   with SAS. With this I would create new data sets when major changes where made to the data. 
   Resulting in a built in version control in the code. Git is better it keeps only one local 
   document/file and keeps versions in the repositiory. It is less confusing what document is the 
   correct one. The version history is a better as well. It allows for more accurate control of 
   different versions of work. I believe that as a get further into the data analysis git will 
   provide a better way to share code files and retrive past versions if something goes wrong. 

1b. A project where multiple people are coding/analizing a dataset a git commit history would be 
   valuable to help all memebers to be able to see and track the changes made since they last worked
   with the data. Commit history can be helpful when asking professors for help as it will allow them
   to see how a student has progressed with an assignment or project.

2a. In this case if we put everything in one repo all students would be able to push items into 
   the repo causing confusion and just a massive amount of files. Also having everything in one repo 
   is very unorganized. It would mean having to search through all the files in the repo to find the 
   correct one. 

2b. I would make a repo for each type of file (one for the group project, one for individual 
   assignments, and one for references) and the repos would all be housed in one folder for the class. 
   The project repo and the references(if needed) would be public or shared with group memebers. 

3a. The second more detailed commit message is more useful. It gives more details on what changes 
   where made and allows for an easier time when looking for a past commit. If you need to go back 
   to a past version the commit message will be helpful in determining which version you need to go 
   back to. 

3b. I would make a commit after I got different parts of the analysis done. A good unit of work 
   would be for example completing data cleanning. So I would have the orginal data commited to the 
   repo, then the cleaned data, then commit as I completed each stage of the needed analysis (after 
   graphs are made, regressions completed, etc.). 

### Graduate Questions 

1a. 
