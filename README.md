# Git Cool Aliases

Here is a little repo with all the cool git aliases you can't code without. Everybody is welcome to add their own!

###Git aliases for log viewing


Here are all the Git cool aliases for better log representation.


####Branch View Log

This branch view log shows the git commits on a oneline way with branch decorations, relative datetime, and the name. Great for a quick glimpse of the log 

	git config --global alias.superlog "log --graph --abbrev-commit --decorate --date=relative --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"
	
![BranchView](/home/juan/workspace/gitCoolAliases/images/BranchView.png  "BranchView")



***


