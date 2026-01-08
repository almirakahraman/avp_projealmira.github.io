Bu proje, Bursa Teknik Üniversitesi Bilgisayar Mühendisliği Bölümü bünyesinde yürütülen Algoritmalar ve Programlama dersi dönem projesi kapsamında geliştirilmiştir. Uygulama, Güneş Sistemi'ndeki farklı gezegenlerin yerçekimi ivmelerini kullanarak temel fizik kurallarını simüle eden C tabanlı bir konsol yazılımıdır.

🚀 Proje Hakkında
Simülasyon, bir bilim insanının 9 farklı fizik deneyini, 8 farklı gezegen koşulunda (Merkür'den Neptün'e) test etmesine olanak tanır. Yazılım tamamen modüler bir yapıda olup, bellek yönetimi için ileri seviye pointer aritmetiği kullanılmıştır.

Simüle Edilen Deneyler
----------------------------------
Serbest Düşme: Zaman bazlı düşme mesafesi hesabı.
Yukarı Atış: İlk hıza göre maksimum yükseklik hesabı.
Ağırlık: Kütle-ivme ilişkisi.
Potansiyel Enerji: Yüksekliğe bağlı enerji hesabı.
Hidrostatik Basınç: Sıvı derinliği ve yoğunluğu bazlı basınç.
Arşimet: Sıvı içerisindeki cisme uygulanan kaldırma kuvveti.
Basit Sarkaç: İp uzunluğuna göre periyot hesabı.
Sabit İp Gerilmesi: Düşey doğrultudaki gerilme kuvveti.
Asansör Deneyi: Hareket yönü ve ivmeye bağlı etkin ağırlık hesabı.

teknik Özellikler ve ZorunluluklarDiller: Tamamen C dili kullanılarak geliştirilmiştir14.Bellek Yönetimi: Tüm dizi erişimleri ve fonksiyon parametreleri pointer (işaretçi) aritmetiği (*(ptr + i)) ile yönetilmektedir

Kullanım Talimatları
Programı bir C derleyicisi (GCC vb.) ile derleyin.

Program açılışında bilim insanı adınızı girin.

Ana menüden simüle etmek istediğiniz deneyin numarasını seçin.

Deney için gerekli olan sayısal verileri (metrikleri) girin.

Program, 8 gezegen için sonuçları birimleriyle birlikte listeleyecektir.

Çıkış yapmak için menü ekranında -1 değerini girin
