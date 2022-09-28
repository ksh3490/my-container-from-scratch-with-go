# Building container tutorial with golang
  
## Test Environment: 
  - WSL2 in Windows 10
  - go 1.17.8 linux/amd64

## Note
  - This code should be run with root permission because of system call flag 'syscall.CLONE_NEWUTS'.
  - If you want to run this source code with a user without root privileges, please use 'sudo'.

## How to run
  - Run Go command in this project path like below:
    - `go run main.go run /bin/bash`
  - Then a container will be started and a bash will run as an isolated process.

## References
  - Liz Rice - Containers from scratch (https://youtu.be/oSlheqvaRso)
  - Deep into Container — Build your own container with Golang (https://dev.to/devopsvn/deep-into-container-build-your-own-container-with-golang-3f5e)
