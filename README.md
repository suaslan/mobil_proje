# Yapay Zekâ Destekli Kişiselleştirilmiş İngilizce Öğrenme Mobil Uygulaması

Mobil Programlama Projesi Flutter, FastAPI ve PostgreSQL tabanlı; İngilizce öğrenme sürecini altı dil yeterliliği bileşeni üzerinden izleyen, yapay zekâ destekli pratikler ve kişiselleştirilmiş öğrenme önerileri sunan çapraz platform mobil uygulama projesi. Proje adı: Henüz belirlenmemiştir. Bu dokümanda özel bir ürün veya marka adı kullanılmamıştır.

## İçindekiler

1. Proje Tanımı ve Problem Analizi

2. Amaç, Hedefler ve Kapsam

3. Sistem Mimarisi

4. Seviye Tespiti ve Değerlendirme Sistemi

5. Kişiselleştirilmiş Öğrenme Motoru

6. Yapay Zekâ Destekli Modüller

7. Kelime Tekrarı ve Kalıcılık

8. Kişisel Öğrenme Paneli ve Oyunlaştırma

9. İş Bölümü ve 10 Haftalık Çalışma Takvimi

10. Güvenlik, Gizlilik, KVKK/GDPR ve Etik

11. Test ve Kalite Güvence

12. Riskler, Azaltma Stratejileri ve Sonuç

13. Kaynakça ve Teknik Başvuru

## 1. PROJE TANIMI VE PROBLEM ANALİZİ

### 1.1. Projenin Tanımı

Proje; kullanıcının İngilizce seviyesini belirleyen, altı temel dil yeterliliği bileşenini ayrı ayrı değerlendiren, kişisel hedeflerine göre öğrenme programı hazırlayan ve yapay zekâ destekli pratiklerle öğrenme sürecini destekleyen çapraz platform bir mobil eğitim uygulamasıdır. Uygulamanın temel çalışma döngüsü aşağıdaki şekilde tasarlanmıştır: Başlangıç değerlendirmesi → Öğrenme profilinin oluşturulması → Kişiselleştirilmiş ders ve pratik → Performansın ölçülmesi → Öğrenme planının güncellenmesi Bu yaklaşım sayesinde uygulama yalnızca tek seferlik bir seviye tespit aracı olarak kalmaz; kullanıcının zaman içindeki performansını izleyen ve öğrenme önerilerini bu verilere göre güncelleyen bir sistem sunar.

### 1.2. Problem Alanı

Dil öğrenen kişiler aynı genel seviyede olsalar bile farklı beceri profillerine sahip olabilir. Bir kullanıcı okuduğu metinleri rahatlıkla anlayabilirken konuşma sırasında zorlanabilir. Başka bir kullanıcı geniş kelime bilgisine sahip olmasına rağmen dil bilgisi veya yazılı anlatım konusunda eksiklik yaşayabilir. Bu nedenle yalnızca tek bir genel puan üzerinden değerlendirme yapmak, kullanıcının gerçek ihtiyaçlarını yeterince açıklamayabilir. Standart öğrenme uygulamalarında içeriklerin herkese aynı sırayla sunulması, kullanıcının zaten bildiği konularda gereksiz zaman harcamasına veya eksik olduğu alanlarda yeterli tekrar yapamamasına neden olabilir. Özellikle konuşma ve yazma gibi üretim becerilerinde yalnızca doğru/yanlış geri bildirimi verilmesi de gelişim için yeterli değildir.

### 1.3. Önerilen Çözüm

Sistem, altı bileşene ilişkin performans verilerini ayrı tutar ve kullanıcının öğrenme amacı, günlük ayırabileceği süre, konu bazlı başarısı ve uygulama içi performansını birlikte değerlendirir. Öğrenme motoru; konu önerilerini, tekrar zamanlarını ve pratik türlerini bu profile göre düzenler. Yapay zekâ bileşenleri özellikle açık uçlu yazılı yanıtların değerlendirilmesi, konuşma pratiği, diyalog oluşturma ve açıklamalı geri bildirim üretme süreçlerinde kullanılır. Böylece kullanıcı yalnızca genel bir seviye sonucu görmek yerine hangi alanlarda güçlü olduğunu ve hangi alanlarda gelişmesi gerektiğini takip edebilir.

## 2. AMAÇ, HEDEFLER VE KAPSAM

### 2.1. Genel Amaç

İngilizce öğrenen kullanıcıların dil yeterliliklerini ölçülebilir ve sürdürülebilir biçimde geliştirmesine yardımcı olan, kişiselleştirilmiş ve yapay zekâ destekli bir mobil öğrenme platformu geliştirmek.

### 2.2. Proje Hedefleri

- Kullanıcının başlangıç seviyesine ilişkin CEFR ile ilişkilendirilmiş tahmini bir öğrenme profili oluşturmak.

- Grammar, Vocabulary, Reading, Listening, Writing ve Speaking bileşenlerini ayrı ayrı değerlendirmek.

- Kullanıcının hedeflerine ve performansına göre günlük öğrenme planı oluşturmak.

- Yapay zekâ destekli konuşma ve yazma pratiği sağlamak.

- Kelime ve konu tekrarlarını aralıklı tekrar yaklaşımıyla planlamak.

- Haftalık ve aylık gelişimi anlaşılır göstergelerle sunmak.

- Yeni dil ve modüllerin eklenmesine elverişli, modüler bir altyapı oluşturmak.

### 2.3. Hedef Kullanıcı ve Öğrenme Amaçları

Hedef kitle; İngilizceye yeni başlayanlardan ileri seviyedeki kullanıcılara, öğrencilerden günlük iletişim veya profesyonel kullanım amacı taşıyan kişilere kadar geniştir. Kullanıcı, ilk kullanım sırasında aşağıdaki öğrenme amaçlarından birini veya birkaçını seçebilir:

- Günlük İngilizce

- İş ve profesyonel İngilizce

- Akademik İngilizce

- Genel dil gelişimi

Hedef kullanıcı kitlesinde farklı yaş grupları bulunabileceği için çocuk kullanıcıların veri işleme, yaşa uygun içerik ve ebeveyn izni gereksinimleri ayrıca değerlendirilmelidir.

### 2.4. İlk Sürüm Kapsamı (MVP)

İlk sürümün hedef dili İngilizcedir. Uygulama Flutter kullanılarak iOS ve Android platformları için geliştirilecektir. İlk sürümde (MVP) yer alması planlanan özellikler:

- Kullanıcı kaydı, giriş ve profil yönetimi

- Onboarding ve öğrenme hedeflerinin belirlenmesi

- Altı bileşeni kapsayan başlangıç seviye tespit akışı

- Seviye ve beceri etiketleriyle düzenlenmiş temel soru havuzu

- Beceri bazlı sonuç ekranı ve tahmini CEFR profili

