# ✈️ Havayolu Yolcu Memnuniyeti Veri Analizi Projesi

Bu proje, [Patika.dev](https://www.patika.dev/) ve [Kız Başına](https://kizbasina.com/) iş birliğinde düzenlenen **Veri Analizi Bootcamp** kapsamında gerçekleştirilmiş ilk bitirme projesidir. Projede, Kaggle üzerinden alınan [Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction) veri seti kullanılarak kapsamlı bir **veri analizi süreci** yürütülmüştür.

---

## 🎯 Projenin Amacı

Bu projenin temel hedefleri:

- Temel istatistiksel yöntemleri kullanarak veri setine dair içgörüler sunmak.
- Eksik ve aykırı verileri analiz etmek,
- Görsel araçlarla bulguları yorumlamak,
- Havayolu yolcu memnuniyetini etkileyen faktörleri analiz etmek,

---

## 🧾 Veri Seti Hakkında

Veri seti, bir havayolu şirketinin yolcularına sunduğu hizmetler hakkında yaptığı memnuniyet anketinin sonuçlarını içermektedir.

### 🔍 Öne Çıkan Değişkenler:
- `Gender`, `Age`, `Customer Type`
- `Type of Travel`, `Class`, `Flight Distance`
- `Inflight wifi service`, `Online booking`, `Gate location`, `Food and drink`
- `Online boarding`, `Seat comfort`, `Checkin service`, `Cleanliness`
- `Satisfaction` 

---

## 🔍 Proje Aşamaları

1. 📥 **Veri Setini Yükleme ve İlk İnceleme**  

2. 📊 **İstatistiksel Özetle**  

3. 🧩 **Eksik Değer Analizi**  

4. 🚨 **Aykırı Değer Tespiti**  

5. 📈 **Veri Görselleştirme**  

6. 🧠 **Sonuçların Yorumlanması**  


---

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

| Teknoloji     | 
|---------------|
| 🐍 Python      | 
| 📓 Jupyter     |
| 🧮 NumPy       |
| 🐼 Pandas      | 
| 📊 Matplotlib  | 
| 🐙 Seaborn     | 

---

## 📌 Sonuçlar

Yapılan analiz ve incelemeler sonucunda şu temel bulgulara ulaşılmıştır:

### 📉 Eksik ve Aykırı Değer Analizi
- `Arrival Delay in Minutes` sütununda **310 eksik veri** tespit edilmiştir. Bu, tüm veri setinin yaklaşık **%0.30**’una karşılık gelmektedir.
- **IQR yöntemi** ile yapılan aykırı değer analizinde aşağıdaki sütunlarda dikkat çeken sapmalar gözlemlenmiştir:
  - ✈️ **Flight Distance**: Uzun mesafeli uçuşları temsil eden aykırı değerler (%2.20), analizlerde özel dikkat gerektirir.
  - 🛫 **Check-in Service**: Puanlama skalasının alt sınırında yoğunlaşan aykırılıklar (%12.41), veri toplama süreçlerindeki tutarsızlıkları işaret edebilir.
  - 🕒 **Departure Delay in Minutes**: Yüksek gecikme süreleri içeren aykırı değerler (%13.98), memnuniyet analizlerinde etkili olabilir.
  - 🛬 **Arrival Delay in Minutes**: Benzer şekilde yüksek varış gecikmeleri (%13.43), yolcu deneyimini negatif etkileyen unsurlar arasında yer alır.


### 📊 Memnuniyet Üzerine Bulgular
- 🧍‍♂️ **Müşteri Tipi**, memnuniyet üzerinde önemli bir belirleyici faktördür. Sadık müşteriler genel olarak daha memnundur.
- 🎟️ **Online Biniş**, 🍿 **Uçak İçi Eğlence**, 💺 **Koltuk Konforu** ve ☕ **Uçak İçi Servis**, memnuniyeti doğrudan etkileyen hizmet alanlarıdır.
- 📏 **Uçuş Mesafesi** arttıkça memnuniyetin de artma eğiliminde olduğu gözlemlenmiştir; özellikle kısa ve orta mesafeli uçuşlarda geliştirme potansiyeli bulunmaktadır.
- 🕑 **Gecikmeler** (kalkış/varış) memnuniyeti olumsuz etkilese de bu etkinin, uçuş içi hizmet kalitesi kadar belirleyici olmadığı bulunmuştur.

---

## 👩‍💻 Geliştirici Hakkında

Merhaba! Ben Yaren Ayan. Bu proje, veri analizi becerilerimi geliştirmek amacıyla Patika.dev & Kız Başına Bootcamp'inde gerçekleştirdiğim bitirme projesi çalışmasıdır. Her türlü öneri ve geri bildiriminiz için bana ulaşabilirsiniz.

* 📧 İletişim: ayanyaren@hotmail.com
* 📌 GitHub: [@yarenayan](https://github.com/yarenayan)  
* 🔗 LinkedIn: [www.linkedin.com/in/yaren-ayan](https://www.linkedin.com/in/yaren-ayan)


---

