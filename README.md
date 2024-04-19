# Meme-Kanseri_Tespit
Meme Kanseri Sınıflandırma ve Tespit Projesi
Özet
Bu projede, meme kanseri teşhisi için veri madenciliği tekniklerinin kullanımıyla bir sınıflandırma modeli geliştirilmiştir. Wisconsin Meme Kanseri Veri Seti'nden elde edilen klinik özellikler içeren veri seti kullanılmıştır. Proje, veri seti ön işleme adımları, model oluşturma ve performans değerlendirme süreçlerini içermektedir.

Metodoloji
Veri Toplama ve Hazırlık
Veri Seti: Wisconsin Meme Kanseri Veri Seti'nden alınmıştır.
Özellikler: Hücrelerin çekirdek ve sitoplazmik özellikleri, dokunun büyüklüğü, simetri gibi morfolojik özellikler içermektedir.
Veri Ön İşleme: Eksik verilerin işlenmesi, gereksiz sütunların kaldırılması, kategorik değişkenlerin kodlanması yapılmıştır.
Model Oluşturma ve Eğitme
Algoritma: Decision Tree sınıflandırma algoritması kullanılmıştır.
Scikit-learn Kullanımı: DecisionTreeClassifier sınıfı kullanılarak model oluşturulmuştur.
Model Değerlendirme
Performans Metrikleri: Doğruluk, hassasiyet, özgüllük, F1 skoru gibi metrikler kullanılmıştır.
Görselleştirme: Sınıflandırma raporu ve karışıklık matrisi ile modelin performansı görselleştirilmiştir.
Sonuçlar ve Analiz
Geliştirilen modelin %XX eğitim doğruluğu ve %92.54 test doğruluğu ile meme kanseri teşhisinde başarılı bir şekilde kullanılabileceği gösterilmiştir.
Modelin kötü huylu ve iyi huylu tümörleri doğru sınıflandırdığı görülmüştür.
Dosya İçeriği
rapor.pdf: Projenin detaylı raporu.
veri_seti.csv: Kullanılan veri seti.
model.py: Model oluşturma ve eğitme işlemlerini içeren Python dosyası.
performans_değerlendirme.py: Modelin performansını değerlendiren Python dosyası.
Kullanım
Veri setini veri_seti.csv dosyasından okuyun.
model.py dosyasını çalıştırarak modeli eğitin.
performans_değerlendirme.py dosyasını çalıştırarak modelin performansını değerlendirin.
Referanslar
Jatoi, I., "Manual of Breast Diseases," Lippincott Williams & Wilkins, 2002.
UHOD: International Journal of Hematology & Oncology / Uluslararasi Hematoloji Onkoloji Dergisi, 2010, Vol 20, Issue 1, p27
Killock, D. Pan-cancer genomic analyses uncover molecular drivers. Nat Rev Clin Oncol 15, 263 (2018).
Kolay, N., Erdoğmuş, P., The classification of breast cancer with Machine Learning Techniques. In Electric Electronics, Computer Science, Biomedical Engineerings' Meeting (EBBT), 1-4, 2016.
Cruz, J. A., Wishart, D. S., Applications of machine learning in cancer prediction and prognosis, Cancer informatics, 2, 2006.
