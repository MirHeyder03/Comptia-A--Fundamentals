# Əsas qeydlər

# `Network Topologies`

There are fiver primary topologies

- Bus
- Star
- Ring
- Mesh
- Hybrid

# Signals

- Analog -  Bir zaman periodunda dəyişən dalğadır.Sinus dalğasını təmsil edir.Dağılmağa daha yatqındır.
- Digital-Dataları 2lik (0 və 1)  ilə daşıyır.Kvadrat dalğalar ilə təmsil olunur.

# **`Motherboard (Anaplata)`**

Kompüterin onurğası anaplatadır, başqa cür sistem lövhəsi adlanır. PCB (printed circuit
board) anaplatanın əsasını təşkil edir və yaşıl, qəhvəyi, mavi, qara və ya qırmızı rənglərdə
olur. Bu, kompüterin ən vacib komponentidir, çünki üzərində bütün digər komponentləri
birləşdirən yollar var.

*Anaplata formaları*
Anaplatalar ATX, micro ATX və ITX kimi formalarına (dizayn) görə təsnif edilir. Anaplata
və korpusu (case) ayrıca əldə edərkən diqqətli olun. Seçdiyiniz korpuslar anaplata ilə fiziki
cəhətdən uyğun olmaya bilər.

### Anaplatanın komponentləri

Bus arxitekturası
PC-də məlumatlar bir komponentdən digərinə bus (siqnal yolları toplusu) vasitəsilə
göndərilir. Köhnə kompüterlər eyni vaxtda bir bit göndərən və sürəti yavaş olan serial bus
istifadə edirdilər. Mühəndislər bunu inkişaf etdirib eyni vaxtda (sinxronlaşdırılmış ayrı-ayrı
xətlər üzərində) səkkiz bit göndərə bilməyə nail oldular, bu da böyük sürət artımına gətirib
çıxardı. Bu, paralel bus adlanırdı. Daha sonra isə serial ötürmə texnologiyası inkişaf etdirildi
və paralel ötürmə texnologiyasından sürətli oldu. Buna görə də bugün gördüyünüz demək
olar ki, hər şey serial bus istifadə edir. Serial ötürmə texnologiyasına misal olaraq Serial
ATA və ya SATA (Serial Advanced Technology Attachment), USB (Universal Serial Bus),
IEEE 1394/FireWire və PCIe (Peripheral Component Interconnect Express) qoşulma
növlərini göstərmək olar.

# `Çipsetlər`

Çipset prosessor üçün periferik funksiyaları yerinə yetirən çiplər və ya sxemlər toplusudur.
Bu çiplər toplusu adətən RAM, genişləndirmə kartları və anaplata üzərində olan hissələr üçün
qoşulmaları təmin edən sxemdir və ümumiyyətlə anakartın quraşdırılmış periferiyalarla necə
əlaqə saxlayacağını təmin edir.
Çipsetlər iki əsas funksional qrupa bölünür:
Northbridge (şimal körpüsü) və Southbridge (cənub körpüsü).

~AMD və Intel öz CPU-larının əksəriyyətinə Northbridge və Southbridge xüsusiyyətlərini
inteqrasiya ediblər. Beləliklə, CPU özü ayrı-ayrı çipsetlər əvəzinə Northbridge və
Southbridge funksiyalarını təmin edir.
Northbridge CPU-ya qoşur:
RAM
İnteqrasiya edilmiş videokart
PCI Express (PCIe)
Southbridge CPU-ya qoşur:
SATA disklər
USB bus
İnteqrasiya edilmiş audio (səs kartı)
Northbridge yüksək sürətli kanalları, Southbridge isə aşağı sürətli kanalları idarə edir.

### Expansion Slots (Genişləndirmə yuvaları)

- ISA – köhnə texnologiyadır.
- PCI (Peripheral Component Interconnect) – 1992-ci il. Bu köhnə texnologiya hesab olunur,
lakin bu gün istifadə olunan bir çox anaplatada hələ də 32 bitlik PCI yuvaları var. PCI
genişləndirmə yuvaları 32 bitlik (4 bayt) kanal üzərində 33 MHz və ya 66 MHz tezliyində
işləyir, nəticədə məlumat sürəti 133 MBps və 266 MBps olur.
- AGP (accelerated graphics port) - 1996-cı il.
- PCIe (PCI Express) – 2004-cü il. Anaplatalar tərəfindən istifadə edilən ən çox yayılmış
genişləndirmə yuvası arxitekturası PCIe-dir. O, AGP və PCI-ni əvəz etmək üçün nəzərdə
tutulmuşdur.
- PCIe 5.0 və PCIe 6.0. PCIe 5.0 versiyası 2019-cu ildə hazırlanıb, hər zolaq üçün 3938 MB/sə qədər və x16 konfiqurasiyasında 63 GB/s-ə qədər ötürmə qabiliyyəti təklif edir. PCIe 6.0
versiyanın hazırlanması 2022-ci ilin əvvəli üçün nəzərdə tutulub.

# `Memory Slots and Cache (RAM yuvaları və Keş)`

### RAM (random access memory)

Məlumat saxlama və ya yaddaş bölməsinin bir növüdür.
Saxlanılan məlumatlara tez bir zamanda daxil olmağa imkan verir. Hard disk və ya USB
yaddaş kartlarından fərqli olaraq RAM lazım olan məlumatları daimi deyil, müvəqqəti olaraq
saxlayır.
RAM yaddaşında kiçik qutular var. Bu qutuların hər biri sıra ilə sütun şəklində yerləşir. Dəstə
şəklində olan RAM qutularındakı hər bir qutucuğa hücrə deyilir. RAM yaddaşı zəruri
məlumatları məhz bu qutucuqlarda saxlayır və istənilən vaxt tez bir zamanda ötürür.
Prosessor da tələb olunan əməliyyat üçün RAM-la əlaqə qurur. Bütün əməliyyatlar haqqında
məlumatlar da RAM-da saxlanılır. RAM-ın yüksək tutumu, kompüterin və ya fərqli
cihazların eyni anda birdən çox əməliyyat üçün məlumat saxlamaq iqtidarında olması
deməkdir. RAM yaddaşı zəif olduğu zaman isə istədiyiniz əməliyyat ya çox yavaş gedir, ya
da ümumiyyətlə yerinə yetirilmir. Kompüter və digər cihazlar söndürüldüyü zaman lazım
olan enerji kəsildiyi üçün RAM yaddaşında olan bütün məlumatlar da itir. Kompüter işə
düşən zaman hard diskdən məlumatlar birinci RAM-a yüklənir, sonra emal etməsi üçün
prosessora göndərilir, buna görə də proses daha sürətli olur.

*Memory və ya RAM yuvaları anaplatada növbəti önəmli yuvalardır.* 

- **DIMM (dual in-line memory module)** - DIMM-lər xüsusi fiziki forması və istifadə etdiyi keçiricilərin və ya pinlərin sayına görə fərqlənir. 168-, 184-, 240- və 288-pin növlərini misal göstərmək olar.
- Bundan əlavə, noutbuk RAM-ın **SODIMM** (small outline DIMM) və MicroDIMM adlanan
daha kiçik formaları da var.
- **SIMM** (single inline memory module) köhnə RAM formasıdır.

