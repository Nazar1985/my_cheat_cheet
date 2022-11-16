## Variables

## [**Source**](https://linuxhint.com/bash_command_output_variable/)

###### Example#1
```commandline
variable=$(command)
variable=$(command [option…] argument1 arguments2 …)
variable=$(/path/to/command)
```
OR
```commandline
variable=`command`
variable=`command [option…] argument1 arguments2 …`
variable=`/path/to/command`
```

###### Example#2
```
current_dir=`pwd`
echo "The current directory is : $current_dir"
```

###### Example#3
**fruits.txt**
```
Mango
Orange
Banana
Grape
Guava
Apple
```

```commandline
count_words=`wc -w fruits.txt`
echo "Total words in fruits.txt is $count_words"
```
`> Total words in fruits.txt is 6 fruits.txt`

###### Example#4
```commandline
output=$(/usr/bin/whoami)
echo $output
> ubuntu
```

###### Example#5
```commandline
#!/bin/bash
filename=`basename $1`
echo "The name of the file is $filename."

```
`$ bash cmdsub3.sh Desktop/temp/hello.txt`

`> The name of the file is hello.txt`