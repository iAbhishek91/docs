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




## windows run shortcuts:

##### - open IE properties:
command: inetcpl.cpl

##### - open system properties:
command: sysdm.cpl




## git:





## mac terminal:




## node:
> Basics:
##### - version of node and npm:
command: npm -v | node -v

##### - initialize npm:
command: npm init

##### - adding dependencies:
command: npm install 'package-name' -save

##### - adding dev-dependencies:
command: npm i 'package-name' --save-dev

##### - adding dependencies:
command: npm i -g 'package-name'