# Simple Stats Logger
Simply logging server stats into file.  
It is preffered to run these programs in background because it might be interrupted.  

# How to use
This tutorial uses screen to manage background task
1. Run the screen command
  ```
  screen
  ```
2. Inside spawned screen, run the desired (logger command)[#simple-stats-logger-command].  example : 
  ```
  ./docker_stats_logger.sh
  ```
3. Watch the log being written to data folder, or send it to background with shortcut ctrl+a and then ctrl+d

# Simple stats logger command

## Docker Stats
  ```
  ./docker_stats_logger.sh
  ```

## Nvidia-smi Stats

## Bitfusion smi

# Credit
https://stackoverflow.com/a/67252305
