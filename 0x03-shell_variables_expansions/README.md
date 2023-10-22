# Bash Alias Scripts

This project contains two Bash scripts to create and remove an alias for the `ls` command.

## create_alias.sh

This script appends the alias definition to the user's `.bashrc` file, allowing you to use `ls` as an alias for `rm *`. Use it with caution, as it can lead to data loss.

## remove_alias.sh

This script removes the previously created `ls` alias from the user's `.bashrc` file. It is useful if you want to revert the changes made by the `create_alias.sh` script.

To use these scripts, make sure they are executable. You can make them executable with the following command:

```bash
chmod +x create_alias.sh remove_alias.sh

