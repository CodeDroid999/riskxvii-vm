
<div align=center>
         
| **Please star ⭐ the repo if you find it useful. Issues and PRs are more then WELCOME!** |
| --- |
         
<table><tbody><tr><td><a href="https://github.com/CodeDroid999/CryptPy/stargazers"> Thank you dear stargazers! ⭐🤩 </a></td><td> <a href="https://github.com//">Docs 🕮 </a></td><td><a href="https://discord.gg/CmFvFJDXZv"> Questions? Ask on Discord 💬 </a></td></tr></tbody></table>

![GitHub Repo stars](https://img.shields.io/github/stars/JovianX/Service-Hub)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/JovianX/Service-Hub)
<!--![GitHub contributors](https://img.shields.io/github/contributors/CryptPy)
![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/platform_engineering)
![Discord](https://img.shields.io/discord/1014893148599754894)
[![StandWithUkraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/badges/StandWithUkraine.svg)](https://github.com/vshymanskyy/StandWithUkraine/blob/main/docs/README.md)--->
</div>

### Riskxvii-vm

Riskxvii-vm is a commandline invoked virtual machine implementation in C. It takes machine code as command line aeguments, assembles it into assembly instructions which are saved in binary files.


### Building riskxvii-vm from Source

# Linux

Dependencies: `gcc, make`

```shell
cd RISKXVII-VM/examples
chmod 755 *
cd RISKXVII/include
chmod 755 *
cd RISKXVII/src
chmod 755 *
make
sudo make install
# alternatively, move the compiled binary to your preferred location
```

# Windows

```shell
cd RISKXVII/src
# invoke the version of make installed on your system
# add the resulting 'laser.exe' to your windows path
```

# Mac OSX

Dependencies: `xcode command line tools`

```shell
xcode-select --install
cd RISKXVII/src
make
sudo make install
# alternatively, move the compiled binary to your preferred location
```
## commands

    -v: 'riskxvii -v' displays version number
    -h: 'riskxvii -h' displays this message again
    -q: 'riskxvii -q' suppresses all warning messages during assembly
    -s: 'riskxvii -s' suppresses all warnings and errors during assembly
    -a: 'riskxvii -a <file>' assembles the specified file
        'riskxvii -a *.asm' assembles all assembly files in current directory
    -p: 'riskxvii -p <file1> <file2>' assembles the specified files as a project
        'riskxvii -p *.asm' assembles all files in current directory as a project
    -c: 'riskxvii -c <file>' removes all files generated during assembly
