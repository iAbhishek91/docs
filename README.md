# Commands cheatbook

## windows powershell:
> search files and folder:

##### - view all the child files and folder:
command: ls
command: Get-ChildItem

##### - search on the directory path mentioned or in the working directory:
command: ls 'path' 'foldername' -Directory
  
##### - search on all the child path mentiod:
command: ls 'path' 'foldername' -Directory -Recurse

> environment path:

##### - view of all the environement variable:
command: Get-ChildItem Env:

##### - view of only specific environment variable:
command: Get-ChildItem Env:path

##### - delete env variable:
command: Remove-Item Env:path

> file operation:

##### - read file:
command: cat filePath

##### - create a file from a string:
command: 'string' > 'fileName'

##### - delete file:
command: Remove-Item -Path 'path'\'filename' | rm 'path'\'fileame'

##### - create a folder:
command: md 'folderName'

##### - delete a folder:
command: rm 'path'\'folderName'

> ssh configuration:

##### - configure ssh key in powershell:
command:        cd path-to-Git/bin (for me : cd C:\Apps\Git\bin)
                bash
                exec ssh-agent bash
                ssh-add MYKEY (~(user directory) works in bash but not in powershell)
                exit (for exiting from bash)


## Mac terminal:
> File and Directory operation:

##### - edit a file (vi):
command: vi filepath
option: i (insert); 
        a (append from current position
        A append from EOL
        :q quit
        :wq quit and save
        :wq! quit and save

##### - delete a file and folder:
command: rm -rf <folder-name> (for folder)
command: rm <file-name> (for files)


## windows run shortcuts:

##### - open IE properties:
command: inetcpl.cpl

##### - open system properties:
command: sysdm.cpl




## git:

##### - clone:
command: git clone <http>|<ssh>

##### - branch:
command: git branch -a (check all the branchs both remote and local)

##### - checkout:
command: git checkout <branch-name>



## mac terminal:




## node:
> Basics:
##### - version of node and npm:
command: npm -v | node -v

##### - initialize npm:
command: npm init

##### - uninstall everything not listed in package.json:
command: npm prune

##### - adding dependencies:
command: npm install 'package-name' -save

##### - adding dev-dependencies:
command: npm i 'package-name' --save-dev

##### - adding dependencies:
command: npm i -g 'package-name'

##### - npm configuration:
command: npm config set <key><value>
command: npm config get <key>
example: npm config get registry
command: npm config delete <key>
command: npm config list [--json] | npm config ls -l
command: npm config edit
command: npm set <key><value>
command: npm get <key>
example: npm get registry