- Kural tabanlı kişiselleştirilmiş görev önerileri

- Temel kelime tekrar sistemi

- Yapay zekâ destekli Writing ve Speaking pratikleri

- Günlük öğrenme planı ve gelişim paneli

MVP dışında bırakılan veya sonraki sürümlerde ele alınabilecek özellikler:

- IRT/CAT tabanlı psikometrik adaptif test sistemi

- Tam çevrimdışı çalışma

- Öğretmen ve kurum yönetim paneli

- Sosyal öğrenme ve grup çalışması

- Birden fazla hedef dil için içerik

- Resmî sınav sertifikasyonu veya resmî yeterlilik belgesi

Bu sınırlar, ilk sürümün belirlenen süre içinde tamamlanabilmesini ve temel kullanıcı akışlarının güvenilir biçimde çalışmasını hedefler.

## 3. SİSTEM MİMARİSİ

### 3.1. Mimari Yaklaşım

Önerilen yapı katmanlı istemci-sunucu mimarisidir. Flutter mobil istemcisi kullanıcı etkileşimini yönetir. Backend, kimlik doğrulama sonrasında istekleri doğrular ve iş kurallarını yürütür. Değerlendirme, öğrenme ve yapay zekâ servisleri ilgili işlemleri gerçekleştirir. PostgreSQL ise kullanıcı, içerik, değerlendirme ve ilerleme verilerini saklar. Harici yapay zekâ servisleri mobil uygulamadan doğrudan çağrılmaz. API anahtarları ve servis kimlik bilgileri yalnızca güvenli sunucu ortamında tutulur.

### 3.2. Sistem Bileşenleri

| Bileşen | Sorumluluk |
| --- | --- |
| Flutter mobil istemci | Ekranlar, navigasyon, yerel durum, mikrofon izni ve API iletişimi |
| API / Backend | İstek doğrulama, yetkilendirme, iş kuralları ve servis orkestrasyonu |
| Kullanıcı servisi | Profil, hedefler, oturum ve hesap yaşam döngüsü |
| Assessment servisi | Test oturumları, soru havuzu, yanıtlar ve beceri puanları |
| Learning servisi | Öğrenme planı, görevler, konu ilerlemesi ve tekrar takvimi |
| AI Gateway | LLM, Speech-to-Text ve Text-to-Speech sağlayıcılarına kontrollü erişim |
| PostgreSQL | Kullanıcı, içerik, değerlendirme ve ilerleme kayıtları |
| Bildirim servisi | Kullanıcının tercih ettiği zamanlarda öğrenme hatırlatmaları |

### 3.3. Önerilen Teknoloji Yığını

| Katman | Teknoloji / Yaklaşım | Kullanım Amacı |
| --- | --- | --- |
| Mobil uygulama | Flutter | Tek kod tabanıyla iOS ve Android geliştirme |
| Programlama dili | Dart | Flutter uygulamasının temel dili |

| Katman | Teknoloji / Yaklaşım | Kullanım Amacı |
| --- | --- | --- |
| Mobil mimari | MVVM + Repository Pattern | Arayüz, iş mantığı ve veri erişimini ayırma |
| Durum yönetimi | Riverpod | Oturum, profil, test, öğrenme planı ve AI oturum durumlarını yönetme |
| Backend | Python / FastAPI | API, iş kuralları ve yapay zekâ servis orkestrasyonu |
| Veritabanı | PostgreSQL | İlişkisel kullanıcı, içerik ve ilerleme verileri |
| Kimlik doğrulama | Supabase Auth | Kullanıcı hesabı ve oturum yönetimi |
| Yapay zekâ entegrasyonu | Backend üzerinden LLM API | Güvenli ve kontrollü model erişimi |
| Bilgi getirme | RAG | Doğrulanmış kaynaklara dayalı açıklama üretimi |
| Ses işleme | Speech-to-Text / Text-to-Speech | Konuşma girdisi ve sesli içerik üretimi |
| Bildirim | Firebase Cloud Messaging | iOS ve Android bildirim altyapısı |
| Sürüm kontrolü | Git / GitHub | Ekip çalışması, kod inceleme ve sürüm takibi |

### 3.4. Veri Akışı

Kullanıcı uygulamada test yanıtı gönderdiğinde Flutter istemcisi, oturum belirteciyle birlikte backend API'sine istek iletir. Backend kullanıcının kimliğini ve yetkisini doğrular, gelen verinin biçimini kontrol eder, ilgili değerlendirme servisini çağırır ve sonucu veritabanına kaydeder. Kişiselleştirme gerekiyorsa öğrenme motoru yeni performans kaydını kullanarak görev önceliklerini günceller. Sonuç mobil istemciye döndürülür. Sesli konuşma akışı: 1. Kullanıcıdan mikrofon izni alınır. 2. Ses girdisi yakalanır. 3. Ses, gerekiyorsa güvenli bağlantı üzerinden ses işleme servisine aktarılır. 4. ASR/STT katmanı sesi metne dönüştürür. 5. ASR güven skoru kontrol edilir. 6. Güvenilir bulunan metin, görev rubriği ve doğrulanmış bilgi kaynakları kullanılarak değerlendirilir. 7. Diyalog yanıtı oluşturulur ve gerekiyorsa TTS ile seslendirilir. 8. Oturum özeti ve gerekli performans göstergeleri kaydedilir. Ham sesin kalıcı olarak saklanması varsayılan tasarım değildir. Sesin saklanması teknik olarak gerekli hâle gelirse işleme amacı, saklama süresi, silme yöntemi ve kullanıcı tercihleri önceden açıklanmalıdır.

### 3.5. Mobil Uygulama İç Mimarisi

Flutter istemcisinde MVVM ve Repository Pattern yaklaşımı kullanılacaktır.

- View: Ekranları ve kullanıcı arayüzünü gösterir.

- ViewModel: Ekran durumunu ve kullanıcı eylemlerini yönetir.

- Repository: Veri kaynaklarını soyutlar.

- Service: API veya cihaz servisleriyle iletişim kurar.

Riverpod; kullanıcı oturumu, profil, seviye testi, öğrenme planı, günlük görevler ve yapay zekâ konuşma oturumlarının durumunu yönetmek için kullanılacaktır. Bu yapı arayüz, durum yönetimi, iş mantığı ve veri erişimini birbirinden ayırarak test edilebilirliği ve bakım kolaylığını artırır.

### 3.6. Temel Veri Varlıkları

| Varlık / Tablo | Örnek İçerik ve Amaç |
| --- | --- |
| Users | Kimlik sağlayıcı kimliği, e-posta referansı ve oluşturulma tarihi |
| UserProfiles | Öğrenme hedefi, çalışma süresi ve kullanıcı tercihleri |

