# wsl-adventures
FOllowing along: https://www.most-useful.com/kde-plasma-on-wsl.html

wslEasy distros are dumb and don't let you apt update. This fixes that:

_sudo sed -i -r 's/([a-z]{2}.)?archive.ubuntu.com/old-releases.ubuntu.com/g' /etc/apt/sources.list
&& sudo sed -i -r 's/security.ubuntu.com/old-releases.ubuntu.com/g' /etc/apt/sources.list_