### **DDR**

- DDR1 - 2.5V - 1 GB - 200 MHz
- DDR2 - 1.8 V - 8 GB - 533 MHz
- DDR3 - 1.5V - 16 GB - 1066 MHz
- DDR4 - 1.2V - 64 GB - 2133 MHz
RAM-ın üzərində PC2 yazılıbsa, deməli DDR2-dir. Yəni PC-dən sonra yazılan rəqəm DDR
versiyasını göstərir.

## Cache memory

Əksər kompüterlərdə olan RAM-ın başqa bir növü kiçik və sürətli olan, məntiqi olaraq CPU
və RAM arasında yerləşən keş yaddaşdır - cache memory. Keş yaddaşı CPU-ya çox
yaxındır, ya CPU çipinin özündə, ya da anakartda CPU-nun bilavasitə yaxınlığında yerləşir
və xüsusi ayrılmış bus-la birləşdirilir. Beləliklə məlumatlar ondan adi RAM ilə müqayisədə
daha tez oxuna bilər (və ona yazıla bilər).

- L1 cache - 64 KB
- L2 cache - 256 KB
- L3 cache - 4–12 MB

# `CPU and Processor Socket`

**CPU (central processing unit)** kompüterin "beyni" sayılır.
CPU olmayan kompüter yoxdur. CPU-nun rolu həm xarici, həm də daxili yollardan (bus)
istifadə edərək kompüterin bütün fəaliyyətini idarə etmək və yönləndirməkdir.

> LGA (land grid array) və PGA (pin grid array)
> 

---

**Overclock** – BIOS-dan girib CPU-nun tezliyini artırmaqdır

---

**Hyperthreading** - Bu termin Intel-in HTT-sinə (Hyper-Threading Technology) aiddir. HTT
qabiliyyətli prosessorlar əməliyyat sisteminə iki prosessor kimi görünür. Nəticədə, iki və ya
daha çox prosessor eyni sistem resurslarından istifadə edir. HTT Windows 10 Task Managerdə özünü göstərir. Bu virtual CPU-lar məntiqi prosessorlar adlanır. CPU-lar nüvələrinin
sayına görə də fərqlənir. Nüvə (core) sayı çox olan CPU-lar daha sürətli işləyir

---

**Liquid cooling (Maye soyutma)** - prosessordan (həmçinin çipsetdən) istilik ötürmək üçün
xüsusi su blokunun istifadə edildiyi texnologiyadır. Su bu blok vasitəsilə radiatora ötürülür və
orada soyudulur.

İstilik boruları
Borunun içində bu maddələrdən olur - su, maye ammonyak, metanol
Borunun materialı - mis, alüminium, paslanmayan polad
İşləmə prinsipi - CPU qızır, istilik borunun içində olan mayeyə keçir, maye buxarlanır, fan
həmin buxarı soyudub yenidən maye halına qaytarır və bu proses mütəmadi olaraq davam
edir.

---

**Undervolting** - Bu əlavə bir sistem deyil, sadəcə olaraq gərginliyi azaltmaqla enerji
istehlakının və bununla əlaqədar olaraq da istilik istehsalının azalmasına təsir göstərir.
Undervolting üçün onu dəstəkləyən BIOS və CPU tələb olunur.

---

# **`Kabel və konnektorlar`**

Kabellərin üç əsas növü var: 

- koaksial
- twisted-pair
- fiber-optik

### Twisted-pair kabel

Twisted-pair (bükülmüş cüt) kabellərin iki fərqli növü var: 

- STP (shielded twisted-pair -qoruyucu bükülmüş cüt)
- UTP (unshielded twisted-pair).

Hər iki növ kabelin içərisindən keçən iki və ya dörd cüt bükülmüş naqil var. Fərq ondadır ki, STP elektrik müdaxiləsini (interferensiya) azaltmaq üçün naqilləri əhatə edən əlavə örgülü folqa qoruyucu təbəqəsinə malikdir.

UTP kabellərinə Ethernet kabel də deyilir. Ethernet əslində IEEE 802.3 standartına əsaslanan
və xüsusi bir kabel növü ilə əlaqəli olmayan qoşulma metodudur. Texniki cəhətdən səhv olsa
da, kabelə istinad etmək üçün bu termindən istifadə etməyin heç bir zərəri yoxdur.

### Twisted-Pair kabel kateqoriyaları

- Category 1 - iki burulmuş cütdən ibarətdir. Yalnız səs ötürülməsi üçün nəzərdə tutulub və bu
gün bir çox köhnə telefon sistemlərində istifadə olunur.
- Category 2 - dörd cüt kabeldir. 4 Mbps-ə qədər sürətlə məlumat ötürülməsini təmin edir.
- Category 3 - 10 Mbps-ə qədər sürətlə məlumat ötürə bilir. CAT-5 çıxmazdan əvvəl 10BaseT
qurğuları üçün istifadə olunurdu.
- Category 4- 16 Mbps-ə qədər sürətlə məlumat ötürə bilir.
- Category 5 - 100 Mbps-ə qədər sürətlə məlumat ötürə bilir.
- Category 5e - 1 Gbps-ə qədər sürətlə məlumat ötürə bilir. Dörd burulmuş cütlər fiziki olaraq
bir-birindən ayrılır. Bu, maksimum interferensiya qorunmasını təmin edir.
- Category 6 - 10 Gbps sürətlə məlumat ötürə bilər, amma yalnız 55 metr məsafəyə qədər.
- Category 6a - 100 metrə qədər məsafədə 10 Gbps sürəti ötürə bilər.
- Category 7 - CAT-6e-nin təkmilləşdirilmiş versiyasıdır. Hər bir tel cütünün qoruyucu örtüyü
var, bu da xarici səs-küyə daha yaxşı müqavimət göstərir. 100 metrə qədər 10 Gbps sürətlə
ötürə bilir. Class F kabel də adlanır.
- Category 8 - Cat8 Ethernet kabelində ən son IEEE standartıdır. 40 Gbps ötürmə sürətinə
malikdir. Əsasən Data mərkəzlərdə istifadə olunur, qalın və ağır kabeldir.
UTP üçün standart maksimum ötürmə məsafəsi 100 metrdir (328 fut).

### Twisted-Pair konnektor növləri

Twisted-pair kabellər RJ (registered jack) adlanan konnektordan istifadə edirlər. Əksər
stasionar telefonlar RJ-11 konnektoru ilə qoşulur. UTP kabeli ilə istifadə edilən konnektor
RJ-45 adlanır. RJ-11-də iki cüt (dörd naqil) və RJ-45-də dörd cüt (səkkiz naqil) üçün yer var.

- Straight through (düz) kabel - fərqli layer-lərdə işləyən avadanlıqları qoşmaq üçün istifadə
olunur. Switch-i routerə, kompüteri switchə və s.
- Crossover kabel - Eyni layer-də işləyən avadanlıqları qoşmaq üçün istifadə olunur.
Kompüteri kompüterə, switch-i switch-ə və s

## Fiber-Optik kabel və növləri

O, rezin xarici örtüklə əhatə olunmuş nazik, elastik şüşədən ibarətdir. 100 Mbps-dən 10
Gbps-ə qədər ötürmə sürətini km-lərlə məsafədə təmin edir. Çünki o, məlumatların
ötürülməsi üçün elektrik siqnalı əvəzinə işıq impulslarından istifadə edir. Elektrik
interferensiya və telefon dinləmələrinə qarşı etibarlıdır.

