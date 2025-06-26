# PUTTY


****PC DE YAPILACAKLAR


PC (Windows) Ethernet Ayarları – Özet:
IP Ataması: El ile (manuel)

IPv4 Adresi: 192.168.1.101

Alt Ağ Maskesi (Subnet Mask): 255.255.255.0


*****JETSON DA YAPILACAKLAR

manuel olarak ıp atama işlemi:

sudo ip addr add 192.168.1.100/24 dev eth0
sudo ip link set eth0 up   ////daha sonra ifconfig ile kontrol edebilirsin.
ping 192.168.1.100(PC'DEN PUTTY ÜZERİNDEN BAĞLANABİLİRİZ IP ATANDI)


sudo mavproxy.py --master=/dev/ttyACM0 --baudrate 115200 --out=udpout:172.20.10.2:14550/// mavproxy wifi üzerinden başlatma kodu

sudo mavproxy.py --master=/dev/ttyACM0 --baudrate 115200 --out=udpout:192.168.1.101:14550/// mavproxy ethernet üzerinden başlatma kodu 101 pc nin ıp 



fotoğraf çekmek için
python3 foto.py çalıştır.

tmux çalıştır iki terminal açabilemk için.
ctrl+b ardından c ile yeni terminal
ctrl+b ardından n veya p şle sayfa gezinme .
