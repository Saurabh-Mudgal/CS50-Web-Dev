# CS50-Web-Dev
Here are the things I have learnt:
## Git
I reccommend using Git Bash. Git is a version control language, just like Python, C++, Java are programming languages. It helps control and collaborate projects. Git Bash is like the IDE for running it. You can use the Windows CMD (Command Line) or Mac equivalent but the difference is that Git Bash provides convenience and effeciency (Think IDLE vs PyCharm).
Here are some common and most widely used commands that you can benefit learning, since you'll using them often if you collaborate over projects:

**mkdr -** Creates a directory or a "folder" on your device for all your project files

**cd .. -** Moves back one step in the folder address

**cd _<folder_name>_ -** Moves forward one step in the folder address (into the specified folder name)

**git init -** Initialises a local repositary on your device.

**touch _<filename>_ -** Creates a file in the present folder address

**git add _<filename>_ -** Adds the file in the directory/ folder to the "changes tray". Changes tray is like a temporary holding area where git tracks the snapshot of the changes until you finally commit them. So that you don't have to commit each file/ change one by one.

**git add . -** Adds all file changes at once to the "change tray".

**git commit -m _'<Your Message>'_ -** Commits all the changes in the "change tray" to the local repositary and logs the commit with a unique hash, the time, the committer's name, and the message.

**git remote -** Allows you to view any remote link's name to the local repositary. Eg. a Github repositary.

**git remote -v -** Allows you to view any remote link's name to local repositary along with http link to the repositary. Eg. a Github repositary.

**git remote add origin _<Repo Link>_ -** Use to add a remote to the local repositary, and assign the default name "origin" to this remote. You can assign other name, but you must be careful to modify accordingly in commands.  Eg. Connecting to a Github repositary.

**git pull origin -** Pull's the present repositary to the local repositary from the remote such as the Github Repo.

**git push -u origin main -** Pushes the changes ie the present local repositary to the remote such as Github Repo.

**git branch -** Displays all current branches in the repositary

**git branch _<branch name>_ -** Creates a branch with the branch name

**git checkout _<branch name>_ -** Changes the working branch to the branch name

**git reset --hard origin/master -** Reverts the version back to the master version

**git reset -- hard <commit> -** Reverts the version back to the commit hash provided

Note, by default you are working in the main branch. When pushing/ pulling commits, be mindful of which branch you are in. That branch will be the pushed/ pulled.
