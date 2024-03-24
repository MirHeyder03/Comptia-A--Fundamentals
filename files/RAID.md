# RAID

## `Reduntant Array of Independent (Or Inexpensive ) Disk`

**Artan performansı (disklərin daha sürətli oxuma və yazması) və nasazlığa dözümlülüyü
(disklərin sıradan çıxması hallarında) təmin etmək məqsədilə bir neçə disk bir sistem kimi
birlikdə işləyə bilər. Belə sistemlər RAID (Redundant Array of Independent (və ya
Inexpensive) Disk) adlanır.**

RAID proqramla (software), məsələn, əməliyyat sistemi vasitəsilə və ya avadanlıqla
(hardware), məsələn, RAID avadanlığının BIOS-u vasitəsilə həyata keçirilə bilər. Hardware
RAID daha səmərəlidir və daha yüksək performans göstərir, amma qiyməti baha olur.
RAID-in bir neçə növü var. Aşağıdakılar ən çox istifadə edilən RAID növləridir:

- Raid 0 - Striping
- Raid 1 - Mirroring
- Raid 5 - Striping with Parity
- Raid 10 (1+0)

# `RAID 0`

Ən az 2 disk olmalıdır və maksimum 32 disk ola bilər. Sürətlidir,
məlumatları disklərə bölüşdürüb yazır. Amma mirroring eləmir. Disklərdən biri yansa
məlumatlar da itirilir. Üstünlüyü disklərin həcminin tam istifadə edilməsidir. 2 ədəd 4
TB disk varsa, 8 TB yaddaşın olur.

- `Düstur`: Minimum*disklərin sayı

![raid0.png](RAID%2058bda834b034429aa1ece8494c09622c/raid0.png)

# `RAID 1`

Mirroring (aynalama) var. Məlumatları disklərə kopyalayıb yazır. Dezavantajı
disklərin həcminin yarısını istifadə edə bilirsən, çünki yarısı kopya etməyə istifadə
olunur. 2 ədəd 4 TB disk varsa, cəmi 4 TB yaddaşın olur. Disklərdən biri yansa
məlumatların itmir. Yanan diski dəyişirsən, avtomatik proses davam edir. Ancaq cüt
sayda disklərə tətbiq edilə bilər.

- `Düstur`: Minimum*2/2

![raid1.png](RAID%2058bda834b034429aa1ece8494c09622c/raid1.png)

# `RAID 5`

Ən az 3 diskə tətbiq edilə bilər. Məlumatlar bərabər şəkildə (striping with
parity) müxtəlif disklərə yazılır. Biri yansa digərlərindən kopyalanır. 4 ədəd 4 TB disk
varsa, cəmi 12 TB yaddaşın olur. Oxuma sürəti yüksək, yazma sürəti aşağıdır. 

- `Düstur`: Minimum*(disk sayı-1)
- Disk sayı artdıqca disk itkisinin faizi azalır

![RAID.png](RAID%2058bda834b034429aa1ece8494c09622c/RAID.png)

## RAID 50 (RAID 5+0) da var

## `RAID 6 (RAID 6+0)`

Ən az 4 diskə tətbiq edilə bilər. 2 Disk aynalama üçün istifadə
olunur. RAID 60 da var.

## `RAID 10 (RAID 1+0)`

RAID 0 və RAID 1 birləşdirilməsi. Minimum 4 diskə tətbiq
edilə bilər. Cüt disklər RAID 1-lə birləşdirilir, bir-birini kopya edir. Sonra birləşən
disklərə RAID 0 tətbiq edilir. RAID 1-in kopya etməsi, RAID 0-ın sürəti üstünlük
qazandırır. 4 ədəd 4 TB diskin varsa cəmi 8 TB yaddaşın olur