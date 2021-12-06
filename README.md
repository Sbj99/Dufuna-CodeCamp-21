
SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop (master)
$ cd Desktop/

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop (master)
$ git clone https://github.com/Dufuna-CodeCamp/Dufuna-CodeCamp-21.git
fatal: destination path 'Dufuna-CodeCamp-21' already exists and is not an empty directory.

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop (master)
$ cd Dufuna-CodeCamp-21/

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21 (about-samuel)
$ cd submissions/

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21/submissions (about-samuel)
$ cd samuelJegede/

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21/submissions/samuelJegede (about-samuel)
$ mkdir aboutMe
mkdir: cannot create directory ‘aboutMe’: File exists

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21/submissions/samuelJegede (about-samuel)
$ cd aboutMe

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21/submissions/samuelJegede/aboutMe (about-samuel)
$ touch .txt

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21/submissions/samuelJegede/aboutMe (about-samuel)
$ cd ../../../

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21 (about-samuel)
$ git status
On branch about-samuel
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        submissions/samuelJegede/aboutMe/.txt

nothing added to commit but untracked files present (use "git add" to track)

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21 (about-samuel)
$ git add .

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21 (about-samuel)
$ git status
On branch about-samuel
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   submissions/samuelJegede/aboutMe/.txt


SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21 (about-samuel)
$ git commit -m "my first task"
[about-samuel 0e32c71] my first task
 1 file changed, 1 insertion(+)
 create mode 100644 submissions/samuelJegede/aboutMe/.txt
[program achievement.txt](https://github.com/Sbj99/Dufuna-CodeCamp-21/files/7662831/program.achievement.txt)
SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21 (about-samuel)
$ cd tests/my_first_pull_request/

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21/tests/my_first_pull_request (about-samuel)
$ ./test.sh
Enter First Name : samuel
Enter Last Name : jegede

Test Results
Total number of tests: 3
Passed tests: 3
Failed tests: 0

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21/tests/my_first_pull_request (about-samuel)
$ cd ../../

SBJ@DESKTOP-AM5MTA1 MINGW64 ~/Desktop/Desktop/Dufuna-CodeCamp-21 (about-samuel)
$ git add .
warning: LF will be replaced by CRLF in tests/logfile.json.
The file will have its original line endings in your working directory
