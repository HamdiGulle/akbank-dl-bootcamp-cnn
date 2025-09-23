# Akbank Derin Öğrenme Bootcamp Projesi
Bu proje, CNN (Convolutional Neural Network) mimarisi kullanarak Intel Image Classification veri setindeki 6 farklı sınıfı (Binalar, Orman, Buzul, Dağ, Deniz, Sokak) doğru bir şekilde sınıflandırmayı amaçlamaktadır.

**Veri Seti**

Intel Image Classification veri seti Kaggle üzerinden temin edilmiştir. Yaklaşık 25.000 eğitim ve 14.000 test görüntüsü içermektedir.

**Kullanılan Yöntemler**

Proje kapsamında, veri ön işleme, veri çoğaltma (data augmentation), CNN tabanlı model oluşturma, hiperparametre optimizasyonu ve model değerlendirmesi gibi adımlar uygulanacaktır.

# Elde Edilen Sonuçlar ve Yorumlama

**Test Doğruluğu**

Eğitilen model, test verisi üzerinde %78.10 gibi yüksek bir doğruluk oranına ulaşmıştır. Bu sonuç, modelimizin daha önce hiç görmediği görüntüleri doğru bir şekilde sınıflandırabildiğini göstermektedir. Bu başarı, uyguladığımız veri çoğaltma (data augmentation) ve CNN mimarisinin etkinliğini kanıtlar niteliktedir.

**Sınıf Bazlı Performans Analizi**

Sınıflandırma raporu, her bir sınıf için modelin performansını daha detaylı olarak ortaya koymuştur:

**En Başarılı Sınıf**

forest (orman) sınıfında model, %98'lik bir recall değeriyle en yüksek performansı göstermiştir.

**İyi Performans Sergileyen Sınıflar**

buildings (binalar) ve street (sokak) gibi sınıflarda da %80'in üzerinde precision ve f1-score değerleri elde edilmiştir.

**Göreceli Zayıf Sınıflar**

glacier (buzul) ve sea (deniz) gibi sınıflarda, precision değerleri recall değerlerinden daha yüksektir.

**Sonuçların Özeti**

Genel olarak, model tüm sınıflarda dengeli ve başarılı bir performans sergilemiştir. Bu sonuçlar, projenin amacına ulaştığını ve geliştirilen CNN modelinin görüntü sınıflandırma problemi için etkili bir çözüm sunduğunu göstermekted

# Linkler

https://www.kaggle.com/code/hamdigulle/akbank-derin-renme-bootcamp-projesi
