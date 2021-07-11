#Auto Install WordPress via AWS

Init script from aws command



#can be ran via terminal

bash <(curl -s https://raw.githubusercontent.com/anoluck/AWS/master/InstallWordPress) dbPass[optional]

#can be ran via aws launch script

launchScript=$(curl -s https://raw.githubusercontent.com/anoluck/AWS/master/InstallWordPress) && bash -c "$launchScript"
