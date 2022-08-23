# COBOL in the 21st Century
It seems like everyone pretty much does the same things on computers today, and they all talk about it on hacker news. Everything is Typescript and Go. Sometimes it's hard to tell if you're even thinking at all, or if you're just copying some blog post. To break out of this cycle, I'm going to do some crazy shit. I'm going to write some COBOL.

The somewhat more serious idea is that there may be insights in the structures and practices adopted in the early computing days that will help us think about computers today.

## Install
Currently working on Ubuntu 20.04.

```bash
# install open cobal
sudo apt-get install open-cobol

# check to see where it's installed
whereis cobc; which cobc

# compile
cobc -x -o helloworld helloworld.cbl

# run
./helloworld
```