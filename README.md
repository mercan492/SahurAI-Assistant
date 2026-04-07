# SahurAI-Assistant
Python ile geliştirilmiş, sahur öğünleri için besin değeri analizi ve kişiselleştirilmiş su ihtiyacı hesaplama aracı. Kullanıcı girdisi temizleme (data cleaning), hata yönetimi ve matematiksel modelleme prensipleriyle kurgulanmıştır.
🤖 Gelişmiş AI Sahur Asistanı v2.0

Bu proje, sahur öğünlerinin besin değerlerini analiz eden ve kişiselleştirilmiş su tüketim ihtiyacını hesaplayan Python tabanlı bir CLI (Komut Satırı Arabirimi) uygulamasıdır.


Proje; veri temizleme (data cleaning), hata yönetimi (error handling) ve matematiksel modelleme prensipleriyle kurgulanmıştır.
✨ Temel Özellikler

    Dinamik Besin Analizi: Mevcut malzemelere göre toplam protein ve kalori hesaplaması.

    Veri Temizleme (Data Cleaning): Kullanıcıdan gelen karmaşık metin girdilerini (Python, lower(), replace(), split()) işleyerek standardize eder.

    Bilimsel Su Hesabı: Kişinin vücut ağırlığına göre bilimsel formüllerle günlük su ihtiyacı projeksiyonu.

    Hata Yönetimi (Robustness): Geçersiz kilo veya malzeme girişlerinde uygulamanın çökmesini engelleyen try-except blokları.
    

🧮 Matematiksel Model ve Mantık

Proje, su ihtiyacı hesaplamasında aşağıdaki biyolojik algoritmayı kullanır:

Su_Ihtiyaci(Litre)=Vu¨cut_Ag˘​ırlıg˘​ı×0.035

Sahurda içilmesi gereken minimum miktar ise toplam ihtiyacın 1/4’ü olarak modellenmiştir.


🛠️ Kullanılan Teknolojiler

    Dil: Python 3.x

    Kütüphaneler: random (Öneri motoru için altyapı)

    Konseptler: Sözlük (Dictionary) Yapıları, List Comprehension, Hata Ayıklama.
    ![GELİŞMİŞ AI SAHUR ASİSTANI Python 19 03 2026 3](https://github.com/user-attachments/assets/a3183df5-8b87-4b09-845f-09da62a91098)
    ![GELİŞMİŞ AI SAHUR ASİSTANI Python 19 03 2026 5](https://github.com/user-attachments/assets/df3a56c3-8cd5-49ac-aa96-eecfe0a7b937)


Geliştiren: Mercan Köseoğlu

Data Analyst & SAP ABAP Consultant
