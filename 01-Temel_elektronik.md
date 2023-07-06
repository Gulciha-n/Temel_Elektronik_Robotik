# Temel_Elektronik_Robotik

### Gerilim ve Akım :
Gerilim : Elektronların hareket edip elektriğin oluşması için gereken yükselti farkı. Birimi volt.
Akım : gerilim sonucunda iletken üzerinden elektrik yüklerinin(elektronların)hareketi. Bir noktadan bir anda geçen elektron miktarı. Birmi amper.

Prizde: alternative current (AC) = yönü ve şiddeti değişir. Depolanamaz.
AC = ölçümü yaparken + ve – önemi yok çünkü AC de yön ve şiddet değişiyor.

Pil , batarya : Direct current (DC) . Depolanabilir. 
Prizdeki bu gerilimi şarj cihazları istenilen değere sabitler. Çünkü cihazlarımızdaki pillerin gerilimi ile prizin gerilimi farklı.
Yalıtkanın gerilimi belli bir değerin üzerinde ise elektriği iletebilir. Yıldırımın havadan geçmesi gibi.

### Jumper kablo :
erkek-erkek=iki tarafta da pin var.
dişi-dişi = iki tarafta da pin yok.
Dişi-erkek = bir tarafta pin var diğer tarafta yok.
Crocodile kablo: pinler arası bağlantı için.

Kısa devre: iki veya daha fazla iletkenin doğrudan temas etmesidir. Bu, elektrik akımının normal akış yolu yerine doğrudan ve hızlı bir şekilde bu düşük dirençli yoldan geçmesine neden olur. Yüksek akım geçişi, kablolarda aşırı ısınmaya ve erimeye neden olabilir, bu da yangın riskini artırır. Ayrıca, kısa devre durumunda koruyucu devre kesiciler veya sigortalar devreye girerek akımı keser ve cihazları korur. Kısacası, kısa devre, normal akım yolundan saparak düşük dirençli bir yol boyunca geçen bir elektriksel hatadır.

### Potansiyometre:
Ayarlı direnç= üç ayağı var baştaki ve sondaki sabit bir değer verir ortadaki bacak ise ayarlanabilir direnci okuduğumuz yer olacak.

### 🕹 Joystick:
joystickteki hareketler ayarlanabililr direncin değrerini değiştirir. Bu değerlere göre de joystick’in hangi konumda olduğunu bir mikroişlemci , bir arduino sayesinde algılamış oluyoruz. En yukarda da buton var.


### Ölçü aleti: 
COM = bu kısma GND ucu bağlanır.(siyah kablo)
VΩmA  = bu kısımda miliamper cinsinden ölçüm yapabiliyoruz.(kırmızı kablo)
Diyot = bu kısımda iletim var mı yok mu kontrolü yapılır. Kısa devre yapılır yani iki iletken birbirine değdirilir gösterge sıfırı gösterir demek ki iletim var.
Direnç ölçümü = renk kodları her zaman tam olarak doğru gödtermeyebilir. Çünkü %5 ya da %10 toleranslı oluyor.
Paralel bağlı dirençlerde yol sayısı artıyor yani elektriğin geçebileceği alan artıyor bu yüzden direnç azalıyor. Seri bağlamada ise gidilen yol azalıyor bu yüzden direnç artıyor.

### Gerilim ölçme :
artı ve eksi uçlara dikkat ederek bağlamamız gerekiyor. Dirençlerde bunun önemi yoktu. COM ucunu eksiye V ucunu artıya bağlamamız gerekiyor. Ters bağlarsak değerin başına eksi işareti gelir.
 1 değerini gördüğümüzde aleti bir kademe daha artırıp ölçüm yaparız. Piller kullanıldıkça gerilim değerleri düşer.

