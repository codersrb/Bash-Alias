## What?
Streamline your development tasks with DevTools, a collection of Bash aliases designed to make your daily coding routines faster and more efficient. Say goodbye to repetitive typing and hello to easy-to-remember commands that automate common tasks. Whether you're navigating directories, running Git commands, or starting up your development server, DevTools has you covered. With a focus on simplicity and ease of use, these aliases are carefully crafted to boost your productivity without sacrificing flexibility. Fork the repository, customize the aliases to suit your workflow, and start coding with speed and convenience. Let DevTools be your trusted companion in your coding journey.

## How to create your own aliases
For those new to creating bash aliases, the process is pretty simple.
First, open up the ~/.bashrc file in a text editor that is found in your home directory.
Uncomment or add the following lines:

```bash
if [ -f ~/.bash_aliases ]; then
    . ~/.bash_aliases
fi
```

Then, create a new file in your home directory called `.bash_aliases`.

```bash
nano ~/.bash_aliases
```

## Review and Copy below Aliases into you .bash_aliases file

```bash
## Artisan & Sail Commands
alias pa='php artisan'
alias sail='bash vendor/bin/sail'
alias sa='bash vendor/bin/sail artisan'
alias snpm='bash vendor/bin/sail npm'

## Git Aliases
alias g='git'
alias gs='git status'
alias ga='git add'
alias gc='git commit -m'
alias gp='git push'
alias nah='git reset --hard;git clean -df'
```

## Restart your terminals to load new aliases.
## Thanks!!