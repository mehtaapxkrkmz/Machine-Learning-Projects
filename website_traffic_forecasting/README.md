# Web Traffic Analysis Project

## Proje Hakkında

Bu proje, "Thecleverprogrammer.com" web sitesinin günlük trafik verilerini analiz etmek amacıyla geliştirilmiştir. Analiz, web sitesi trafiğini daha iyi anlamak için zaman serisi analiz teknikleri ve mevsimsel modelleme kullanılarak yapılmıştır. Ayrıca, verilerin durağan olup olmadığını belirlemek için çeşitli istatistiksel yöntemler uygulanmıştır. SARIMAX modeli kullanılarak gelecekteki trafik tahminleri yapılmıştır.

### Kullanılan Yöntemler ve Modüller:
- **Pandas**: Veri işleme ve manipülasyon.
- **Statsmodels**: Zaman serisi analizi ve SARIMAX modeli.
- **Matplotlib** ve **Plotly**: Verilerin görselleştirilmesi.
- **Seaborn**: İleri düzey görselleştirme ve grafikler.
- **Scikit-learn**: Verilerin ölçeklendirilmesi ve modelleme.

## Proje Adımları:
1. **Veri Temizleme ve Hazırlama**: "Views" (görüntüleme) sayısı üzerinde çeşitli veri işleme teknikleri uygulanmıştır.
2. **Zaman Serisi Decomposition**: Mevsimsel ve trend bileşenleri analiz edilmiştir.
3. **Otokorelasyon ve PACF Analizi**: Verinin otokorelasyonu ve parcelleme otokorelasyon fonksiyonu hesaplanmıştır.
4. **SARIMAX Modeli**: Web sitesi trafiği üzerinde mevsimsel zaman serisi analizi yapılmış ve gelecekteki trafik tahmin edilmiştir.
5. **Sonuçların Görselleştirilmesi**: Zaman serisi ve mevsimsel bileşenler görselleştirilmiştir.

## Kullanım

Bu projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

1. Projeyi yerel bilgisayarınıza indirin:
    ```bash
    git clone https://github.com/your-username/web-traffic-analysis.git
    ```

2. Gerekli Python kütüphanelerini yükleyin:
    ```bash
    pip install -r requirements.txt
    ```

3. Projeyi çalıştırmak için aşağıdaki komutu kullanın:
    ```bash
    python analysis.py
    ```

## Lisans

Bu proje, **MIT Lisansı** altında lisanslanmıştır.

