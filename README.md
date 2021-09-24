# Config-files

Configurations and Dot files.

## Tmux Config

* Tested the configuration on below OS with default tmux installation:
  * CentOS 6.10
  * CentOS 7.9
  * CentOS 8.2
  * RHEL 7.7
  * Amazon Linux 2
  * Ubuntu 16.04 LTS
  * Ubuntu 18.04 LTS

## VIM Config

* Source the config file by adding the below to local .vimrc or /etc/vim/vimrc.
* Update the path of .my_vimrc accordingly.
  
  ```sh
  " Source a configuration file if available
  if filereadable("/home/jbteja/.my_vimrc")
    source /home/jbteja/.my_vimrc
  endif
  ```