Fiber-optik kabelin iki növü var: single-mode və multimode. Single-mode fiber (SMF) kabel
işığın yayılması üçün yalnız bir rejimdən (və ya yoldan) istifadə edir, multimode-fiber
(MMF) kabel isə işığın birdən çox rejiminin eyni vaxtda yayılmasına imkan verir.

- MMF kabel 550 metrə qədər məsafədə 10 Gbps sürətlə ötürə bilər. Single-mode fiber kabel
ümumiyyətlə magistral kabel kimi istifadə olunur. Həm də adətən telefon sistemlərində
istifadə olunan kabel növüdür. İşıq yalnız bir rejimdən istifadə edərək single-mode fiber-optik
kabeldən keçir, yəni o, birbaşa lifin ortasından düz keçir, divarlarına dəyib sınmır.
84
- Single-mode fiber-optik kabeldən istifadə edən cihazlar adətən kabeldən keçən işığı yaratmaq
üçün lazerdən istifadə edirlər. SMF kabel istifadə olunan standartdan asılı olaraq 40 kilometrə
qədər 10 Gbit/s ötürə bilir

### Fiber-Optik konnektor növləri

Əsas istifadə olunan 3 növü var:

- ST (straight tip)
- SC (subscriber connector (square connector))
- LC (local connector)

# `Power konnektorları`

Anaplatadakı bu yuva xüsusi konnektor (24 pinli) vasitəsilə anakartı enerji təchizatı ilə təmin
edir.

Anaplatada Disk konnektorları

- IDE (integrated drive electronics) = PATA (Parallel ATA) disklər 40 pinli kabel istifadə
edirlər

- SATA (Serial ATA)
    
    Müxtəlif növ SATA kabelləri var:
    
    - SATA 1 - 1.5 Gbps
    - SATA 2 - 3 Gbps
    - SATA 3 - 6 Gbps
    
- External SATA (eSATA)
    
    eSATA elektrik ötürmür, bu da müasir yüksək sürətli həmkarları ilə müqayisədə böyük
    çatışmazlıqdır. Bu məhdudiyyəti aradan qaldırmaq üçün Power over eSATA, eSATA+,
    eSATAp və ya eSATA/USB adlanan başqa portlarını görə bilərsiniz.
    

- SCSI (Small Computer System Interface)
Üçüncü tip disk konnektoru SCSI adlanır, "scuzzy" kimi tələffüz olunur. Siz ev
kompüterlərində SCSI interfeyslərini görməyəcəksiniz, bu daha çox serverlərdə və yüksək
səviyyəli iş stansiyalarında istifadə olunur.
SCSI-nin ilk versiyaları SPI (SCSI Parallel Interface) paralel bus texnologiyasından istifadə
edirdi. 1986-cı ildə hazırlanmış ilk standart 5 Mbps məlumat ötürülməsini təmin edən 8 bitlik
bus idi. 7 cihazı dəstəkləyə bilirdi.
1994-cü ildə 15-ə qədər cihazı dəstəkləyən və 320 Mbit/s ötürmə sürətinə malik olan 16 bitlik
versiya hazırlandı.
SPI standartdan asılı olaraq müxtəlif konnektorları var idi. Adətən 50-pin, 68-pin və 80-pin
konnektorları istifadə olunurdu
- SAS (Serial Attached SCSI)
2005-ci ildən başlayaraq SPI, serial bus qoşulma növü olan SAS ilə əvəz olundu. SCSI
ümumiyyətlə IDE kimi analoqlarından daha sürətli, lakin daha bahalı idi. SAS da SATA-dan
bir az daha sürətlidir. Ev kompüterlərində və ya laptop anaplatalarda SAS portlarını
görməyəcəksiniz, bu daha çox serverlərdə istifadə olunur. 15.000 rpm disklərin əksəriyyəti
SAS disklərdir.

**HDD (hard disk drive) sistemləri (və ya qısaca hard disklər)**
PATA hard disklərinin əksəriyyəti maksimum ötürmə sürəti 100 MBps olan ATA/100
standartına uyğundur. ATA/133 və ATA/167 kimi daha sürətli ATA standartları var, lakin bu
standartlardan istifadə edən disklər nadirdir. SATA 3 (həmçinin SATA 6 Gb/s kimi də
tanınır) 600 MBps maksimum ötürmə sürətinə malikdir.

# `BIOS/UEFI və POST mərhələsi`

- BIOS : Basic Input/Output System
- UEFI : Unified Extensible Firmware Interface

**Firmware (proşivka**) cihazda kodlanmış hər hansı bir proqrama verilən addır. Adətən **ROM
(read-only memory**) çipidir və əməliyyat sistemindən asılı olmadan işləyə bilir. Ən çox
kompüterlər, printerlər və əməliyyat sistemi olmayan cihazlar firmware istifadə edir.
Firmware kimi kompüterin çipində yazılmış **BIOS-u (Basic Input/Output System)** nümunə
göstərmək olar. Həmçinin, SCSI və videokartlar kimi bəzi genişləndirmə kartları periferik
qurğuların quraşdırılması üçün öz mikro proqram təminatı olan firmware-lərdən istifadə edir.
ROM BIOS çipi olaraq da adlandırılan BIOS çipi anaplatadakı ən vacib çiplərdən biridir. Bu
xüsusi yaddaş çipində sistemi işə salan və əməliyyat sisteminin də yüklənməsini təmin edən
BIOS sistem proqramı var.

BIOS çipini anaplatada necə tapmaq olar ?
Bu çipin üzərində BIOS sözü və istehsalçının adı (AMI, Phoenix/Award, Winbond və s.) ola
bilər. Yeni anaplatalarda BIOS-u müəyyən etmək biraz çətin ola bilər, hətta southbridge-ə
inteqrasiya oluna bilər, lakin onun funksionallığı dəyişməz olaraq qalır. BIOS-un yeni
versiyası **UEFI**-dir (Unified Extensible Firmware Interface). Klassik BIOS-da Secure Boot
funksiyası yoxdur.

### **POST kartı**

> POST – kompüter işə düşəndə ona qoşulan avadanlıqları yoxlayır.
> 

POST mərhələsində problemi təyin etmək üçün POST kartı istifadə edilə bilər. Bu,
sistemdəki genişləndirmə yuvasına (PCIe, PCI və ya USB) taxılan və yükləmə prosesi
irəlilədikcə rəqəmsal kodları bildirən lövhədir. Hər bir kod yoxlanılan xüsusi komponentə
uyğundur. POST kartı hansı nömrəni göstərirsə, problemi müəyyən etmək üçün kartın
təlimatında həmin nömrəyə baxa bilərsiniz.
Anaplata istehsalçıları səhv (error) mesajlarını göstərmək üçün müxtəlif siqnal kodlarından
istifadə edirlər. POST mərhələsi zamanı bip siqnal eşidirsinizsə, həmin siqnalın nə demək
olduğunu öyrənmək üçün internetdə axtarın. Siqnal kodlarına BIOS istehsalçısının saytında,
həmçinin bu saytda baxa bilərsiniz:

