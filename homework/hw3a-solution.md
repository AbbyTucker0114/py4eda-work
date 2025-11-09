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

1a. README and .gitignore where both files necessary to set up an effective git repository, so 
   commmitng them together with a clear commit message makes sense. The homework solution file is 
   different and was placed into a folder within the repo. Commiting everthing at once would have 
   lost the ability save the files in different folders as well as the ability to have specific 
   detailed commit messages.

1b. I would commit after I wrote the code to load the data, get halfway through the analysis, and 
   updatae the README file. I would commit after the code to load the data to have back up loaded 
   version of the data. I would commit after I updated the README file to ensure the update is saved. 
   I would commit after half the analysis is done to save progress assuming the code is working; this
   would give a point to return to should the code break in the future. Staging helps with these 
   decieions by allowing for only select files to be commited, allowing for more clear commit history
   and commit messages. 

1c. `git status` show the status of your files. It shows what files are staged to commitand what files 
   have untracked changes. This when used before a commit, can help guide decisions about what is 
   staged and what needs to be staged, as well as what is included in the next commit. This will help 
   guide commit messages and commit history. This code should be used before a commit to ensure the 
   files being commited to ensure the correct files are being commited and that the files that are 
   grouped in one commit make sense for fututre use. 

2a. What is meant by "distributed" version control system is that git stores all commit versions and 
   show the changes between commits. Git also allows for other to get the complete repo history when 
   pulled not just a copy of the files but independent version of the files. With the class_repo this 
   allowed me to pull independent files from the class git hub repo into a local repo on my computer. 
   These files are now independent of the files in the orginal repo. I can make local changes to the 
   files and save them in my local repo without changing the files in the class repo. I can also pull 
   new files from the original class repo. This is differnt from a Google drive type document becasue 
   those types of files are one shared file that updates for everyone not individual files each person 
   is working on. 

2b. By allowing for saving changes to the local repo without internet allows for version control even 
   without internet connection. This enables us to work offline and then push those changes into the 
   GitHub repo for those to see and use when internet connection is available. 

2c. `git clone` allows us to clone a remote GitHub repo into a local repo. `git pull` allows us to 
   pull changes made in a GitHub repo from a GitHub repo into the local repo. `git push` allows us to 
   push files/commits from the local repo into the GitHub repo. I can pull from the class repo becasue
   it pulls any changes or new files into my local repo but I cannot push my files/commits into it 
   becasue I do not have permission becasue it is not my repo and I have not been given permission. 
   I can push and pull from my repo becasue it is my repo and I have premission to push files into it,
   and I can share permission with others. 

3a. When deciing what to commit I would logic as a guide, and commit when it make sense in a project. 
   Using clear commit messages will help others to understand the thought process behind the commit 
   thought process. Balancing process vs polished is hard but having seperate branches in the same repo
   allows for one branch to track progess through a course and one branch to have the final ploished 
   work to act as a portfolio. 

3b. The README files should be tailored toward the audience it is intended for. A portfolio README is 
   tailored toward showcasing your work. So the README would need to describe you and you skills, what
   you have learned and tools used, and the decisions made and be relfective of your journey. An open 
   source project README is tailored towards those who want use the code or work on the project. So 
   the README would need to describe the poject and how it works, guidelines for contributions and is 
   more instructional.

3c. The value of building a public portfolio during coursework rather than waiting until later is you 
  gain skills on how to build maintain the portfolio before one is needed. Another benifit is that 
  there are professors and other students to turn to for guidance on how to accomplish goals and workout
  errors and bugs. Habits of how to effectively use these tools (push, pull, clone, and commit) will 
  add skills other might not have to our reseme and skillset that might set us apart. 