| Varlık / Tablo | Örnek İçerik ve Amaç |
| --- | --- |
| Questions | Soru metni, tür, seviye, beceri, konu ve cevap anahtarı |
| AssessmentSessions | Test oturumu, başlangıç/bitiş zamanı ve durum |
| AssessmentResponses | Kullanıcı yanıtı, yanıt süresi ve puan |
| SkillAssessments | Beceri bazlı sonuç ve tahmini seviye |
| Lessons / Topics | Ders içeriği, kazanım, seviye ve konu ilişkisi |
| VocabularyItems | Kelime, anlam, tür, telaffuz ve örnek |
| UserVocabulary | Öğrenme durumu, son/sonraki tekrar ve başarı geçmişi |
| LearningPlans / DailyTasks | Kişiselleştirilmiş plan ve görev durumu |
| SpeakingSessions | Senaryo, oturum zamanı ve özet performans |
| WritingSubmissions | Kullanıcı metni, görev ve değerlendirme özeti |
| ProgressRecords | Zaman damgalı beceri ve etkinlik göstergeleri |

Bu veri modeli ilk tasarım önerisidir. Uygulama geliştirilirken ilişkiler, indeksler, veri saklama süreleri ve erişim politikaları gerçek API ve ekran gereksinimlerine göre netleştirilecektir.

## 4. SEVİYE TESPİTİ VE DEĞERLENDİRME SİSTEMİ

### 4.1. Onboarding

İlk kullanımda kullanıcıdan hedef dil, öğrenme amacı, günlük çalışma süresi ve isteğe bağlı öz değerlendirme bilgisi alınır. Kullanıcı seviyesini bilmiyorsa yerleştirme testine yönlendirilir. Öz değerlendirme, test sonucunun yerine geçmez; yalnızca başlangıç bağlamı sağlar.

### 4.2. Altı Değerlendirme Bileşeni

Bu projede altı bileşen ayrı ayrı takip edilir. Akademik açıdan Grammar ve Vocabulary dilsel yeterlilik bileşenleri; Reading, Listening, Writing ve Speaking ise temel iletişim becerileri olarak ele alınır. Bu ayrım, altı bileşenin CEFR'de aynı kategoride tanımlandığı anlamına gelmez.

| Bileşen | Ölçülecek Örnek Yetkinlikler |
| --- | --- |
| Grammar | Zamanlar, cümle yapısı, edatlar, bağlaçlar ve dil bilgisi doğruluğu |
| Vocabulary | Kelime anlamı, bağlam, kelime türü, eş/zıt anlam ve kullanım |
| Reading | Ana fikir, detay, çıkarım ve bağlamdan anlam çıkarma |
| Listening | Ana fikir, ayrıntı, konuşma hızı ve farklı aksanları anlama |
| Writing | Dil bilgisi, kelime çeşitliliği, tutarlılık ve anlatım açıklığı |
| Speaking | Anlaşılabilirlik, akıcılık, kelime kullanımı, dil bilgisi ve etkileşim |

### 4.3. CEFR ile İlişkilendirme

İçerikler ve görevler A1, A2, B1, B2, C1 ve C2 düzeyleriyle eşleştirilir. CEFR yalnızca kelime veya dil bilgisi zorluğu olarak yorumlanmamalı; kullanıcının gerçek iletişim görevlerini ne ölçüde yerine getirebildiği dikkate alınmalıdır. Her bileşen için ayrı seviye tahmini tutulur. Örnek kullanıcı profili:

| Bileşen | Örnek Tahmini Düzey |
| --- | --- |
| Grammar | B1 |
| Vocabulary | B2 |
| Reading | B2 |
| Listening | B1 |
| Writing | A2 |
| Speaking | A2 |

Bu profil, kullanıcının okuma ve kelime bilgisinin daha güçlü; yazma ve konuşma becerilerinin ise daha fazla çalışmaya ihtiyaç duyduğunu gösterir. Tek bir genel seviye gösterilecekse bunun beceri sonuçlarından türetilmiş özet bir gösterge olduğu açıkça belirtilmelidir.

### 4.4. Test Tasarımı ve Önerilen Başlangıç Kapsamı

Test havuzu; seviye, beceri, konu, soru türü ve hedef kazanım etiketleriyle saklanır. Çoktan seçmeli sorular otomatik puanlanabilir. Yazma ve konuşma görevleri ise ölçüt tabanlı rubrikler ve yapay zekâ destekli değerlendirme ile analiz edilir.

| Bileşen | Önerilen Başlangıç Kapsamı | Ölçüm Yöntemi | Değerlendirme Çıktısı |
| --- | --- | --- | --- |
| Grammar | 20 soru | Çoktan seçmeli / boşluk doldurma | Dil bilgisi düzeyi ve konu eksikleri |
| Vocabulary | 20 soru | Bağlam içinde anlam / kelime seçimi | Kelime bilgisi düzeyi ve konu eksikleri |
| Reading | 10 soru | Kısa ve uzun metin anlama | Okuma düzeyi |
| Listening | 10 soru | Kısa diyalog ve konuşma anlama | Dinleme düzeyi |
| Writing | 2 görev | Kısa yazı ve düzeye uygun üretim görevi | Yazma rubriği puanı ve geri bildirim |
| Speaking | 2 görev | Kendini tanıtma veya konu üzerinden konuşma | Konuşma rubriği puanı ve geri bildirim |

Bu soru ve görev sayıları ilk prototip için öneridir; geçerlilik ve güvenirlik çalışması yapılmış nihai test uzunluğu değildir. Kullanıcı deneyimi ve ölçüm kalitesi pilot uygulama sonrasında birlikte değerlendirilerek güncellenmelidir.

### 4.5. Puanlama ve Değerlendirme Çıktıları

- Altı bileşen için ayrı puan veya performans bandı üretilir.

- Her sonuç, yeterli ölçüm verisi bulunduğunda CEFR A1-C2 ile ilişkilendirilmiş tahmini düzey ve güven

göstergesiyle sunulur.

- Writing ve Speaking değerlendirmelerinde göreve özel rubrikler kullanılır.

- Rubrikler göreve uygunluk, anlaşılabilirlik, dil bilgisel doğruluk, kelime çeşitliliği, tutarlılık ve akıcılık gibi

ölçütleri içerebilir.

- Telaffuz değerlendirmesi yalnızca otomatik konuşma tanıma çıktısına dayandırılmaz.

- Yapay zekâ geri bildirimi, rubrik puanını açıklayan örneklerle desteklenir.

- Hatalı veya belirsiz değerlendirmelerde kesin hüküm yerine kullanıcıya tekrar hakkı ve gelişim önerisi sunulur.

- Test tamamlandığında beceri profili, öncelikli gelişim alanları, önerilen günlük çalışma planı ve tekrar edilecek

kelime/konu listesi oluşturulur.

### 4.6. Madde Havuzu ve Kalite Güvencesi

