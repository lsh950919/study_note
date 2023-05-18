# study_note

I needed some space to record my understanding of code or anything that might be useful in the future

# Git & Github


# Vim


# Commands
```ssh-keygen -t rsa -b 4096 -C "email@example.com```

* -t is type of encryption, -b is strength of encryption, and -C is the identifier

* this creates two files: ~/.ssh/id_rsa and ~/.ssh/id_rsa.pub

* the one that ends with .pub is the public key that other people can have access to, and the one that doesn't end in .pub should never be shared with others since 
this is the actual identifier of my machine.

```ssh-add -K ~/.ssh/id_rsa```

* is the command to register the new key to the machine.

``` pbcopy <file_path>```

* this copies the contents from a file to the clipboard. Does it require installation of the package? idk


# Tmux


# Pytorch


# Deep Learning
Curriculum Learning - concept that involves randomly choosing to use the ground truth output or generated output from the previous time step (also called scheduled sampling)

# Reinforcement Learning
Learning from rewards calculated by an action of an agent inside a specific environment

state/observation (partial state) -> action -> reward

## Markov Decision Process
All problems trying to be solved by RL is represented as an MDP

1. Markov Property: probability of immediate next state only depends on the most recent state and action, and does not depend on anything prior (memory-less property)
$$Pr(S_(t+1)=s'|S_0, S_1, ..., S_(t-1), S_t) = Pr(S_(t+1)=s'|S_t)$$


