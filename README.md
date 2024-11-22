# Kredi Kartı Müşteri Segmentasyonu

Bu proje, kredi kartı kullanıcılarını belirli gruplara ayırmak için kümeleme (clustering) yöntemleri kullanılarak müşteri segmentasyonu oluşturmayı amaçlamaktadır. Analizden elde edilen içgörüler, pazarlama stratejilerinin belirlenmesinde ve müşteri hedeflemede kullanılabilir.

---

## Veri Seti Hakkında

Bu veri seti, son altı ay içinde yaklaşık 9.000 aktif kredi kartı kullanıcısının davranış verilerini özetlemektedir. Veri seti, müşteri düzeyinde 18 davranışsal değişken içermektedir.

### Veri Seti Genel Özellikleri
- **Amaç:** Müşteri segmentasyonu ve davranış analizi

---

## Veri Seti 

| Sütun Adı                     | Tanım                                                                                 |
|-------------------------------|---------------------------------------------------------------------------------------|
| **CUST_ID**                   | Kredi kartı sahibinin benzersiz kimliği (Kategorik)                                   |
| **BALANCE**                   | Hesapta kalan bakiye miktarı                                                         |
| **BALANCE_FREQUENCY**         | Bakiyenin ne sıklıkla güncellendiği (0 ile 1 arasında bir skor, 1 = sık, 0 = nadir)   |
| **PURCHASES**                 | Hesaptan yapılan toplam alışveriş tutarı                                             |
| **ONEOFF_PURCHASES**          | Tek seferde yapılan maksimum alışveriş tutarı                                        |
| **INSTALLMENTS_PURCHASES**    | Taksitle yapılan alışverişlerin toplam tutarı                                        |
| **CASH_ADVANCE**              | Kullanıcıya verilen nakit avans miktarı                                              |
| **PURCHASES_FREQUENCY**       | Alışverişlerin yapılma sıklığı (0 ile 1 arasında skor)                                |
| **ONEOFFPURCHASESFREQUENCY**  | Tek seferlik alışverişlerin sıklığı (0 ile 1 arasında skor)                          |
| **PURCHASESINSTALLMENTSFREQUENCY** | Taksitli alışverişlerin sıklığı (0 ile 1 arasında skor)                      |
| **CASHADVANCEFREQUENCY**      | Nakit avans ödemelerinin sıklığı                                                     |
| **CASHADVANCETRX**            | "Nakit Avans" ile yapılan işlem sayısı                                               |
| **PURCHASES_TRX**             | Yapılan alışveriş işlemleri sayısı                                                   |
| **CREDIT_LIMIT**              | Kullanıcının kredi kartı limiti                                                      |
| **PAYMENTS**                  | Kullanıcı tarafından yapılan toplam ödeme miktarı                                    |
| **MINIMUM_PAYMENTS**          | Kullanıcı tarafından yapılan minimum ödeme miktarı                                   |
| **PRCFULLPAYMENT**            | Kullanıcının yaptığı tam ödeme yüzdesi                                               |
| **TENURE**                    | Kredi kartı hizmet süresi (ay olarak)                                                |

---

## Projede Kullanılan Teknikler ve Adımlar

1. **Keşifsel Veri Analizi (EDA):**
   - Veri setinin genel özelliklerini anlamak ve eksik verileri analiz etmek.
   - Değişkenler arasındaki ilişkileri görselleştirmek.

2. **Ön İşleme ve Temizleme:**
   - Eksik verilerin işlenmesi.
   - Verilerin ölçeklendirilmesi.

3. **Kümeleme Modelleri:**
   - **K-Means Clustering**: Kullanıcıları belirli segmentlere ayırmak için.
   - 

4. **Sonuçların Görselleştirilmesi:**
   - Müşteri gruplarının özelliklerini görselleştirmek.
   - Segmentlerin pazarlama stratejileri açısından yorumlanması.



