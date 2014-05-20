bash
====

##Bash scripts and functions.

To use simply:
- Create this repo in your home directory.
- Link bash/dot-bashrc to ~/.bashrc

###Sample Shell Commands

####Raw code commands
| Command | Description | 
|:------- | :---------- |
| **grepc** | grep in code files, current dir only |
| **grepd** | grep in code files and subdirs |
| **greph** | grep in header files and subdirs |
| **grepjx** | grep in java and xml files |
| **grepjs** | grep in js files and subdirs, IGNORING node_modules |
| **greppy** | grep in python files and subdirs EXCLUDING infra |
| **greppyi** | grep in python files and subdirs INCLUDING infra |

####GIT helper commands
| Command | Description | 
|:------- | :---------- |
| **glog** | Show short, custom, one-line versions of git log |
| **ghstatus** | Show (short) status of all Hermes modules repos |
| **ghdiff** | Show diff of all Hermes modules repos |
| **ghlog** | Show the last N commits on all Hermes modules repos |
| **ghfetch** | Fetch from upstream (non-personal) in all Hermes modules repos |
| **ghrebase** | Rebase the current branch (if no outstanding changes) in all Hermes repos |
| **gc** | Checkout branch - git checkout |
| **gb** | Show branches - git branch -vv |

####Random helper commands
| Command | Description | 
|:------- | :---------- |
| **ut** | Time conversion script |
| **mmcolor** | Echo the first arg wrapped in tty color setting escapes |

