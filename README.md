# task-10
I began by installing UFW on my Fedora system and disabling the default firewalld service to avoid conflicts. 
Once UFW was enabled, I focused on reducing the system's attack surface by configuring specific security rules.

Commands i used today
sudo dnf install ufw 
sudo systemctl stop firewalld 
sudo systemctl disable firewalld 
sudo ufw enable 
sudo ufw deny ssh 
sudo ufw deny from 91.108.23.100 
sudo ufw status verbose

Tools I used today
Operating System: Fedora Linux
Firewall Manager: UFW (Uncomplicated Firewall)
Package Manager: DNF (used to install UFW)
Gemini
