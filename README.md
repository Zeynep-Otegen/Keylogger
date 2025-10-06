# Keylogger Simülasyonu (Eğitim Amaçlı Proje)
##  Video Gösterimi
Hocanın talebi üzerine test, arkadaşımın bilgisayarında gerçekleştirilmiş ve ekran kaydı alınmıştır. 
Link:https://youtu.be/cyv-1Fks1Mo
Bu videoda başka bilgisayarlarda çalışıp çalışmadığını anlamak için arkadaşım Meral Yavuztürk rızası alınmış olup onun bilgisayarında çekilmiştir.
##  Video İçeriği
-Video github repom üzerinden başlıyor ve karşı bilgisayara attığım zip dosyası önceden indirilmiş olup içinde olan .exe dosyası çalıştırılıyor.
-Ardından karşı taraf açtığı metin dosyasında 50 karaktere ulaşana kadar farklı ve rastgele tuşlara basıyor.
##  E-Mail Ekran Görüntüsü
-Aynı zaman içinde 50 karaktere ulaşan tuş kayıtları test için hazırlanan mail hesabına aktarılıyor.

<img width="1919" height="1079" alt="Ekran görüntüsü 2025-10-05 200948" src="https://github.com/user-attachments/assets/3ced5b4e-2c45-43db-8bb1-7d21edc93a40" />

-Tabiki de kodlarda da görüleceği üzere daha fazla ve farklı karakterler de kayıt edilebilir.

---

##  Proje Amacı
Bu proje, **tuş kaydı mantığını öğrenmek** ve **veri kaydı işlemini mail aktarımı üzerinde göstermek** amacıyla geliştirilmiştir.  
Gerçek bir keylogger değildir — yalnızca **izinli, eğitim amaçlı bir simülasyondur.**

Uygulama, yazılan karakterleri yerel bir kaydeder ve belirli bir karakter sınırına (50 karakter) ulaştığında belirli bir mail adresine gönderilir ve özel tuşlarla (ctrl+shift+herhang bir tuş) kendini kapatır.  
Herhangi bir gizli veriye veya kullanıcı izni olmadan sistem genelindeki tuşlara **erişmez.**

---

##  Etik ve Güvenlik Açıklaması
- Proje yalnızca **ders kapsamında eğitim amacıyla** hazırlanmıştır.  
- Uygulama **yalnızca test amaçlı** çalıştırılmıştır; herhangi bir gizlilik ihlali yapılmamıştır.  
- Test, **arkadaşımın açık rızasıyla** kendi bilgisayarında gerçekleştirilmiştir.  
- Gerçek şifreler, kişisel bilgiler veya sistem verileri hiçbir şekilde toplanmamıştır.  
- Projeye ait çalıştırılabilir dosya (`.exe` veya `.zip`) **bu repoda yer almamaktadır.**

---

##  Lisans ve Sorumluluk Reddi
Bu proje **tamamen eğitim amaçlıdır.**  
Gerçek kullanıcı verisi toplamak veya üçüncü kişilere zarar verecek amaçlarla kullanılması yasaktır.  
Yazar, projenin kötüye kullanımından sorumlu tutulamaz.

---

##  Gizli Bilgiler (.env Kullanımı)
Projede e-posta gönderimi gibi işlemler için test amacıyla bir Gmail hesabı kullanılmıştır.  
Bu bilgiler `.env` dosyasında saklanır ve **GitHub deposuna dahil edilmemiştir.**

**.env** : gmail şifresi içerir
## 🧹 Güvenli Teslim ve Temizlik
- `.env` dosyası GitHub’a yüklenmemiştir.  
- Test sonrası uygulama silinmiş, geçici dosyalar temizlenmiştir. 
**.gitignore** dosyasında bu dosya gizlenmiştir:

