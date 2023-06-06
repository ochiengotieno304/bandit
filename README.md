# Overthewire War Games (Bandit)

## Bandit 0

![alt text](images/bandit0.png "bandit0")

- ssh server login with port specification
- syntax `ssh <username>@<host> -p <port>`

## Bandit 1

![alt text](images/bandit1.png "bandit1")

- `ssh` server login
- `ls` to view directory content
- `cat` to view file content

## Bandit 2

![alt text](images/bandit2.png "bandit2")

- `ssh` server login
- `ls` to view directory content
- `cat` to view file content
- accessing dashed filenames

## Bandit 3

![alt text](images/bandit3.png "bandit3")

- `ssh` server login
- `cd` to change directory
- `ls -a` to view hidden directory content
- `cat` to view file content

## Bandit 4

![alt text](images/bandit4.png "bandit4")

- `ssh` server login
- `cd` to change directory
- `ls -a` to view hidden directory content
- `cat <path>/-filename` view dashed filenames

## Bandit 5

![alt text](images/bandit5.png "bandit4")

- `ssh` server login
- `cd` to change directory
- `find` search for files in a directory hierarchy
- `du` estimate file space usage
- `ls` list directory content
- `find -readable -type f ! -executable -exec du -b {} + | grep 1033` or `find -readable -type f ! -executable -exec ls -l {} + | grep 1033`
