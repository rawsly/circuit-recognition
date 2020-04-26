
# Circuit Recognition

Projeyi çalıştırmak için:

 - https://nodejs.org/en/ adresine girip Node.js kurulmalı.
 
 - NodeJS'in yüklendiğinden emin olmak için Windows ise CMD'yi, MacOS veya Linux'ta terminale şu komutlar yazılmalı:
 
  `node --version`
  
  `npm --version`
  
  Bu komutlar ayrı ayrı yazıldıktan sonra node ve npm versiyonlarını yazdıracaktır.
  
  - CMD'yi (Terminali) yönetici moduyla (CMD'ye sağ tıklayınca yönetici modu ile açılması için buton var.) açıp şu komut yazılmalı:
  
  `npm install -g http-server`
  
  - Projeyi indirdikten sonra Visual Studio Code gibi bir code editörü ile projeyi açılmalı.
  
  - Eğer Visual Studio Code kullanıldıysa "CTRL + " (tırnak)" kombinasyonu ile VSCode içinde bulunan terminal açılmalı. Terminale şu komut yazılmalı:
  
  `http-server -p 8000`
  
  Bu komut "http://localhost:8000" adresinde bir port açacak ve proje bu portta çalışacaktır.

Projeyi hiç açmadan da çalıştırabilirsin. CMD'yi açıp projenin olduğu dizine git. Örneğin:

![enter image description here](https://i.imgur.com/U6VPksb.png)

**Not:** Mailde paylaştığın dosyaların isimleri aslında tutorial'da gösterilenlerle uyuşmalı. Örneğin, dosyanın adı **model.json** olması lazım.

 Modelin doğru çalışması için bu çok önemli. Sanırım senin gönderdiklerinin önünde uzunca bir mesaj var. Şöyle mesela:

>  model-export_iod_tf_js-Circuits_2_20200206030136-2020-03-04T19_37_11.660Z_**group1-shard2of3.bin**
> --> group1-shard2of3.bin

 şeklinde olmalı.
