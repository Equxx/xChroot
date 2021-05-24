# xChroot
 Selamun aleyküm arkadaşlar...

xChroot projesi, Linux dağıtımlarında kullanılabilen (Ubuntu,Debian gibi..) bash script tabanlı bir yazılımdır.

Bu proje githubdan çekilerek düzenlenmiştir.

Canlı yayın için kanalımıza abone olmayı unutmayın...

Canlı yayın linkleri :

www.twitch.tv/equxx

www.dlive.tv/equxx

Gelelim konumuza;
xChroot projesi, Debian yada herhangi bir dağıtımda 'debootstrap' adlı yazılım aracılığıyla herhangi bir kök dizine işletim sistemi kurup, varolan pencere sistemi üzerinden - ki bu x window system olarak geçer- programları çalıştırmasına yarar. Kısaca toparlayacak olursak yapacağımız yada yaptığımız bir hata sonucu işletim sistemi "SAÇMALARSA" dizini silip yeniden kurulum yapıyoruz. Böylelikle işletim sistemini yeniden kurmaya gerek yok. Yanlız dezavantajı sadece komut satırı aracılığıyla yazılımı çalıştırabiliyorsunuz. Tek eksisi o. Onu da yaparsınız artık. Gerekli indirmeler ve yönergeler aşağıda belirtilmiştir.

xChroot için hazırlık

$ sudo apt update && sudo apt upgrade -y

$ sudo apt install debootstrap -y

$ cd /

$ sudo mkdir /dst

$ cd /dst

$ sudo mkdir /stable

$ sudo debootstrap stable /dst/stable

$ git clone https://github.com/Equxx/xChroot

$ sudo ./xChroot

