# Öğrenci Not Kayıt ve Raporlama Sistemi (C#)

C# programlama dilinde geliştirilmiş, hata yakalama (exception handling) ve dizi (array) yönetimi prensiplerini barındıran terminal tabanlı bir not hesaplama otomasyonudur.

## Özellikler
* **Dinamik Sınıf Mevcudu:** Kullanıcının belirlediği sayıda öğrenci için dinamik kayıt oluşturma.
* **Veri Doğrulama (Validation):** Geçersiz girişleri (harf veya 0-100 aralığı dışındaki sayılar) `try-catch` bloklarıyla engelleyen güvenli altyapı.
* **Otomatik Hesaplama:** Vize (%40) ve Final (%60) ağırlıklarına göre dönem sonu ortalaması ve harf notu (AA, BA, BB vb.) ataması.
* **Detaylı Sınıf Raporu:** Tüm öğrencilerin verilerini düzenli bir tablo halinde listeleme; sınıfın en yüksek, en düşük ve genel ortalamasını ekrana yazdırma.

## Kullanılan Teknolojiler
* C# (.NET Console Application)

## Nasıl Çalıştırılır?

Projeyi çalıştırmak için bilgisayarınızda .NET SDK kurulu olmalıdır. Terminal üzerinden kodun bulunduğu dizine gidip aşağıdaki komutu çalıştırabilirsiniz:

```bash
dotnet run
