<h1 align="center">Espresso Systems Testnet</h1>

## Sorunlarınız için Espresso Systems Turkish kanalı: [Telegram linki](https://t.me/EspressoSystemsTurkish)

![image](https://user-images.githubusercontent.com/101149671/174169233-5e811b69-3414-4bbb-bbff-ce9cadbfc16e.png)

<h1 align="center">Espresso Systems Testnet Türkçe rehberine hoş geldiniz</h1>

# Sırasıyla:

1/ Öncelikle kurulumu yapacağımız bir linux sunucu ayarlamamız gerekli.

2/ putty ile sunucumuza bağlanıyoruz.

# Docker yazılımını sunucumuza indiriyoruz:
```
sudo snap install docker
```

# Docker compose dosyamızı indiriyoruz (tek tek giriyoruz):
```
curl https://www.espressosys.com/cape/docker-compose.yaml --output docker-compose.yaml
docker-compose pull
apt-get install screen
screen -S Espresso
docker-compose up
```
# Ardından kişisel bilgisayarımızda komut istemine sağ tıklayarak yönetici olarak başlatıyoruz ve aşşağıdaki 2 komutu giriyoruz (tek tek giriyoruz)

Sunucu IP yazan yere sunucumuzun IP adresini girerlim.
```
netsh interface portproxy add v4tov4 listenaddress=127.0.0.1 listenport=80 connectaddress=sunucuip connectport=80
netsh interface portproxy add v4tov4 listenaddress=127.0.0.1 listenport=80 connectaddress=sunucuip connectport=80
```
![image](https://user-images.githubusercontent.com/101149671/174170473-11fc7972-e24c-4c59-ba61-166ab3588cdc.png)


#  Ardından kişisel bilgisayarımızda tarayıcımıza girerek localhost diyoruz. Set up a new CAPE Wallet kısmına giriyoruz: 

![image](https://user-images.githubusercontent.com/101149671/174170393-4f4b85bd-066b-4719-a8c4-3cb08e143fce.png)

#  Reveal keys diyerek yeni bir cüzdan oluşturuyoruz. Oluşan cüzdan bilgilerini saklayalım.

![image](https://user-images.githubusercontent.com/101149671/174170527-5b23a248-3f79-48b3-a14e-456d21f2b71b.png)

# Create keystore kısmına tıklıyoruz: 

![image](https://user-images.githubusercontent.com/101149671/174170549-8ebb198d-23d0-44fa-877f-0430ed65e2b4.png)

# Ardından Accounts kısmına gelerek Generate new address diyerek cüzdan adresi oluşturuyoruz:

![image](https://user-images.githubusercontent.com/101149671/174170575-dab78df3-9685-4d98-b5c1-b933342823f8.png)

# Ardından altta ki twitte aşşağıdaki gibi cüzdan adresimizi yolluyoruz.

Twit linki: https://twitter.com/EspressoSys/status/1537447721916698625?s=20&t=YvCHet3bK0KM5goCr-9YGg

![image](https://user-images.githubusercontent.com/101149671/174170692-7524aad1-f062-4959-a0bb-0367dcb9f2ab.png)


## Sorunlarınız için Espresso Systems Turkish kanalı: [Telegram linki](https://t.me/EspressoSystemsTurkish)


Teşekkürler <3

# Hesaplar:

[<img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" width="16px"> Twitter   ](https://twitter.com/Ruesandora0) 

[<img src="https://cdn-icons-png.flaticon.com/512/1336/1336494.png" width="16px"> Forum   ](https://forum.rues.info/index.php)

[<img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="16px"> Telegram Announcement   ](https://t.me/RuesAnnouncement)

[<img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="16px"> Telegram Chat   ](https://t.me/RuesChat)

[<img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="16px"> Telegram Node   ](https://t.me/RuesNode)

[<img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="16px"> Telegram Node Chat](https://t.me/RuesNodeChat)
