Oculus Quest 2 Usb OTG wiki'ye hoşgeldiniz!

Oculus Quest 2 sahibi olanlar için bu makalede usb ile nasıl film yüklenir ve izlenir konusunu aydınlığa kavuşturacağız.

Öncelikle "oculus" uygulamasını telefonunuzda açıp "Cihazlar" bölümünden Oculus cihazınızı gördüğünüzde "Gelitirici Modu" Seçeneğine giriniz. Ekrana gelen menüden "Geliştirici Modu" Seçeneğinin sağında bulunan butonu aktif ediniz.

Eelinizdeki bilgisayara göre aşağıdaki adresten "Platform Tools" indiriniz.

https://developer.android.com/studio/releases/platform-tools

Ardından Oculus Quest 2 cihazınızı type-c to type-c veya type-c to usb kablosu ile bilgisayarınıza bağlayınız.

Bağlantı esnasında gözlüğünüzü takınız ve bilgisayara izin verilsin mi sorunusunu onaylayınız. 

Ardından Mac için komut satırını açınız ve "platform-tools" klasörü hangi dizin içerisinde ise oraya giriniz ve ardından aşağıdaki komutu yazınız.

./adb devices 

yukarıdaki komutu yazdığınızda aşağıdaki gibi bir çıktı alıyorsanız gözlükle haberleşmemiz gerçekleşmiş demektir.

List of devices attached
1XXXXX37EXX023	device

Bu adımdan sonra aşağıdaki linkden "file-manager_2.6.6(2100266).apk" dosyasını bilgisayarınıza indirin ve platform-tools klasörünün içerisine taşıyın.

https://apkcombo.com/tr-tr/apk-downloader/?device=&arches=&sdkInt=&sa=1&lang=en&dpi=480&q=com.alphainventor.filemanager

ardından tekrar komut satırı ekranına dönün ve aşağıdaki  komutu yazın.

./adb install file-manager_2.6.6(2100266).apk

yukarıdaki komutu çalıştırdığınızda almanı gereken mesaj aşağıdaki gibidir.

Performing Streamed Install
Success

Artık type-c to usb otg kablosu ile cihaza bağladığınız usb diskin içini görebilmeniz için gereken uygulama cihazınıza yüklenmiştir.

Yukarıdaki adımlar windows ve linux içinde geçerlidir. 

Oculus gözlüğünüzü taktığınızda "Uygulamalar" Kısmına girdiğinizde yüklenen uygulamayı göremeyeceksiniz. Sağ üst kısımda bulunan "Tümü" Seçeneğine tıkladığınızda en altta bulunan "Bilinmeyen Kaynaklar" seçeneğini seçtiğinizde yüklediğiniz uygulamayı görebileceksiniz.

Teşekkürler.

