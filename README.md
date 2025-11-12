

# E-TİCARET MÜŞTERİ SEGMENTASYONU VE BİRLİKTELİK ANALİZİ

Bu proje kapsamında, e-ticaret verileri üzerinde müşteri segmentasyonu ve birliktelik analizi uygulanarak, müşteri davranışlarının detaylı bir şekilde incelenmesi hedeflenmiştir. Çalışma sonucunda elde edilen bulgular, şirketlerin pazarlama stratejilerini veri temelli kararlarla güçlendirmesine olanak sağlamaktadır.

## Proje Amacı

Projenin temel amacı, müşterileri satın alma alışkanlıklarına göre gruplandırmak ve en değerli müşteri kitlesinin (şampiyon segmentinin) satın alma eğilimlerini ortaya çıkarmaktır. Bu sayede, müşteri değeri artışını destekleyen stratejik satış önerileri geliştirilebilmektedir.

## Uygulanan Analitik Aşamalar

### 1. Müşteri Segmentasyonu (RFM Analizi)

* Proje kapsamında, müşterilerin son alışveriş tarihi (Recency), alışveriş sıklığı (Frequency) ve toplam harcama tutarı (Monetary) dikkate alınarak RFM analizi uygulanmıştır.
* Veri dağılımlarındaki dengesizlikler logaritmik dönüşüm ve standardizasyon yöntemleriyle giderilmiş, analiz öncesi veri normalleştirilmiştir.
* Optimum küme sayısı Elbow (Dirsek) Yöntemi ile belirlenmiş ve K-Means Kümeleme Algoritması uygulanmıştır.
* Sonuç olarak müşteriler, "Şampiyonlar (Monetary: £8074)", "Risk Altındakiler" ve "Kış Uykusundakiler" gibi anlamlı segmentlere ayrılmıştır. Bu ayrım sayesinde, farklı müşteri grupları için hedeflenmiş pazarlama stratejileri geliştirilebilmiştir.

### 2. Birliktelik Analizi (FBT)

* Kümeleme sonucunda en değerli müşteri grubu olan Şampiyonlar segmenti belirlenmiş ve bu gruba özel Birliktelik Analizi (Frequent Bought Together - FBT) gerçekleştirilmiştir.
* Bu analizde, müşterilerin faturalarındaki ürün kombinasyonları incelenmiş ve birlikte en sık satın alınan ürün çiftleri hesaplanmıştır.
* Elde edilen sonuçlara göre, "LUNCH BAG" ve "JUMBO BAG" gibi ürünlerin yüksek oranda birlikte satın alındığı tespit edilmiştir. Bu bulgular, şirketin çapraz satış (cross-sell) fırsatlarını belirlemesi açısından önemli içgörüler sağlamıştır.

## Kullanılan Teknolojiler

* Python (Pandas, NumPy)
* Scikit-learn (KMeans, StandardScaler)
* Matplotlib, Seaborn

## Sonuç ve Katkılar

* Şirket müşterileri, satın alma davranışlarına göre anlamlı segmentlere ayrılmıştır.
* Şampiyon müşteri segmentinin alışveriş eğilimleri belirlenmiştir.
* Birlikte satın alınma eğilimleri ortaya çıkarılarak, pazarlama stratejileri için kullanılabilir öneriler üretilmiştir.

Bu proje ile, müşteri sadakatinin artırılması, sepet ortalamasının yükseltilmesi ve pazarlama bütçesinin daha verimli kullanılabilmesi hedeflenmiştir. Analiz sonuçları, veri temelli karar verme süreçlerinde şirketlere önemli katkı sağlamaktadır.

---
Bu metin, tüm yazım stilleri basitleştirilmiş ve kopyala-yapıştır için hazırdır.