- Her soru; CEFR düzeyi, hedeflenen öğrenme çıktısı, konu etiketi, zorluk seviyesi ve doğru cevap/açıklama

bilgisiyle etiketlenir.

- A1-C2 aralığının dengeli kapsanması hedeflenir.

- Tekrar testlerinde aynı soruların ezberlenmesini azaltmak için eşdeğer zorlukta paralel soru formları hazırlanır.

- Pilot uygulamada madde güçlüğü, ayırt edicilik, tamamlanma oranı, süre ve kullanıcı geri bildirimi incelenir.

- Sorunlu maddeler yeniden yazılır veya havuzdan çıkarılır.

- Yazma ve konuşma puanlamasında insan değerlendiricilerle örneklem kontrolü yapılarak yapay zekâ

puanlarının tutarlılığı izlenir.

### 4.7. Akademik Referans Çerçevesi

Testin ana referans çerçevesi, Avrupa Konseyi tarafından yayımlanan CEFR Companion Volume olmalıdır. CEFR; A1-C2 düzeylerini tanımlayan betimleyiciler sunar ve dil kullanımını anlama, üretme, etkileşim ve aracılık gibi iletişimsel etkinlikler üzerinden ele alır. İngilizce dil bilgisi ve kelime maddelerinin düzeylere göre seçilmesinde English Profile, özellikle English Grammar Profile ve English Vocabulary Profile, yardımcı kaynak olarak kullanılabilir. Cambridge English Skills Test ve Oxford Test of English ise beceri bazlı değerlendirme ve modüler test akışı açısından karşılaştırmalı tasarım örnekleri olarak incelenebilir. Ticari sınavların korunan soru içerikleri kopyalanmayacak; yalnızca kamuya açık çerçeve, açıklama ve örnek görev türlerinden yararlanılarak özgün maddeler geliştirilecektir. Uygulama sonucu “tahmini CEFR düzeyi” olarak adlandırılacak; Cambridge veya Oxford sınavlarının resmî sonucu, denkliği ya da sertifikası izlenimi verilmeyecektir.

## 5. KİŞİSELLEŞTİRİLMİŞ ÖĞRENME MOTORU

### 5.1. Amaç ve Girdiler

Öğrenme motoru, başlangıç testini ve uygulama içi öğrenme kayıtlarını kullanarak kullanıcıya hangi içeriğin, hangi sırayla ve ne zaman sunulacağını belirler. Başlıca girdiler:

- Altı bileşene ait performans sonuçları

- Konu bazlı başarı ve hata örüntüleri

- Kelime tekrar geçmişi

- Görev tamamlama durumu

- Yanıt süresi ve tekrar başarısı

- Kullanıcının öğrenme hedefi

- Günlük kullanılabilir çalışma süresi

- Kullanıcının içerik ve bildirim tercihleri

### 5.2. MVP'de Kullanılacak Öğrenme Modeli

İlk sürümde IRT (Item Response Theory) ve CAT (Computerized Adaptive Testing) kullanılmayacaktır. Bu modellerin 4. bölümdeki başlangıç testinde zorunlu olmadığı belirtilen kapsamla çelişmemesi için MVP'de kural tabanlı ve statik soru havuzuna dayalı bir yaklaşım uygulanacaktır. MVP kapsamında: 1. Sorular önceden hazırlanmış ve etiketlenmiş bir havuzdan seçilir. 2. Sorular beceri, konu ve hedeflenen düzey bilgileriyle saklanır. 3. Çoktan seçmeli sorular cevap anahtarına göre puanlanır. 4. Writing ve Speaking görevleri tanımlı rubrikler üzerinden değerlendirilir. 5. Altı bileşenin sonuçları ayrı ayrı tutulur.

6. Öğrenme motoru düşük performans gösterilen ve kullanıcının hedefiyle ilişkili alanlara daha fazla görev önceliği verir. Bu aşamadaki kural tabanlı puanlama ve öneriler, ürünün ilk sürümünü çalıştırmak için kullanılan başlangıç yaklaşımıdır. Pilot verilerle doğrulanmadan bilimsel olarak kalibre edilmiş psikometrik ölçüm veya kesin CEFR yeterliliği olarak sunulmayacaktır.

### 5.3. Faz-2: IRT ve CAT Tabanlı Geliştirmeler

IRT ve CAT, soru güçlüğü ve ayırt ediciliği gibi madde parametreleri yeterli sayıda kullanıcı verisiyle incelenip kalibre edildikten sonra sonraki geliştirme aşamasında değerlendirilecektir. Faz-2 kapsamında:

- Soru maddelerinin güçlük ve ayırt edicilik parametrelerinin incelenmesi

- Yeterli örneklem verisiyle madde havuzunun kalibre edilmesi

- Kullanıcı yetenek tahmininin IRT yaklaşımıyla modellenmesi

- Bir sonraki sorunun önceki yanıtlara göre seçildiği CAT akışının geliştirilmesi

- Adaptif test sonuçlarının sabit test sonuçlarıyla karşılaştırılması

- Ölçüm güvenilirliği ve test süresinin değerlendirilmesi

Bu geliştirmeler, gerekli veri ve kalibrasyon çalışmaları tamamlanmadan MVP'nin zorunlu parçası olarak kabul edilmeyecektir.

### 5.4. Altı Bileşene Dayalı Dinamik Görev Önceliği

Öğrenme motorunun temel farklılaştırıcı yönü, kullanıcıyı tek bir genel puanla tanımlamak yerine altı bileşendeki gelişimini ayrı izlemesidir. Motor, kullanıcının hedefi ve performansına göre görev önceliklerini dinamik biçimde belirler. Örneğin Reading ve Vocabulary düzeyleri yüksek, Writing ve Speaking düzeyleri düşük olan bir kullanıcıya üretim becerileri için daha fazla pratik fırsatı sunulabilir. Bu işlem, IRT/CAT tabanlı adaptif test anlamına gelmez; MVP'de kural tabanlı öğrenme planı önceliklendirmesidir.

### 5.5. Konu Ustalığı ve İçerik Seçimi

Her konu için başlangıçta 0–1 aralığında bir ustalık göstergesi tutulabilir. İlk prototipte doğruluk, tekrar başarısı ve zaman içindeki performans eğilimi izlenir. Tek bir yanlış yanıtın bütün öğrenme planını değiştirmemesi için kararlar yeterli gözlem birikimiyle alınır. Motor:

- Kullanıcının hedefiyle ilişkili ve düşük performans gösterdiği konuları belirler.

- Günlük süre sınırına göre görevleri seçer.

- Sürekli zorlanılan konuları daha küçük öğrenme adımlarına böler.

- Yüksek başarı gösterilen konuları daha ileri içeriklerle destekler.

- Unutmayı önlemek için kazanılmış konuların tekrarını sürdürür.