### **CMOS**

Kompüteriniz söndürüldükdə və elektrik kabelindən ayrıldıqda müəyyən parametrləri
saxlamalıdır:

- Tarix, Vaxt, HDD konfiqurasiyası, RAM, Overclock kimi CPU parametrləri
- İnteqrasiya edilmiş portlar (parametrləri, enable/disable olması)
- Boot ardıcıllığı, Virtuallaşdırma dəstəyi
- Təhlükəsizlik (parollar, Trusted Platform Module parametrləri, LoJack)

Kompüteriniz bu parametrləri CMOS (complementary metal oxide semiconductor) adlanan
xüsusi yaddaş çipində saxlayır

BIOS özündə olan standart məlumat ilə başlayır və sonra CMOS-dan alınan məlumatları
oxuyur, məsələn, kompüterin istifadə etməsi üçün hansı disklər konfiqurasiya edilib, yükləmə
sektorlarını hansı disklərdə axtarmalıdır və s.

CMOS yaddaşı adətən tutum baxımından təkmilləşdirilə bilməz, BIOS çipinə və ya
Southbridge-ə inteqrasiya oluna bilər.

CMOS batareyası
Texniki fərqlər olsa da praktikada BIOS və CMOS (BIOS çipi və CMOS çipi) terminləri birbirinin əvəzinə istifadə olunur.

# `**Videokart**`

Video adapter (daha çox qrafik adapter və ya videokart adlanır) monitorda və ya proyektorda
görüntünü göstərməsi üçün kompüterə yerləşdirdiyiniz genişləndirici kartdır. Video kart CPU
tərəfindən ona göndərilən məlumatları piksellərə, ünvanlara və monitor üçün tələb olunan
digər elementlərə çevirmək işini görür.

Videokartların iki növü var: onboard (inteqrasiya olunmuş) kartlar və addon (əlavə) kartlar.
İnteqrasiya edilmiş videokart prosessorda quraşdırılmış GPU-dur. CPU ilə paylaşılan sistem
yaddaşından istifadə edir.

İnteqrasiya edilmiş kartın üstün cəhəti onun genişləndirmə yuvasına ehtiyacının olmamasıdır.
Mənfi cəhət odur ki, videokart xarab olsa yeni anaplata almaq lazımdır və ya əlavə kart
quraşdıra bilərsiniz. İkinci bir mənfi cəhəti isə inteqrasiya edilmiş videokartların adətən
yüksək parametrli olmamasıdır. Əgər istifadəçi güclü videokart istəyirsə, onda əlavə kart
almaq lazımdır.

Əlavə kartlara gəldikdə, PCIe genişləndirmə yuvasına taxıla bilər. Siz hələ də köhnə AGP
yuvası olan nadir anaplata tapa bilərsiniz və bəzi PCI videokartları görə bilərsiniz, lakin onlar
nadirdir. PCIe-nin tərtib olunduğu texnologiya video üçün AGP və PCI-nin əsaslandığı
texnologiyadan daha yaxşı işləyir.

# `Video kabellər`

## VGA konnektor və portu - analoq texnologiya

VGA (Video Graphics Array) konnektoru illər boyu kompüterlər üçün video standartı idi və
bu gün də istifadə olunur. İlk dəfə 1987-ci ildə IBM tərəfindən təqdim edilmiş, digər
kompüter istehsalçıları tərəfindən tez bir zamanda qəbul edilmişdir. VGA 15 pinli video
konnektordur və analoq texnologiyadır. O, DVI və HDMI kimi daha yeni rəqəmsal
standartlarla əvəz olundu və 2013-cü ildən başlayaraq tədricən ləğv edilməli idi.

## DVI (Digital Visual Interface)

Analoq VGA standartlarını əvəz etmək, daha uzun məsafəyə və daha yüksək keyfiyyətlə
ötürülə bilən rəqəmsal video siqnal əldə etmək məqsədilə DVI konnektorlar (1999-cu ildə)
hazırlanmışdır.
İlk baxışda DVI konnektoru standart D-sub konnektor kimi görünə bilər, ancaq bir qədər
fərqlidir.
DVI konnektorların üç əsas kateqoriyası var:

- DVI-A yalnız analoqdur. Mənbə analoq siqnalı göndərməli və monitorun da analoq siqnalı
qəbul etmək funksiyası olmalıdır.
- DVI-D yalnız rəqəmsaldır.
- DVI-I analoq/rəqəmsal konnektroun birləşməsidir. Mənbə və monitor eyni texnologiyanı
dəstəkləməlidir, bu kabel rəqəmsal və ya analoq siqnalla işləyir.
- DVI-D və DVI-I konnektorları iki növdə olur: single-link və dual-link. Dual-link
konnektorları daha yüksək sürət və siqnal keyfiyyətinə malikdir. DVI-A və DVI-I analoq
keyfiyyəti VGA keyfiyyətindən üstündür.

## HDMI (High-Definition Multimedia Interface) —tam rəqəmsaldır

HDMI (High-Definition Multimedia Interface) tam rəqəmsaldır.
HDMI 2002-ci ildə təqdim edilib. Standart və High Speed növləri var. Standart kabellər 720p
resolution, 1080i görüntü təmin edir. Yüksək Sürətli kabellər təkcə 1080p deyil, həm də daha
yeni 4K və 3D texnologiyalarını dəstəkləməyə qadirdir.
1080p - piksel deyil. p - progressive scan, 1080i - interlaced scan

## DisplayPort

DisplayPort 2008-ci ildə VGA və DVI-ı əvəz etmək üçün VESA (Video Electronics
Standards Association) tərəfindən hazırlanıb. Digər rəqəmsal interfeyslər və VGA ilə
müqayisədə daha az enerji istifadə edən rəqəmsal interfeysdir. DisplayPort kabelləri 33 metrə
qədər istifadə etmək olar. DisplayPort əsasən video üçün nəzərdə tutulub, lakin o, HDMI
kimi audio və videonu eyni vaxtda ötürə bilir

# `Çoxfunksiyalı kabellər`

## USB (Universal Serial Bus)

| Adı | Rəngi |
| --- | --- |
| USB 1.1 | White |
| USB 2.0 | Black |
| USB 3.0 | Blue  |
| USB 3.1 | Teal |
| USB 3.2 | n/a |

# `Modem`

Analoq dial-up bağlantısından istifadə edərək İnternetə qoşulan hər hansı bir kompüterə
modem və ya modulyator/demodulyator lazımdır. Modem kompüterdən gələn rəqəmsal
siqnalları telefon xətləri üzərindən ötürülə bilən analoq siqnallara çevirən cihazdır. Şəkildə
göstərilən PCI modeminin iki RJ-11 (Registered Jack 11) portu var: biri telefon xəttinə, digəri
isə telefona qoşulmaq üçündür. Bu, ona görədir ki, telefon kabellərini dəyişdirmədən və ya
ayrıca splitter istifadə etmədən kompüterin qoşulduğu divarda olan eyni RJ-11 yuvasından
istifadə edə bilsin. Ancaq unutmayın ki, kompüter İnternetə qoşulu olduqda telefondan
istifadə edə bilməyəcəksiniz.

### `DSL və Kabel Modemlər`

