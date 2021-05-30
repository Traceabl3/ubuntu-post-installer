# ubuntu-post-install.sh
Simple post install script for Ubuntu 

# Author:
  David Brien <br>
  @traceabl3
#
# Description:
  A simple post-installation bash script for Ubuntu (20.04) <br>
  Based on snwh[0] , ravishi[1] , and rougeth[2] scripts. <br>
  [0] - https://github.com/snwh/ubuntu-post-install/ <br>
  [1] - https://gist.github.com/ravishi/3706813s <br>
  [2] - https://gist.github.com/rougeth/ubuntu-post-install.sh

  Credit to https://www.addictivetips.com/ubuntu-linux-tips/make-ubuntu-post-installation-script/ for the walkthrough.

# Set up:

  Download the file: <br>
  Save the file in the home directory. <br>
  
# Edit the file: 

  To edit the shebang file from terminal usung the nano editor, $~ nano -w ubuntu-post-install.sh <br>
  Replace <passowrd> with your root password only on the local machine. <br>
  Add or change the programs that you would like to install with the script from apt, snap, or flatpak. <br>
  When editing is complete, press (CTL + O) to save, then press Enter. <br>
  Press (CTL + X) to exit the nano editor. <br>

# Use: 

  Run the following commands to execute the script from a new terminal window (Ctrl + Alt + T), entering your password after each command: <br>
  $ sudo chmod +x ~/ubuntu-post-install.sh <br>
  $ sudo bash ubuntu-post-installer.sh <br>
  As the script runs, it will ask for your permission to procede at each step, but will not pause for your password at sudo comands if you changed <password> in the previous step. <br>
