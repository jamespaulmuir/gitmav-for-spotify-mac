cd ~/
git clone git://github.com/jamespaulmuir/gitmav-for-spotify-mac.git
cd git-mav-for-spotify-mac
chmod +x gitmav.sh
add alias to .gitconfig
	[alias]
        	mav = !~/gitmav-for-spotify-mac/gitmav.sh &
