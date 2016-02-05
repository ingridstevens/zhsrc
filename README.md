# zhsrc
ZSH dotfile

This README will be helpful if you're trying to customize your ZSH dotfile.

1. Locate your dotfile
`cd ~`
`nano .zshrc`
2. Edit your dotfile
At the bottom of your dotfile there might be a section called `Example Aliases`. Below this I've added my custom aliases.
*Spaces matter!* `alias gs = "git status"` might not work but `alias gs="git status"` does.
3. Save your file
If you're using nano as your text editor, `CTRL-O` writes your changes and `CTRL-X` exits the file.
4. Test your file
Test your file by trying one of your shortcuts.
For example, I'd navigate to a repo and try `$ gs` to see if I get the same result as `git status`
