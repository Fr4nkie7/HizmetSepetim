## 📸 Screenshots – v2.0.0

### 🏠 Home – Ürün – Ödeme (YENİLENDİ)
| Home | Product | New Payment Flow |
|------|---------|----------|
| ![](./screenshots/version-history/v1.5.0/01_home.jpg) | ![](./screenshots/version-history/v1.0.0/singleUrun.jpg) | ![](./screenshots/version-history/v2.0.0/payment-flow.png) |

### 📍 Adres Yönetimi & Randevu
| Select Address | Add Address | Booking (Saat Seçimi) |
|----------------|-------------|---------|
| ![](./screenshots/version-history/v1.0.0/selectAdress.jpg) | ![](./screenshots/version-history/v1.0.0/addAddress.jpg) | ![](./screenshots/version-history/v1.0.0/booking.jpg) |

### 👤 Profil Ekranları
| Profile | Edit Profile | Address List |
|--------|--------------|---------------|
| ![](./screenshots/version-history/v1.0.0/profileScreen.jpg) | ![](./screenshots/version-history/v1.0.0/editProfile.jpg) | ![](./screenshots/version-history/v1.0.0/addressList.jpg) |
# 📱 Hizmet Sepetim – Sürüm v2.0.0

Bu sürüm, Hizmet Sepetim uygulamasının finansal işlemlerdeki esnekliğini ve güvenilirliğini artıran, büyük bir mimari ve özellik güncellemesidir. Temel odak noktası **Parçalı Ödeme Sistemi** ve **Transaction Güvenliği**dir.

---

## 🚀 Bu Sürümde Neler Var?

- **💰 Parçalı Ödeme (Split Payment) ENTEGRASYONU:**
    - Cüzdan bakiyesi ve kart ile ödemenin karıştırılarak yapılması.
    - Go Backend tarafında **MySQL Transaction** (ACID) yönetimi ile finansal veri bütünlüğü sağlandı.
- **✨ Yenilenmiş Ödeme Ekranı (Jetpack Compose):**
    - Wallet bakiyesi ve kullanım togglesi eklendi.
    - Dinamik olarak hesaplanan `Card Payment` (Karttan Ödenecek) tutarı gösterildi.
    - Ek Hizmet (Addon) seçimi ve fiyat hesaplaması entegre edildi.
- **🛠️ Backend Stabilizasyonu:** `wallet_transactions` tablosundaki ENUM kısıtlamasından kaynaklanan kritik hata çözüldü.

---

## 📸 Ekran Görüntüleri – v2.0.0

### **🏠 Ana Ekran / Ürün Detay / Yeni Ödeme Ekranı**
| Home | Single Ürün | **YENİ: Ödeme Akışı (Split Payment)** |
|------|-------------|----------------------------|
| ![](./screenshots/version-history/v1.5.0/01_home.jpg) | ![](./screenshots/version-history/v1.0.0/singleUrun.jpg) | **![](./screenshots/version-history/v2.0.0/payment-flow.png)** |

---

### **📍 Adres İşlemleri & Randevu Seçimi**
| Select Address | Add Address | Saat Seçimi |
|----------------|-------------|------------|
| ![](./screenshots/version-history/v1.0.0/selectAdress.jpg) | ![](./screenshots/version-history/v1.0.0/addAddress.jpg) | ![](./screenshots/version-history/v1.0.0/booking.jpg) |

---

### **👤 Profil**
| Profile | Edit Profile |
|---------|--------------|
| ![](./screenshots/version-history/v1.0.0/profileScreen.jpg) | ![](./screenshots/version-history/v1.0.0/editProfile.jpg) |

---

## 📝 Sürüm Notu
Bu sürüm, **HizmetSepetim**'i bir adım öteye taşıyarak esnek ve güvenli ödeme seçenekleri sunmaktadır. Backend'de kurulan Transaction altyapısı sayesinde finansal süreçlerimiz artık kurumsal standartlara uygundur.

---

Hazırlayan: **Buğra Akdemir**
Tarih: **11.12.2025**