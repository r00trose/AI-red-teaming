# 📚 Denetimli Öğrenme Algoritmaları

## Denetimli Öğrenme Algoritmaları
Denetimli öğrenme algoritmaları, birçok makine öğrenimi (ML) uygulamasının temelini oluşturur ve sistemlerin etiketli verilerden öğrenerek doğru tahminler yapmasını sağlar. Denetimli öğrenmede her veri noktası bilinen bir sonuç ya da etiketle ilişkilendirilir. Bunu, doğru cevapların önceden verilmiş bir örnekler kümesine sahip olmak gibi düşünebilirsiniz. 

Algoritmanın amacı, yeni ve görülmemiş veriler için etiketi tahmin edecek bir eşleme fonksiyonu öğrenmektir. Bu süreç, özellikler (girdi değişkenleri) ile karşılık gelen etiketler (çıktı değişkenleri) arasındaki desenleri ve ilişkileri tanımlamayı içerir. Bu sayede algoritma, bilgisini yeni örneklere genelleyebilir.


## Denetimli Öğrenme Nasıl Çalışır
Bir çocuğa farklı meyveleri tanıtmayı öğrettiğinizi hayal edin. Ona bir elma gösterip, **“bu bir elma”** diyorsunuz. Sonra bir portakal gösterip, **“bu bir portakal”** diyorsunuz. Etiketli örnekler defalarca sunulduğunda, çocuk rengine, şekline ve boyutuna göre meyveleri ayırt etmeyi öğrenir.  

Denetimli öğrenme algoritmaları da benzer şekilde çalışır. Büyük bir etiketli örnek veri kümesiyle beslenirler ve bu veriyi kullanarak yeni ve görülmemiş örneklerin etiketlerini tahmin edebilecek bir model eğitirler. Eğitim süreci, modelin parametrelerini ayarlayarak tahminleri ile gerçek etiketler arasındaki farkı en aza indirmeyi içerir.


## Denetimli Öğrenme Problemleri
Denetimli öğrenme problemleri genel olarak iki ana kategoriye ayrılabilir:

- **Sınıflandırma (Classification):** Kategorik bir etiketi tahmin etmek.  
  Örnek: e-postaları spam / değil olarak sınıflandırmak, resimlerde kedi, köpek ya da kuş olduğunu belirlemek.
- **Regresyon (Regression):** Sürekli bir değeri tahmin etmek.  
  Örnek: ev fiyatını büyüklüğe, konuma ve diğer özelliklere göre tahmin etmek, borsa tahminleri yapmak.


## Denetimli Öğrenmede Temel Kavramlar

### Eğitim Verisi (Training Data)
Eğitim verisi, denetimli öğrenmenin temelidir. ML modelini eğitmek için kullanılan etiketli veri kümesidir. Bu küme, girdi özellikleri ile onlara karşılık gelen çıktı etiketlerinden oluşur.  
Kalite ve miktar, modelin doğruluğunu doğrudan etkiler.  

> Eğitim verisini, doğru çözümleri verilmiş örnek problemler olarak düşünebilirsiniz.


### Özellikler (Features)
Verinin ölçülebilir nitelikleri ya da modelin girdisi olan değişkenlerdir.  
Örnek (ev fiyatı tahmini için):  
- Büyüklük  
- Yatak odası sayısı  
- Konum  
- Evin yaşı  


### Etiketler (Labels)
Bilinen sonuçlar ya da hedef değişkenlerdir. Modelin tahmin etmeye çalıştığı “doğru cevaplar”dır.  
Örnek: Ev fiyatı tahmininde **gerçek satış fiyatı**.


### Model
Özellikler ile etiketler arasındaki ilişkinin matematiksel bir temsilidir.  
Eğitim verisinden öğrenilir ve yeni, görülmemiş veriler için tahmin yapmakta kullanılır.  
Modeli, “özellikleri girdi olarak alıp etiketi tahmin eden bir fonksiyon” gibi düşünebilirsiniz.  


### Eğitim (Training)
Algoritmaya eğitim verisinin verilmesi ve modelin parametrelerinin tahmin hatalarını en aza indirecek şekilde ayarlanması sürecidir.


### Tahmin (Prediction)
Model eğitildikten sonra yeni veriler için kullanılabilir.  
Örnek:  
- Bir e-postayı spam olarak sınıflandırmak  
- Hisse senedi fiyatlarını tahmin etmek  


### Çıkarım (Inference)
Tahmin kavramını kapsayan daha geniş bir kavramdır.  
- Verideki temel yapıyı ve desenleri anlamak  
- Parametreleri tahmin etmek  
- Özellikler arasındaki ilişkileri keşfetmek  

Örnek:  
- Karar ağacındaki en önemli özellikleri belirlemek  
- Doğrusal regresyondaki katsayıları yorumlamak  


## Değerlendirme (Evaluation)
Modelin performansını ölçmek için kullanılan temel metrikler:  
- **Doğruluk (Accuracy):** Doğru tahminlerin oranı  
- **Kesinlik (Precision):** Pozitif tahminlerin ne kadarının gerçekten pozitif olduğu  
- **Duyarlılık (Recall):** Gerçek pozitiflerin ne kadarının doğru tahmin edildiği  
- **F1-Skoru:** Kesinlik ve duyarlılığın harmonik ortalaması  


## Genelleme (Generalization)
Modelin yeni, daha önce hiç görmediği veriler için doğru tahminler
