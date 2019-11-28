![](https://img.shields.io/badge/go--mygen-tools-orange?style=flat-square&logo=appveyor)
![](https://img.shields.io/badge/download-4M-green?style=flat-square&logo=appveyor)
![](https://img.shields.io/badge/release-linux%2Cmac%2Cwin-blue?style=flat-square&logo=appveyor)
<br/>
![](https://img.shields.io/badge/go--mygen-3.1.0beta-green)
![](https://img.shields.io/badge/go--mygen-3.0.0beta-green)
![](https://img.shields.io/github/stars/yezihack/go-mygen)
![](https://img.shields.io/github/issues/yezihack/go-mygen)
![](https://img.shields.io/github/forks/yezihack/go-mygen)
![](https://img.shields.io/github/license/yezihack/go-mygen)

[英文](README-EN.md)|[中文](README.md)

# go-mygen
> Code generator tools with MYSQL,avoid ORM performance penalty

## version
1. 3.1.0beta version
1. Compatible with linux,win,mac

## Install
```
go get github.com/yezihack/go-mygen
```
## Using v3 releases
> [release](https://github.com/yezihack/go-mygen/releases/tag/3.0.0beta)

## Features
- Generate the markdown document for the database table
- Generate the structure entities for the golang table
- Custom structure parsing entities, such as json,gorm, XML, etc
- Generate golang operation mysql add, delete, modify and select code statements
- Custom build directory
- Clear screen, exit and other functions


## Parameters info
```
-h value       Database address (default: "localhost")
-P value       port number (default: 3306)
-u value       Database user name (default: "root")
-p value       Database password (default: "root")
-c value       Coding format (default: "utf8mb4")
-d value       Database name
```

### See help and version
`go-mygen help`
`go-mygen version`

## QuickStart
- You must first connect to the specified database
- For operation tips page
- Enter different commands on the interface to operate

### Display operation with password
```
go-mygen -h localhost -P 3306 -u root -p 123456 -d default
```

### Protected password operation
```
go-mygen -h localhost -P 3306 -u root -d dbname
```

## Other
> If an error is found, please welcome issues
```
xx>  input state
xx:  message tips
xx>> error output
```