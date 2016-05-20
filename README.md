# Automatic-PPTP-VPN-Connection-Shell
This shell script is intended to monitor if your pptp vpn connection is off, and if it's disconnected, it will help to rebuild the connection by running at the internal time step you want.<br>
1 Before you start using the shell, you should install pptp-setup (which is included in pptp-linux) and setup your pptp vpn.<br>
2 Download the shell (by using git or simply downloading the zip archive) and place it in /bin folder, then give it execute permission by typing 'chmod +x checkvpn'. <br>
3 Edit this shell to change your pptp vpn connection name (which is located after 'pon'). <br>
4 Write 'sudo /bin/checkvpn &' into '/etc/rc.local' to make it run when system boots. <br>
5 Enjoy it!  <br>

# PPTP VPN 断线重连脚本
见英文介绍 ：）
