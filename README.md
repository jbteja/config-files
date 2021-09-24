# config-files
Configurations and Dot files.
<br>

# Tmux Config
  * Tested the configuration on below OS with default tmux instalation:
    - CentOS 6.10
    - CentOS 7.9
    - CentOS 8.2
    - RHEL 7.7
    - Amazon Linux 2
    - Ubuntu 16.04 LTS
    - Ubuntu 18.04 LTS
<br>

# VIM Conig
  * Source the config file by adding the below to .vimrc. 
  * Update the path of .my_vimrc accordingly.
  ```
  " Source a configuration file if available
  if filereadable("/home/jbteja/.bt_vimrc")
    source /home/jbteja/.my_vimrc
  endif
  ```
