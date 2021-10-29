apt install screen -y

screen -S unjail




wget https://raw.githubusercontent.com/alexobninsk/Script-for-Evmos/main/unjail.sh \
&& chmod +x unjail.sh \
&& ./unjail.sh -b evmosd -k $evmos_wallet_name -s 120m
