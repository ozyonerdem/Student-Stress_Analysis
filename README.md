# Student-Stress_Analysis
**Öğrenci Yaşam Tarzı ve Stres İlişkisi Analizi**

- Bu proje, student_lifestyle_dataset.csv veri setini kullanarak öğrenci yaşam tarzı alışkanlıkları ile stres seviyeleri arasındaki gizli bağlantıları ortaya çıkarmayı amaçlamaktadır. Denetimsiz Öğrenme (Unsupervised Learning) tekniği olan K-Means Kümeleme algoritması kullanılarak, veri setindeki öğrenciler doğal profillere ayrılmış ve bu profillerin stres ve akademik başarı (GPA) ile olan ilişkileri analiz edilmiştir.


**📈 Keşfedilen Bağlantılar ve Sonuçlar**

- Yapılan analiz sonucunda, veri setinde belirgin 3 farklı öğrenci profili olduğu keşfedilmiştir. Bu profiller, öğrenci hayatındaki temel "ödünleşmeleri" (trade-offs) ve denge noktalarını gözler önüne sermektedir.

İşte modelin ortaya çıkardığı 3 temel profil:

1. Profil: 🎓 Akademik Mükemmeliyetçiler

- Analiz: Bu grup, en yüksek akademik başarıyı (3.38 GPA) en yoğun çalışma temposuyla (8.9 saat/gün) elde etmektedir. Ancak bu başarının bedeli, istisnasız olarak en yüksek stres seviyesidir (2.0/2.0).

- Keşfedilen Bağlantı: Yüksek akademik başarı, doğrudan en yüksek stres seviyesiyle ilişkilidir.

2. Profil: 🧘‍♂️ Dengeli ve Huzurlular

- Analiz: Bu grup, en düşük stres seviyesine (0.8/2.0) sahip olanlardır. Sırları, günde ortalama 7.9 saat ile en dengeli uyku süresine sahip olmalarıdır. Akademik başarıları makul düzeydedir.

- Keşfedilen Bağlantı: Yeterli ve düzenli uyku, stresi yönetmedeki en kritik faktördür.

3. Profil: 🏃‍♂️ Yorgun Savaşçılar

- Analiz: Bu, projenin en çarpıcı bulgusunu içeren profildir. Bu grup, "Dengeli" grupla neredeyse aynı akademik çabayı gösterip (6.6 saat/gün) benzer notlar almasına rağmen, onlardan çok daha streslidir (1.3/2.0).

- Keşfedilen Bağlantı: Bu iki grup arasındaki tek büyük fark uykudur. Bu profil, uykudan feragat etmenin, akademik başarıya bir katkı sağlamadan stresi doğrudan artırdığını matematiksel olarak kanıtlamaktadır.

**📊 Görsel Sonuçlar**

- Modelin oluşturduğu profillerin karşılaştırıldığı Pairplot grafiği, bu bağlantıları görsel olarak doğrulamaktadır.
<img width="1965" height="2033" alt="download" src="https://github.com/user-attachments/assets/45be711b-98c7-401e-9a3e-df987273fdeb" />


**🛠️ Kullanılan Teknolojiler**

- Dil: Python

- Kütüphaneler: Pandas, Scikit-learn, Matplotlib, Seaborn

- Ortam: Google Colab