### Isı sensörleri :
Isıya göre direnci değişen malzemelere ısı sensörleri denir. Bu malzemeler elektriksel iletkenliğini ısıya göre değiştirir bu yüzden bunları sensör olarak kullanabiliriz.
NTC-PTC Isı Sensörleri
NTC ve PTC, ısıya duyarlı dirençler olarak kullanılan iki farklı tür ısı sensörünü ifade eder.
1.	NTC (Negative Temperature Coefficient): NTC sensörleri, sıcaklık arttıkça direncin azaldığı (negatif bir sıcaklık katsayısına sahip olduğu) ısıya duyarlı dirençlerdir. NTC sensörler, sıcaklığın ölçülmesi veya kontrol edilmesi amacıyla kullanılır. Direnç değeri sıcaklıkla ters orantılı olarak değiştiği için, sıcaklık arttıkça direnç değeri azalır. Bu özellik, NTC sensörlerini sıcaklık değişimlerini algılamak ve ölçmek için ideal hale getirir.
2.	PTC (Positive Temperature Coefficient): PTC sensörleri ise sıcaklık arttıkça direncin arttığı (pozitif bir sıcaklık katsayısına sahip olduğu) ısıya duyarlı dirençlerdir. PTC sensörlerinin direnç değeri sıcaklık arttıkça artar, bu da sıcaklık değişimlerini tespit etmek için kullanılabilecekleri anlamına gelir. PTC sensörleri, aşırı ısınmaya karşı koruma, sıcaklık kontrolü ve akım sınırlama gibi uygulamalarda kullanılır.


### LM35 Isı Sensörü
Sıcaklığa bağlı olarak farklı gerilim değerleri ölçer.
LM35, sıcaklığı doğrudan analog bir voltaj çıkışıyla temsil eden bir lineer sıcaklık sensörüdür. Isıya duyarlı bir dirençten oluşur ve bu direnç, sıcaklığa bağlı olarak direnç değerini değiştirir. Sensör, sıcaklık arttıkça direncin de arttığı bir PTC yapısına sahiptir.


### LDR Işık Sensörü
LDR (Light Dependent Resistor), ışığa bağlı olarak direnci değişen bir sensördür. Farklı ışık seviyelerini algılamak ve ölçmek için kullanılır. Işık yoğunluğu arttıkça, LDR'nin direnci azalır; ışık yoğunluğu azaldıkça ise direnci artar.

### NTC ve PTC , ısıya göre direnci değişen maddeler, LDR ışığa göre direnci değişen maddelerdir.


### Renk sensörü :
Renk sensörleri, çevredeki renkleri algılamak ve bu bilgiyi elektronik sinyallere dönüştürmek için kullanılan özel cihazlardır. Renk sensörleri genellikle optik sensörler veya görüntü sensörleri olarak da adlandırılır. 
1. Işık Kaynağı: Renk sensörleri, örnekleme yapacakları nesneye (genelde beyaz) ışık gönderirler. Işık kaynağı genellikle LED'lerden oluşur ve çeşitli renklerde ışık yayabilir. Bu ışık kaynağı, nesnenin üzerine düşen ışığı yansıtarak ya da nesne tarafından emilerek çalışır.
2. Algılama: Renk sensörleri, nesneden yansıyan veya emilen ışığı algılamak için bir algılayıcı veya sensör kullanır. Algılayıcı, ışığın farklı dalga boylarını algılamak için özel bir filtre veya fotodiyot dizisi kullanır.
3. Renk Algılama: Algılayıcı, farklı dalga boylarındaki ışığın yoğunluğunu veya frekansını ölçer. Bu, her bir renk için farklı bir sinyal üretir. Örneğin, kırmızı renkli bir nesne algılandığında, kırmızı ışığın yoğunluğunu veya frekansını ölçen bir sinyal üretilir.
4. Veri İşleme: Algılayıcı tarafından elde edilen renk bilgileri, renk sensörü içindeki işlem birimine iletilir. Bu işlem birimi, renk bilgisini analiz eder ve önceden tanımlanmış renklerle karşılaştırarak belirli bir renk değerini belirler. Bu işlem genellikle mikrodenetleyici veya diğer benzer bir cihaz tarafından gerçekleştirilir.

5. Çıkış: Renk sensörü, belirlenen renk değerini çıkış olarak sağlar. Bu çıkış, dijital veya analog bir sinyal olabilir ve başka bir cihaza aktarılabilir. Renk sensörünün çıkışı, algılanan renge bağlı olarak belirli bir aksiyonu tetiklemek veya renk bilgisini kullanmak için kullanılabilir.

Renk sensörleri, endüstriyel otomasyon, renk eşleme, renkli baskı, robotik ve daha birçok uygulama alanında kullanılır. Temel olarak, renk sensörleri ışığı algılayarak ve renk bilgisini işleyerek çevredeki renkleri belirlemek için tasarlanmıştır.

