# study_note

I needed some space to record my understanding of code or anything that might be useful in the future

# Git & Github


# Vim


# Commands
```ssh-keygen -t rsa -b 4096 -C "email@example.com```
-t is type of encryption, -b is strength of encryption, and -C is the identifier

this creates two files: ~/.ssh/id_rsa and ~/.ssh/id_rsa.pub

the one that ends with .pub is the public key that other people can have access to, and the one that doesn't end in .pub should never be shared with others since 
this is the actual identifier of my machine.

```ssh-add -K ~/.ssh/id_rsa```
is the command to register the new key to the machine.

``` pbcopy <file_path>```
this copies the contents from a file to the clipboard. Does it require installation of the package? idk


# Tmux


# Pytorch
