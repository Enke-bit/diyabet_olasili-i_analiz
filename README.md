# Diyabet Veri Kümesi Analizi

Bu proje, diyabet tanısına odaklanan bir sağlık hizmetleri veri kümesinin analizini içerir. Veri kümesi, hastalarla ilgili çeşitli özellikleri kapsar ve diyabet olasılığını tahmin etmeye yönelik analizler yapmayı amaçlar.

## Veri Kümesi Açıklaması

Bu sağlık hizmeti diyabet veri seti, diyabet tanısına özel olarak odaklanarak, hastalarla ilgili kapsamlı bir dizi özelliği kapsar. Veri kümesi aşağıdaki anahtar sütunları içerir:

- **Pregnancies:** Bir hastanın hamile kalma sayısı.
- **Glucose:** Plazma glikoz konsantrasyonu.
- **BloodPressure:** Hastaların kan basıncı düzeyleri.
- **SkinThickness:** Triseps bölgesindeki deri kıvrımının kalınlığı.
- **Insulin:** Serum insülin seviyeleri.
- **BMI (Body Mass Index):** Vücut kitle indeksi.
- **DiabetesPedigreeFunction:** Aile öyküsüne dayalı diyabet olasılığı puanı.
- **Age:** Hastaların yaşı.
- **Outcome:** Diyabet hastası olup olmadığını gösteren ikili sonuç değişkeni (1: Evet, 0: Hayır).

## Proje Yapısı

- **data:** Veri kümesini içerir (`health care diabetes.csv`).
- **notebooks:** Veri analizinin yapıldığı Jupyter Notebook dosyasını içerir.
- **scripts:** Veri analizi ve görselleştirme için Python script dosyasını içerir.
- **README.md:** Proje hakkında genel bilgi ve talimatları içerir.

## Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki Python kütüphanelerine ihtiyaç vardır:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Gerekli kütüphaneleri yüklemek için:

```bash
pip install pandas numpy matplotlib seaborn
