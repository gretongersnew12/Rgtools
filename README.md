# Rgtools
YouTube channel GRETONGERS NEW
# CODE PERINTAH INSTALL TOOLS INJEK PAKET RUANG GURU VIA TERMUX 2020
untuk editing payload / config bisa lihat vidio tutorialnya
 cek Youtube ADMIN : GRETONGERS NEW
BOLEH UPLOAD ASALKAN IZIN DENGAN SAYA
BUATNYA CAPEK YAA MOHON SUPORT DENGAN SUBSCRIBE GRATIS KE CHANNEL SAYA
 sehabis memasukan 1 printah tekan enter ya

# $ pkg update && pkg upgrade

# $ pkg install python

# $ pkg install python2

# $ pkg install bash

# $ pkg install nano

# $ pkg install gem

# $ gem install lolcat

# $ pkg install lolcat

# $ pkg install toilet

# $ pkg install figlet

# $ pkg install git

# $ git clone https://github.com/gretongersnew12/Rgtools

jika mau menjalankan SC nya ketikan perintah dibawah

# $ cd Rgtools
# $ sh rg.sh

jika sudah berjalan kalian hanya tinggal ketikan nomor saja
Untuk awalan saya sarankan install bahan2 yang di perlukan dulu ketik 1
COPYRIGHT : ©GRETONGERS NEW
# BY : ABDUL MUKHLIS
### Pro Version

    ...
    "PsiphonCore": 1,
    "Psiphon": {
        "CoreName": "psiphon-tunnel-core",
        "Tunnel": 4,
        "Region": "",
        "Protocols": [
            "FRONTED-MEEK-HTTP-OSSH",
            "FRONTED-MEEK-OSSH"
        ],
        "TunnelWorkers": 8,
        "KuotaDataLimit": 0,
        "Authorizations": [
            "blablabla"
        ]
    }
    ...


### Rules

**XL Iflix or Axis Gaming (Default)**

    ...
    "Rules": {
        "akamai.net:80": [
            "video.iflix.com",
            "videocdn-2.iflix.com",
            "iflix-videocdn-p1.akamaized.net",
            "iflix-videocdn-p2.akamaized.net",
            "iflix-videocdn-p3.akamaized.net",
            "iflix-videocdn-p6.akamaized.net",
            "iflix-videocdn-p7.akamaized.net",
            "iflix-videocdn-p8.akamaized.net"
        ]
    },
    ...

**Direct**

    ...
    "Rules": {
        "*:*": [
            "*"
        ]
    },
    ...

or

    ./brainfuck-psiphon-pro-go -f "*" -w "*:*"

**Telkomsel 0P0K**

    ...
    "Rules": {
        "akamai.net:443": [
            "118.97.159.51:443",
            "118.98.95.106:443"
        ]
    },
    ...

or

    ./brainfuck-psiphon-pro-go -f 118.97.159.51:443,118.98.95.106:443 -w akamai.net:443

**XL King**

    ...
    "Rules": {
        "akamai.net:80": [
            "ak-quic.stream.music.joox.com.edgesuite.net",
            "ak-hk.stream.music.joox.com.edgesuite.net",
            "ak-ng.stream.music.joox.com.edgesuite.net",
            "ak-quic.app.joox.com.edgesuite.net",
            "ak-ng.app.joox.com.edgesuite.net",
            "e5121.b.akamaiedge.net",
            "www.pubgmobile.com"
        ]
    },
    ...

**Joox**

    ...
    "Rules": {
        "akamai.net:80": [
            "ak-quic.stream.music.joox.com.edgesuite.net",
            "ak-hk.stream.music.joox.com.edgesuite.net",
            "ak-ng.stream.music.joox.com.edgesuite.net",
            "ak-quic.app.joox.com.edgesuite.net",
            "ak-ng.app.joox.com.edgesuite.net",
            "e5121.b.akamaiedge.net"
        ]
    },
    ...

**Ruang Guru and Udemmy (XL or Axis)**

    ...
    "Rules": {
        "akamai.net:80": [
            "*"
        ],
        "fastly.net:80": [
            "c.shared.global.fastly.net",
            "rg-video.ruangguru.com"
        ]
    },
    ...
