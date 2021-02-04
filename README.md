# Fiche-Linux-Tips

## VSCODE ANDROID 


Installé Terminux

- pkg install wget openssl-tool proot -y && hash -r && wget https://raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/Installer/Ubuntu/ubuntu.sh && bash ubuntu.sh

After

./start-ubuntu.sh

- wget https://github.com/cdr/code-server/releases/download/2.1698/code-server2.1698-vsc1.41.1-linux-arm64.tar.gz

- tar -xvf ./code-server2.1698-vsc1.41.1-linux-arm64.tar.gz

- rm *.gz

- cp ./code-server2.1698-vsc1.41.1-linux-arm64/code-server /bin

- export PASSWORD="PASS"

- mv code-server* vsc

- mv ./vsc/code-server ./vsc/code


*/ now just write code
and it's open localhost:8080
in your browser */

