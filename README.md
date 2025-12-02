🐾 EcoPaw - Heyvanlara Qayğı Platforması
EcoPaw, sahibsiz küçə heyvanlarının qidalanması, sağlamlığı və onlara nəzarəti təmin etmək üçün hazırlanmış veb əsaslı ağıllı platformadır. Bu layihə könüllüləri, donorları və heyvansevərləri vahid mərkəzdə birləşdirir.

🌟 Əsas Özəlliklər
Çoxdilli Dəstək: Azərbaycan (AZ), İngilis (EN), Türk (TR) və Rus (RU) dillərində tam interfeys tərcüməsi.

İstifadəçi və Könüllü Sistemi:

Firebase Authentication ilə qeydiyyat və giriş.

Könüllü Rejimi: Könüllülər üçün xüsusi rəng mövzusu (sarı/narıncı) və tapşırıq paneli.

Ağıllı yemləmə cihazlarının xəritəsi və statusu (yem/su bitib xəbərdarlığı).

İanə Sistemi: İstifadəçilərin layihəyə dəstək olması üçün interaktiv ianə forması.

Canlı Statistika: Günlük bəslənmə sayı, aktiv cihazlar və könüllü sayı.

Ağıllı Axtarış: Regionlara (məs: Xankəndi, Şuşa, Bakı) görə cihazların axtarışı.

Responsive Dizayn: Mobil və masaüstü cihazlar üçün tam uyğunlaşdırılmış (Tailwind CSS ilə).

🛠 İstifadı Olunan Texnologiyalar
Frontend: HTML5, JavaScript (ES6 Modules)

Stil (CSS): Tailwind CSS (CDN vasitəsilə)

İkonlar: FontAwesome

Backend & Verilənlər Bazası: Google Firebase (Auth, Firestore)

🚀 Layihəni İşə Salmaq
Layihəni lokal kompüterinizdə işlətmək üçün aşağıdakı addımları izləyin:

1. Faylları yükləyin
Layihəni kompüterinizə yükləyin və ya klonlayın:

Bash

git clone https://github.com/username/ecopaw.git
2. Serverdə açın
Layihə JavaScript modullarından (type="module") istifadə etdiyi üçün birbaşa HTML faylını açmaq bəzi brauzerlərdə CORS xətası verə bilər. Ən yaxşı nəticə üçün VS Code "Live Server" və ya oxşar lokal serverdən istifadə edin.

3. Firebase Konfiqurasiyası
Kodun daxilindəki firebaseConfig obyektinin öz Firebase layihənizə uyğun olduğundan əmin olun. Hazırkı kodda demo API açarları yerləşdirilib.

📖 İstifadə Qaydaları
Giriş/Qeydiyyat: Sağ yuxarı küncdəki "Giriş" düyməsi ilə hesab yaradın.

Könüllü Olmaq:

Hesabınıza daxil olduqdan sonra "Könüllü Ol" səhifəsinə keçin.

Formu doldurun.

Təsdiqləndikdən sonra interfeys avtomatik olaraq "Könüllü Rejiminə" keçəcək və xəritədəki problemli cihazları görə biləcəksiniz.

Tapşırıq İdarəetməsi: Ana səhifədə "Yem bitib" və ya "Su bitib" xəbərdarlığı olan cihazlar üçün "İşi Qəbul Et" düyməsini sıxın.

📂 Fayl Strukturu
Plaintext

ecopaw/
├── index.html       # Əsas tətbiq faylı (Bütün kodlar buradadır)
├── README.md        # Layihə sənədləşdirməsi
└── assets/          # (Əgər gələcəkdə şəkillər əlavə olunarsa)
🤝 Töhfə vermək (Contributing)
Töhfə vermək istəyirsinizsə, zəhmət olmasa "Pull Request" göndərin və ya xətalar barədə "Issues" bölməsində məlumat verin.
