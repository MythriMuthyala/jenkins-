# jenkins-
Description

Installing Jenkins and creating a basic pipeline project for hello world project.
Git commands used:

    mkdir <file_name> to create the folder
    cd <file name> to go inside the folder
    git init, initializing folder as git repository
    git add . to add all the files into git track
    git commit -m "<message>", it commits whatever is there in the track
    git remote add origin <GitHub repository link>, builds connection between git and github
    git push --set-upstream origin master, sends all the files from git to github.

Steps:

    Before installing Jenkins, install the supported JDK package(JDK-17,21)
    Install Jenkins Installer from the web
    Install Jenkins
    Configure the jenkins and install the required plug-ins in the 'http://localhost:8080/' site and log in to your Jenkins
    Create a new item in Jenkins with the desired name in Pipeline item type
    Select pipeline script and create the item
    Now Build the item and visualize the console output

Jenkins Installation:
![my3 jenkins installation](https://github.com/user-attachments/assets/89c56c1c-bf99-459e-b9ca-2f6ac4c67f27)


Output:
![my3 jenkins proof of executing hello world](https://github.com/user-attachments/assets/c41420b0-e1ed-47b6-bc03-9a936e7c321d)

