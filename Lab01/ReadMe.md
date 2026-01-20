## Lab 01

- Name:Julie Peterson-Ramos
- Email:peterson-ramos.2@wright.edu

Instructions for this lab: https://pattonsgirl.github.io/CEG2350/Labs/Lab01/Instructions.html

## Part 1 - GitHub Profile

1. [julipeter12's GitHub Profile](https://github.com/julipeter12)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         | Displays help about Powershell commmand and concepts |
| Get-Location | pwd    | Shows a path of where you are in your files |
| Get-ChildItem | ls    | Shows a list of what is in the file you are looking at |
| mkdir   | mkdir       | Used to create a new directory |
| Set-Location | cd     | Changes the current working directory |
| New-Item | touch      | Creates a new item in a location |
| Move-Item | mv        | Moves a item from one location to another but also removes it from the original location |
| Copy-Item | cp        | Copies one item to another location but leaves it in the original location |
| Remove-Item | rm      | Removes/Deletes a file from a location |
| notepad.exe | vim     | Launches Notepad |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Powershell

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: cd $HOME   C:\Users\julia
2. Create a directory named `DirA`: mkdir DirA 
3. Create a directory named `Dir B`: mkdir 'Dir B'
4. Go into `DirA`: cd .\DirA\
5. Go into `Dir B` from `DirA`: cd '..\Dir B\'
6. Return to your user's home directory: cd ~
7. Create a file named `test.txt`: New-Item text.txt
8. Move the file named `test.txt` into `DirA`: mv C:\Users\jcpculia\test.txt C:\Users\julia\DirA\test.txt
9. Contents of `test.txt`: notepad.exe test.txt
```
You got this!
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: cp test.txt copy.txt
11. View the contents of `DirA`: ls 
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: First made a copy of test.txt to fodder.txt using cp test.txt fodder.txt then I moved the file to Dir B using mv fodder.txt 'C:\Users\julia\Dir B\'
13. Delete / remove both `fodder.txt` AND `Dir B`: Went back one directory (C:\Users\julia) and used rm 'Dir B' to remove the directory and everyting inside the directory including fofder.txt. It did ask me before deleting if I was sure I wanted to delete Dir B. 


## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.



