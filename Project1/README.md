## Lab 01

- Name: Teresa Mamani Romero
- Email: mamaniromero.2@wright.edu

Instructions for this lab: https://pattonsgirl.github.io/CEG2350/Labs/Lab01/Instructions.html

## Part 1 - GitHub Profile

1. [your_github_username_here's GitHub Profile](FIXTHISURL-https://github.com/your_username)

https://github.com/tcmamani/tcmamani.git

## Part 2 - Research

| Windows | Linux / Mac |          Action                   |
| ---     | ---         |           ---                     |
| help    | man         |   manual information              |
| Get-Location | pwd    |   shows the current directory     |
| Get-ChildItem | ls    |   lists all files and directories |
| mkdir   | mkdir       |   creates a new directory         |
| Set-Location | cd     |   Change the current directory    |
| New-Item | touch      |   create a new file               |
| Move-Item | mv        |   move or rename a file           |
| Copy-Item | cp        |   copies a file                   |
| Remove-Item | rm      |   Removes a file                  |
| notepad.exe | vim     |   Open or edit a text file.txt    |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Powershell

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: pwd <br>
    /home/teresamr
2. Create a directory named `DirA`: mkdir DirA <br>
    ls <br>
        Dir A
3. Create a directory named `Dir B`: mkdir 'Dir B' <br>
    ls <br>
        'Dir B'
4. Go into `DirA`: cd DirA <br>
    pwd <br>
        /home/teresamr/DirA
5. Go into `Dir B` from `DirA`: cd ../DirB <br>
    pwd <br>
        /home/teresamr/Dir B
6. Return to your user's home directory: cd ~ <br>
    pwd <br>
        /home/teresamr
7. Create a file named `test.txt`: touch test.txt <br>
    ls -l test.txt <br>
        -rw-r--r-- 1 teresamr teresamr 0 Sep  5 00:57 test.txt
8. Move the file named `test.txt` into `DirA`: mv test.txt DirA/ <br>
    ls -l DirA <br>
        -rw-r--r-- 1 teresamr teresamr 0 Sep  5 00:57 test.txt
9. Contents of `test.txt`: vim DirA/test.txt <br>
    Press i to insert text <br>
    Text inserted <br>
    Press Esc and type :wq <br>
    cat DirA/test.txt
```
Hello, This is Teresa.
I am from Peru.
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: cp DirA/test.txt DirA/copy.txt <br>
11. View the contents of `DirA`: ls DirA/ <br>
    copy.txt    test.txt <br>
    cat DirA/copy.txt <br>
        Hello, this is Teresa. <br>
        I am from Peru.
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: cp DirA/test.txt 'Dir B'/fodder.txt <br>
    ls 'Dir B'/ <br>
        fodder.txt <br>
    cat 'Dir B'/fodder.txt <br>
        Hello, this is Teresa. <br>
        I am from Peru.
13. Delete / remove both `fodder.txt` AND `Dir B`: rm -r 'Dir B' <br>
    ls <br>
        DirA

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

Note:
I added extra steps to verify each step was correct and that the commands worked as expected. 


