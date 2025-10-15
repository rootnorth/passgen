🔐 PASSGEN

UYARI: .ENC UZANTILI DOSYANIN DEĞİŞTİRİLMESİ VEYA SİLİNMESİ SONUCU GÜVENLİK NEDENİYLE PROGRAM KENDİ KENDİNİN ŞİFRELERİNİ YOK EDECEK

Basit Şifre Yöneticisi ve Üreticisi
MADE WITH ❤
👥 Katkıda Bulunanlar
- [@rootnorth](https://github.com/rootnorth) — Kodlama, şifre üretim mantığı
- [@haretor](https://github.com/haretor) — Yapı, test ve dökümantasyon

 & @haretor

🧩 Genel Bakış

PASSGEN, Python ile yazılmış, tamamen terminal üzerinden çalışan bir şifre oluşturma ve yönetim aracıdır.
Yeni sürüm, şifrelerinizi güvenli biçimde saklamak için şifreleme (encryption) desteği ve otomatik requirements.bat başlatma özelliğiyle güçlendirilmiştir.

🚀 Özellikler

✅ Güçlü, rastgele şifre üretimi

Python’un secrets modülü ile gerçek rastgelelik (kriptografik güvenli).

✅ Farklı karakter setleri desteği

Harfler, rakamlar, semboller isteğe göre kombinlenebilir.

✅ Şifrelenmiş veri saklama

Tüm kayıtlar artık passwords.enc dosyasında şifrelenmiş olarak tutulur.

Şifreleme, kullanıcı tarafından belirlenen bir master parola ile yapılır.

✅ requirements.bat otomatik çalıştırma

Program, başlatıldığında aynı klasörde bulunan requirements.bat dosyasını otomatik olarak çalıştırır.

Bu sayede gerekli bağımlılıklar (örn. cryptography) kolayca yüklenebilir.

✅ JSON tabanlı veri yapısı (şifrelenmeden önce)

Şifreler düzenli bir yapıda saklanır, gerektiğinde çözülebilir.

✅ Terminal tabanlı menü sistemi

Kullanıcı dostu, basit ama güçlü menü arayüzü.

🧱 Kurulum
windows için:
projenin detaylarındaki py ve bat dosyalarını indirin.

linux için:
Projeyi klonlayın:

git clone https://github.com/rootnorth/passgen
cd passgen


Python 3.7+ sürümünün kurulu olduğundan emin olun.

1️⃣ Gerekli bağımlılıkları yükleyin

Eğer requirements.bat dosyası varsa, program açıldığında otomatik olarak çalışacaktır.
Manuel yüklemek isterseniz:

pip install cryptography

2️⃣ Programı çalıştırın
python passgen.py

💡 Kullanım

Program açıldığında ilk olarak master parola ister.
Bu parola, şifreleme/çözme için kullanılır ve unutulmamalıdır.

Ardından ana menü gelir:

PASSGEN BY ROOTNORTH, HARETOR

Menu:
 1) Şifre Oluştur
 2) Kaydedilmiş şifreleri göster
 3) Çıkış

🔸 1) Şifre Oluştur

Site adı ve kullanıcı adı girilir.

Şifre uzunluğu ve karakter seti seçilir.

Şifre üretilir ve şifrelenmiş şekilde diske kaydedilir (passwords.enc).

🔸 2) Kaydedilmiş Şifreleri Göster

Şifrelenmiş dosya çözülür (master parola ile).

Tüm kayıtlar listelenir, detay görmek için numara seçilebilir.

🔸 3) Çıkış

Program güvenli şekilde kapanır.

Veriler diskte şifreli kalır.

🔐 Teknik Detaylar

secrets modülü: Rastgele ve güçlü parola üretimi.

cryptography (Fernet): AES tabanlı dosya şifreleme/çözme.

json: Veri formatı düzeni.

subprocess: Program açılışında requirements.bat çalıştırma.

os, datetime, string: Sistem, zaman ve karakter işlemleri.

Karakter seti seçenekleri:
Seçim	Açıklama
letters	Sadece harfler
letters_digits	Harf + rakam
all	Harf + rakam + semboller (varsayılan)
⚠️ Güvenlik Uyarısı

Bu proje öğrenme ve kişisel kullanım amaçlıdır.
Gerçek ortamlarda:

Master parolanızı kimseyle paylaşmayın.

passwords.enc dosyasını yedekleyin ama güvenli ortamda saklayın.

passwords.json dosyasını asla GitHub’a yüklemeyin.

.gitignore dosyasına ekleyin:

passwords.json
passwords.enc

📄 Lisans

Bu proje MIT Lisansı altında yayınlanmıştır.
Kod serbestçe kullanılabilir, geliştirilebilir ve dağıtılabilir.

İstersen buna uygun olarak .gitignore ve requirements.bat içeriğini de sana hazırlayayım — requirements.bat dosyasında otomatik olarak pip install cryptography komutu çalışsın.
Hazırlayayım mı?
