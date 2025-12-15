# 🎧 MİA - Müşteri İstek Analizi Uygulaması

> **"Müşteriyi dinleyen değil, anlayan sistem."**

MİA, firmaların veya geliştiricilerin müşterilerden gelen talepleri sistemli bir şekilde toplaması, yapay zeka destekli olarak sınıflandırması ve görsel grafiklerle analiz etmesi için **Clomosy** platformunda geliştirilmiş bir mobil uygulamadır.

---

## 🚀 Proje Hakkında

Kurumsal yapılarda müşteri taleplerinin dağınık iletilmesi, taleplerin kaybolmasına veya analiz edilememesine yol açmaktadır. Bu proje, çalışan verimliliğini artırmak ve müşteri memnuniyetini sağlamak amacıyla geliştirilmiştir.

**MİA'nın temel farkı:** Kullanıcının serbest metin olarak girdiği talep açıklamasını analiz eden **Yapay Zeka (AI)** altyapısına sahip olmasıdır. Bu sayede talep, otomatik olarak ilgili modüle (Örn: Ödeme, Teknik Destek) atanır.

## ✨ Temel Özellikler

* **📂 Modül Bazlı Sınıflandırma:** Taleplerin kategorize edilerek düzenli tutulması.
* **🤖 Yapay Zeka Destekli Tahmin:** Talep metninden otomatik modül tahmini ve yönlendirmesi.
* **📊 Görsel Analiz ve Raporlama:** Yönetici paneli üzerinden taleplerin grafiksel dağılımı.
* **💾 Veritabanı Yönetimi:** Tüm verilerin SQLite üzerinde güvenli ve sistemli tutulması.
* **role-based Access:** Kullanıcı talep oluştururken, yöneticilerin durum güncellemesi ve analiz yapabilmesi.

## 📱 Ekran Görüntüleri

| Giriş Ekranı | Talep Oluşturma & AI | Yönetici İstatistikleri |
##giriş ekranı
<img width="343" height="726" alt="image" src="https://github.com/user-attachments/assets/d68dadf0-5ff0-4066-be3f-90b6d95f4c02" />
##talep ekranı
<img width="341" height="734" alt="image" src="https://github.com/user-attachments/assets/eafb6f39-e779-4779-834a-fb503986ef24" />
##talep listesi
<img width="343" height="724" alt="image" src="https://github.com/user-attachments/assets/27c879bc-1ec1-4a35-86fe-948a9fa65980" />
##admin ekranı
<img width="343" height="708" alt="image" src="https://github.com/user-attachments/assets/17d8de2c-3755-4c23-8c4e-282164cd9083" />
##admin modül listesi
<img width="354" height="703" alt="image" src="https://github.com/user-attachments/assets/c2dcb9f6-a5ca-41c5-bbc6-10580ccde96b" />
##istatikler
<img width="399" height="572" alt="image" src="https://github.com/user-attachments/assets/028e69aa-b1a7-4c93-87b0-b6c2fae3476c" />









## 🛠️ Kullanılan Teknolojiler ve Bileşenler

Bu proje **Clomosy** mobil uygulama geliştirme platformu kullanılarak hazırlanmıştır.

* **Dil/Platform:** Clomosy (TRObject)
* **Veritabanı:** SQLite
* **Veri Formatı:** JSON
* **Görsel Bileşenler:**
    * `TCIProGrid`: Veri listeleme ve düzenleme.
    * `TCIChart`: Grafiksel analizler.
    * `TCIListView`: Talep listeleri.
    * `TCIProButton` & `TCILabel`: Arayüz etkileşimleri.
* **Yapay Zeka:** Clomosy AI Modül Tahmini Entegrasyonu.

## 🔄 Uygulama Akışı

1.  **Talep Girişi:** Kullanıcı form aracılığıyla talebini yazar.
2.  **AI Analizi:** Sistem açıklamayı okur ve uygun modülü (Örn: "Yeni Ürün", "Ödeme") tahmin eder.
3.  **Otomasyon:** Tahmin edilen modül forma otomatik seçili gelir.
4.  **Kayıt:** Veriler SQLite veritabanına işlenir.
5.  **Yönetim:** Yönetici talepleri listeler, durumlarını günceller.
6.  **Analiz:** Modül yoğunlukları grafiksel olarak sunulur.

## 📈 İstatistikler ve Analiz

Yönetici paneli, gelen taleplerin hangi modüllerde yoğunlaştığını gösteren pasta ve çubuk grafikler sunar. Bu sayede "Riskli Müşteriler" veya "En Çok Talep Alan Modüller" kolayca tespit edilebilir.

---

### 👤 Geliştirici

* **Ad Soyad:** Sude Sığırcı
* **Üniversite:** Konya Teknik Üniversitesi
* **Bölüm:** Yazılım Mühendisliği
* **İletişim:** sudesgrc4646@gmail.com

---
*Bu proje, müşteri istek yönetim süreçlerini dijitalleştirmek ve akıllı hale getirmek amacıyla geliştirilmiştir.*