### 5.6. Günlük Plan Örneği

Günlük 30 dakika ayıran ve Speaking becerisi daha fazla çalışmaya ihtiyaç duyan bir kullanıcı için örnek plan:

- 5 dakika kelime tekrarı

- 5 dakika Grammar çalışması

- 5 dakika kısa Listening veya Reading etkinliği

- 10 dakika Speaking pratiği

- 5 dakika geri bildirim ve kapanış

Bu dağılım sabit değildir; kullanıcının tercihlerine, hedeflerine ve performansına göre değişir.

### 5.7. Öğrenme Döngüsü

Her görev tamamlandığında performans kaydı oluşturulur. Öğrenme motoru bu kaydı kullanıcının profilindeki ilgili beceri ve konuyla ilişkilendirir. Plan, belirlenen periyotta veya yeterli yeni veri oluştuğunda güncellenir. Böylece tek bir yanlış cevap öğrenme planını gereksiz biçimde değiştirmez. 6. YAPAY ZEKÂ DESTEKLİ MODÜLLER

### 6.1. AI Speaking Partner

Kullanıcı restoran, seyahat, iş görüşmesi veya günlük sohbet gibi bir senaryo seçer. Sistem kullanıcının seviyesine ve amacına uygun bir diyalog başlatır. Kullanıcı sesli yanıt verir; Speech-to-Text (STT) katmanı yanıtı metne dönüştürür. Diyalog motoru bağlamı koruyarak karşılık üretir. Oturum sonunda dil bilgisi, kelime kullanımı, görevi tamamlama, anlaşılabilirlik ve akıcılık açısından geri bildirim sunulur. ASR/STT hata riskinin azaltılması:

- ASR servisinin sunduğu güven skoru (confidence score) kontrol edilir.

- Güven skoru, pilot testlerle belirlenmiş eşik değerin altındaysa yanıt otomatik olarak düşük puanlanmaz;

kullanıcıdan tekrar konuşması veya metni düzeltmesi istenir.

- Gürültülü veya anlaşılmayan seslerde sistem kesin değerlendirme vermek yerine yeniden kayıt seçeneği

sunar.

- Konuşma puanı yalnızca ASR metnine dayandırılmaz.

- Kelime/cümle akış hızı (words per minute), duraklama ve akıcılık göstergeleri yardımcı metrik olarak

kullanılabilir; tek başına başarı ölçütü yapılmaz.

- Aksan farklılıkları otomatik olarak hata kabul edilmez. Anlaşılabilirlik ve iletişimsel başarı esas alınır.

- Telaffuz değerlendirmesi için yalnızca metin dökümü yeterli olmadığından, uygun ses analizi veya örneklem

bazlı insan kontrolü gerekir.

### 6.2. AI Writing Assistant

Kullanıcı serbest metin yazar veya bir görev yönergesine yanıt verir. Sistem metni aşağıdaki ölçütlerle inceler:

- Dil bilgisi doğruluğu

- Kelime seçimi ve çeşitliliği

- Yazım ve noktalama

- Cümle yapısı

- Tutarlılık ve akıcılık

- Görevin yönergeye uygun biçimde tamamlanması

Geri bildirim; orijinal ifade, önerilen düzeltme, kısa açıklama ve alternatif doğal ifade biçiminde sunulur. Temel amaç kullanıcının kendi yazısını geliştirmesidir; metnin tamamını gerekçesiz biçimde yeniden yazmak değildir.

### 6.3. Grammar Coach ve RAG Entegrasyonu

Grammar Coach, kullanıcının tekrar eden hata örüntülerini konu etiketleriyle ilişkilendirir. Örneğin geçmiş zaman kullanımında tekrarlanan hata tespit edilirse kısa konu anlatımı, örnekler, kontrollü alıştırma ve yeni bir uygulama görevi önerilir. Yapay zekânın yanlış dil bilgisi kuralı veya gerçeğe aykırı açıklama üretmesi (hallucination/halüsinasyon) riskini azaltmak için RAG (Retrieval-Augmented Generation) mimarisi kullanılacaktır. Önerilen RAG akışı:
1. Dil bilgisi konusu veya kullanıcı sorusu alınır.
2. Soru, doğrulanmış ve kullanımına izin verilen kaynak havuzunda aranır.
3. İlgili içerik parçaları ve kaynak metaverileri getirilir.
4. LLM'e yalnızca ilgili kaynak bağlamı ve sınırlandırılmış görev yönergesi iletilir.
5. Yanıtın getirilen kaynaklarla tutarlılığı kontrol edilir.
6. Yeterli kaynak bulunamazsa modelin kural uydurması yerine yanıtın doğrulanamadığı belirtilir.
7. Uygun olduğunda kullanıcıya kullanılan kaynağın adı veya referansı gösterilir. Kaynak havuzu; CEFR ile uyumlu, editoryal olarak doğrulanmış ve kullanım/lisans koşulları uygun dil bilgisi materyallerinden oluşturulmalıdır. Cambridge veya Oxford gibi kaynaklardan yararlanılması durumunda ilgili içeriklerin telif ve lisans koşullarına uyulmalıdır. Bu kaynakların adının belirtilmesi, korunan içeriklerin izinsiz kopyalanabileceği anlamına gelmez.

### 6.4. Vocabulary

Her kelime; anlam, kelime türü, telaffuz, örnek cümle, bağlam ve kullanıcının öğrenme durumu ile saklanır. Kullanıcı yeni kelimeyi kişisel listesine ekleyebilir. Kelimenin hatırlanma durumu tekrar takvimini etkiler.

### 6.5. Listening Laboratory

Dinleme içerikleri seviye ve konu etiketleriyle sunulur. Kullanıcı ses kaydını dinler ve ana fikir, ayrıntı veya bağlam sorularını yanıtlar. Gerektiğinde metin dökümü ve açıklama, öğrenme hedefi tamamlandıktan sonra gösterilir. Farklı aksanlar içerik planına kademeli olarak eklenir.

### 6.6. Reading Laboratory

Okuma içerikleri seviyeye ve ilgi alanına göre seçilir. Kullanıcı metin içinde bilmediği kelimeleri inceleyebilir ve kelime listesine ekleyebilir. Metin sonrasında ana fikir, ayrıntı, çıkarım ve kelime bağlamı soruları sunulur.

### 6.7. Yapay Zekâ Güvenilirliği ve Kontrol

Yapay zekâ çıktıları olasılıksal olduğundan modelin ürettiği her açıklama doğrudan doğru kabul edilmemelidir. Sistem; sınırlandırılmış istemler, seviye etiketleri, doğrulanmış içerik havuzu, RAG, çıktı kontrolleri ve gerektiğinde insan incelemesiyle desteklenmelidir. Kaynak desteği olmayan veya belirsiz yanıtlar kesin bilgi gibi sunulmamalıdır.

