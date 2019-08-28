#Lazygit function to add, commit, and push a file with one command
#Add lines to /etc/bash.baschrc
#Command: lazygit "My commit message"
#Source: https://stackoverflow.com/a/23328996
function lazygit() {
    git add .
    git commit -a -m "$1"
    git push
}
