# IP/Subnet

|  | Public IP Range | Private IP Range | Subnet Mask | # of Networks | # of Hosts per Network |
| --- | --- | --- | --- | --- | --- |
| Class A | 1.0.0.0 to127.0.0.0 | 10.0.0.0 to 10.255.255.255 | 255.0.0.0 | 126 | 16,777,214 |
| Class B | 128.0.0.0 to 191.255.0.0 | 172.16.0.0 to 172.31.255.255 | 255.255.0.0 | 16,382 | 65,534 |
| Class C | 192.0.0.0 to 223.255.255.0 | 192.168.0.0 to192.168.255.255 | 255.255.255.0 | 2,097,150 | 254 |
| Class D | 224-239 |  |  |  |  |
| Class E | 240-255 |  |  |  |  |
- 127.0.0.1-127.255.255.255 : **loopback ip : şəbəkə kartını yoxlamaq üçün lazım olan ip**
- 169.254.0.0-169.254.255.255 -APİPa -**Automatic Private IP Addressing :**

DHCP yoxdursa.avotomatik apipa ip alır

## `Multi Cast`

- Class D | 224.0.0.0 to 239.255.255.255 | Not Applicable | Not Applicable | Used for multicast groups | Not Applicable |
- Class E | 240.0.0.0 to 255.255.255.254 | Not Applicable | Not Applicable | Reserved for experimental purposes | Not Applicable |

# `IP Subnetting`

Qayda və düsturlar

$$
2^x=subnet   
$$

$$
2^y-2=host
$$

$$
256-subnet mask= subnet id
$$

# **`IP Subnetting Class A`**

10.10.20.1  subnet mask : 255.248.0.0/13 digerlerini tapin?

Number of subnets = 2^5=32

number of hostes =2^19=524288

subnet id= 256-248=8

network adress ⇒ 10.8.0.0

host address range ⇒ 10.8.0.1-10.15.255.254

Total Number of Hosts : 524,288

Number of Usable Hosts : 524,286

broadcast address ⇒ 10.15.255.255

Subnet details

| Subnet ID | Subnet Address | Host Address Range | Broadcast Address |
| --- | --- | --- | --- |
| 1 | 10.0.0.0 | 10.0.0.1 - 10.7.255.254 | 10.7.255.255 |
| 2 | 10.8.0.0 | 10.8.0.1 - 10.15.255.254 | 10.15.255.255 |
| 3 | 10.16.0.0 | 10.16.0.1 - 10.23.255.254 | 10.23.255.255 |
| …. | …… | ….. | ….. |
| 31 | 10.240.0.0 | 10.240.0.1 - 10.247.255.254 | 10.247.255.255 |
| 32 | 10.248.0.0 | 10.248.0.1 - 10.255.255.254 | 10.255.255.255 |

# **`IP Subnetting Class C`**

192.168.1.0   /28
subnet mask : 255.255.255.240
network adress : 192.168.1.0
host range : 192.168.1.1 - 192.168.1.14
broadcast adress : 192.168.1.15

Total Number of Hosts : 2^4=16

Number of Usable Hosts 2^4-2=14

number of subnets : 2^4=16 (4 “1-lerin sayi)
number of hosts per subnet : 2^4-2=14 (burdaki 4 0-larin sayi)
subnet id = 256-240=16

Subnet details

| 192.168.1.0 | 192.168.1.1 - 192.168.1.14 | 192.168.1.15 |
| --- | --- | --- |
| 192.168.1.16 | 192.168.1.17 - 192.168.1.30 | 192.168.1.31 |
| 192.168.1.32 | 192.168.1.33 - 192.168.1.46 | 192.168.1.47 |
| ……………………… | ……………………………………….. | ……………………. |
| 192.168.1.224 | 192.168.1.225 - 192.168.1.238 | 192.168.1.239 |
| 192.168.1.240 | 192.168.1.241 - 192.168.1.254 | 192.168.1.255 |

# `CIDR`

- CİDR - Classless inter-domain routing
- CİDR ilə bizim hər bir şəbəkənin eyni sayda host aralığı olar.
- /24 CİDR sayılır.
- CİDR ilə İP aralığına qənaət edə bilmirik.
- Əyər bir İP ilə müxtəlif subnet masklar istifadə etsəniz CİDR qaydalarını pozmuş olarsınız.

# `VLSM`

- VLSM ilə biz bir İP ilə bir neçə Subnet mask istifadə edə bilərik.
- 192.168.1.1/26, 192.168.1.64/27 sayılır subnetting.
- VLSM sayəsində biz İP address aralığına qənaət edirik.
- VLSM ilə host bitləri (0-lar) şəbəkə bitləri ilə əvəz olunur.

 

| Prefix size | Network mask | Usable hosts per subnet |
| --- | --- | --- |
| /1 | 128.0.0.0 | 2,147,483,646 |
| /2 | 192.0.0.0 | 1,073,741,822 |
| /3 | 224.0.0.0 | 536,870,910 |
| /4 | 240.0.0.0 | 268,435,454 |
| /5 | 248.0.0.0 | 134,217,726 |
| /6 | 252.0.0.0 | 67,108,862 |
| /7 | 254.0.0.0 | 33,554,430 |

| Class A |  |  |
| --- | --- | --- |
| /8 | 255.0.0.0 | 16,777,214 |
| /9 | 255.128.0.0 | 8,388,606 |
| /10 | 255.192.0.0 | 4,194,302 |
| /11 | 255.224.0.0 | 2,097,150 |
| /12 | 255.240.0.0 | 1,048,574 |
| /13 | 255.248.0.0 | 524,286 |
| /14 | 255.252.0.0 | 262,142 |
| /15 | 255.254.0.0 | 131,070 |

| Class B |  |  |
| --- | --- | --- |
| /16 | 255.255.0.0 | 65,534 |
| /17 | 255.255.128.0 | 32,766 |
| /18 | 255.255.192.0 | 16,382 |
| /19 | 255.255.224.0 | 8,190 |
| /20 | 255.255.240.0 | 4,094 |
| /21 | 255.255.248.0 | 2,046 |
| /22 | 255.255.252.0 | 1,022 |
| /23 | 255.255.254.0 | 510 |
| Class C |  |  |
| /24 | 255.255.255.0 | 254 |
| /25 | 255.255.255.128 | 126 |
| /26 | 255.255.255.192 | 62 |
| /27 | 255.255.255.224 | 30 |
| /28 | 255.255.255.240 | 14 |
| /29 | 255.255.255.248 | 6 |
| /30 | 255.255.255.252 | 2 |
| /31 | 255.255.255.254 | 0 |
| /32 | 255.255.255.255 | 0 |