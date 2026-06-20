# 🚀 Akbank Derin Öğrenme Bootcamp - Proje Deposu

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras" />
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
</div>

---

## 📝 Proje Hakkında
Bu çalışma, **Akbank Derin Öğrenme Bootcamp** kapsamında Python ve TensorFlow/Keras kütüphaneleri kullanılarak geliştirilmiş bir **Görüntü Sınıflandırma (Image Classification)** projesidir. Projede, derin öğrenme mimarilerinden yararlanılarak balık türlerinin yüksek doğrulukla sınıflandırılması amaçlanmıştır.

📌 **Kaggle Notebook Bağlantısı:** [Akbank DL Project](https://www.kaggle.com/code/sifanurozdemir/akbank-dl-project)

---

## 👥 Geliştiriciler
Bu proje, takım olarak iş birliği içerisinde geliştirilmiştir:
* **Şifanur Özdemir**
* **Berat Keskin** — [GitHub Profili](https://github.com/BeratxKeskin)

---

## 📊 Veri Seti (Dataset)
Projede Kaggle üzerinde yer alan **"A Large Scale Fish Dataset"** kullanılmıştır.
* **Toplam Örnek Sayısı:** 9.000 adet görüntü
* **Sınıf Sayısı:** 10 farklı balık türü
* **İçerik:** Her bir sınıfa ait zengin görsel çeşitlilik ve her görsele ait sınıf etiketleri (labels).

---

## 🛠️ Kullanılan Teknolojiler & Kütüphaneler

| Teknoloji / Kütüphane | Kullanım Amacı |
| :--- | :--- |
| **Python** | Projenin ana programlama dili |
| **TensorFlow & Keras** | Derin öğrenme model mimarisinin (CNN) kurulması ve eğitilmesi |
| **NumPy** | Matris işlemleri ve sayısal veri manipülasyonu |
| **Pandas** | Veri analizi ve yapılandırılmış veri yönetimi |
| **Matplotlib** | Eğitim metriklerinin ve sonuçların görselleştirilmesi |

---

## 🔄 Proje Yaşam Döngüsü (Temel Adımlar)
1.  **Veri Yükleme:** Veri setinin Kaggle ortamından projeye güvenli bir şekilde aktarılması.
2.  **Veri Ön İşleme (Pre-processing):** Görsellerin modele uygun boyutlara getirilmesi (Resizing), piksel değerlerinin normalize edilmesi ve aşırı öğrenmeyi (overfitting) önlemek amacıyla **Veri Artırma (Data Augmentation)** tekniklerinin uygulanması.
3.  **Model Oluşturma:** Özellik çıkarımı ve sınıflandırma için özelleştirilmiş bir **Evrişimsel Sinir Ağı (CNN)** mimarisinin tanımlanması, derlenmesi (compile) ve eğitilmesi.
4.  **Model Değerlendirmesi:** Eğitim ve doğrulama (validation) setleri üzerinde model performansının analiz edilmesi; kayıp (loss) ve doğruluk (accuracy) grafiklerinin çizilmesi.

---

## 📈 Sonuçlar ve Başarım

Eğitim süreci sonunda elde edilen model, test ve doğrulama verileri üzerinde üstün bir performans göstermiştir:

* 🎯 **Doğruluk Oranı (Accuracy):** `%97`
* 📌 **Değerlendirme:** Geliştirilen Evrişimsel Sinir Ağı, farklı balık türlerini karmaşık arka planlara ve varyasyonlara rağmen yüksek kararlılıkla ayırt edebilmektedir.

---

<div align="center">
  <sub>Akbank Derin Öğrenme Bootcamp kapsamında bizleri destekleyen tüm eğitmenlerimize ve ekip arkadaşlarımıza teşekkür ederiz.</sub>
</div>
