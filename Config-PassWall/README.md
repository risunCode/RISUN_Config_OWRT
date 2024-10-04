> [!IMPORTANT]
> - Brought to you by: RisunTuru
> - https://t.me/hiddentokio
> - https://t.me/risuntrash
> - Credit: Reyre for base configuration

# Download Config passwall
> [!NOTE]
> - Download [Disini](https://github.com/risunCode/RISUN_Config_OWRT/releases/download/oktober-update-24/passwall)
> - buka file manager
> - Masuk ke etc/config
- Cari passwall dan hapus.
- Lalu terakhir: upload passwall yang sudah didownload tadi

# Pengaturan DNS Passwall (PENTING)
- Samakan saja kalo nggak ngerti
- Lalu klik save and apply di bagian bawah
![dns-passwall](https://github.com/user-attachments/assets/00c194dd-971c-4419-ba06-4e59ec0a08f5)

# Pengaturan Rule
- Default = Global (artinya bakal ngikut ke satu akun vpn saja)
- Kalo mau direct tinggal ubah seperti rule game
![pw-basic-settings](https://github.com/user-attachments/assets/5be3c5f3-bd79-434e-97fd-7c239117d7ea)

## Passwall Screenshoots
![passwall-screen](https://github.com/user-attachments/assets/58aa369a-b544-4234-80bd-45e86b9979e3)

## Tambah akun bisa lewat
> - Node List
> - bisa pake link vmess/vless/trojan atau masukin manual
> - Jangan lupa klik save & apply selalu setelah buat perubahan.
![add-node](https://github.com/user-attachments/assets/22d4174c-af58-42d7-8278-61a3c849ebaa)

### Pros using PassWall than other tunnel
> [!IMPORTANT]
> - 1. Hijack ICMP (allowing ping for all app)
> - 2. Good DNS resolver (unlike clash, passwall hampir tidak pernah gagal dalam hal dns resolver)

## ADBLOCK BAWAAN SUDAH GACOR* 
- Untuk blokir iklan di website berita
- Jika ingin blokir iklan aplikasi gunakan dns adblock
- [97%](https://d3ward.github.io/toolz/adblock)
- [100%](https://test.adminforge.de/adblock.html)

## DNS Yang disarankan 
- Secara bawaan saya menggunakan Google DNS karna itu yg terbaik
- DOH Google 8.8.8.8

### DNS adblock tidak dianjurkan karena
- Memperlambat koneksi (latensi/ping/ms)
- Resolver DNS sering gagal*, akhirnya jadi lola walaupun speedtest kencang.

> [!NOTE]
> - DNS Adblocker by NextDNS
> - Hosts list:Adguard (FULL), Goodbye Ads, Steven Black, HaGeZi - Multi PRO++ 
**PRO++**
> - Tidak Dianjurkan untuk normal user
> - Bakal nge-break fungsi iklan hp, gunakan dengan bijak
```bash
https://dns.nextdns.io/ed447c/PRO
```

## End of this blog.
> [!NOTE]
> - Terakhir diubah oleh : RisunTuru
> - pada : 4 Oktober 2024
