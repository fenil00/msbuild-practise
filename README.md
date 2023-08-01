# msbuild-practise

## Table of contents

- [msbuild-practise](#msbuild-practise)
  - [Table of contents](#table-of-contents)
  - [Location of MsBuild](#location-of-msbuild)
  - [Make MsBuild avilable from Powershell](#make-msbuild-avilable-from-powershell)
  - [Commands](#commands)

## Location of MsBuild

![Alt text](images\LocationOfMsBuild.png)


## Make MsBuild avilable from Powershell

Open enviroments variables and add MsBuild path "C:\Program Files\Microsoft Visual Studio\2022\Enterprise\MSBuild\Current\Bin" to "PATH" for current user as follows,

![Alt text](images\enviromentpath.png)

Now MsBuild will be recognised from Powershell/CommandLine.

![Alt text](images\powershell_msbuild.png)

## Commands

Build project 

`msbuild MsbuildPractise.csproj -t:Build`