Ənənəvi modem mahiyyətcə köhnəlib – əksər evlər və bir çox müəssisələr indi kabel modem
və ya DSL (digital subscriber line) modemdən istifadə etməklə internetə çıxırlar. Kabel
modemlər televiziya kabel xətlərindən, DSL modemlər isə telefon xətlərindən istifadə edir.
Həm kabel, həm də DSL modemlər rəqəmsaldır və buna görə də texniki cəhətdən modem
sayılmırlar, çünki onlar analoq siqnalları modulyasiya və demodulyasiya etmirlər.

Provayder tərəfdə müştərinin DSL xəttindən internet bağlantısı sorğusunu qəbul edən və ya DSLAM (DSL Access Multiplexer) olur.

- HDSL - high bit-rate Digital Subscriber Line
- SDSL - Symmetric Digital Subscriber Line
- VDSL - Very high bit-rate Digital Subscriber Line
- ADSL - Asymmetric Digital Subscriber Line

## `Access Point`

Access point - istifadəçiyə şəbəkəyə daxil olmağa imkan verən istənilən nöqtədir. Termin
adətən istifadəçilərə 802.11 texnologiyası ilə şəbəkəyə qoşulmağa imkan verən wireless
access pointi ifadə etmək üçün istifadə olunur.

## `Repeater və Extender`

Repeater və ya extender - siqnalı qəbul edən, gücləndirən və göndərən kiçik, güclü bir
cihazdır. Repeaterin bütün məqsədi kabel xəttinin funksional məsafəsini uzatmaqdır.
Məsələn, UTP-nin 100 metrlə məhdudlaşdığını bilirsiniz, amma 160 metr uzunluğunda bir
kabel xətti çəkmək lazımdırsa necə olacaq ? Mərkəzdə repeater qoyub, iki kabel çəkib işlədə
bilərsiz. Repeater və extenderlər OSI modelinin Physical layer-ində (Layer 1) işləyir. Onlar
məlumatları yoxlamırlar və ya ona heç bir dəyişiklik etmirlər, sadəcə qəbul edirlər və
göndərirlər.

## `Bridge`

Bridge OSI modelinin Data Link layer-ində (Layer 2) fəaliyyət göstərir. Şəbəkəni bir neçə
collision domain seqmentlərinə bölmək üçün istifadə olunur. Bridge şəbəkənin hansısa
seqmentində heç bir qəbuledicisi yoxdursa, istənməyən trafikin həmin seqmentə girməsinin
qarşısını alır.
Məsələn, bir şəbəkə seqmentində 100 host varsa, eyni vaxtda hamı mübadilədə olarsa
performans orta səviyyədə olacaq. Əgər şəbəkəni hər biri 50 hostdan ibarət iki seqmentə
bölmək üçün bridge-dən istifadə etsəniz, hər iki tərəfdə trafik xeyli azalacaq və performans
yaxşılaşacaq.
Əgər bridge “destination MAC address”-i bilirsə, o, paketləri düzgün seqmentə yönləndirə
bilər, əks halda paketləri bütün seqmentlərə yönləndirir. Bridge-lərin əsas çatışmazlığı onların
broadcast paketləri ötürməsidir.

# `Switch`

Switch Layer 2-də işləyir və eynilə hub kimi mərkəzləşdirilmiş keçid təmin edir. Hub trafiki
hər porta göndərir, amma switch gələn paketin Layer 2 headerini (MAC addressi) yoxlayır və
onu yalnız getməli olduğu porta yönləndirir.
Switch-lər iki növdə olur: unmanaged və managed.

### Unmanaged switch

Iki və ya daha çox kompüteri birləşdirir və trafiki MAC ünvana uyğun
olaraq göndərilən porta ötürür. Managed switch - portları konfiqurasiya etmək, trafiki idarə
etmək və problemlər üçün trafiki monitor etmək imkanı verir. İdarəetmə üçün switch SNMP
(Simple Network Management Protocol) şəbəkə protokolundan istifadə edir. Managed
switch-lər baha olur, lakin QoS, redundancy, port mirroring və VLAN kimi funksiyaları var.

## QoS

(quality of service - xidmət keyfiyyəti) administratorlara müəyyən şəbəkə trafikinə
prioritet (üstünlük) verməyə imkan verir. Yüksək prioritetli trafik xüsusi serverdən və ya
xüsusi proqramdan gələ bilər. Bu daha çox VoIP (Voice over IP)-də tətbiq olunur. Şəbəkə
üzərindən kompüter və telefon zəngləri trafiki keçir, zəng trafikinə yüksək prioritet verilir ki,
danışıq keyfiyyətli olsun.

## Port Mirroring

(port aynalama) - Bu, şəbəkə monitoru ilə birlikdə istifadə olunan
troubleshooting funksiyasıdır. Bir port başqa bir portu mirror etməsi üçün konfiqurasiya edilə
bilər. Həmin porta trafik göndərildikdə, o da mirror edildiyi porta göndərir. Mirroring
(aynalanmış) porta qoşulmuş şəbəkə monitoru daha sonra şəbəkəni və ya cihazı orijinal
portda oflayn etmədən trafiki analiz edə bilər.

## `VLAN`

(Virtual LAN) -da eyni fiziki switch-ə qoşulmuş kompüterlər çoxlu məntiqi
şəbəkələrə bölünə bilər. Bu, hər bir VLAN-da şəbəkə trafikini azaldır, çünki trafik digər
VLAN-lardan təcrid olunur. Görəcəyiniz demək olar ki, hər bir hub və ya switch üzərində bir
və ya daha çox status göstərici indiqator işığı var. Normal əlaqə varsa yaşıl işıq, əlaqədə
nasazlıq varsa sarı işıqla göstərilir.

# `Router`

Routerlər çoxlu şəbəkə növlərini birləşdirən və məlumatların göndərilməsi üçün ən yaxşı
yolu müəyyən edən yüksək intellektual cihazlardır. Onlar paketləri çoxlu şəbəkələr üzrə
istiqamətləndirmək və ən yaxşı yolu müəyyən etmək məqsədilə şəbəkə ünvanlarını saxlamaq
üçün routing table-lardan (marşrutlaşdırma cədvəllərindən) istifadə edirlər. Routerlər OSI
modelinin Network layer-ində (layer 3), IP ünvanlara əsasən işləyirlər. Onlar bir neçə
şəbəkəni bir-birinə bağlayır. Routerlər broadcast sorğuları yönləndirmir. WAN qurulduqda,
ən azı iki router istifadə olunur.

Son bir neçə ildə wireless router-lər kiçik biznes və ev şəbəkələri üçün istifadə olunur. Onlar
şəbəkə ilə əlaqəli routerlərin bütün funksiyalarına malikdirlər, lakin nisbətən ucuzdurlar

# `Firewall`

