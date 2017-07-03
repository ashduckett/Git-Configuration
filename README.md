# How to use

Get hold of the udacity-terminal-config directory from the repository. Next put the file named bash_profile into your home directory.

You can access your home directory by typing cd.
You can then open it using start .
Once the bash_profile is in there, rename it using

mv bash_profile .bash_profile

Next put a copy of this directory into your home directory.

Rename the directory so it has a dot at the start of its name using the same command as above.

Everything should be cushty.

# Configuration

# sets up Git with your name
git config --global user.name "<Your-Full-Name>"

# sets up Git with your email
git config --global user.email "<your-email-address>"

# makes sure that Git output is colored
git config --global color.ui auto

# displays the original state in a conflict
git config --global merge.conflictstyle diff3

git config --list


To set up your code editor with Visual Code 

git config --global core.editor "code --wait"