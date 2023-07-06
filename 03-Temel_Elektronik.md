## Temel Elektronik 
### Motorlar :
Motor herhangi bir enerji türünün mekanik enerjiye dönüşmesini sağlayan malzemedir.
Elektrik Motorları: Elektrik enerjisini manyetik alanlar ve elektromanyetik kuvvetler aracılığıyla mekanik harekete dönüştüren motorlardır. DC motorlar ve AC motorlar gibi alt kategorilere ayrılabilir.

### DC motorları:
DC motorları, doğru akım (DC) elektrik enerjisini mekanik enerjiye dönüştüren motorlardır. DC motorlar, manyetik alan ve elektromanyetik kuvvetlerin etkileşimiyle çalışır(doğru akım). DC motorların iç yapısı bir doğal mıknatıs ile bizim elektriklendirdiğimiz (bobinle oluşturduğumuz) mıknatısları birbirlerine uygun konumlandırdığımızda bir hareket sağlanır bu da elektrik motorunu oluşturur.
Bobinler demir üzerine sarılır bunun nedeni bakır iletkeninin manyetik alanı kuvvetlendirmektir. Bu sayede çok daha fazla manyetik alan üretir.

### Manyetik Alan: 
manyetik bir kaynaktan yayılan ve manyetik etkileşimlere neden olan bir alan olarak tanımlanır. Manyetik alan, elektromanyetik kuvvetin var olmasını sağlar
### Elektromanyetik Kuvvet:
elektrik yüklerinin manyetik alanlarda etkileşime girdiği kuvvettir. Manyetik alan, elektromanyetik kuvvetin var olmasını sağlar.


