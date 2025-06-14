<h1 align="center">🎬 Türkçe Film Yorumlarıyla Duygu Analizi (NLP Projesi)</h1>

<p align="center">
  <b>Türkçe metinlerle yapılmış bir duygu analizi (sentiment analysis) projesi</b><br>
  <i>Doğal Dil İşleme (NLP), TF-IDF, Naive Bayes Sınıflandırma</i>
</p>


##  Proje Açıklaması

Bu projede, <b>80.000+</b> Türkçe film yorumu içeren veri seti kullanılarak, yorumların <b>pozitif</b> veya <b>negatif</b> olup olmadığı sınıflandırılmıştır. Python kullanılarak veri temizliği, metin ön işleme (text preprocessing) ve makine öğrenmesi (Naive Bayes) uygulanmıştır.


## Kullanılan Teknolojiler

<ul>
  <li><b>Python</b></li>
  <li><b>Pandas, Numpy</b> - Veri işleme</li>
  <li><b>NLTK</b> - Türkçe stopword temizleme</li>
  <li><b>Scikit-learn</b> - TF-IDF, modelleme, metrikler</li>
  <li><b>Matplotlib, Seaborn</b> - Görselleştirme</li>
</ul>


## Veri Seti

- Dosya Adı: <code>turkish_movie_sentiment_dataset.csv</code>
- Özellikler:
  - <b>comment</b>: Film yorumu
  - <b>point</b>: Verilen puan (örnek: 4.5)
  - <b>label</b>: Otomatik oluşturulan etiket ("positive" veya "negative")


## Uygulanan Adımlar

<ol>
  <li><b>Veri Yükleme ve Keşif (EDA)</b></li>
  <li><b>Veri Temizliği:</b> Noktalama işaretleri, küçük harfe çevirme, sayı ve stopword kaldırma</li>
  <li><b>TF-IDF</b>: Metinleri sayısal vektöre çevirme</li>
  <li><b>Model Eğitimi:</b> Naive Bayes ile sınıflandırma</li>
  <li><b>Model Değerlendirme:</b> Accuracy, precision, recall, F1-score, confusion matrix</li>
</ol>


## Model Performansı
 
> Gerçek (Accuracy)doğruluk skoru:  0.7469662381352877.
> Doğal dil işleme projeleri için makul bir başarı oranıdır.
Özellikle Türkçe yorumlar gibi dilsel zorluklar barındıran bir veriyle çalışıldığında, Naive Bayes gibi temel bir model için bu oran oldukça yerinde kabul edebiliriz.

> Ek olarak `classification_report` ve `confusion_matrix` analizleri de yapılmıştır.



## 📂 Veri Seti

Veri seti bu Kaggle da  yer almaktadır:  
👉 turkish_movie_sentiment_dataset.csv

