You can use the NordVpn_Us software in two different ways, giving the same result.
1 - use the Python3 interpreter: the "Sources" folder contains the python programs "nordvpn_Fr.py" and "nordvpn_Us.py".
	copy the one that suits you (Fr or Us) in your .scripts folder (for example), then nordvpn_Fr.bash (or nordvpn_Us.bash) in the same place.
	Correct the .bash file to adapt the path "cd /home/--you--/.Scripts/NordVpn/NordVpn_Us" to your case.
	Finally, create a launcher on your desktop to launch the nordvpn_Fr.bash file in a terminal (mandatory). 
	Also use the "nordvpn-choix-logo40_v.png" icon
	
2 - or else use the directly executable program "nordvpn_Fr" (or "nordvpn_Us") which is in the "dist_NordFrUs" folder. Then just create
	on the desktop a launcher pointing directly to "nordvpn_Fr", with the icon "nordvpn-choix-logo40_v.png", and marked "run in a terminal" (required).
	This program was created by pyinstaller which encapsuled in "nordvpn_Fr" the environment required by the execution of "nordvpn_Fr.py"
	When running "nordvpn_Fr", a temporary folder is created in which the "nordvpn_Fr" program unpacks this environment as well as the "nordvpn_Fr.py" 
	program which runs immediately.
	This method is simpler than the first, but does not show you the sources files.