![Temel Elektronik ve Robotiğe Giriş - Google Chrome 7_6_2023 5_55_28 PM](https://github.com/Gulciha-n/Temel_Elektronik_Robotik/assets/120305183/0782322b-7c3c-498f-9d3d-36ba47010050)



### Redüktörlü motorlar:
motor redüktör ve dişlilerden oluşur. motorun çıkış hızını azaltmak veya torkunu artırmak için kullanılan bir dişli mekanizmasıyla birleştirilmiş motorlardır. Redüktörlü motorlar, yüksek hızda dönen bir motorun çıkışını düşük hıza veya yüksek torka (yüksek tork = güç) dönüştürmek için tasarlanmıştır.
### Titreşim motorları : 
dc motorun ucuna dengesiz bir yük yerleştirerek oluşturulabilir.

### Servo motorlar: 
belirlenen bir açıya göre hareket eden DC motorlardır. 180 veya 360 derece olabilir. Servo motorlar, belirli bir konuma hassas bir şekilde dönebilme yeteneğine sahiptir.
### PWM :
puls width modulation. 0 ve 1 lerden oluşan dijital sinyalin belirli bir süre içerisinde ne kadar 0 ne kadar 1 içeriyor buna bakarak servo motor  bunu anlamdırıp hareket edecektir.
Hangi derecenin kaç PWM e denk geleceği: (örn: 90 derece için iki tane 1.5 ms)



![Temel Elektronik ve Robotiğe Giriş - Google Chrome 7_6_2023 7_01_49 PM](https://github.com/Gulciha-n/Temel_Elektronik_Robotik/assets/120305183/c85d4793-03de-4bd0-b929-fc8657910ffa)



### PWM Sinyali:
Servo motorun kontrol edilmesi için bir PWM (Darbe Genişlik Modülasyonu) sinyali kullanılır. Yani gödeerdiğimiz veri PWM sinyali şeklindedir. PWM sinyali, darbe genişliğinin değiştirilmesiyle motorun konumunu ve hızını kontrol etmek için kullanılır.

Servo motoru çalıştırabilmek için sadece + ve – ile hareket ettiremeyiz yanında bilgi içeren bir veri göndermemiz gerekiyor bu veriyi de PWM sinyali ile gönderiyoruz. Hangi açı ile dönmesini istiyorsak ona göre bir veri göndermemiz gerekiyor. 
Kahverengi kablo = GND
Kırmızı kablo = VCC
Sarı ya da turuncu kablo = PWM 

### Step motorları :
belirli açılarla hareket eder her bir step belirli bir açıya tekabül eder. DC motordan farkı sürekli hareket etmez bizim verdiğimiz sinyale göre adım adım hareket eder.
Step motorlar, dijital giriş sinyalleriyle kontrol edilir ve adımlar arasındaki dönme açısını kontrol etmek için belirli bir adım açısı kullanırlar.
Bobinlere verdiğimiz elektriklenme sonucunda ortada bulunan mıknatıs açısal olarak hareket eder. 


### KONDANSATÖRLER :
Gerilim depolar. 
iki iletken levha arasında bir yalıtkan malzemeden oluşan devre elemanlarıdır. Devre içerisinde kısa süreliğine gerilim depolayıp şarjlı bir pil gibi üzerinde gerilim bulundurur. Yönlü ya da yönsüz olabilir.  Farad , kondansatörün elektrik depolama birimidir. 
Bobin ile zıt çalışır. Bobin akım depolaması yaparken kondansatör gerilim depolaması yapar.

### LCD ekranlar : 
LCD ekranlarda, piksellerin kontrolü için genellikle + (pozitif) ve - (negatif) elektrotlar kullanılır. Bu elektrotlar, elektrik sinyallerinin iletilmesini sağlar. Piksellerdeki sıvı kristallerin hizalanması, bu elektrik sinyalleriyle kontrol edilir. Elektrotlara uygulanan voltaj düzeyleri, sıvı kristallerin şekil değiştirmesini ve ışığın geçişini etkiler. Böylece, + ve - elektrotlar arasındaki etkileşim, piksellerin sıvı kristallerinin hizalanmasını kontrol ederek görüntü oluşturulmasını sağlar. Bu nedenle, + ve - elektrotların birbirini çekmesi veya itmesi LCD ekranların çalışma mantığıyla ilişkilidir.



![Temel Elektronik ve Robotiğe Giriş - Google Chrome 7_6_2023 7_41_01 PM](https://github.com/Gulciha-n/Temel_Elektronik_Robotik/assets/120305183/566ee25b-6b60-406f-ad16-fb0b00c86053)


### SD kart modülü:
Veri kaydetme veya veri okuma gibi uygulamalarda kullanılır. 
SD (Secure Digital) bellek kartlarını okumak ve yazmak için kullanılan elektronik bileşenlerdir. Bu modüller, mikrodenetleyiciler veya bilgisayarlarla iletişim kurarak veri depolama işlevi görürler. İşlevsel olarak, SD kart modülleri genellikle bir kart yuvası ve bir iletişim arayüzünden oluşur.
SD kart modüllerinin temel özellikleri şunlardır:
1. Kart Yuvası: Bu yuva, SD kartının fiziksel olarak bağlanmasını sağlar.
2. İletişim Arayüzü: mikrodenetleyiciler veya bilgisayarlarla iletişim kurmak için bir iletişim arayüzüne sahiptirler.
3. Veri Aktarımı: SD kart modülleri, SD kartlarındaki verileri okumak ve yazmak için veri aktarımı işlevine sahiptirler. Bu sayede, verilerin depolandığı SD kartları okuyabilir ve üzerlerine yeni veriler yazabilirler.
4. Güç Beslemesi: SD kart modülleri, genellikle 3.3V veya 5V gibi bir güç kaynağından çalışır. Bu güç kaynağı, modülün kendisini ve takılı olan SD kartı besler.



### DİYOT:
Diyotlar, elektrik akımının sadece bir yönde akmasına izin veren bir tek yönlü geçirgenlik özelliğine sahiptir. Bir diyot, doğru yönde bağlandığında (anot pozitif, katot negatif) akımı geçirirken, ters yönde bağlandığında (anot negatif, katot pozitif) akımın geçmesini engeller.
 

### Transistör :
iki diyotun seri ve ters bir şekilde bir araya gelmesi ile oluşmuştur. Elektronik devrelerde sinyalleri kontrol etmek, yükseltmek veya anahtarlama işlemlerini gerçekleştirmek için kullanılan yarıiletken bir bileşendir. Transistörler, üç bacağı olan bir yapıya sahiptir.
Transistörler, bir sinyali yükseltmek veya zayıflatmak için kullanılabilir. Örneğin, bir ses sinyalini güçlendirmek için kullanılan bir ses yükselteci transistörler içerir. Elektronik devrelerde mantıksal işlemleri gerçekleştirmek, sinyalleri anahtarlama, analog sinyalleri dijital sinyallere dönüştürme gibi birçok işlevde transistörler kullanılır.
PNP ve NPN olarak iiki türü vardır.

### KABLOSUZ HABERLEŞME:
İki cihaz arasındaki iletişim, elektromanyetik dalgaların kullanılmasıyla sağlanır.
Bluetooth, NRF(radyo frekansı) , ESP(Wi-Fi)
Bluetooth: Kısa mesafeli iletişim için tasarlanmıştır ve düşük güç tüketimi ile çalışır. Aynı anda tek cihaza bağlanabilir. Bluetooth, cihazların birbirleriyle kablosuz olarak bağlantı kurmasını ve veri transferi yapmasını sağlar. Genellikle akıllı telefonlar, bilgisayarlar, hoparlörler, kulaklıklar ve diğer elektronik cihazlar arasında kullanılır.

TX= transfer    ,  RX = receive  

![Temel Elektronik ve Robotiğe Giriş - Google Chrome 7_6_2023 9_12_02 PM](https://github.com/Gulciha-n/Temel_Elektronik_Robotik/assets/120305183/f4cf2aef-fc10-47c4-b3d0-670800dfc19d)


![Temel Elektronik ve Robotiğe Giriş - Google Chrome 7_6_2023 9_15_49 PM](https://github.com/Gulciha-n/Temel_Elektronik_Robotik/assets/120305183/51fddb26-91f4-4249-a325-2be7ad63d91a)



### NRF (Nordic RF):
Düşük güç tüketimi ve yüksek performans sağlar. Özellikle IoT (nesnelerin interneti) projelerinde yaygın olarak kullanılan NRF, sensörler, uzaktan kumandalar, kablosuz ağlar ve diğer kablosuz iletişim uygulamalarında tercih edilir.ortalama 100 metre. Aynı anda 126 cihaza bağlanabilir.

### ESP (Espressif Wi-Fi): 
Wi-Fi çözümlerini içeren bir dizi mikrodenetleyici ve modüldür. ESP mikrodenetleyicileri, Wi-Fi bağlantısı sağlayarak internete erişim imkanı sunar. ESP8266 ,bir Wi-Fi a bağlanıp TCP/IP protokolü ile haberleşme sağlar bu sayede internete veri gönderip veri alabiliriz.  IoT projelerinde, akıllı ev sistemlerinde, sensör ağlarında ve diğer Wi-Fi tabanlı uygulamalarda kullanılır. ESP mikrodenetleyicileri, düşük maliyetleri ve geniş işlevsellikleri nedeniyle geniş bir geliştirici topluluğuna sahiptir.

Geliştirme kartları içerisinde mikroişlemci bulunur.
içerisine yüklediğimiz kodları çalıştırabileceğimiz malzemelerdir. 
Micro:bit =: BBC tarafından geliştirilen ve eğitim amaçlı kullanılan bir mikrodenetleyici geliştirme kartıdır. Python, JavaScript veya blok tabanlı programlama dilleri kullanılarak programlanabilir. Kullanıcılar, Micro:bit üzerindeki sensörleri okuyabilir, LED'leri kontrol edebilir, hareket sensörü ve pusula gibi özelliklerden faydalanabilir, ses ve müzik çalabilir, kablosuz iletişim kurabilir ve daha pek çok işlem gerçekleştirebilir.


