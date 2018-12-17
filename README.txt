README
Terran Travels Traveler System Installation Guide

TERRAN TRAVELS TRAVELER SYSTEM INSTALLATION ON AN ARCH LINUX DISTRO.
1.	Open a terminal.
a.	Right click on the desk top and select “Open a terminal here”.
b.	Or open the app menu and search for “Terminal” and open it from there.
2.	Type in the terminal
pacman -Sy terantravltravlersys
3.	Press Enter.
4.	Enter the password you used to login to the system and press enter. (The password won’t show up in the terminal but it is being typed regardless.)
5.	Writings will come up on the terminal, do not cut power or interrupt the installation in any way. The system will detect the available hardware and set itself up.
6.	Exit the terminal when the system name shows up on the left side and the blinking cursor returns.
TERRAN TRAVELS TRAVELER SYSTEM INSTALLATION ON A DEBIAN LINUX DISTRO.
1.	Open a terminal.
a.	Right click on the desk top and select “Open a terminal here”.
b.	Or open the app menu and search for “Terminal” and open it from there.
2.	Type in the terminal
sudo apt-get-repository ppa:terantravl/terantravltravlersys;
sudo apt-get update;
sudo apt-get install terantravltravlersys;
3.	Press Enter.
4.	Enter the password you used to login to the system and press enter. (The password won’t show up in the terminal but it is being typed regardless.)
5.	Writings will come up on the terminal, do not cut power or interrupt the installation in any way. The system will detect the available hardware and set itself up.
Exit the terminal when the system name shows up on the left side and the blinking cursor returns.
TERRAN TRAVELS TRAVELER SYSTEM INSTALLATION ON A FEDORA LINUX DISTRO.
1.	Open a terminal.
a.	Right click on the desk top and select “Open a terminal here”.
b.	Or open the app menu and search for “Terminal” and open it from there.
2.	Type in the terminal
curl -–silent -–location localhost://rpm.terantravl.tts/terantravltravlersys | bash –
sudo dnf copr enable tts/terantavltravlersys
sudo dnf install terantavltravlersys
3.	Press Enter.
4.	Enter the password you used to login to the system and press enter. (The password won’t show up in the terminal but it is being typed regardless.)
5.	Writings will come up on the terminal, do not cut power or interrupt the installation in any way. The system will detect the available hardware and set itself up.
Exit the terminal when the system name shows up on the left side and the blinking cursor returns.
TERRAN TRAVELS TRAVELER SYSTEM INSTALLATION ON AN OPENSUSE LINUX DISTRO.
1.	Open a terminal.
a.	Right click on the desk top and select “Open a terminal here”.
b.	Or open the app menu and search for “Terminal” and open it from there.
2.	Type in the terminal
wget localhost://rpm.terantravl.tts/terantravltravlersys | bash –
zipper install terantravltravlersys.rpm
3.	Press Enter.
4.	Enter the password you used to login to the system and press enter. (The password won’t show up in the terminal but it is being typed regardless.)
5.	Writings will come up on the terminal, do not cut power or interrupt the installation in any way. The system will detect the available hardware and set itself up.
Exit the terminal when the system name shows up on the left side and the blinking cursor returns.