## 7. KELİME TEKRARI VE KALICILIK

### 7.1. Aralıklı Tekrar Yaklaşımı

Kelimeler, kullanıcının hatırlama başarısına göre artan veya azalan aralıklarla yeniden sunulur. Örnek başlangıç takvimi 1, 3, 7, 14 ve 30 gündür. Bu değerler kesin bilimsel eşikler değil, ilk ürün tasarımı için önerilen başlangıç aralıklarıdır.

### 7.2. Tekrar Kararları

Kullanıcı kelimeyi kolayca hatırlarsa sonraki tekrar aralığı uzatılır. Zorlanırsa veya yanlış yanıtlarsa aralık kısaltılır. Kullanıcıya kelimeyi yalnızca tanıma değil, cümle içinde üretme görevi de verilebilir. Böylece pasif tanıma ile aktif kullanım birbirinden ayrılır.

### 7.3. Kelime Durumları

- Yeni: Kullanıcı henüz çalışmadı.

- Öğreniliyor: Kelime tekrar sürecinde.

- Güçlendi: Kullanıcı birden fazla oturumda başarılı hatırlama gösterdi.

- Tekrar gerekli: Son denemede unutuldu veya uzun süredir gözden geçirilmedi.

## 8. KİŞİSEL ÖĞRENME PANELİ VE OYUNLAŞTIRMA

### 8.1. Ana Panel

Ana panelde günlük hedef, önerilen görevler, bekleyen kelime tekrarları, son tamamlanan dersler ve beceri gelişimi gösterilir. Kullanıcı bir sonraki adımını kolayca anlayabilmelidir.

### 8.2. Gelişim Analitiği

Haftalık ve aylık görünümde aşağıdaki göstergeler raporlanır:

- Beceri bazlı performans eğilimi

- Tamamlanan görev sayısı

- Çalışma süresi

- Kelime tekrar başarısı

- Writing ve Speaking oturumları

- Hedef tamamlama durumu

Ölçümler aynı metrik ve ölçekle sunulmalı; veri yetersiz olduğunda kesin gelişim iddiası yapılmamalıdır.

### 8.3. Oyunlaştırma

Günlük görev, haftalık hedef, öğrenme serisi ve rozet gibi mekanikler kullanıcı motivasyonunu destekler. Oyunlaştırma, öğrenme başarısının yerine geçmez. Kullanıcıyı aşırı bildirim veya cezalandırıcı seri kaybı mekanikleriyle baskı altına almayan bir tasarım tercih edilir.

## 9. İŞ BÖLÜMÜ VE 10 HAFTALIK ÇALIŞMA TAKVİMİ

Proje geliştirme süreci, backend ve frontend görevleri birbirini destekleyecek şekilde 10 haftaya ayrılmıştır.

- Backend: Elif Su Aslan

- Frontend: Sudenaz Akdaş

| Hafta | Backend – Elif Su Aslan | Frontend – Sudenaz Akdaş |
| --- | --- | --- |
| 1. Hafta | FastAPI proje kurulumu, PostgreSQL veritabanı tasarımı ve API yapısının belirlenmesi | Flutter proje kurulumu, UI/UX tasarımı, sayfa akışları ve navigasyon |
| 2. Hafta | Kullanıcı ve profil servisleri, kimlik doğrulama entegrasyonu | Giriş, kayıt, profil ve onboarding ekranları |
| 3. Hafta | Altı dil bileşeni için soru bankası ve seviye tespit API'leri | Grammar, Vocabulary, Reading, Listening, Writing ve Speaking test ekranları |
| 4. Hafta | Puanlama algoritması, beceri bazlı değerlendirme ve CEFR ile ilişkili tahmini seviye sonuçları | Test sonuçları, beceri grafikleri ve seviye değerlendirme ekranları |
| 5. Hafta | Kişiselleştirilmiş öğrenme motoru, günlük görev planlama ve öneri algoritması | Ana sayfa, günlük öğrenme planı ve görev takip ekranları |
| 6. Hafta | Kelime tekrar algoritması, Grammar, Reading ve Listening içerik servisleri | Kelime kartları, tekrar sistemi, Grammar, Reading ve Listening ekranları |
| 7. Hafta | AI Writing Assistant, yazılı yanıt analizi ve geri bildirim API'leri | AI Writing ekranı, metin giriş alanı ve düzeltme/geri bildirim arayüzü |
| 8. Hafta | AI Speaking Partner, konuşmayı metne dönüştürme (STT) ve seslendirme (TTS) entegrasyonu | AI Speaking ekranı, mikrofon kullanımı, ses kaydı ve konuşma arayüzü |
| 9. Hafta | Kullanıcı ilerleme kayıtları, gelişim analitiği, bildirim servisleri ve backend entegrasyonu | Gelişim paneli, istatistik grafikleri, hatırlatıcılar ve frontend entegrasyonu |

| Hafta | Backend – Elif Su Aslan | Frontend – Sudenaz Akdaş |
| --- | --- | --- |
| 10. Hafta | API ve birim testleri, güvenlik kontrolü, performans iyileştirmeleri ve hata düzeltmeleri | Widget ve kullanılabilirlik testleri, cihaz uyumluluğu, arayüz iyileştirmeleri ve son düzenlemeler |

Çalışma yöntemi: Frontend ve backend geliştirmeleri, önceden belirlenen API sözleşmeleri üzerinden yürütülecektir. Ekip üyeleri entegrasyon, test, hata giderme ve kod inceleme süreçlerinde koordineli çalışacaktır. İlk dokuz hafta temel geliştirme ve entegrasyon çalışmalarına, onuncu hafta ise genel test, hata düzeltme ve son iyileştirmelere ayrılmıştır.

## 10. GÜVENLİK, GİZLİLİK, KVKK/GDPR VE ETİK

### 10.1. Teknik Güvenlik Önlemleri

- İstemci ve sunucu arasındaki iletişim HTTPS üzerinden gerçekleştirilmelidir.

- Yapay zekâ sağlayıcı anahtarları mobil uygulama paketine gömülmemeli, güvenli sunucu ortamında

saklanmalıdır.

- Özel API uçlarında kimlik doğrulama ve yetkilendirme uygulanmalıdır.

- Kullanıcı yalnızca kendi profilini, öğrenme kayıtlarını ve içerik geçmişini okuyup değiştirebilmelidir.

- Veritabanı erişim politikaları ve kullanıcı bazlı yetki kontrolleri test edilmelidir.

- Hassas veriler için uygun aktarım ve saklama güvenliği uygulanmalıdır.

- Veri saklama süreleri ve silme prosedürleri tanımlanmalıdır.

- API istek sınırlandırması, hata kaydı ve kötüye kullanım kontrolleri değerlendirilmelidir.

### 10.2. KVKK ve GDPR Kapsamında Ses Verileri

