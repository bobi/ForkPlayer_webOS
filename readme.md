## ForkPlayer build for WebOS to instal via developer tools http://forkplayer.tv/smart-tv/install_forkplayer_webos_ide/

**build**

ares-package.cmd -e .git -e readme.* -e LICENSE* ForkPlayer_webOS

**install**
ares-install.cmd -d <tv-name> com.forkplayer.tv_1.0.3_all.ipk
