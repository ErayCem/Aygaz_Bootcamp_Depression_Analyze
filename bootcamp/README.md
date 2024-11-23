# Depresyon ve Madde Bağımlılığı İlişkisi Analizi

Bu proje, depresyon ve madde bağımlılığı geçmişi arasındaki ilişkiyi incelemeyi amaçlayan bir veri analizi çalışmasıdır. Proje, çeşitli sosyal, psikolojik ve sağlıkla ilgili faktörleri analiz ederek, depresyon ve madde bağımlılığının nasıl ilişkili olduğunu görselleştirir. Veri seti, bu faktörlerin her birini içeren çeşitli demografik verilerle birlikte gelir.

## Proje İçeriği

Bu projede aşağıdaki veri analizi ve görselleştirme işlemleri gerçekleştirilmiştir:

- **Veri Ön İşleme**: Eksik veriler, boş değerler ve aykırı değerlerle ilgili analizler yapılmış, gerekli veriler ortalama ve medyan değerlerle doldurulmuştur.
- **Veri Görselleştirme**:
  - Çocuk sayısına göre birey sayısının dağılımı.
  - Medeni duruma göre yaş dağılımı.
  - Fiziksel aktivite düzeyine göre beslenme alışkanlıkları.
  - İş durumu ve gelir dağılımı.
  - Madde bağımlılığı geçmişi ve ailede depresyon geçmişi arasındaki ilişki.

## Kullanılan Kütüphaneler

- **pandas**: Veri işleme ve analizi için.
- **matplotlib**: Grafik ve görselleştirme için.
- **seaborn**: İleri düzey görselleştirmeler ve veri görselleştirmeleri için.

## Veri Seti

Projede kullanılan veri seti, depresyon ve madde bağımlılığı ile ilişkili demografik ve sağlık verilerini içermektedir. Veri seti, aşağıdaki sütunları içerir:

- **Age**: Yaş
- **Marital Status**: Medeni durum
- **Education Level**: Eğitim seviyesi
- **Number of Children**: Çocuk sayısı
- **Smoking Status**: Sigara içme durumu
- **Physical Activity Level**: Fiziksel aktivite düzeyi
- **Employment Status**: İş durumu
- **Income**: Gelir
- **Alcohol Consumption**: Alkol tüketimi
- **Dietary Habits**: Beslenme alışkanlıkları
- **Sleep Patterns**: Uyku düzeni
- **History of Mental Illness**: Psikiyatrik hastalık geçmişi
- **History of Substance Abuse**: Madde bağımlılığı geçmişi
- **Family History of Depression**: Ailede depresyon geçmişi
- **Chronic Medical Conditions**: Kronik tıbbi hastalıklar

## Veriye Genel Bakış

Bu projede, veri setinde yer alan sütunlar üzerinde çeşitli analizler ve görselleştirmeler yapılmıştır. Eksik veriler, uygun ortalama ve medyan değerlerle doldurulmuştur. Ayrıca, bazı sütunlar için "Bilinmiyor" gibi genel açıklamalar eklenmiştir. Bu veriler, daha sonra analizler için kullanıma uygun hale getirilmiştir.

## Grafikler

Aşağıdaki grafikler projede yer alan görselleştirmelerdir:

1. **Medeni Duruma Göre Yaş Dağılımı**: Medeni duruma göre yaşın nasıl dağıldığını gösteren bir kutu grafiği.
2. **Medeni Duruma Göre Eğitim Seviyesi Dağılımı**: Medeni duruma göre eğitim seviyesi dağılımını gösteren bir bar grafiği.
3. **Fiziksel Aktivite Düzeyine Göre Beslenme Alışkanlıkları**: Fiziksel aktivite düzeyine göre beslenme alışkanlıklarını gösteren bir bar grafiği.
4. **İş Durumuna Göre Gelir Dağılımı**: İş durumuna göre gelirin nasıl dağıldığını gösteren bir kutu grafiği.
5. **Madde Bağımlılığı Geçmişi ve Ailede Depresyon Geçmişi İlişkisi**: Madde bağımlılığı geçmişi ve ailede depresyon geçmişi arasındaki ilişkiyi gösteren bir bar grafiği.

## Kurulum

Bu projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. Bu projeyi yerel bir klasöre klonlayın:
   ```bash
   git clone https://github.com/yourusername/Depression-Substance-Abuse-Analysis.git
   ```

2-Gerekli Python kütüphanelerini yükleyin:

pip install -r requirements.txt

3-Verilerin bulunduğu dosyayı projenin ilgili dizinine yerleştirin ve data.csv dosyasına referans vererek projeyi çalıştırabilirsiniz.

Katkıda Bulunma
Bu proje açık kaynaklıdır ve katkılarınızı beklemektedir! Katkıda bulunmak için aşağıdaki adımları takip edebilirsiniz:

1-Bu projeyi çatallayın (fork).
2-Yeni bir özellik geliştirin veya hata düzeltmesi yapın.
3-Değişikliklerinizi bir pull request olarak gönderin.
