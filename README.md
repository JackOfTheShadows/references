# references

This project was inspired by  https://github.com/cheat/cheat/tree/cheat-python but rather than python it is recreated in bash.

With the following project, you can quickly reference notes you have made in the terminal.

## Setup

Use stow to set up the files:

```bash
stow -t ~ name_of_folder
```

Add the following entry to ```.bash_aliases```

```bash
ref_cheat {
    cat ~/.local/cheat/$1
}
```
