#Build Instructions
Before start using please make sure you are using Linux/UNIX based OS


## Usage
Open your favorite terminal and type following commands:
```bash
cd ~/Desktop/
mkdir rashidisayev_test
git clone https://github.com/rashidisayev/random.git
chmod +x simple_random.sh
sh simple_random.sh 1 10
```
Numbers after the command sh simple_random.sh are range of numbers between which random numbers will be displayed
You can specify any range and the script will display it to you.

## Description
This script displays numbers in random order in the range you specified.

## Known limitations / bugs
In this script, the user's guide is not intentionally taken into account, so without this documentation, the user will not understand how to use it. Also, the error handler is not taken into account here, this why  users will not understand what they are doing wrong.
