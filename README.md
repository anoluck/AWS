#Auto Install WordPress via AWS

Init script from aws command



#can be ran via terminal

bash <(curl -s https://raw.githubusercontent.com/anoluck/AWS/master/InstallWordPress) dbPass[optional]

#can be ran via aws launch script

launchScript=$(curl -s https://raw.githubusercontent.com/anoluck/AWS/master/InstallWordPress) && bash -c "$launchScript"

#reminders

& = run 1st cmd in background then run the 2nd cmd

&& = run 1st cmd if return true, run 2nd command

|| = run 1st cmd if return false, run 2nd command

; = run 1st then 2nd cmd regardless

grep -q "test123" ./test || sed -i '/line 2/a test123' ./test
