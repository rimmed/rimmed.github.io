  402  yaourt efl
  403  yaourt efl | less\
  404  yaourt efl | less
  405  yaourt terminology
  406  mc /usr/lib/evas/
  407  sudo mc /usr/lib/evas/
  408  yaourt terminology
  409  cd Workspace/enlightenment.org/apps/terminology/
  410  sudo make uninstall
  411  yaourt terminology
  412  yaourt enlightenment
  413  enlightenment_start 
  414  systemctl status 
  415  cat /etc/systemd/user.conf 
  416  systemctl status 
  417  systemctl status connman-vpn.service 
  418  systemctl disable connman-vpn.service 
  419  whereis desctop-manager.service
  420  whereis desktop-manager.service
  421  systemctl status display-manager.service 
  422  systemctl enable display-manager.service 
  423  cat /usr/lib/systemd/system/
  424  m
  425  cat /etc/systemd/system/gdm.service 
  426  sudo cp /etc/systemd/system/gdm.service /etc/systemd/system/enlightenment.service
  427  vim /etc/systemd/system/enlightenment.service 
  428  sudo vim /etc/systemd/system/enlightenment.service 
  429  systemctl status enlightenment.service 
  430  systemctl enable enlightenment.service 
  431  reboot 
  432  systemctl status enlightenment.service 
  433  /usr/bin/enlightenment_start 
  434  systemctl disable nmbd.service 
  435  systemctl status enlightenment.service 
  436  sudo vim /etc/systemd/system/enlightenment.service 
  437  reboot 
  438  systemctl status systemd-modules-load.service 
  439  ls /etc/modules-load.d/
  440  journalctl --help
  441  journalctl -b
  442  systemctl status vboxweb.service 
  443  ls /etc/modules-load.d/
  444  ls /usr/lib/modules-load.d/
  445   /usr/lib/modules-load.d/virtualbox-guest-dkms.conf 
  446  sudo rm /usr/lib/modules-load.d/*
  447  ls /usr/lib/modules-load.d/
  448  journalctl -b
  449  systemctl status dbus
  450  journalctl -b | grep dbus
  451  vim ~/.xinitrc
  452  sudo vim /etc/systemd/system/enlightenment.service 
  453  reboot 
  454  whereis startx
  455  sudo vim /etc/systemd/system/enlightenment.service 
  456  reboot 
  457  startx 
  458  sudo rm /etc/systemd/system/enlightenment.service 
  459  ls /etc/systemd/user/
  460  ls /etc/systemd/user/sockets.target.wants/
  461  ls /usr/lib/systemd/user
  462  cat /usr/lib/systemd/user/enlightenment.service 
  463  systemctl --user status enlightenment.service 
  464  systemctl --user enable enlightenment.service 
  465  cat /usr/lib/systemd/user/graphical-session
  466  cat /usr/lib/systemd/user/graphical-session.target 
  467  reboot 
  468  systemctl --user status enlightenment.service 
  469  loginctl enable-linger rimmed
  470  reboot 
  471  systemctl --user status enlightenment.service 
  472  systemctl --user start enlightenment.service 
  473  journalctl -b
  474  journalctl -b --user
  475  systemctl --user start enlightenment.service 
  476  cat /usr/lib/systemd/user/enlightenment.service 
  477  yaourt xorg-xinit
  478  cat /usr/lib/systemd/user/enlightenment.service 
  479  systemctl --user start enlightenment.service 
  480  rm ~/.xinitrc 
  481  systemctl --user start enlightenment.service 
  482  vim /usr/lib/systemd/user/enlightenment.service 
  483  sudo vim /usr/lib/systemd/user/enlightenment.service 
  484  systemctl --user start enlightenment.service 
  485  systemctl --user status enlightenment.service 
  486  journalctl -xe --user
  487  journalctl -xe --user
  488  sudo vim /usr/lib/systemd/user/enlightenment.service 
  489  systemctl --user start enlightenment.service 
  490  journalctl -xe --user
  491  reboot 
  492  journalctl -b
  493  journalctl -b --user
  494  yaourt xlogin
  495  vim ~/.xinitrc
  496  systemctl --user disable enlightenment.service 
  497  systemctl --user enable xlogin@rimmed
  498  systemctl --user enable xlogin
  499  systemctl enable xlogin@rimmed.service
  500  reboot 
  501  cd Documents/
  502  ls
  503  vim eflete_requ/eflete_requerements.txt 
  504  vim ~/Workspace/github/configs/vimrc 
  505  vim eflete_requ/eflete_requerements.txt 
  506  cd 
  507  cd Workspace/github/rimmed.github.io/
  508  ls
  509  vim _drafts/2017-07-18-enlightenment_systemd_autostart.md
  510  history 
  511  history >> _drafts/2017-07-18-enlightenment_systemd_autostart.md
