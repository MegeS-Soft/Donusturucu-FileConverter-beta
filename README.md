# Donusturucu-FileConverter v1.0-beta 🚀

Donusturucu-FileConverter, günlük dosya dönüştürme ihtiyaçlarını hızlı ve pratik bir şekilde karşılamak için geliştirilmiş bir **masaüstü dosya dönüştürücü uygulamadır**.

Bu proje şu anda **Beta sürümündedir** ve aktif olarak geliştirilmeye devam etmektedir.

---

## ✨ Özellikler

- 📄 **CSV → Excel (XLSX)** dönüştürme  
- 📄 **PDF → Word (DOCX)** dönüştürme  
- 📊 Excel çıktılarında sayısal veri formatlama desteği  
- 🖱️ Basit ve kullanıcı dostu arayüz  
- 📁 Sürükle & bırak dosya desteği  
- 🖥️ Windows masaüstü uygulaması (WinForms)

---

## 🛠️ Desteklenen Dönüşümler

| Kaynak Dosya | Hedef Dosya |
|-------------|------------|
| CSV         | Excel (.xlsx) |
| PDF         | Word (.docx) |

---

## ⚙️ Teknik Altyapı

- **Dil:** C# (.NET)
- **Arayüz:** WinForms
- **CSV İşleme:** CsvHelper
- **Excel Oluşturma:** ClosedXML
- **PDF → Word:** Microsoft Word Interop

> ⚠️ PDF → Word dönüşümü için bilgisayarınızda **Microsoft Word yüklü olmalıdır**.

---

## ⏳ PDF → Word Dönüşümü Neden Biraz Daha Yavaş?

PDF dosyalarının Word formatına dönüştürülmesi, doğası gereği daha karmaşık bir işlemdir.

Bu uygulama, PDF → Word dönüşümünde **Microsoft Word’ün kendi içe aktarma motorunu** kullanır.  
Bu sayede:

- Tablolar
- Görseller
- Sayfa düzeni
- Türkçe karakterler

mümkün olan en doğru şekilde korunur.

👉 Ancak bu yöntem, sistemin Word altyapısını kullandığı için **dosya boyutuna ve içeriğe bağlı olarak biraz daha zaman alabilir**.

Bu durum bir hata değil; **daha kaliteli ve doğru dönüşüm sağlamak için bilinçli bir tercihtir**.

---

## 🧪 Beta Sürüm Hakkında

Bu proje şu anda **Beta** aşamasındadır.

Bu ne anlama gelir?
- ✔️ Uygulama çalışır ve kullanılabilir durumdadır
- ✔️ Temel özellikler stabildir
- 🔄 Performans iyileştirmeleri ve yeni özellikler eklenebilir
- 💡 Geri bildirimlere açıktır

İlerleyen sürümlerde:
- Performans optimizasyonları
- Yeni format destekleri
- Kullanıcı deneyimi iyileştirmeleri
planlanmaktadır.
