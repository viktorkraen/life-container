# Never change directory names in the container and don't move them 📁

# Why? 💭
This can lead to numerous bugs and misunderstandings in the program. Currently 
everything is already configured and working, so there is no need to change 
anything. Directories in the container may be **hard-coded**. If you want to use 
backups, you should pay attention to [Git](https://git-scm.com/) to avoid losing the correct container 
in case of errors.

# How to update the container then? 🔄
Answer: through `LC Helper`. It will take care of all the work, so there is no 
need to do anything manually