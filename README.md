# http-ssl-ssh-tunneling
http ssl ssh tunneling vpn for android and linux devices

# packages :

[+] - apt install git python openssh sshpass netcat -y

[+] - apt install screen 

# configuration :

past your data into file settings.ini 

![image](https://user-images.githubusercontent.com/46646744/120905618-2c1ee080-c64b-11eb-9ce8-fcc24da98004.png)

note : if are using leave the first part of settings.ini empty you have only te setup your ssh settings

# how it works!

(root is required in android )

[+] - git clone https://github.com/abdoxfox/http-ssl-ssh-injector.git

# if you will use custom payload or direct ssh connection :

* setup yor custom payload and proxy (if need it  else leave it empty) and ssh details in settings.ini file.

[+] - cd http-ssl-ssh-injector

[+] - sudo su 

[+] - chmod +x runvpn.sh

[+] - chmod +x proxification

[+] - chmod +x redsocks

[+] - chmod +x runvpn.sh

[+] - ./runvpn.sh 1          (argument 1 means that you will use payload / direct ssh connection)

 # if are using ssl (sni bughost )

* setup your sni bughost and ssh details in settings.ini file and run the following command :

[+] - cd http-ssl-ssh-injector

[+] - sudo su 

[+] - chmod +x runvpn.sh

[+] - chmod +x proxification

[+] - chmod +x redsocks

[+] - ./runvpn.sh 2         (argument 2 means that you will use ssl  method )


