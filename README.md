# sudoers-add

Bash script that takes a sudoers config validates it and adds it to /etc/sudoers.d/{sudoers-file-name}

## Usage

`./sudoer.sh [file_path] [sudoers-file-name]`

`[content] | ./sudoer.sh sudoers-file-name`

This will take a sudoers config validate it and add it to /etc/sudoers.d/{sudoers-file-name}

The config can come from a file, first usage example or piped in second example.
