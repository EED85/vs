# VS Studio Tips

## cool plugins

- git lens
- Anaconda Extension Pack -> Python debugger included?
- Markdown Preview
- Maekdownlinit
- GIthub Pull requests
- Python
- gitinore
- github notifications?

## using terminals

- use one powershell and one for python
  - with powershell you can use git commands and pip install
  - with python you can print out / manipulate python stuff

## Shortcuts

- [Shortcuts](https://www.microsoft.com/germany/techwiese/know-how/visual-studio-code-keyboard-shortcuts)
- Ctrl + c - quit infinite loop
- Ctrl + # - mulitline Comment
- Ctrl + k  s save all (Press ctrl + k, release and thren press s)
- Ctrl + shift +  P or F1
- Ctrl + p - open a file from your
- Ctrl+K V -> Edit markdown Files side by side
- Ctrl+Shift+M -> view Errors
- shift+alt+f12 -> find all occurences in file
- Rename Variable with f2 instead of replacing

## create custom Code snipets

[Link](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

## Git workflow

### basic workflow - One Person / One PC

1. "" -> git commit
    adds all changes and untracked files and commits them
2. -> git push

#### commiting one specific file

1. git stage changes ("git sc")
2. git commit changes
3. git push

### Using several PCs

run git pull first, before appliying the basic worklfow

### several users

1. git checkout to new branch (name it develop_YourName)
2. apply basic workflow to branch
3. create Pull request on Githib
4. merge it via github pull requests plugin
5. delete develop branch on github
6. checkout master
7. git pull

## using pip command libs

open an Terminal (Python)
PS C:\DEV\git\Python_test> & python -m pip install -U autopep8

## Using debugger

[Debugging](https://code.visualstudio.com/Docs/editor/debugging)
