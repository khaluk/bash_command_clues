# bash_command_clues
Bash command line clues and command examples

# find and kill proccess using tcp port 1883
 fuser
  -k kill
  -n  (file, udp, or tcp)
 -SIGNAL
sudo fuser -KILL -k -n tcp 1883

