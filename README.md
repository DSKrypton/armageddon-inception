# SRM aka safe remove
Adding recycle bin to otherwise irreversible rm command.

## Installation
* clone or download the content of this repo
* make srm_install script executable and run it
for example by following chain of commands:
    * `cd <path_to_directory_with_srm_files>`
    * `chmod +x srm_install` 
    * `./srm_install`

## How to use
To remove file or directory **<name>** in your current directory execute `srm <name>` command. 
All removed this way objects will be compressed into **<name>_<datetime>.tar.gz** and moved to **~/RECYCLE**
Keep in mind that archives automatically deleted after 1 week.
