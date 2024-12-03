# Music Clustering and Visualization Project

## Proje Açıklaması
Bu proje, müzik verilerini analiz etmek ve gruplandırmak için çeşitli veri işleme ve görselleştirme tekniklerini kullanmayı amaçlamaktadır. Projede, müzik verisindeki "Beats Per Minute (BPM)", "Energy", "Danceability" gibi özellikler kullanılarak **K-Means** algoritmasıyla kümeler oluşturulmuş ve bu kümeler etiketlenerek detaylı bir şekilde analiz edilmiştir.

Verilerin görselleştirilmesi için **Plotly** kütüphanesi kullanılarak interaktif 3D scatter grafikleri oluşturulmuştur. Bu sayede müzik segmentlerinin özellikler bazında farklılaşması kolayca gözlemlenebilmiştir.

## Kullanılan Teknolojiler
- **Python:** Veri analizi, kümeleme ve görselleştirme işlemleri için.
- **Scikit-learn:** K-means algoritması için.
- **Plotly:** 3D görselleştirme için.
- **Pandas:** Veri işleme ve manipülasyon için.

## Veri Özellikleri
Proje aşağıdaki veri özelliklerini kullanmaktadır:
- **Beats Per Minute (BPM):** Müzik temposunu temsil eder.
- **Energy:** Parçanın dinamik enerjisini ifade eder.
- **Danceability:** Bir parçanın dans edilebilirliğini ölçer.

Kümeler, bu özellikler kullanılarak anlamlı gruplar halinde ayrılmış ve analiz edilmiştir.

## Kullanım Talimatları
1. Proje gereksinimlerini yüklemek için aşağıdaki komutu çalıştırın:
   ```bash
   pip install -r requirements.txt

##Görselleştirme
Proje, interaktif bir 3D scatter grafiği sunmaktadır. Bu grafik üzerinde fare ile küme üyeleri hakkında bilgi alınabilir ve verilerin dağılımı kolayca analiz edilebilir.

##Lisans
Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için aşağıdaki bağlantıyı inceleyebilirsiniz: MIT License
