# AI
# Duygusal Yüz Tanıma Projesi

Bu proje, derin öğrenme tekniklerini kullanarak duygusal yüz tanıma alanında bir model geliştirmeyi amaçlayan bir çalışmadır. Model, farklı duygusal ifadeleri temsil eden yüz fotoğraflarını analiz ederek insanların duygusal durumlarını sınıflandırmak üzere tasarlanmıştır.

## Veri Seti

Proje için Kaggle platformundan elde edilen geniş bir veri seti kullanılmıştır. Bu veri seti, farklı duygusal ifadeleri temsil eden yüz fotoğraflarını içerir. Veri setinde 7 farklı duygusal ifade sınıfı bulunmaktadır: angry, disgusted, fearful, happy, neutral, sad, surprised. Fotoğraflar, çeşitli ırk, cinsiyet, yaş ve arka plan koşullarına sahip insanların yüz ifadelerini içerir.

## Proje Aşamaları

1. Veri Seti Toplama: Kaggle platformundan elde edilen geniş ve çeşitli bir veri seti toplandı.

2. Veri Ön İşleme: Toplanan veri seti işlenerek görüntü verileri normalize edildi ve etiketler kodlandı.

3. Derin Öğrenme Modeli: Convolutional Neural Network (CNN) kullanarak derin öğrenme modeli oluşturuldu. Modelin içeriği katmanlarla ayrıntılı olarak tanımlandı.

4. Model Eğitimi: Oluşturulan model, eğitim verisi üzerinde eğitildi ve doğruluk oranını artırmak için farklı denemeler gerçekleştirildi.

5. Sonuçlar: Yapılan denemeler sonucunda elde edilen doğruluk oranları ve modelin performansı değerlendirildi.

## Kullanım

1. Proje klasöründe gerekli kütüphaneleri ve bağımlılıkları yüklemek için `requirements.txt` dosyasını kullanabilirsiniz.

2. Veri seti yolu belirtildikten sonra `load_dataset` fonksiyonu ile veri seti yüklenebilir.

3. Model oluşturulup eğitildikten sonra, test verisi kullanılarak duygusal yüz ifadeleri sınıflandırılabilir.



---
Yazar: [Oğuz Kağan ZELYURT]
