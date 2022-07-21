# installings-command-git-ftp
the commands for adding git-ftp in your project

# step one open gitBash in adminstrator mode
# then write thise command one by one

git clone https://github.com/git-ftp/git-ftp git-ftp.git

cd git-ftp.git && chmod +x git-ftp

cp ~/git-ftp.git/git-ftp /bin/git-ftp

# go to your project file and run gitBash
# check for install git-ftp by this command

git ftp -v

# Setup
git config git-ftp.url "ftp://ftp.example.net:21/public_html"
git config git-ftp.user "ftp-user"
git config git-ftp.password "secr3t"

# first init command

git ftp init

# Or if the files are already there
git ftp catchup

# enjoy push comand

git ftp push

