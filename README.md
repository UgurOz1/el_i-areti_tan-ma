# El İşareti Tanıma Sistemi 🖐️

Bu proje, gerçek zamanlı olarak el işaretlerini tanıyan bir yapay zeka uygulamasıdır. Şu anda A, B, C ve D harflerini tanıyabilmektedir.

## 🚀 Özellikler

- Gerçek zamanlı el işareti tanıma
- Webcam üzerinden canlı görüntü işleme
- MediaPipe ile el landmark tespiti
- Random Forest sınıflandırıcı ile işaret tanıma
- Yüksek doğruluk oranı
- Kullanıcı dostu arayüz

## 🛠️ Kullanılan Teknolojiler

- Python 3.x
- OpenCV
- MediaPipe
- scikit-learn
- NumPy
- pickle

## 📦 Kurulum

1. Repoyu klonlayın:
```bash
git clone [https://github.com/UgurOz1/el_isareti_tanima]
```

2. Gerekli paketleri yükleyin:
```bash
pip install opencv-python mediapipe scikit-learn numpy
```

## 🎯 Kullanım

Proje 4 ana bölümden oluşmaktadır:

1. **Veri Toplama** (`veri_toplama.py`):
   - Webcam üzerinden el işaretleri için veri toplanır
   - Her işaret için 100 görüntü kaydedilir

2. **Veri İşleme** (`veri_isleme.py`):
   - Toplanan görüntüler işlenir
   - El landmarkları çıkarılır
   - Veriler pickle formatında kaydedilir

3. **Model Eğitimi** (`model_egitimi.py`):
   - Random Forest modeli eğitilir
   - Model performansı ölçülür
   - Eğitilen model kaydedilir

4. **Gerçek Zamanlı Tanıma** (`son.py`):
   - Webcam üzerinden canlı el işareti tanıma
   - Tanınan işaretin ekranda gösterilmesi

## 🚀 Başlangıç

Programı çalıştırmak için:

```bash
python son.py
```


## 👥 Katkıda Bulunma

1. Fork'layın
2. Feature branch'i oluşturun
3. Değişikliklerinizi commit'leyin
4. Branch'inizi push'layın
5. Pull request oluşturun

## 🤝 İletişim

-uguro9319@gmail.com

---
⭐️ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın! 
