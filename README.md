🎯 Futbol Maç Tahmin Sistemi — Çok Ajanlı AI Destekli Analiz
Bu proje, 27.000+ maçlık büyük bir veri seti kullanarak, futbol maçlarının sonuçlarını tahmin etmek için çok ajanlı (multi-agent) yapay zeka destekli bir sistem geliştirmeyi amaçlamaktadır. Sistem, kullanıcının girdiği iddaa oranları (ev sahibi, beraberlik, deplasman) üzerinden çeşitli analiz ajanlarını çalıştırarak maç sonucu tahminleri üretir.Ve bununla kalmayıp üretilen tahminden tahmin hakkında sohbette edebilirsiniz.

🚀 Özellikler
📊 Gerçek maç verileriyle eğitilmiş tahmin altyapısı (27.000 maç)

🧠 5 farklı "ajan" ile maç sonucu analizleri:

Ajan 1: Oranlara göre filtreleme

Ajan 2: K-en yakın komşuluk benzerliği

Ajan 3: Yakın geçmiş analizleri

Ajan 4: Random Forest makine öğrenmesi modeli

Ajan 5: Bütün sonuçların ortalamasını alıp nihai kararı üretme

💬 Gemini (Google Generative AI) ile AI açıklamaları — her tahmin sonrasında AI analizini doğal bir dille açıklar

🧠 Kısa süreli hafıza sistemi ile bağlamlı AI sohbeti

📁 CSV ve Excel desteği ile veri yükleme

🎯 Yüzdelik tahmin çıktıları ile yüksek sezgisel analiz

🛠️ Nasıl Çalışır?
Kullanıcı, ev sahibi, beraberlik ve deplasman oranlarını girer.

Veritabanı taranır ve en yakın oranlara sahip geçmiş maçlar filtrelenir.

3 farklı ajandan gelen analizler toplanır ve Random Forest modelinin tahmini ile harmanlanır.

Nihai olasılık ve sonuç, tablolu biçimde kullanıcıya sunulur.

Gemini AI (Gemini 1.5 Flash) ile, tahmin doğal dilde açıklanır.

Kullanıcı dilerse AI ile diyaloğa devam edebilir.

📦 Kullanılan Teknolojiler
Python (pandas, numpy, scikit-learn, sqlite3)

Google Colab

Google Generative AI (Gemini 1.5 Flash API)

Random Forest Classifier

Rich (renkli konsol çıktıları için)

SQLite veritabanı

27.000 maçlık özel veri seti

ÖNEMLİ 
Veri setini Excel!e aktarıp daha sonrasında GOOGLE AI STUDİO'dan GOOGLE GEMİNİ API alıp GOOGLE COLAB'A entegre edip modeli çalıştırdıktan sonra veri setini yükledikten sonra oranlarınızı girip gerekirse sohbet şeklinde maç hakkında ek bilgiler de verebilip daha iyi tahminler yaptırabilirsiniz.