Firewall, hardware və ya software olaraq sizin şəbəkənin mühafizəçisi rolunu oynayan
xidmətdir. Yəqin ki, şəbəkədə internetə qoşulmuş ən vacib cihazdır. Firewall-lar sizi iki yolla
qoruya bilər: Onlar şəbəkə resurslarınızı hakerlərdən qoruyur və eyni zamanda şəbəkənizdəki
kompüterlərin internetdəki arzuolunmaz məzmuna daxil olmasının qarşısını ala bilər.
Firewall, şəbəkə administratoru tərəfindən müəyyən edilmiş qaydalara əsasən paketləri filter
edir.
Firewall-lar serverdə və ya routerda quraşdırılmış proqram təminatı və ya avadanlıq və
proqram təminatının kombinasiyası ola bilər. Əksər firewallların ən azı iki şəbəkə bağlantısı
olur: biri internetə (public) tərəfə, biri də daxili (internal və ya private) şəbəkəyə baxır. Bəzi
firewall-larda yarı-daxili şəbəkə üçün də üçüncü şəbəkə portu olur. Bu port veb və e-poçt
serverləri kimi həm public, həm də private hesab edilə bilən serverləri qoşmaq üçün istifadə
olunur. Bu şəbəkə DMZ (demilitarized zone) adlanır.

Firewall-lar network-based və ya host-based ola bilər. Host-based firewall (məsələn,
Windows Firewall) yalnız quraşdırıldığı fərdi kompüteri qoruyur.
Firewall-larda ACL (access control list) konfiqurasiya edilir. ACL hansı trafikin firewalldan
keçəcəyini və hansı trafikin blok ediləcəyini müəyyən edən qaydalar toplusudur. ACL-lər
adətən IP ünvan, port nömrəsi, domen adı və ya hər üçünün bəzi kombinasiyası vasitəsilə
trafiki bloklamaq üçün konfiqurasiya edilir. Kerio, PfSense, PaloAlto, Fortigate və s.
firewall-lar var.

# `Storage Devices (Yaddaş qurğuları)`

### **Önəmli 2 anlayış**

- Volatile Storage (elektrik-dən asılıdır)
- Non-Volatile Storage (elektrik-dən asılı deyil)

## HDD (Hard disk drive)

Hard diskin anatomiyası
Hard disk hermetik şəkildə bağlanmış disk korpusuna tozun daxil olmasının qarşısını almaq
üçün təmiz otaqda yığılır. 

Hard diskin komponentləri:

- Platter - Platterlər maqnitlə örtülmüş bir və ya daha çox alüminium, şüşə və ya keramika
disklərdir.
- Spindle – qolu fırladan dairə
- Read/write head - read-write qolu həmçinin actuator adlanır.
- Track - hər bir platter, track adlanan konsentrik dairələrə bölünür. Platterin xarici tərəfindən
sıfırdan başlayaraq daxili tərəfə doğru track-lərin sayı artmağa davam edir. Hər bir track
minlərlə bayta qədər böyük miqdarda məlumat saxlaya bilər.
- Sector - hər bir track, sector-lar adlanan daha kiçik hissələrə bölünür. Sector diskdəki ən
kiçik yaddaş vahididir. Hər track-də eyni sayda sector var, bu o deməkdir ki, sector-lar diskin
mərkəzinə yaxın olan track-lərdə bir-birinə daha yaxın yığılıb. Tək bir track-də minlərlə
sector ola bilər. Sektorun məlumat ölçüsü demək olar ki, həmişə ya 512 ya da 4096 baytdır.
- Cluster - sector-lar çox vaxt cluster yaratmaq üçün qruplaşdırılır. Əgər bitişik cluster-lər
mövcud deyilsə, verilənlər diskin başqa yerində yazılır və fayl parçalanmış hesab olunur.
- Cylinder - Platterin kənarından eyni məsafədə olan bütün track-lərin kolleksiyası cylinder
adlanır

### HDD ölçüləri

Fiziki olaraq, ən çox yayılmış hard disk ölçüləri 3,5" və 2,5"-dir.
Masaüstü kompüterlər ənənəvi olaraq 3,5 düymlük disklərdən istifadə edir. 2,5 düymlük
disklər noutbuklar üçün hazırlanmışdır.
1,8 düymlük disklər bəzi noutbuklarda və daha kiçik cihazlarda istifadə olunur.
1 inch (düym) = 2.54 sm

## SSD (Solid-State Drives)

Ənənəvi hard disklərdən fərqli olaraq, SSD-lər hərəkət etməyən hissələrə malikdir - onlar
digər flash kartlarda olduğu kimi solid-state (möhkəm-vəziyyətli) yaddaş texnologiyasından
istifadə edirlər.

***SSD-lər mexaniki disklərlə müqayisədə bir sıra üstünlüklərə malikdir :***

1. Daha sürətli başlama və oxuma vaxtları
2. Daha az enerji istehlakı və az istehsal olunan istilik
3. Səssiz işləməsi
4. Hərəkətli hissələrin olmaması səbəbindən fiziki zərbə və istilik istehsalı
nəticəsində zədələnməyə daha az həssasdır.
5. Kvadrat santimetr sahə üçün daha yüksək məlumat sıxlığı

***SSD-lərin çatışmazlıqları :***

1. SSD texnologiyası hər bayt üçün daha bahalıdır.
2. İstifadə müddəti məhdud sayda yazıb-silmə əməliyyatlarının sayı ilə məhdudlaşır.
Yəni çox uzunömürlü olmurlar.

## NVMe (Non-Volatile Memory Express)

M.2 kimi, NVMe disklər də SATA və PCIe bus-ı dəstəkləyir. Siz PCIe və M.2 yuvalarına
uyğun NVMe SSD-ləri və hətta PCI interfeysli 2,5″ NVMe disklərini tapa bilərsiniz. Hazırkı
NVMe SSD-lər 3,5 GBps-ə qədər məlumat oxumanı dəstəkləyə bilər, bir şərtlə ki,
qoşulduqları interfeys onu da dəstəkləsin. Fərqli şəkildə desək, bir NVMe SATA 3 SSD-nin
hələ də 600 MBps ilə məhdudlaşacağını unutmayın; PCIe-də eyni məhdudiyyət yoxdur.

## NAS

Network Attached Storage (Network Area Storage də deyilir) - Prosessoru, RAM-ı,
disk slotları, firmware-i (əməliyyat sistemi) olan avadanlıqdır. Taxılan disklərin eyni
model, eyni ölçülərdə olması məsləhətdir. Web interfeysdən konfiqurasiya edilir. NASda olan disklər şəbəkə üzərindən serverlərə ISCSI (oxunuşu: ayskazi) olaraq əlavə edilir
və serverlər bu diskləri lokal disk kimi görüb istifadə edirlər.

## SAN

(Storage Area Network) .NAS-la eyni işi görür, fərqi budur ki, optik kabellə
qoşulur. Eyni parametrli NAS-la müqayisədə 10 qat bahadır, ona görə də çox yerdə

# `OSI`

OSI modelinin hər bir təbəqəsi fərqli cihazlarla işləyir:

