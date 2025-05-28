# 🛒 Online Shopping App

**Mobil Mağaza** — basit bir Android alışveriş uygulaması. Kullanıcılar hesap açabilir, giriş yapıp ürünleri listeleyebilir, sepete ekleyip satın alma simülasyonu yapabilir. Admin girişiyle yeni ürün ekleme ve silme yetkisi de mevcut!

---

## 🚀 Özellikler

- 📱 **Kullanıcı Kaydı & Girişi**  
  - Ad, e-posta, şifre ile kayıt  
  - SharedPreferences ile “otomatik giriş”  

- 🏠 **Anasayfa**  
  - Veritabanından (`HomeDatabase`) çekilen ürünleri listeleme  
  - Ürün başlığı, tanımı, fiyat ve görsel  
  - **Seed Data**: Uygulama ilk açılışında otomatik eklenen 10 ürün  

- 🛒 **Sepete Ekle & Listele**  
  - Sepet ikonuna dokununca ürün SQLite’a (`CartDatabase`) eklenir  
  - Sepet rengi güncellenir  
  - “Sepet” menüsünde eklenen ürünleri görüntüleme  
  - **Sepeti Temizle** butonu  

- 👤 **Hesap Bilgileri**  
  - Kayıtlı kullanıcı profilini gösterme ve düzenleme  

- 🔒 **Admin Modu**  
  - Kullanıcı adı: `admin`, şifre: `123`  
  - Admin girişinde nav-menu’ye **“Ürün Ekle”** ve **“Sil”** butonları eklenir  
  - Yeni ürün ekleme ekranı (`AddProductActivity`)  
  - Ürün silme butonu (`HomeAdapter`)  

---
![1](https://github.com/user-attachments/assets/aad09ca8-df37-4c93-992c-b35b6bafc30e)

