# Bash Aliases: Simplify Your Full Stack Laravel Development Workflow
Welcome, this is a curated collection of Bash aliases tailored specifically for Full Stack Laravel developers. These aliases are designed to enhance your productivity by  reducing repetitive typing, and improving the overall development experience.

## What is Bash Aliases?
These are a set of Bash aliases meticulously crafted to streamline your daily coding routines. By providing easy-to-remember commands, it aims to make your development process faster and more efficient. Whether you're navigating directories, managing Git repositories, or running Laravel Artisan commands, DevTools has got you covered.

## How to Use Bash Aliases?
To start using Bash Aliases, follow these simple steps:

- Open your `~/.bashrc` file in a text editor. This file is typically located in your home directory.
- Uncomment or add the following lines at the end of the file:
- ```bash
    if [ -f ~/.bash_aliases ]; then
        . ~/.bash_aliases
    fi
    ```
- Save the changes and exit the text editor.

- Create a new file called `.bash_aliases` in your home directory:
- ```bash
    nano ~/.bash_aliases
    ```
- Copy and paste the provided aliases into the .bash_aliases file.
- Save the changes and exit the text editor.

## Available Aliases
Below are some of the aliases included in DevTools:
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
alias gc='git commit'
alias gp='git push'
alias nah='git reset --hard;git clean -df'
```

## Restart Your Terminal
To apply the changes and load the new aliases, restart your terminal session.

## Get Started with Bash Aliases
Fork the repository, customize the aliases to fit your workflow, and start coding with speed and convenience. Let it be your trusted companion in your Laravel development journey.
Happy coding! 🚀