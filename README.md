# git-marge
Punish yourself or your users for mistyping `git merge` à la `sl`

Install this script by moving or symlinking it to any directory in your `PATH`, e.g. `/usr/local/bin`<br>
Git will recognize any executable script placed in your `PATH` that starts with `git-` as a Git command.

Original ASCII art by Horroroso<br>
https://www.asciiart.eu/cartoons/simpsons

Example output:
```
user@hostname:~$ git marge
        ,
        (                          )
         \                        /
        ,' ,__,___,__,-._         )
        )-' ,    ,  , , (        /
       ;'"-^-.,-''"""\' \       )
       (      (        ) /  __  /
        \o,----.  o  _,'( ,.^. \
        ,'`.__  `---'    `\ \ \ \_
 ,.,. ,'                   \    ' )
 \ \ \\__  ,------------.  /     /
( \ \ \( `---.-`-^--,-,--\:     :
 \       (   (""""""`----'|     :
  \   `.  \   `.          |      \
   \   ;  ;     )      __ _\      \
   /     /    ,-.,-.'"Y  Y  \      `.
  /     :    ,`-'`-'`-'`-'`-'\       `.
 /      ;  ,'  /              \        `
/      / ,'   /                \  -hrr-

git: 'marge' is not a git command. See 'git --help'.

The most similar command is
        merge
```
