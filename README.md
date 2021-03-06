# Essential Programming
> programación esencial

## Getting Started

This instruction will help you make a code precisely.

## UNIX

* tar.gz file

In short, a TAR file creates one archive file out of multiple files without compressing them, while the GZ file format compresses a file without creating an archive. Combined into the tar GZ file extension, you can archive and compress multiple files into one.

## C++
[basic](https://www.cprogramming.com/tutorial/c++-tutorial.html)



## Ecole 42

Open VScode from Terminal

Add,
```
code () { VSCODE_CWD="$PWD" open -n -b "com.microsoft.VSCode" --args $* ;}
```
Making a Norminette shortcut

Add, "alias ..." line in /.zshrc file
```
echo 'alias norm=“python3 -m norminette“' >> ~/.zshrc
```
If you don't make an alias,
```
~/.norminette/norminette.rb <filename.c>
```






## Git

* Generating SSH key on Mac - ssh-keygen
-- [SSH](https://man7.org/linux/man-pages/man1/ssh-keygen.1.html)

* git options
If i don't want to commit this file but I already pushed
```
git rm --cached <filename>
```
--cached means deleting files in staging-area, without touching the working tree (storage).
Without --cached, delete everything, including working tree.

* Git Sheet -- [GIT](https://www.javatpoint.com/git-cheat-sheet)


## iTerm2

To set Powerlevel10k on iTerm2,

Add this sentence in /.zshrc file
```
ZSH_THEME=“powerlevel10k/powerlevel10k
```

Useful options
```
source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh
source ~/.zsh/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
source ~/.zsh/zsh-completions/zsh-completions.plugin.zsh
```

!! If you get an error while editing a zshrc file and computer immediately show
```
a session ended very soon after starting
```
It means you get some typo in zshrc file, check it precisely.

## LaTex



