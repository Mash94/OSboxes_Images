# OSboxes_Images
A little list of steps to follow to change some important parameters as UserName, password user, password root

Press F12
Press SHIFT

Recovery Mode
Root

mount -o remount,wr /

passwd <username>
  change it
  
passwd root
  change it
  
sudo usermod -l <newname> -d /home/<newname> -m <oldname>
