# 🔔 Derin Öğrenme İle Kolon Kanserinin Sınıflandırılması

Kolon kanseri, gelişmiş ülkelerde ciddi bir sağlık sorunu olmakta ve en sık görülen kanser türleri arasında gelmektedir. Bu hastalığın erken teşhisi hastaların hayatta kalma şansını artırmaktadır. Geciken teşhisler ise ölümle sonuçlanabilmektedir.  Bu yüzden sağlıkta yapay zeka uygulamaları erken teşhis için büyük önem taşımaktadır.

Bu çalışmada Kolon Bt görüntülerinden kolon kanserinin sınıflandırılması üzerine bir çalışma yaptım.

İki farklı CNN modeli kullandım. Bunlardan biri hazır olan EfficientNetB0 modeli diğeri ise kendi geliştirdiğim basit CNN modeliydi.

İki modelide eğittim ve test ettim. 

Başarı sonuçlarını 4 farklı metrik(doğruluk,kesinlik,duyarlılık,F1-Score) ile kıyasladım.

Kendi geliştirdiğim model %100 F1-Score  elde ederek EfficientNetB0 modelini geride bıraktı.

✔️ CNN Modeli Başarı Sonuçları:

Accuracy: 99.65%

Precision: 1.00

Recall:    1.00

F1 Score:  1.00

✔️ EfficientNetB0 Modeli Başarı Sonuçları:

Accuracy: 81.73%

Precision: 0.83

Recall:    0.79

F1 Score:  0.80

