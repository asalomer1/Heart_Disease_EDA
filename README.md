# Kalp Hastalığı Keşifsel Veri Analizi
Aygaz Veri Bilimi Bootcamp

Kalp hastalığı veri setinde birbirinden farklı sağlık verileri içeren bir veri setidir. (Diyabet geçirme durumu, Astımı bulunma durumu Cilt kanseri olma durumu vb..)

Veri setine aşağıya bıraktığım linkten ulaşıp veri seti hakkında daha detaylı bilgi edinebilirsiniz.

https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease


#### Değişkenler
1. HeartDisease = Kalp hastalığı bulunup bulunmadığı. (Makine öğrenmesi modelinin tahmin etmesi gereken parametre)
2. BMI = Beden kitle indeksi
3. Smoking = Sigara kullanma durumu
4. AlcoholDrinking = Alkol tüketme durumu
5. Stroke = Daha önce atak geçirilme durumu
6. PhysicalHealth = Son 30 gün içerisinde kaç günün fiziksel (sakatlık, hastalık vb.) sağlığın kötü olma durumu
7. MentalHealth	= Son 30 gün içerisinde kaç günün mental (stres, depresyon vb.) sağlığın kötü olma durumu
8. DiffWalking = Yürüme veya merdiven çıkma esnasında zorlanma olma durumu
9. Sex = Cinsiyet
10. AgeCategory = Yaş kategorisi
11. Race = Irk
12. Diabetic = Diyabet olma durumu
13. PhysicalActivity = Fiziksel aktivite yapılma durumu
14. GenHealth = Genel olarak sağlınızın nasıl olduğunu düşünüyorsunuz? 
15. SleepTime = Ortalama uyku saati
16. Asthma = Astım bulunma durumu
17. KidneyDisease = Böbrek rahatsızlığı bulunma durumu
18. SkinCancer = Cilt kanseri bulunma durumu

# Kaggle Hesabım
https://www.kaggle.com/asalomer1

#### Proje Senaryosu: 

* Bu çalışma, HeartDisease veri seti üzerinden analiz edilmiştir. Bu veri seti, bireylerin sağlık durumlarıyla ilgili çok sayıda değişken içermektedir ve kalp hastalığı riski üzerine odaklanmaktadır. Analizlerin amacı, bireylerin belirli sağlık verileri (örneğin, uyku süresi, sigara kullanımı, şeker hastalığı geçmişi, fiziksel aktivite düzeyi) ışığında kalp hastalığına yatkınlığını tahmin eden bir model geliştirmektir.

#### Problemin Çözüme Yönelik Potansiyeli
##### Sağlık Sektöründe Proaktif Çözümler:

* Bu veri seti, bireylerin sağlık durumları, yaşam alışkanlıkları ve demografik özellikleriyle kalp hastalığı gibi ciddi sağlık sorunları arasındaki ilişkileri anlamak için önemli bir kaynak sunuyor. İçerdiği bilgiler, halk sağlığını iyileştirmek ve bireylerin yaşam kalitesini artırmak adına farklı problemlerin çözümüne yönelik olarak kullanılabilir.

#### Risk Tahmini ve Önleyici Sağlık Politikaları:


 Veride yer alan sigara kullanımı, diyabet, uyku süresi ve genel sağlık durumu gibi değişkenler, kalp hastalığı gibi riskli durumların önceden tahmin edilmesini sağlayabilir. Örneğin, sigara içme alışkanlığı olan veya uyku süresi yetersiz bireyler, daha yüksek risk grubunda değerlendirilebilir. Bu analizler, bireysel sağlık taramalarında ve risk grubundaki kişilere özel tedbirlerin alınmasında kullanılabilir.

##### Eğitim ve Farkındalık Programları:
Elde edilen analizlerle, sigara kullanımı, fiziksel aktivite eksikliği veya düzensiz uyku gibi faktörlerin sağlık üzerindeki olumsuz etkileri daha iyi anlaşılabilir. Bu tür bilgiler, toplum genelinde farkındalık yaratmak ve sağlıklı yaşam alışkanlıklarını teşvik etmek amacıyla kullanılabilir. Örneğin, diyabetin fiziksel sağlık üzerindeki etkilerini vurgulayan eğitim programları geliştirilebilir.

#### Sağlık Hizmetlerinin Daha Etkin Yönetimi:
Sağlık hizmeti sunan kurumlar, bu analizlerden elde edilen bilgilerle kaynaklarını daha etkin bir şekilde yönetebilir. Örneğin, kalp hastalığı riski yüksek bireylerin daha sık kontrol edilmesi veya belirli bölgelerdeki sağlık kampanyalarının yoğunlaştırılması sağlanabilir.

#### Bireysel ve Toplumsal Sağlık Stratejileri:
Veri setinden elde edilen bulgular, bireylerin sağlık durumlarını iyileştirmek için uygulanabilir stratejiler geliştirilmesine yardımcı olabilir. Özellikle uyku süresi ve fiziksel aktivite gibi bireyin kontrol edebileceği faktörlerin üzerinde durularak yaşam kalitesinin artırılması hedeflenebilir.

#### Hedefli Kamu Sağlığı Yatırımları:
Elde edilen bilgiler, kamu sağlığına yönelik yatırımların doğru alanlara yönlendirilmesine katkı sağlayabilir. Örneğin, diyabet oranı yüksek bireylerin olduğu bölgelerde, bu sağlık sorununa yönelik klinik hizmetlerinin artırılması planlanabilir.

##### _Sonuç olarak, bu veri seti sadece bireysel düzeyde değil, aynı zamanda toplum genelinde uygulanabilecek stratejilere rehberlik edebilecek büyük bir potansiyele sahiptir. Sağlık riski yüksek bireylerin belirlenmesi ve bu bireylere yönelik kişiselleştirilmiş yaklaşımlar, hem bireylerin yaşam kalitesini artırabilir hem de sağlık hizmetlerinin etkinliğini artırabilir._


#### Analiz Sonuçları:
* Cinsiyet ve Kalp Hastalığı Arasındaki İlişki:

 Cinsiyet, kalp hastalığı riskini belirlemede anlamlı bir faktör olarak bulunmuştur (p < 0.05). Erkek bireylerde risk daha yüksek gözükmektedir.
* GenHealth ve Kalp Hastalığı Arasındaki İlişki:

 Genel sağlık durumu kötü olarak değerlendirilen bireylerin kalp hastalığı riski oldukça yüksektir. Bu değişkenin modelde güçlü bir etken olduğu tespit edilmiştir.

* En fazla bulunan yaş aralığı ise %12 ile "18-24" yaş aralığıdır.
* "American Indian/Alaskan Native" ırkı yani "Amerikan Kızılderelileri" olarak geçen ırk fiziksel sağlık bakımından en sağlıklı olanlarıdır.
* Korelasyon matrisinde numerikal verilerin birbirleriyle ilişkisi olmadığı gözlemlenmiştir.
#### Makine Öğrenmesi Model Önerisi
Problemin çözümü için önereceğim makine öğrenmesi modeli "Classification Algorithms - Sınıflandırma Algoritmaları" olacaktır, çünkü hedef değişkenimiz ikili (binary) kategoriktir (HeartDisease: 0 veya 1)
