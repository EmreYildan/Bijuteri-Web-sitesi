# Grup 115 Bijuteri Projesi

Bu proje, PHP ve MySQL kullanılarak geliştirilmiş basit bir bijuteri mağazası otomasyon sistemidir.

## 📁 Klasör Yapısı
 
 Admin/  
   
    ├─ admin.panel.php              → Yönetici ana paneli 

    ├─ yorum.yonet.php              → Kullanıcı yorumlarını yönet
   
    ├─ admin.giris.php              → Yönetici girişi 
   
    ├─ admin.kayit.php              → Yönetici kaydı 

    ├─ musteri.goruntule.php        → müşterileri listeler

    ├─ admin.siparis.yonet.php      → Siparişleri yönetme 
   
    ├─ admin.cikis.php              → Yönetici çıkışı  
    
    └─ admin.duzenle/               → Yönetici düzen işlemleri 
        ├─ stok.php                 → Stok bilgilerini yönetir 
        ├─ urun.ekle.php            → Yeni ürün ekler 
        └─ urun.sil.php             → Ürün silme işlemi 

        └─ Destek.admin/                       → Admin Destek işlemleri
        ├─ admin.destek.mesajlasma.php         → Kullanıcıyla mesajlaşma
        ├─ admin.destek.talepleri.php          → Tablolama yapar 
        
        
Destek/  
   
    ├─ destek.mesajlasma.php      → Destekle mesaj yazışma
    
    ├─ destek.talep.gonder.php    → Destek Talep gonderme
    
    └─ destek.talepleri.php       → Destekten Talep 



 favori/  
   
    ├─ favorilerim.php       → Favori ürünler listesi 
    
    ├─ favorilere.ekle.php   → Favoriye ürün ekleme 
    
    └─ favori.sil.php        → Favoriden silme 
    
 sepet/  
   
    ├─ sepet.php             → Sepet görüntüleme 
    
    └─ sepete.ekle.php       → Sepete ürün ekleme 

    sifre/  
   
    ├─ sifre.sifirla.php     → Şifre sıfırlama 
    
    └─ sifre.yenile.php      → Şifre Yenileme
    
 urunler/  
   
    ├─ bileklik.php         → Bileklik ürünleri 
    
    ├─ filtre.php           → Ürün filtreleme 
   
    ├─ kolye.php            → Kolye ürünleri 
   
    ├─ kupe.php             → Küpe ürünleri 
   
    ├─ yüzük.php            → Yüzük ürünleri 
    
    ├─ ürün.detay.php       → Ürün detayları 
    
    └─ images/              → Ürün görselleri klasörü 
    
📄 Diğer Dosyalar  
    
    ├─ anasayfa.php         → Ana sayfa 
    
    ├─ baglanti.php         → Veritabanı bağlantısı 
    
    ├─ giris.php            → Kullanıcı girişi 
    
    ├─ kayit.php            → Kullanıcı kaydı 
    
    ├─ cikis.php            → Kullanıcı çıkışı 
   
    ├─ profil.php           → Kullanıcı profili 
   
    ├─ siparislerim.php     → Sipariş geçmişi 
    
    ├─ siparis.durum.php    → Sipariş durumu 
   
    ├─ urun.arama.php		 → Ürün arama

    ├─ README.md		       → Readme 

    ├─ bijuteri.sql	       → Sql dosyamızın dışarı aktarılmış hali


    
  

## ⚙️ Teknolojiler

- PHP 7.x
- MySQL
- HTML / CSS
- XAMPP

## 🧪 Kurulum

1. htdocs içine projeyi kopyalayın.
2. XAMPP üzerinden Apache ve MySQL’i başlatın.
3. veritabani.sql dosyasını phpMyAdmin üzerinden içe aktarın.
4. http://localhost/bijuteri/giris.php adresinden projeyi başlatın.

## 👥 Geliştirici

- Grup 115
- Göksel Bekdemir
- Emre Yasin Yıldan
- Emirhan Bıkmaz

## 📄 Lisans

Bu proje eğitim amaçlı hazırlanmıştır. Herhangi bir ticari kullanım için uygun değildir.

Bu proje yalnızca kişisel kullanım ve referans amacıyla paylaşılmıştır.  
Ticari, akademik veya bireysel herhangi bir projede kullanılması yasaktır.  
Kodların tamamı veya bir kısmı izinsiz olarak kopyalanamaz, dağıtılamaz, çoğaltılamaz veya türetilmiş çalışmalar oluşturulamaz.

Telif Hakkı ©[2025] Goske1,EmreYildan,EmirhanBikmaz

Tüm hakları saklıdır.
>>>>>>> ebd83485aa5d78aedf3dd0fb30acc329f5249162
