> [!IMPORTANT]
> Brought to you by: RisunTuru
> - https://t.me/hiddentokio

###  DONE GAK BANG WKWK, DONE LAH
> [!NOTE]
> - Fixed.
> - hal yang kuperbaiki cuma meminimalisir fail aja
> - Gunakan tunnel yang menurut kalian enak aja.
- tunnel yg enak itu, responsif
- responsif itu apa? , pas lu suruh buka apapun dia lancar aja gak lola
- aku pakai passwall untuk icmp hijack + udah ngerasa nyaman dah gada alasan lain.
  
## Video Perbandingan PW vs Clash
https://github.com/user-attachments/assets/61381276-940f-4ad6-a4da-71c4684471d4
 
## Untuk me-reproduksi malasah ini
Gunakan:
- CLASH dengan redir-host tun mix mode.
- Internet 5Mbps dengan ping/latensi 380ms ketika download & upload).
- Kedua konfig sudah bebas dns bocor.
- GoogleDNS pada kedua tunnel TCP + TLS + DoH

### Intisari
- hal ini dikarenakan dns resolver yang cacat.
- tunnel pw adalah yg terbaik karna lebih responsif dalam mengurus dns.
- clash lebih sering mengalami dns resolve fail, mengakibatkan hal yang seharusnya tampil real-time, menjadi delay.

### Contoh DNS Resolver cacat.
- Dia akan fail & terus mengirim permintaan
- itulah alasan mengapa internet menjadi delay
![cacat-dns](https://github.com/user-attachments/assets/e42fa691-798e-40b8-9976-e9b533b59bf5)

### Contoh DNS Resolver yang baik.
- Minim atau bahkan tidak ada DNS Resolve fail
- Alhasil saat kamu scrolling youtube, maka semua thumbnail akan muncul tampa delay
![dns-fixed](https://github.com/user-attachments/assets/aaaf073f-2113-44aa-b0fb-ae55f727b909)

## FAQ (Frequently Asked Question)
> [!IMPORTANT]
> 1. Tanya : Apakah mempengaruhi kecepatan internet/gaming
> 2. Jawab : YA!, Secara tidak langsung, dns memiliki tanggung jawab untuk itu.
- Kamu mungkin bingung di speedtest kencang,
- tapi pas dipakai malah lola, ya itu dikarenakan konfigurasi clash yang cacat

> [!NOTE]
> - Terakhir diubah oleh : RisunTuru
> - pada : 30 September 2024