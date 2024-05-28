# SAAT DEVRESİ
## DÖNEM PROJESİ

### 2023-Güz

Proje kapsamında bir dijital saat devresi tasarımı yapılmıştır. Tasarımda saat ledleri (00-23), dakika ledleri (00-59) ve saniye ledleri (00-59) kullanılmıştır. Her bir led bir sayacın çıktısı olarak kabul edilip belirtilen aralık boyunca saydırma işlemi yapmıştır. Saniye 59'a geldiğinde dakikayı, dakika 59'a geldiğinde saati tetiklemiştir yani arttırmıştır. Aşağıda devrede kullanılan kurallar verilmiştir.

- Saniye için MOD-60 sayacı, Dakika için MOD-60 sayacı, Saat için ise MOD-24 sayacı olmuştur.
- MOD sayaçların tasarımı için durum tablosu ve bu tabloya bağlı olarak flip floplarının denklemi çıkartılmıştır.
- D flip flop kullanılmıştır.
- Sayaç çıktıları 7 segment led üzerinde gösterilmiştir.

![Dijital Saat Tasarımı](dijital_saat_tasarimi.jpg)
