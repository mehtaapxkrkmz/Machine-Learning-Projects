# Otel Tavsiye Sistemi

Bu proje, verilen bir lokasyona ve açıklamaya dayalı olarak otel tavsiyeleri sağlayan bir sistemdir. Sistem, kullanıcının girdiği açıklamayı doğal dil işleme (NLP) teknikleriyle analiz ederek otellerin etiketleriyle karşılaştırır ve benzer otelleri önerir. Proje, otel yorumlarından ve ilgili etiketlerden yararlanarak otelleri karşılaştırmak ve tavsiye etmek için metin işleme ve benzerlik hesaplamalarını kullanır.

## Nasıl Çalışır?

### 1. **Veri Ön İşleme:**
   - Veri seti, otellerin ismi, etiketleri, ortalama puanı, adresi ve lokasyon bilgilerini içerir.
   - Kullanıcı tarafından girilen açıklama (örneğin "İş seyahati için gidiyorum") işlenir. Bu açıklama kelimelere ayrılır, küçük harfe dönüştürülür ve yaygın kullanılan kelimeler (stop-words) kaldırılır.
   - Kalan kelimeler lemmatize edilerek (kelimenin kök haline dönüştürülerek) standart hale getirilir.

### 2. **Benzerlik Hesaplama:**
   - Sistem, verilen lokasyona ait otelleri filtreler ve her bir otelin etiketleriyle karşılaştırma yapar.
   - Kullanıcının açıklamasının işlenmiş hali ile otelin etiketleri karşılaştırılır ve ortak kelimeler üzerinden bir benzerlik skoru hesaplanır. Ortak kelimelerin sayısı ne kadar fazla olursa, benzerlik skoru o kadar yüksek olur.

### 3. **Sıralama ve Filtreleme:**
   - Oteller, benzerlik skoru yüksek olanlardan başlanarak sıralanır.
   - Aynı otel adı tekrarı önlenir, böylece bir otel birden fazla kez önerilmez.
   - Ayrıca, oteller ortalama puanlarına göre de sıralanır, böylece daha yüksek puanlı oteller öncelikli olarak önerilir.

### 4. **Tavsiye Çıktısı:**
   - Benzerlik skoru en yüksek ve ortalama puanı en yüksek olan oteller önerilir. İlk 5 otel, otel adı, ortalama puan ve adres bilgileri ile kullanıcıya sunulur.

## Kurulum

Otel Tavsiye Sistemi'ni kullanabilmek için aşağıdaki kütüphanelerin yüklü olması gerekmektedir:

- `nltk`: Doğal dil işleme için.
- `pandas`: Veri işleme ve analiz için.
- `numpy`: Sayısal hesaplamalar için.

## Lisans 

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır. Lisans, projenin kopyalanması, dağıtılması, değiştirilmesi ve ticari olmayan amaçlarla kullanılmasını sağlar. Ancak, projede kullanılan diğer bağımlılıkların lisanslarına da dikkat edilmelidir.