Uygulamanın Speaking modülünde işlenen ses kayıtları kişisel veri niteliği taşıyabilir. Bununla birlikte her ses kaydı kendiliğinden biyometrik veri sayılmaz. Ses verisinin kişinin kimliğini benzersiz biçimde belirlemek veya doğrulamak amacıyla özel teknik işlemden geçirilmesi, biyometrik veri olarak değerlendirilmesinde önemlidir. Türkiye'de biyometrik veriler KVKK kapsamında özel nitelikli kişisel veri kategorisindedir. GDPR'da da biyometrik veriler, gerçek kişinin benzersiz biçimde tanımlanması amacıyla işlendiğinde özel nitelikli veri kapsamına girer. Bu nedenle uygulamada:

- Ses verisinin hangi amaçla işlendiği kullanıcıya açıkça anlatılmalıdır.

- Mikrofon izni yalnızca ilgili özellik kullanılacağı zaman istenmelidir.

- Ses verisi yalnızca konuşma pratiği için işleniyorsa kimlik tespiti amacıyla kullanılmamalıdır.

- Ham sesin kalıcı saklanmaması varsayılan yaklaşım olmalıdır.

- Sesin sunucuya veya üçüncü taraf AI sağlayıcısına aktarılması gerekiyorsa aktarım, amaç, saklama süresi ve

silme yöntemi açıklanmalıdır.

- İşleme faaliyeti özel nitelikli kişisel veri kapsamına giriyorsa KVKK ve GDPR bakımından uygulanabilir hukuki

işleme şartları ayrıca değerlendirilmelidir. Açık rıza gereken durumlarda rıza belirli, bilgilendirmeye dayalı ve özgür iradeyle verilmiş olmalıdır.

- Yurt dışındaki servis sağlayıcılara veri aktarımı yapılacaksa ilgili mevzuattaki sınır ötesi aktarım koşulları

incelenmelidir.

- Kullanıcıya ilgili mevzuat kapsamında başvuru, erişim ve silme süreçleri sunulmalıdır.

Önemli not: Ses kaydının biyometrik veri olup olmadığı, işleme amacı ve kullanılan teknik yönteme bağlıdır. Bu bölüm teknik proje tasarımı için hazırlanmıştır; hukuki görüş veya mevzuata tam uyum garantisi değildir. Gerçek kullanıcı verisiyle yayına geçilmeden önce güncel KVKK/GDPR hükümleri ve uzman görüşü değerlendirilmelidir.

### 10.3. Gizlilik ve Veri Minimizasyonu

Uygulama yalnızca işlevlerini yerine getirmek için gerekli verileri toplamalıdır. Ham ses kayıtlarının sürekli saklanması varsayılan gereksinim değildir. Konuşma değerlendirmesi için gerekli metin ve özet performans göstergeleri saklanabilir. Ses saklanacaksa amaç, saklama süresi, erişim yetkileri ve silme yöntemi açıkça belirlenmelidir. Harici yapay zekâ sağlayıcılarına gönderilen veri türleri gizlilik açıklamasında belirtilmelidir. Kullanıcı verileri model eğitimi veya farklı amaçlar için kullanılacaksa bunun hukuki dayanağı ve kullanıcıya sunulacak bilgilendirme ayrıca değerlendirilmelidir.

### 10.4. Etik ve İçerik Güvenliği

- Yapay zekâ değerlendirmeleri resmî dil sertifikası veya kesin uzman kararı gibi sunulmamalıdır.

- Modelin belirsiz olduğu durumlarda kullanıcıya kesin hüküm verilmemelidir.

- Aksan farklılıkları veya konuşma tanıma hataları kullanıcı aleyhine otomatik puanlamaya neden olmamalıdır.

- İçeriklerde ayrımcı, zararlı veya yaşa uygun olmayan çıktılara karşı kontroller uygulanmalıdır.

- Çocuk kullanıcılar için yaşa uygun içerik, veri işleme ve ebeveyn izni gereksinimleri incelenmelidir.

- Uygulamanın yayın öncesinde Apple App Review Guidelines ve Google Play kullanıcı verisi politikaları kontrol

edilmelidir.

## 11. TEST VE KALİTE GÜVENCE

### 11.1. Test Türleri

| Test Türü | Kapsam |
| --- | --- |
| Unit Test | Puan hesaplama, tekrar aralığı, görev seçimi ve backend iş kuralları |
| Widget Test | Flutter bileşenleri, form doğrulama ve ekran durumları |
| Integration Test | Giriş, test çözme, AI isteği, veri kaydı ve sonuç görüntüleme |
| API Test | Şema doğrulama, yetki kontrolü, hata kodları ve hız sınırları |
| AI Değerlendirme Testi | Örnek yazı/konuşma setlerinde tutarlılık ve rubrik uyumu |
| ASR Testi | Farklı aksan, konuşma hızı, mikrofon kalitesi ve arka plan gürültüsünde tanıma performansı |
| RAG Testi | Getirilen kaynakların ilgililiği, kaynakla tutarlılık ve kaynak bulunamadığında güvenli yanıt |
| Usability Test | Farklı seviyelerde kullanıcıların görevleri tamamlayabilmesi |
| Performance Test | API gecikmesi, ses akışı ve uygulama yanıt süresi |
| Security Test | Yetkisiz erişim, veri sızıntısı ve gizli anahtar kontrolü |

### 11.2. Başarı Ölçütleri

Ölçülebilir kabul kriterleri geliştirme sırasında belirlenmelidir. İlk sürüm için örnek kabul kriterleri:

- Kullanıcı test sonucu kaybolmadan kaydedilir.

- Öğrenme planı doğru beceri ve konuyla ilişkilendirilir.

- Kullanıcı başka bir hesaba ait özel verilere erişemez.

- ASR güven skoru yetersiz olduğunda sistem hatalı biçimde kesin puan üretmez.

- RAG yanıtı için yeterli kaynak bulunmadığında sistem kural uydurmak yerine belirsizliği belirtir.

- AI servisi hata verdiğinde uygulama kontrollü hata mesajı gösterir.

- Kullanıcı desteklenen cihazlarda temel kullanıcı akışını çökme olmadan tamamlayabilir.

### 11.3. Pilot Değerlendirme

Yayın öncesinde farklı başlangıç seviyelerinden küçük bir pilot kullanıcı grubu ile kullanılabilirlik ve içerik kalitesi değerlendirilmelidir. Pilot çalışma ilk aşamada kullanılabilirlik, hata oranı, görev tamamlama, ASR hata örüntüleri ve AI geri bildirim tutarlılığı gibi ölçütlere odaklanmalıdır. Pilot çalışma, uygulamanın dil öğrenme başarısını bilimsel olarak kanıtladığı şeklinde sunulmamalıdır. Böyle bir iddia için daha kapsamlı ve uygun araştırma tasarımına sahip değerlendirmeler gerekir.

