# docker

This is the repo with the docker basic installation steps and sample projects.

1 Sample node application docker build and run
    Pre-requsit docker should be installed.
    Clone this repo and go to the node-sample folder.
    Open Command prompt(for Windows)/teminal(for linux and mac)
    Run "docker --version" command to check the whether docker is installed or not.
    Run "docker build ." to create docker image
    Note the image id from the last command output
    Run "docker run -p 3000:3000 <image id>"
    In the console it should show "Server running at http://localhost:3000/"
    Check the browser application should be running 

