# apt

curl -s --compressed "https://projects.asylum-os.com/apt/KEY.gpg" | sudo apt-key add -

sudo curl -s --compressed -o /etc/apt/sources.list.d/asylum.list "https://projects.asylum-os.com/apt/apt.list"