## 12. RİSKLER, AZALTMA STRATEJİLERİ VE SONUÇ

### 12.1. Riskler ve Azaltma Yaklaşımları

| Risk | Olası Etki | Azaltma Yaklaşımı |
| --- | --- | --- |
| Yapay zekâ yanıtlarının tutarsızlığı / halüsinasyon | Yanlış öğrenme geri bildirimi | RAG, doğrulanmış içerik, kaynak kontrolü, sınırlandırılmış istemler ve belirsizlik bildirimi |
| Speech-to-Text / ASR hataları | Konuşma puanının adaletsiz olması | Güven skoru eşikleri, tekrar hakkı, metin doğrulama, gürültü kontrolü ve aksan duyarlılığı |
| Yetersiz soru bankası | Seviye tespitinin güvenilir olmaması | Kazanım eşlemesi, paralel soru formları ve pilot kalibrasyon |
| AI servis maliyeti | Kullanım maliyetinin yükselmesi | İstek kotası, önbellek, kısa bağlam ve maliyet izleme |
| Kapsamın büyümesi (Scope Creep) | Takvimin uzaması | MVP sınırları, önceliklendirme ve aşamalı geliştirme |
| Kişisel veri ihlali | Kullanıcı güveni ve mevzuat riski | Veri minimizasyonu, erişim kontrolü, güvenli aktarım ve güvenlik testleri |
| Platform mağaza reddi | Yayın gecikmesi | Güncel mağaza kurallarına göre yayın öncesi kontrol listesi |
| AI değerlendirmesinde tutarsızlık | Kullanıcıya yanlış performans bilgisi verilmesi | Rubrik, örnek test seti, insan değerlendiriciyle örneklem kontrolü |

### 12.2. Sonuç ve Genel Değerlendirme

Bu projede İngilizce öğrenme sürecini seviye tespiti, kişiselleştirilmiş öğrenme, aktif pratik ve gelişim takibi bileşenleriyle birleştiren yapay zekâ destekli bir mobil uygulamanın mühendislik tasarımı sunulmuştur. Projenin temel farklılaştırıcı yönü, kullanıcıyı yalnızca tek bir genel dil seviyesiyle tanımlamak yerine altı bileşendeki gelişimini ayrı ayrı izlemesi ve bu verileri kişiselleştirilmiş öğrenme planına dönüştürmesidir. Özellikle Writing ve Speaking gibi üretim becerilerinde daha fazla desteğe ihtiyaç duyan kullanıcılara hedefli pratik sunulması amaçlanmaktadır. İlk sürümde IRT/CAT gibi ileri psikometrik adaptif test yöntemlerinin zorunlu tutulmaması, kapsamın kontrol altında tutulmasını ve temel işlevlerin güvenilir biçimde geliştirilmesini sağlayan bilinçli bir MVP kararıdır. Kural tabanlı öğrenme önceliklendirmesi ilk sürümde uygulanacak; IRT/CAT ise yeterli veri ve kalibrasyon çalışması sonrasında Faz-2 kapsamında değerlendirilecektir. RAG tabanlı bilgi getirme yaklaşımı, doğrulanmış kaynaklarla desteklenmeyen dil bilgisi açıklamalarının önüne geçmeyi; ASR güven skoru ve tekrar mekanizmaları ise konuşma değerlendirmesinde oluşabilecek teknik hataların kullanıcı puanını haksız biçimde etkilemesini azaltmayı hedefler. Flutter, FastAPI ve PostgreSQL tabanlı modüler mimari iOS ve Android platformlarını destekleyen genişletilebilir bir başlangıç sunar. Projenin başarısı yalnızca teknik modüllerin çalışmasına değil; içerik kalitesine, ölçme sisteminin güvenilirliğine, kullanıcı deneyimine, veri güvenliğine ve gerçek kullanıcılarla yapılacak değerlendirmelere bağlıdır.

## 13. KAYNAKÇA VE TEKNİK BAŞVURU

### 13.1. Yazılım ve Platform Dokümantasyonları

- Flutter Documentation – App Architecture: https://docs.flutter.dev/app-architecture

- Flutter Documentation – Testing: https://docs.flutter.dev/testing/overview

- FastAPI Documentation: https://fastapi.tiangolo.com/

- PostgreSQL Documentation: https://www.postgresql.org/docs/

- Supabase Documentation: https://supabase.com/docs

- Riverpod Documentation: https://riverpod.dev/

- Firebase Cloud Messaging: https://firebase.google.com/docs/cloud-messaging

- Apple App Review Guidelines: https://developer.apple.com/app-store/review/guidelines/

- Google Play User Data Policy: https://support.google.com/googleplay/android-developer/answer/10144311

### 13.2. Dil Öğretimi ve Ölçme-Değerlendirme Kaynakları

- Council of Europe – Common European Framework of Reference for Languages (CEFR):

https://www.coe.int/en/web/common-european-framework-reference-languages

- English Profile – English Grammar Profile ve English Vocabulary Profile: https://englishprofile.org/

- Cambridge English: https://www.cambridgeenglish.org/

- Oxford Test of English: https://www.oxfordtestofenglish.com/

### 13.3. Veri Koruma ve Gizlilik Kaynakları

- Kişisel Verileri Koruma Kurumu – Özel Nitelikli Kişisel Verilerin İşlenmesine İlişkin Rehber:

https://www.kvkk.gov.tr/Icerik/8183/Ozel-Nitelikli-Kisisel-Verilerin-Islenmesine-Iliskin-Rehber

- Kişisel Verileri Koruma Kurumu – Biyometrik Verilerin İşlenmesinde Dikkat Edilmesi Gereken Hususlara İlişkin

Rehber: https://www.kvkk.gov.tr/Icerik/7047/Biyometrik-Verilerin-Islenmesinde-Dikkat-Edilmesi-Gereken-Husus lara-Iliskin-Rehber

- Kişisel Verileri Koruma Kurumu – Mobil Uygulamalarda Mahremiyetin Korunmasına Yönelik Tavsiyeler:

https://www.kvkk.gov.tr/Icerik/7751/Mobil-Uygulamalarda-Mahremiyetin-Korunmasina-Yonelik-Tavsiyeler

- General Data Protection Regulation (GDPR), özellikle Madde 4 ve Madde 9:

https://eur-lex.europa.eu/eli/reg/2016/679/ Not: Bu README, proje önerisini ve planlanan teknik yaklaşımı açıklar. Henüz geliştirilmemiş özellikler tamamlanmış gibi değerlendirilmemelidir. Kullanılan kütüphane, servis ve sürümlerin gerçek uygulama deposundaki durumla eşleştirilmesi; yayın öncesinde teknik, güvenlik ve mevzuat kontrollerinin güncellenmesi gerekir.
