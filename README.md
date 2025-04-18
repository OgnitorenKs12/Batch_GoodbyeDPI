#### Prepared by: Hüseyin UZUNYAYLA / OgnitorenKs
- ► Mail: ognitorenks@gmail.com
- ► Site: [https://ognitorenks.blospot.com](https://ognitorenks.blospot.com)
- Supported languages = English │ Turkish

# GoodbyeDPI │ OgnitorenKs
• GoodbyeDPI uygulamasının batch script ile arayüzlendirilmiş halidir. GoodbyeDPI'ın amacı devletin kendi sınırları içinde yasakladığı adreslere VPN olmadan erişmenizi sağlamasıdır. Normalde bu yasaklar internet servis sağlayıcısının DNS adresinde uygulanır siz DNS adresi değiştirince sorunsuz kullanmaya devam edersiniz. Ancak DNS değiştirme yöntemi tek başına çoğu internet servis sağlayıcısında çalışmıyor. Çünkü her ne kadar DNS adresi değiştirilse bile veriler internet servis sağlayıcınızın sunucuları üzerinden iletiliyor. Sunucularda yapılan "Derin Paket İncelenmesi" yöntemiyle yasaklı siteler engellenmeye devam ediyor. İşte GoodbyeDPI uygulaması tam olarak burada işimize yarıyor. Derin Paket İncelemesini atlatmak için verileri küçük paketlere bölerek yollar. Derin Paket İncelemesi de ne olduğunu anlayamadığı için yasaklama yapmaz. Böylece sitelere doğrudan erişme imkanınız olur. 

• GoodbyeDPI ile bu şekilde özgür bir internet deneyimi yaşamanız için programın her zaman çalışması gerekiyor. Bundan dolayı uygulamayı indirip kullanmak isterseniz. Silinmeyecek bir konuma almanız gerekmektedir. Ancak bu uygulamayı hizmet olarak yükleyip her açılışta çalışacak şekilde ayarladığımız için çalıştığını yalnızda Görev yöneticisinde göreceksiniz. 1 MB bile bulmayan RAM kullanımı vardır.

• GoodbyeDPI uygulaması benim yaptığım bir uygulama değildir. Ben sadece uygulamanın arayüzlü bir şekilde kurulup, yönetilmesi için batch script ile bir yönetim programı hazırladım. Uygulamanın resmi adresi= https://github.com/ValdikSS/GoodbyeDPI

### UYARI
• Daha önce ulaşabildiğiniz ancak GoodbyeDPI ile giremediğiniz site/oyun/uygulama olursa GoodbyeDPI devre dışı bırakıp kontrol edin.
• GoodbyeDPI, VPN'ler ile uyumlu çalışmaz. Herhangi bir VPN'e bağlanmanız gerekirse GoodbyeDPI'a durdur/devre dışı bırak/kaldır seçeneklerinden uygun olan işlemi yapmanız gerekmektedir.
• Programı tamamen silmek istediğinizde klasör silinmez ve hata verirse Unlocker programını yükledikten sonra klasöre sağ tıklayın ve Unlocker simgesine tıklayın. Daha sonra görseldeki gibi silme işlemini yapın. https://www.iobit.com/en/iobit-unlocker.php
![Repo1](https://raw.githubusercontent.com/OgnitorenKs12/Batch_GoodbyeDPI/main/.github/SS/TR0.png)

### Kurulum
Öncelikle programı indirip silinmeyecek bir konuma atınız. Klasör yolunda Türkçe harf ve boşluk olmasın.
Uygulamayı yönetici olarak çalıştırın.
Uygulama öncelikle sistemde GoodbyeDPI adında hizmetin kurulu olup olmadığını kontrol edecek. Yüklü değilse kurulum ekranına yönlendirecek. Hizmet olarak kurulum için 1 tuşlayıp, enter tuşuna basın.
![Repo1](https://raw.githubusercontent.com/OgnitorenKs12/Batch_GoodbyeDPI/main/.github/SS/TR1.png)
DNS adresi seçmenizi isteyecek uygulama içine Claudflare ve Google'ın DNS adreslerini ekledim. Birini tuşlayın ilerleyin. Kurulum işleminin bitmesini bekleyin.
![Repo2](https://raw.githubusercontent.com/OgnitorenKs12/Batch_GoodbyeDPI/main/.github/SS/TR2.png)
Kurulum işlemi bitince sizi hizmeti yöneteceğiniz menüye aktaracak. Bu menünün üst bölümünde hizmetin çalışma durumu hakkında bilgi vermektedir.
![Repo3](https://raw.githubusercontent.com/OgnitorenKs12/Batch_GoodbyeDPI/main/.github/SS/TR3.png)
Çalıştır: Hizmeti yeniden çalıştırmanızı sağlar. Durdur ve devre dışı bırak fonksiyonlarında sonra kullanabilirsiniz. Üst menüdeki bilgi ekranı yukarı görseldeki gibi olur.
Durdur: Hizmeti durdurur, sistemi yeniden başlattığınızda veya çalıştır bölümünü uyguladığınızda aktifleşir. Üst menüdeki bilgi ekranı aşağıdaki gibi olur.
![Repo4](https://raw.githubusercontent.com/OgnitorenKs12/Batch_GoodbyeDPI/main/.github/SS/TR4.png)
Devre dışı bırak: Hizmeti devre dışı bırakır. Sistem yeniden başlasa dahi açılmaz. Uygulama içinden çalıştır seçeneğiyle aktifleştirebilirsiniz. Üst menüdeki bilgi ekranı aşağıdaki gibi olur.
![Repo5](https://raw.githubusercontent.com/OgnitorenKs12/Batch_GoodbyeDPI/main/.github/SS/TR5.png)
Kaldır: Hizmeti siler ve yönetim menüsünden sizi kurulum menüsüne aktarır.