# passgen
🔐 PASSGEN – Basit Şifre Yöneticisi ve Üreticisi
GELİŞTİRİCİLERİMİZ METNİN EN ALTINDADIR MADE WITH ❤

PASSGEN, Python ile yazılmış bir şifre oluşturma ve yönetim aracıdır.
Kullanıcı dostu terminal arayüzü sayesinde güçlü şifreler üretip yerel olarak güvenli bir şekilde saklamanıza olanak tanır.

🚀 Özellikler

✅ Güçlü, rastgele şifre üretimi (secrets modülü ile)

✅ Harf, rakam ve sembol kombinasyonlarını destekler

✅ Üretilen şifreleri JSON dosyasında saklar (passwords.json)

✅ Kaydedilmiş şifreleri görüntüleme ve detaylarına erişim

✅ Basit, terminal tabanlı menü sistemi

🧩 Kurulum

Bu projeyi klonlayın:

git clone https://github.com/kullaniciadi/passgen.git

cd passgen


Python 3.7+ sürümünüzün kurulu olduğundan emin olun.
Gerekirse Python’un resmi sitesinden
 yükleyebilirsiniz.

Programı çalıştırın:

python passgen.py

💡 Kullanım

Program çalıştığında üç ana seçenek sunar:

PASSGEN BY ROOTNORTH, HARETOR

Menu:
 1) Şifre Oluştur
 2) Kaydedilmiş şifreleri göster
 3) Çıkış

🔸 1) Şifre Oluştur

Site adı / kullanıcı adı girilir.

Şifre uzunluğu ve karakter seti seçilir.

Şifre otomatik oluşturulur ve passwords.json dosyasına kaydedilir.

🔸 2) Kaydedilmiş Şifreleri Göster

Daha önce oluşturulmuş tüm kayıtları listeler.

Detay görmek için numara girilebilir.

🔸 3) Çıkış

Programdan güvenli şekilde çıkış yapılır.

🧱 Teknik Detaylar

Şifre üretimi secrets modülü ile yapılır (kriptografik olarak güvenli).

Veriler passwords.json adlı dosyada JSON formatında tutulur.

Karakter seti seçenekleri:

letters → Sadece harfler

letters_digits → Harf + rakam

all → Harf + rakam + semboller (varsayılan)

⚠️ Güvenlik Uyarısı

Bu proje öğrenme ve kişisel kullanım amaçlıdır.
Gerçek üretim ortamlarında şifreleri düz metin halinde saklamak önerilmez.
Daha güvenli bir sistem için:

Şifreleri şifreleyerek (örn. cryptography kütüphanesi ile) saklayın.

passwords.json dosyasını versiyon kontrolüne dahil etmeyin.

👨‍💻 Geliştiriciler

## 👥 Katkıda Bulunanlar
Proje Yöneticisi - Kodlama: rootnorth <rootnorth@users.noreply.github.com>
Fikir - Testing: haretor <haretor@users.noreply.github.com> 

📄 Lisans

Bu proje MIT Lisansı
 altında lisanslanmıştır.
