# HOSTETE DISCORD DDoS LOGS V2
<h3>Installation process</h3>
<hr><ht>
mkdir hostetelogs

iptables -A FORWARD -i tun0 -o eth0 -j ACCEPT

sudo apt-get update && sudo apt-get upgrade -y

sudo apt-get install tcpdump -y

sudo apt-get install dos2unix -y

sudo apt-get install curl -y

sudo apt-get install screen -y

chmod +x attacklog.sh

dos2unix attacklog.sh

screen bash attacklog.sh

<hr><ht>
  <h3>How to change Discord Webhook?</h3>
  <hr><ht><br>
  Editing attacklog.sh or you're down
