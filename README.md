# Bağıl Hafıza
"**Bağıl Hafıza**" , her uyandığı gün bir önceki günü unutan bir adamın karısının intikamını almaya çalıştığı bir **hikayeli** oyundur. Oyunda belirtilen basit görevleri yaparak hikayenin seni götürdüğü yere gidersin

## Animasyon Bilgilendirmesi
Normalde oyunda birçok animasyon bulunuyor fakat animasyonlar, birçok resimin birleşmesinden oluşuyor. Bu yüzden internete yüklediğimde doğru sonuç vermiyor. Fakat siz eğer bilgisayarınıza yükleyip aşağıdaki kısımda yorum satırlarını kaldırırsanız. Animasyonlar etkinleşecektir

    var  charAnimationFilesRight = [

    "./imgs/char1/1.png",
    
    /* "./imgs/char1/2.png",
    
    "./imgs/char1/3.png",
    
    "./imgs/char1/4.png",
    
    "./imgs/char1/5.png",
    
    "./imgs/char1/6.png",
    
    "./imgs/char1/7.png",
    
    "./imgs/char1/8.png",
    
    "./imgs/char1/9.png",
    
    "./imgs/char1/10.png",
    
    "./imgs/char1/11.png",
    
    "./imgs/char1/12.png",
    
    "./imgs/char1/13.png",
    
    "./imgs/char1/14.png",
    
    "./imgs/char1/15.png",
    
    "./imgs/char1/16.png",
    
    "./imgs/char1/17.png",
    
    "./imgs/char1/18.png",
    
    "./imgs/char1/19.png",
    
    "./imgs/char1/20.png",
    
    "./imgs/char1/21.png",
    
    "./imgs/char1/22.png"*/]
    
      
    
    var  charAnimationFilesLeft = [
    
    "./imgs/char3/1.png",
    
    /* "./imgs/char3/2.png",
    
    "./imgs/char3/3.png",
    
    "./imgs/char3/4.png",
    
    "./imgs/char3/5.png",
    
    "./imgs/char3/6.png",
    
    "./imgs/char3/7.png",
    
    "./imgs/char3/8.png",
    
    "./imgs/char3/9.png",
    
    "./imgs/char3/10.png",
    
    "./imgs/char3/11.png",
    
    "./imgs/char3/12.png",
    
    "./imgs/char3/13.png",
    
    "./imgs/char3/14.png",
    
    "./imgs/char3/15.png",
    
    "./imgs/char3/16.png",
    
    "./imgs/char3/17.png",
    
    "./imgs/char3/18.png",
    
    "./imgs/char3/19.png",
    
    "./imgs/char3/20.png",
    
    "./imgs/char3/21.png",
    
    "./imgs/char3/22.png"*/]
    
    //oda gorsel
    
    var  rooms = [
    
    "./imgs/roomm/roomm.png",
    
    /* "./imgs/roomm/roomm1.png",
    
    "./imgs/roomm/roomm2.png",
    
    "./imgs/roomm/roomm3.png",
    
    "./imgs/roomm/roomm4.png",
    
    "./imgs/roomm/roomm5.png",
    
    "./imgs/roomm/roomm6.png"*/
    
    ]
    
    //arac gorsel
    
    var  cars = [
    
    "imgs/car/1.png",
    
    /*"imgs/car/2.png",
    
    "imgs/car/3.png",
    
    "imgs/car/4.png",
    
    "imgs/car/5.png",
    
    "imgs/car/6.png",
    
    "imgs/car/7.png",
    
    "imgs/car/8.png",*/
    
    ]

# Dosyalar

 - index.html
 Bu dosya oyunun kodlarının yazıldığı içerisinde html,css, JavaScript barındıran ve hiçbir kütüphane içermeyen dosyadır
 
 - imgs
 Bu bir klasördür ve içerisinde oyunda kullanılan tüm resim materyallerini içerir
 - sounds
 Bu da bir klasördür ve oyunda kullanılan tüm sesleri içerir
 
 - Senaryo
Oyundaki senaryoyu ve oynanışı gösterir




## Nasıl Oynanır

Oyundaki ana karakter **A** ve **D** tuşları ile sağa sola gider. Etkileşime girilen cisimler mevcuttur ve bu cisimlerle  **E** tuşu ile etkileşime girebilirsin. Eğer arabaya binmişsen **Q** tuşu ile çıkabilirsin. Bir cisimle etkileşimi bitirmek istiyorsan **ESC** tuşuna basabilirsin.

## Oyun içi görüntüler

   ![Oyun Menu](https://github.com/Alidari/alidari.github.io/blob/c7e3134c8ca6ef7ac22442435393bdadcefe5ba1/imgs/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202023-05-15%20211414.png?raw=true)

![oyun ici](https://github.com/Alidari/alidari.github.io/blob/c7e3134c8ca6ef7ac22442435393bdadcefe5ba1/imgs/oyunici1%20%281%29.png?raw=true)
![oyun ici](https://github.com/Alidari/alidari.github.io/blob/c7e3134c8ca6ef7ac22442435393bdadcefe5ba1/imgs/oyunici1%20%282%29.png?raw=true)![enter image description here](https://github.com/Alidari/alidari.github.io/blob/master/imgs/oyunici2.png?raw=true)
![enter image description here](https://github.com/Alidari/alidari.github.io/blob/master/imgs/oyunici3.png?raw=true)
## SES

Oyunda bir çok konuşma, müzik ve sesli anlatım şekli yer alıyor. Oynarken sesi açmayı **unutmayınız**

## Oyun hızı

    var  speedGame = 5;
default olarak tanımlanmış oyun hızı bu hızdır. Eğer oyun size yavaş geldiyse hızlandırabilirsiniz
