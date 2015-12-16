# Scripts

This is my personal collection of shell scripts.

## The scripts

### Cheat

This is a small utility that prints textual cheatsheets that you have to create
on your computer. It uses the `CHEATSHEET_DIR` environment variable to decide
where the cheatsheets are stored, and searches that directory whenever you use
this command.

Store cheatsheets as textfiles with a `.txt` extension inside your
`CHEATSHEET_DIR` folder, and use the command as follows:

    cheat subject

Where subject is the name of your cheatsheet file without the `.txt` extension.

You can also list all your cheatsheets with the following command:

    cheat -l