7—Application layer - Application layer şəbəkə xidmətlərinə daxil olmaq imkanı verir. Bu,
fayl xidmətləri, çap xidmətləri və digər proqramların işlədiyi təbəqədir.
6—Presentation layer - Bu təbəqə verilənlərin “görünüşünü” və ya formatını müəyyən edir,
məlumatların sıxılmasını və şifrələnməsini idarə edir.
5—Session layer - Bu təbəqə müxtəlif kompüterlərdə tətbiqlərə seans qurmaq, saxlamaq və
sonlandırmaq üçün imkan verir. Sessiya bir virtual söhbətdir. Məsələn, bir faylı ötürmək üçün
lazım olan bütün prosedurlar bir seans təşkil edir. Sessiya bitdikdən sonra yeni proses
başlayır. Bu təbəqə parolların, girişlərin müəyyən edilməsi və şəbəkə monitorinqi kimi
prosedurları idarə edir.
4—Transport layer - Transport layer məlumat axınına nəzarət edir, ötürülməsi və ya qəbulu
ilə bağlı hər hansı problemləri həll edir. Böyük mesajları daha kiçik seqmentlərə bölür. TCP
protokolu məlumatı seqmentlərə bölür, nömrələyir və sıra ilə təyinat hostunun bütün
seqmentləri qəbul etdiyini yoxlayır, qarşı tərəfdən seqmentin qəbul edildiyi təsdiqi gəlməzsə
yenidən həmin seqmenti göndərir. UDP protokolu isə təsdiq gəlməyini gözləmədən göndərir.
TCP/IP - Transmission Control Protocol/Internet Protocol - Paketlərin bir kompüterdən
digərinə çatdırılmasından əmin olmaq istəyirsinizsə, TCP/IP bunu edə bilər. Protokol UNIX,
Linux, macOS, Windows, iOS və Android kimi fərqli əməliyyat sistemlərində işləyə bilər.
3—Network layer - Network layer mesajların məntiqi ünvanlanmasına cavabdehdir. Bu
təbəqədə məlumatlar paket adlanan hissələrə bölünür. Bu layer IP-ə əsasən işləyir. Network
layer yol polisi kimi bir şeydir. O, şəbəkənin vəziyyətinə, marşrutlaşdırma protokollarına
əsaslanaraq məlumatın göndərilməsi üçün ən yaxşı yolu təyin edir, trafiki idarə edir. Router
bu layer-də işləyir.
2—Data Link layer - Bu təbəqə məlumatları frame adlanan hissələrə ayırır. Ötürülməni
asanlaşdırır, daha rahat idarə etməyə və frame-lərdə səhvlərin yoxlanılmasına imkan verir.
Switch bu layer-də işləyir. Data Link layer hər bir NIC üçün unikal fiziki ünvanı (physical
address, həmçinin MAC ünvanı adlanır) göstərir. Data Link təbəqəsi əslində iki hissəyə
bölünür: MAC (Media Access Control) və LLC (Logical Link Control).
LLC - Data link layer üçün sinxronizasiyaya, məlumat axınına və xətaların yoxlanılması
funksiyalarına nəzarət edir.
1—Physical layer - Bu təbəqə məlumatların hansı üsulla ötürüldüyünü təsvir edir. Məlumat
parçasının naqillər üzərindən göndərilən elektrik siqnallarına və ya işıq impulslarına, hava ilə
göndərilən radio dalğalarına çevrilməsini müəyyən edir. Bu, kabelin elektrik, optik, mexaniki
və funksional interfeysləri ilə əlaqədardır.

# `NIC - Network Interface Card`

NIC, həmçinin şəbəkə adapter kartı adlanır, kompüter və kabellər arasında fiziki interfeysi
təmin edir. O, məlumatları hazırlayır, göndərir və məlumat axınına nəzarət edir. O, həmçinin 

CPU-nun başa düşməsi üçün məlumatları qəbul edib baytlara çevirir. NIC-lər bir çox forma
və ölçüdə olur.
Məsələn, wireless şəbəkəniz 802.11g/n/ac-ı dəstəkləyirsə, 802.11ac kartı alın, çünki o, ən
sürətlidir.
- NIC-lər full-duplex və ya half-duplex rejimində məlumat göndərə bilər. Half-duplex rabitə o
deməkdir ki, göndərən və qəbul edənlərdən yalnız biri eyni vaxtda məlumat ötürə bilər. Fullduplex rabitədə kompüter eyni vaxtda məlumat göndərə və qəbul edə bilər.

### NIC-lərdə MAC address

Hər bir kartın MAC ünvanı adlanan unikal avadanlıq ünvanı olmalıdır. Əgər bir şəbəkədə 2
kartın eyni MAC ünvanı varsa, heç biri əlaqə qura bilməyəcək. Bu səbəbdən, IEEE şəbəkə
kartı ünvanları üçün bir standart yaratdı və bu ünvanların bir hissəsini NIC istehsalçılarına
təyin etdi, digər hissəsini isə istehsalçı özü təyin edir. MAC ünvanları 48 bit uzunluğundadır
və B6-15-53-8F-29-6B kimi onaltılıq sistemlə yazılır. ipconfig /all komandası ilə CMD-də
MAC ünvana baxmaq olar.

### NIC Driver

Hər zaman driverləri yükləmək üçün ən yaxşı yer istehsalçının veb-saytıdır. Device
Manager-də kartlara baxmaq, Update Driver etmək mümkündür.

## `IEEE 802`

IEEE (The Institute of Electrical and Electronics Engineers) şəbəkə növlərini
standartlaşdırmaq üçün bir alt komitə yaratdı. IEEE 802 başlıqlı bir neçə standart var. Bu gün
ən çox istifadə edilənlər 802.3 CSMA/CD (Ethernet) LAN və 802.11 Wireless şəbəkələrdir.

- Lan,Ethernet (IEEE 802.3),
- Wi-Fi Wireless Network (IEEE 802.11)
- Bluetooth (IEEE 802.15.1)

# **`Server`**

Dedicated Server - xüsusi, ayrılmış server.
Nondedicated Server - bir və ya bir neçə xidməti təmin etmək üçündür.

Seeverlə əməliyyat sistemi yükləyib müxtəlif rollar vermək olar. 

- DHCP
- DNS
- Firewall
- Web Server
- File Server
- Print Server
- Proxy Server
- Mail Server və s. kimi fəaliyyət göstərə bilər.

# `Network Services`

Demilitarized zone

Demilitarized zone (DMZ), bir şəbəkədə xüsusi təhlükəsizlik zonasıdır. Bu, hər iki daxili və xarici şəbəkə trafiqinin izlənə biləcəyi və idarə edilə biləcəyi bir zonadır. DMZ, daxili şəbəkəni xarici təhdidlərdən qorumaq üçün çox vacib bir elementdir.

Print server

Print server, şəbəkədəki istifadəçilərin printeri idarə etmələrinə imkan verir. Bu, printerlərin daha səmərəli və idarə olunan bir şəkildə istifadə olunmasını təmin edir.

File server 

File server, şəbəkədəki istifadəçilərin məlumatları saxlamaq, paylaşmaq və idarə etmək üçün istifadə etdiyi bir serverdir. Bu, məlumatların şəbəkədəki istifadəçilər arasında təhlükəsiz və effektiv bir şəkildə paylaşılmasını təmin edir.

Web server

Web server, şəbəkədəki istifadəçilərin veb səhifələri görmək və idarə etmək üçün istifadə etdiyi bir serverdir. Bu, veb məzmunun təhlükəsiz və effektiv bir şəkildə paylaşılmasını təmin edir.

# `File System`

- FAT16 -max 2GB qədər volume dəstəkləyir.Çox köhnə hesab olunur
- FAT32-32GB qədər dəstəkləyir.File köçürmələri zamanı 4GB limiti var.
- NTFS - 16 exabytes volume.BitLocker encryption,kompress
- ReFS - dayana dayanıqlıdır.

