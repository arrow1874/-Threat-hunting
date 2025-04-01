sudo apt update
sudo apt dist-upgrade
sudo apt autoremove
 
 
cd /tmp
 
curl https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb > msfinstall
 
chmod +x msfinstall
sudo ./msfinstall
 
msfdb init
 
msfconsole
 
sudo msfupdate
