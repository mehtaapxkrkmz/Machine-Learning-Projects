# YouTube Video Analizi Projesi

Bu proje, YouTube videolarının başlıkları ve videoların sayısal özellikleri üzerinde yapılan çeşitli analizleri içermektedir. Proje, başlık uzunlukları, başlıklarda büyük harf kullanımını, izlenme sayıları ve diğer sayısal veriler arasındaki korelasyonları analiz etmektedir. Ayrıca, video başlıklarında yer alan kelimelerden bir kelime bulutu (word cloud) oluşturulmuştur.

## Projeye Genel Bakış

Proje kapsamında yapılan analizler ve görselleştirmeler şunlardır:

- **Başlık Uzunluğu Dağılımı**: Video başlıklarının uzunlukları hesaplanmış ve başlık uzunluğu dağılımı görselleştirilmiştir.
- **Başlıkta Büyük Harf Kullanımı**: Başlıklarda büyük harf bulunan videoların sayısı ve oranı incelenmiştir. Bu analiz, başlıklarda büyük harf kullanımının videoların popülerliği veya diğer özelliklerle bir ilişkisi olup olmadığını anlamayı amaçlar.
- **Korelasyon Analizi**: Video başlıklarının uzunluğu, izlenme sayıları, beğeni sayısı gibi sayısal veriler arasındaki ilişkiler görselleştirilmiştir. Bu analiz, videoların başlık uzunluğu ile diğer metrikler arasında bir ilişki olup olmadığını gözlemlemeyi hedefler.
- **Kelime Bulutu**: Video başlıklarında sıkça kullanılan kelimelerden bir kelime bulutu oluşturulmuştur. Bu görselleştirme, başlıklarda en yaygın kullanılan kelimeleri belirlemeye olanak tanır.

## Proje Akışı

1. **Veri Hazırlığı ve İşleme**: Projeye başlarken, YouTube video başlıkları ve videoların çeşitli sayısal özellikleri (izlenme sayısı, beğeni sayısı vb.) içeren bir veri seti kullanılmıştır. Başlık uzunluğu gibi yeni özellikler hesaplanmış ve veriler üzerinde temizlik işlemleri yapılmıştır.
   
2. **Başlık Uzunluğunun İncelenmesi**: Başlıkların uzunluğu hesaplanmış ve bir histogram grafiği ile başlık uzunluklarının dağılımı görselleştirilmiştir.

3. **Başlıklarda Büyük Harf Kullanımının İncelenmesi**: Başlıkta büyük harf bulunan videoların sayısı ve oranı bir pasta grafiği ile görselleştirilmiştir. Bu analiz, başlıklarda büyük harf kullanımının önemli olup olmadığını incelemek amacıyla yapılmıştır.

4. **Korelasyon Analizi**: Başlık uzunluğu ile diğer sayısal veriler (izlenme sayısı, beğeni sayısı vb.) arasındaki ilişkiler incelenmiş ve bir korelasyon haritası oluşturulmuştur. Bu, başlık uzunluğu ile diğer özelliklerin birbirine nasıl bağlı olduğunu gösterir.

5. **Kelime Bulutu (Word Cloud)**: Video başlıklarında en sık kullanılan kelimelerden bir kelime bulutu oluşturulmuş ve görselleştirilmiştir. Bu, başlıklarda en çok kullanılan terimleri belirlemeye yardımcı olur.

## Kullanılan Görselleştirme Yöntemleri

- **Histogram**: Başlık uzunlukları dağılımını görselleştirmek için histogram kullanılmıştır.
- **Pasta Grafiği**: Başlıklarda büyük harf kullanım oranlarını görmek için pasta grafiği kullanılmıştır.
- **Isı Haritası (Heatmap)**: Korelasyonları görselleştirmek için ısı haritası kullanılmıştır.
- **Kelime Bulutu (Word Cloud)**: Başlıklarda en yaygın kullanılan kelimeleri görselleştirmek için kelime bulutu oluşturulmuştur.

## Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır. Lisans, projenin kopyalanması, dağıtılması, değiştirilmesi ve ticari olmayan amaçlarla kullanılmasını sağlar. Ancak, projede kullanılan diğer bağımlılıkların lisanslarına da dikkat edilmelidir.

