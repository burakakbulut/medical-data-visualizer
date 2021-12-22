## Medical Data Visualizer

Bu projede Pandas, Matplotlib ve Seaborn kütüphanelerini kullanarak medikal muayene verilerini görselleştirecek ve hesaplamalar yapacağız.

**Medikal Veri Seti**

Veri setindeki satırlar hastaları, sütunlar ise vücut ölçüleri, çeşitli kan testlerinin sonuçları ve yaşam tarzı seçimleri gibi bilgileri temsil eder. Kalp hastalığını, vücut ölçüleri, kan değerleri ve yaşam tarzı seçimleri arasındaki ilişkiyi keşfederek teşhis edeceğiz.

<img width="615" alt="medical_examination" src="https://user-images.githubusercontent.com/34520028/147151177-97febdf6-ba4e-4919-af3b-8ccd92a55cfd.png">

Aşağıdaki soruları Pandas, Matplotlib ve Seaborn kütüphanelerini kullanarak yanıtlayacağız.
- overweight adında bir sütun ekleyin. Bir kişinin fazla kilolu olup olmadığını belirlemek için öncelikle Vücut Kitle Endekisi’ni vücut ağırlığının boy uzunluğunun karesine bölerek hesaplayın Bu değer 25’ten fazla ise kişi fazla kiloludur. Fazla kilolu DEĞİL için 0 değerini ve fazla kilolu için 1 değerini kullanın.
- Kolesterol ve glikoz değelerinden 0 her zaman iyi, 1 ise her zaman kötüdür. Eğer kolesterol ve glikoz değerleri 1 ise 0 olarak güncelleyin. Değer 1 veya daha fazla ise 1 olarak güncelleyin.
- Veri setini cardio değişkenine göre bölerek yeni bir dataframe oluşturun. Pandas kütüphanesinden melt fonksiyonunu kullanarak sadece 'cholesterol', 'gluc', 'smoke', 'alco', 'active', ve 'overweight' değişkenlerini yeni dataframe dahil edin. Oluşturduğunuz dataframe’den Seaborn kütüphanesinin catplot() fonksiyonundan yararlanarak kategorik özelliklerin değer sayılarını gösteren aşağıdaki grafiği oluşturun.
