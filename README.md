

# Step Create Project Golang
1. go initial 
```
go mod init  example.com/{package project}
```

2. create file lib install in file : "go.mod" == requirement.txt (python)
```
# Add lib install on file go.mod 
go build
```

3. *if have file : "go.sum"  for file check sum version download same "package-lock.json"

4. go install module package 
```
## Install lib like pip install (python)
go get {package lib example: github.com/haccer/subjack }
```

## command [go mod] = pip (python)
go mod คือ ตัวช่วยจัดการ package tool lib  
```
# คำสั่งลบ lib package ไม่ได้ใช้งานออกจาก lib 
go mod tidy
```
