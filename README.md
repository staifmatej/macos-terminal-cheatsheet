# MacOS terminal cheatsheet

**NOTE:** I created this cheatsheet for myself as a summary of common commands for Macintosh (MacOS) that I regularly use, so I can quickly look them up. I don't comment or explain the commands here in much detail, since that's not the purpose of this cheatsheet.

## Global configuration file:
Open with `nano`:
```
nano ~/.zshrc
```
To immediately save and load changes in `~/.zshrc`, I need to run the command:
```
source ~/.zshrc
```
## Anaconda for package management
For environment activation:

```
conda activate ml1
```
To list all libraries in the environment (the environment must be activated):
```
conda list
```
To list all environments:

```
conda env list
```
Deactivate environment:

```
conda deactivate
```
To install some lib (e.g. `polars`) I must already have the environment activated:
```
conda install polars
```

To show the local version in the current environment:
```
conda list numpy
```

## Git (I have local files, want to push to remote repo)

```
git init
git remote add origin git@github.com:staifmatej/bi-pa2.git
git pull origin main --no-rebase --allow-unrelated-histories
gpush
```

## Terminal shortcuts

```
Control + E  # end of the line.
Control + A  # beginning of the line.
Control + U  # delete from cursor to beginning of the line.
Control + J  # insert a new line in terminal, but does not send (unlike Enter).
```

## CLion / PyCharm

```
Cmd + ←  # jump to the beginning of the line in code.
Cmd + →  # jump to the end of the line in code.
```
