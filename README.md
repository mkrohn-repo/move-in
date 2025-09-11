# move-in

Welcome. Directories are described below. This repository is **actively maintained**.

## Usage 

Clone and copy what you need:

```bash
git clone https://github.com/mkrohn-repo/move-in.git
#or
git clone git@github.com:mkrohn-repo/move-in.git
```

## What's Inside:

### `dotfiles`
**Platform/SRE toolbox — dotfiles**  
- zsh configuration with sample aliases and pyenv setup you can toggle on/off  
- sample git, vim, and bash profiles  
- **Note:** automation doesn’t auto-rename files — shells are personal. Pick what’s useful.  


### `useful_python`
**Platform/SRE toolbox — Python helpers**  
- **boto3**: reusable for AWS sessions, pagination, and common tasks
- **requests**: wrappers for handling HTTP requests
- **requests_v2**: wrappers for handling HTTP requests, revised to include timeouts, test code, typing and docstrings.

## Roadmap
- Add bearer token and retry support to HTTP(S) request functions 
- Expand boto3 session/pagination into a reusable module  
- Grow test coverage for all new functions