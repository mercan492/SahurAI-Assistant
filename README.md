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