# `Printer`

Impact printer (zərbəli printer)

- Daisy-Wheel (tam zərəbli)
- Dot-matrix (yarı zərbəli)

İnkjet printerlər 

Inkjet printerlər işləyirklər mürəkkəb damlacıqlarını kağıza püskürtməklə. Bu, printerin proqramı tərəfindən idarə olunur, həmin proqram çap ediləcək şəkil və ya mətni nöqtələr şəklinə tərcümə edir. Bu nöqtələr sonra printerin mürəkkəb kartuşunun kiçik nozzulları vasitəsilə kağıza püskürtülür. Püskürtülən mürəkkəb daha sonra tez qurur, kağızda çap edilmiş şəkli və ya mətni buraxır.

mürəkkəbi püskürməklə

Laser printer 

Laser printerlər işıq (laser) vasitəsi ilə toneri (toz formada mürəkkəb) kağıza çap edir. Bu prosesdə laser ışığı tonerin kağıza yapışmasını təmin edən elektrik yükünü dəyişir. Daha sonra, toner kağıza press olunur və istilik ilə qurudulur.

Thermal printers

Mum(Şam) əsaslı mürəkkəbi əridmək və ya kağıza köçürmək üçün termal(yüksək) istilik çap başlığından istifadə edən və ya təsviri yaratmaq üçün xüsusi işlənmiş kağızı seçici şəkildə qızdıran printer növü 

# `DHCP`

DORA prinsipi ilə işləyir

Şəbəkə qoşulmuş client kompüter şəbəkədə broadcast edir,əgər dhcp yoxdursa,apipa-dan ip alır.dhcp varsa dhcp ip verir.

PC ⇒ DHCP

1. DHCP Discover (broadcast)
2. DHCP OFFER (unicast)
3. DHCP REQUEST (broadcast)
4. DHCP ACK (unicast)

# `DNS`

### Common DNS record types

Type Meaning
SOA ⇒ Start of Authority. It signifies the authoritative DNS server for that zone.
NS ⇒  Name Server. It’s the name or address of the DNS server for that zone.
MX ⇒ Mail Exchanger. It’s the name or address of the email server.
A ⇒ IPv4 host record
AAAA ⇒ Called “quad A,” it’s the host record for IPv6 hosts.
CNAME ⇒ Canonical Name. It’s an alias; it allows multiple names to be assigned to
the same host or address.

# `Mail Server`

- SMTP 25 Sending email and transferring email between mail servers
- POP3 110 Receiving email
- IMAP4 143 Receiving email. It’s newer and has more features than POP3.

# `**Cloud**`

Bulud texnologiyası faylları saxlamaq və ya proqramları işə salmaq üçün uzaq serverlərə
daxil olduğunuz bir üsuldur. Yüzlərlə kommersiya buludları mövcuddur. Onların bir çoxu
Microsoft, Google, HP, Apple və Amazon kimi böyük şirkətlərə məxsusdur. Əsasən, onlar öz
şəbəkələrində sizin üçün hardware (avadanlıq) və software (proqram) təminatı qururlar və siz
ondan istifadə edirsiniz.

- IaaS

you manage : Data,Applications

service provider manages : Networking,Storage,Servers,Virtualization,O/S,Middleware,Runtime

- PaaS

you manage : O/S,Middleware,Runtime,Data,Applications

service provider manages : Networking,Storage,Servers,Virtualization

- SaaS

service provider manages : Networking,Storage,Servers,Virtualization,O/S,Middleware,Runtime,Data,Applications

# `Hypervisor`

Hypervisor virtuallaşdırma üçün imkan verən proqram təminatıdır və VMM (virtual machine
manager) kimi də tanınır. Hypervisor eyni hostda birdən çox VM yaradıb, onları ayrı-ayrı
əməliyyat sistemi ilə işlətməyə imkan verir. VM-lər həmin hostun fiziki resurslarından eyni
zamanda istifadə edirlər.

![hyper.png](%C6%8Fsas%20qeydl%C9%99r/hyper.png)

- Type 1 hypervisor-lara misal olaraq Microsoft Hyper-V, Vmware ESX və Citrix
XenServer-i göstərmək olar. (soldakı)
- Type 2 hypervisor-lara misal olaraq Microsoft-un Windows Virtual PC və Azure Virtual
Serveri, Oracle VM VirtualBox, Vmware Workstation və Linux KVM-i göstərmək olar.(sağdakı)

## Emulator

Virtual maşınların fiziki maşın kimi işləməsi üçün fiziki maşının bütün tələbləri hypervisor
tərəfindən təkrarlanır və bu proses emulyasiya (emulation) adlanır. Hypervisor və emulator
terminləri eyni məna daşımasa da, bir-birinin əvəzinə işlənir. Hypervisor bir çox əməliyyat
sistemini dəstəkləyə bilər, amma texniki cəhətdən emulator xüsusi bir əməliyyat sistemi ilə
işləyir. Misal üçün, Andy pulsuz emulator-dur. Andy-ni masaüstü kompüter və ya noutbuka yazıb, sonra Andy daxilində Android proqramlarını quraşdıra bilərsiz. Beləliklə, öz sevimli mobil oyunlarınızı masaüstü kompüterlər və ya noutbuklarda oynaya bilərsiz. Bluestack da eyni məqsədli emulator proqramdır.

# `Operating System`

Cooperative Multitasking

Preemptive Multitsaking

### Multithreading

Multithreading is the ability of a single application to have multiple requests in to the processor at one time. This results in faster application performance because it allows a program to do many things at once.

32 bitlik prosessorlarda 4 RAM-dan çox istifadə etmək olmur.

## Operating System Life Cycle

- Alpha
- Beta
- Release Candidate
- Current
- Service Pack
- Mainstream Support
- Extended Support

# **`Network Adapters`**

- Bridge adapter

Host ilə Guest eyni şəbəkədən ip-ni alır.Bir-birini görür.Host-un internetə çıxışı varsa,Guest-in də var.

- NAT - **Network address translation**

Şəbəkə qurulub.Guest Host ilə eyni şəbəkədən ip-ni almır.Bir-birini görür.

- Host Only

Şəbəkə qurulub.Guest Host ilə eyni şəbəkədən ip-ni almır.Bir-birini görür.

Host-un internetə çıxışı olsada,Guest-in yoxdur.

- VMnet

Şəbəkə qurulmur,biz ilə qururuq. Host Guestin əlaqəsi yoxdu.

Guest-lərin bir-biri ilə əlaqəsi var.

VMnet 8 - NAT

VMnet 1- Host Only

- LAN segment

Şəbəkə qurulmur,biz qururuq. Host  ilə Guestin əlaqəsi yoxdu.

Guest-lərin bir-biri ilə əlaqəsi var.VMnet-dən fərqli olaraq şəbəkəyə ad veririk.

# `Driver`

Driver, kompüter sistemindəki müxtəlif avadanlıqların işləməsini idarə edən proqramdır. Hər bir avadanlıq üçün xüsusi driverlər mövcuddur ki, bu driverlər avadanlığın dəqiq funksionallığını müəyyən edir. Driverin düzgün işləməsi, kompüterin stabil və effektiv işləməsi üçün çox önəmlidir.