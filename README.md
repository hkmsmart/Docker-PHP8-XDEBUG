Docker PHP8 MYSQL8 PhpMyAdmin Phpstorm
Klasorler oluşması için text.txt dosyası eklenmiştir, containerı ayağa kaldırmadan önce siliniz.

Github üzerinden projeyi indiriyoruz ve docker compose ayağa kaldırıyoruz.
>    docker-compose up -d

İndirdikten sonra docker projemizin içinde bulunan www klasörünü phpstorm ile açalım.

Üst menüden edit configurations tıklayıp ilk önce docker-compose.yml dosyamızı ekliyoruz.

daha sonra phpxdebug ayarlarımızı ve server yolumuzu tanımlıyoruz.

En son bölümde xdebug için php.ini ye eklediğimiz tanımlar ve dockerfile da xdebug indirmemiz için gerekli kodlar bulunmaktadır. Bunları yapmanıza gerek yoktur. 
Github projesinde hazırdır. Sadece phpstorm tanımlamalarını yapınız.



Resimli Anlatım Blog Linki:https://hkmsmart.blogspot.com/2024/07/docker-php8-mysql8-phpmyadmin.html
