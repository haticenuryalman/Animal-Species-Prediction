# Animal Species Prediction

Bu proje, hayvan türü sınıflandırması yapmak için Konvolüsyonel Sinir Ağı (CNN) kullanarak geliştirilmiş bir derin öğrenme modelini içermektedir. Proje, PyTorch ve Matplotlib kütüphanelerini kullanarak, hayvan türlerini doğru şekilde sınıflandırmak amacıyla eğitilmiş bir model sunmaktadır.

# Proje Hakkında
Bu projede, verilen görselin bir hayvan türüne ait olup olmadığını tespit etmek için bir CNN (Convolutional Neural Network) modeli kullanılmıştır. Model, farklı türdeki hayvan görsellerini sınıflandırmak üzere eğitilmiştir. Proje, veri ön işleme, model eğitimi, test ve görselleştirme adımlarını içermektedir.

Model, eğitim ve test sürecinde kayıp (loss) ve doğruluk (accuracy) gibi metrikleri kullanarak performansını takip eder. Kullanıcı, modelin doğruluğunu görselleştirme grafikleriyle kolayca izleyebilir.

# Kullanılan Teknolojiler
PyTorch: Derin öğrenme ve sinir ağları için popüler bir açık kaynaklı kütüphane.

TorchVision: Görsel verilerle çalışmak için kullanılan bir PyTorch kütüphanesi.

Matplotlib: Eğitim sürecinde kayıp ve doğruluk gibi metrikleri görselleştirmek için kullanılan bir kütüphane.

scikit-learn: Veri işleme ve model değerlendirme için kullanılan kütüphane.

Pillow: Görselleri yüklemek ve ön işleme yapmak için kullanılan Python kütüphanesi.

# Proje Yapısı
/Animal-Species-Prediction
│
├── dataset/                # Eğitim ve test için görsel veri seti
│   ├── cat/                # Kedilere ait görseller
│   ├── dog/                # Köpeklere ait görseller
│   ├── ...                 # Diğer hayvan türlerine ait görseller
│
├── model.py                # CNN modelinin tanımlandığı dosya
├── train.py                # Modelin eğitildiği dosya
├── test.py                 # Modelin test edilmesi için dosya
├── utils.py                # Yardımcı fonksiyonlar (veri ön işleme, görselleştirme vb.)
├── simple_cnn_model.pth    # Eğitilmiş model dosyası
└── README.md               # Proje açıklaması (bu dosya)

# Projenin anlatıldığı Youtube videosu: 
https://youtu.be/n7zxnek17es

Haticenur Yalman






