# Financial Time Series Sector Analysis with Machine Learning 
*Sector analysis and classification of stocks using financial time series data and feature extraction with TSFresh*

---

## 📈 Sektörel Hisse Senedi Davranış Benzerliği Analizi

### 🔍 Proje Hakkında  
Bu projede, YFinance üzerinden alınan hisse senedi fiyat verileri kullanılarak, farklı sektörlerde yer alan şirketlerin belirli zaman aralıklarındaki fiyat davranışları analiz edilmiştir. Amaç, hisse senetlerinin dönemsel performansları üzerinden, hangi sektörlerin birbirine benzer davranışlar sergilediğini tespit etmektir.

Zaman serisi verileri üzerinde TSFresh kütüphanesi ile kapsamlı öznitelik çıkarımı yapılmış, ardından makine öğrenmesi modelleri ile sektörel sınıflandırma ve benzerlik analizi gerçekleştirilmiştir.

### ⚙️ Kullanılan Yöntemler ve Teknolojiler  
- **YFinance:** Hisse senedi verilerinin çekilmesi  
- **TSFresh:** Zaman serisi üzerinden otomatik öznitelik çıkarımı  
- **Pandas, NumPy, Scikit-learn:** Veri işleme ve makine öğrenmesi  
- **XGBoost, Random Forest:** Sınıflandırma ve benzerlik tahmini için ML algoritmaları  
- **Matplotlib, Seaborn:** Görselleştirme  

### 🧠 Uygulanan Süreç  

**Veri Toplama:**   
  - Finans  
  - Sağlık  
  - Teknoloji  
- Her sektörden 500'er adet şirket hisse senedi rastgele örneklem yöntemiyle seçildi.

**Veri Hazırlama:**  
- Seçilen şirketlerin geçmiş fiyat verileri, YFinance API'si kullanılarak çekildi.  
- Veriler aylık bazda getirilere dönüştürülerek, zaman serisi formatına uygun hale getirildi.

**Öznitelik Çıkarımı:**  
- TSFresh kütüphanesi ile zaman serisi verilerinden öznitelik çıkarımı ve öznitelik seçimi yapıldı.

***Finansal Faktör Analizi***
- Momentum  ,Volatilite, MACD (Moving Average Convergence Divergence)  ,Hareketli Ortalamalar (Moving Averages)  

**Modelleme ve Benzerlik Analizi:**  
- Makine öğrenmesi algoritmaları ile, farklı sektörlerdeki şirketlerin fiyat davranışları analiz edildi.  
- Amaç, diğer başka sektörlerdeki şirketlerin, Finans, Sağlık veya Teknoloji sektörlerinden hangisine daha benzer davranış sergilediğinin tahmin edilmesi.
---

### 📊 Sonuçlar  
- Bu çalışma kapsamında, farklı sektörlere ait hisse senetlerinin belirli zaman aralıklarındaki fiyat değişimleri analiz edilerek, sektörler arası davranış benzerliklerinin tespit edilmesi amaçlanmıştır. Yapılan analizler sonucunda, sektörlerin dönemsel getiri eğilimlerinin belirli koşullar altında birbirine yakınlık gösterdiği gözlemlenmiştir. Ekonomik dalgalanmaların veya makroekonomik olayların etkili olduğu dönemlerde, bazı sektörlerin senkronize şekilde hareket ettiği söz konusudur 
- Uygulanan zaman serisi analizleri ve öznitelik çıkarımı yöntemleriyle, hisseler ve başka sektörler arası korelasyon düzeyleri hesaplanmış; davranışsal olarak birbirine en yakın çiftleri başarılı bir şekilde belirlenmiştir..  
- Bu bulgular, yatırım portföyü oluşturulması ve risk dağılımı açısından yol gösterici niteliktedir.  
- Özellikle tedarik zinciri yönetimi bağlamında, sektörler arası davranışsal benzerliklerin bilinmesi, paydaşların ve iş ortaklarının daha bilinçli şekilde seçilmesine olanak tanımaktadır. Finansal dalgalanmalara benzer tepki veren sektörlerde faaliyet gösteren tedarikçilerin veya müşterilerin birlikte değerlendirilmesi, operasyonel dayanıklılığı artırabilir ve bütünleşik risk yönetimini kolaylaştırabilir.
- Geliştirilen benzerlik analizi mekanizması, piyasa senkronizasyonlarını erken fark etmeye yardımcı olabilir.
---





