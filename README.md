# Movy

Tiny bash script to clean up your desktop.

Takes any number of rules to move files from your Desktop to pre-defined directories.

- The target directories need to exist
- By default files will be ignored for 1 day. Value can be increased
- Files will not be overridden. If a file with the same name already exists in the target dir, the file will not be moved

Source and base target dir are defined in the movy file.

The patterns and the target dirs for the file type are defined in each rule file.