### Hareket sensörleri:
1. PIR (Passive Infrared) Hareket Sensörleri:
   - PIR sensörleri, bir veya daha fazla PIR detektöründen oluşur. Bu detektörler, piroelektrik malzemelerden yapılmış küçük sensörlerdir.
   - PIR sensörleri, piroelektrik malzemelerin ısı enerjisini algılayarak elektrik sinyalleri üretmesini kullanır. Bu malzemeler, insan veya hayvan gibi hareket eden nesnelerin yaydığı kızılötesi (infrared) ışınları algılar.
   - Sensördeki lens, ışığı algılamak için bir odaklama yapar ve algılanacak alana yönlendirir. Lensin arkasında yer alan PIR detektörü, ısı değişikliklerini algılar ve bunu elektrik sinyallerine dönüştürür.
   - Algılanan hareket, sensörün çıkışında bir değişikliğe yol açar ve bu değişiklik, başka bir cihaza veya kontrol mekanizmasına iletilerek uygun bir tepki tetiklenebilir.


### Güneş pilleri 
Üzerine düşen ışığı , koparılan elektron sayesinde elektriğe dönüştürür. Güneş pilleri, güneş ışınlarını emerek içerdikleri yarıiletken malzemelerdeki elektronları uyarır. Bu uyarılmış elektronlar, serbest hale gelir ve belirli bir yönde akar. Bu elektron akışı, bir devre üzerinde elektrik akımı oluşturur ve güneş pili elektrik enerjisi üretir. Yani, güneş pilleri güneş enerjisini doğrudan elektrik enerjisine dönüştürürler.

Kızılötesi (IR) ışık sensörleri, çevredeki kızılötesi ışığı algılayarak elektriksel sinyaller üretir. Bu sinyaller, sensör üzerindeki fotodiyot veya fototransistör gibi özel yarıiletken bileşenlerin kızılötesi ışığa verdiği tepkiye dayanır. Algılanan kızılötesi ışık seviyesine bağlı olarak, sensör çıkışı değişir. Bu çıkış, genellikle bir mikrodenetleyici veya başka bir cihaz tarafından işlenir. Kızılötesi ışık sensörleri, uzaktan kumandalar, hareket sensörleri ve otomatik aydınlatma sistemleri gibi birçok uygulamada kullanılır.



### Buzzer 
Piezoelektrik malzeme = herhangi bir fiziksel etki ile uçlarında enerji oluşan malzemelerdir.
Piezoelektrik buzzerlar, piezoelektrik etkiyi kullanarak çalışan ses üreten bileşenlerdir. Piezoelektrik malzemeler, mekanik gerilim veya elektrik yükleriyle etkileşerek ses titreşimleri oluştururlar. 
Buzzer, elektrik sinyallerini ses sinyallerine dönüştüren bir elektronik bileşendir. Genellikle küçük bir hoparlör olarak da düşünülebilir. Buzzerlar, sesli uyarılar, alarm sistemleri, çeşitli elektronik cihazlar ve projelerde kullanılır.
Buzzer'ın iki bacağı vardır - pozitif (+) ve negatif (-). Pozitif bacağını güç kaynağının pozitif (+) uçuna bağlayın ve negatif bacağını güç kaynağının negatif (-) uçuna bağlayın. Buzzer'ın çalışması için uygun bir gerilim (genellikle 5V veya 12V) sağlamalısınız.


### Ultrasonik sensörler :
ses dalgalarını kullanarak mesafe ölçümü yapabilen cihazlardır. Bir ultrasonik sensör, yüksek frekanslı ses dalgaları gönderir ve bu dalgaların yansımalarını alarak nesnenin mesafesini hesaplar.
Sensör, ses dalgalarını gönderir ve bu dalgalar nesneye çarpar. Ardından, dalgaların yansımaları sensöre geri döner. Sensör, gönderilen ve alınan dalgalar arasındaki zaman farkını hesaplayarak nesnenin mesafesini belirler genellikle Arduino veya diğer mikrodenetleyici tabanlı projelerde mesafe ölçümü, engel algılama, varlık tespiti gibi uygulamalarda kullanılır kullanılabilirler.
Trig :Gelen sesi algilayıp ses üreten kısma gönderir.
Echo :sensörden üretilip engele çarpan veriyi tekrar sensöre getirir.

