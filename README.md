# Cleanthis

Use this tool if you want to clean a folder and move its contents into a backup folder within your home directory, 
specifically into a filetype folder. Check the code if necessary. Additionally, this code is suitable to be placed 
in $HOME/.local/bin. Change the file permissions to make it executable so you can run it from anywhere.

## Config

Place the config file from the config folder into `$HOME/.config/personal` because the code reads the config file from there. 
The code that performs this read is in the cleanthis file and is specified by the `DEFAULT_CONFIG_FILE` variable. 
This setup is intended to remind you that this config is personal. 
Also, don't forget to change the `default_directory` location in the config:

```bash
default_directory = "/home/Users/backup"
```

This folder is used for all your cleaned files.
