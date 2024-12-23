# Prefix dan Subnet IP Address Extractor

> **Peringatan:** :red_circle: Alat ini dibuat khusus untuk keperluan pendidikan dan penelitian. Penulis tidak bertanggung jawab atas segala bentuk penyalahgunaan atau kerusakan yang mungkin timbul dari penggunaan program ini. Harap gunakan dengan bijak dan hanya di lingkungan di mana Anda memiliki izin eksplisit.

Prefix dan Subnet IP Address Extractor adalah alat yang digunakan untuk mengekstrak dan menganalisis informasi dari alamat IP, seperti prefix (jumlah bit jaringan dalam format CIDR) dan subnet (mask, network ID, broadcast address, dan range host). Alat ini membantu memantau, mengelola, dan mengoptimalkan konfigurasi jaringan, terutama dalam pengaturan subnetting pada sistem yang kompleks.

~ (v1.0.0.1) Selasa 24 Desember 2024 - First Release Prefix IP Address Extractor by Xeme

#
<b>[ Cara Penggunaan Aplikasi Prefix and Subnet IP Address Extractor ]</b>

1. Download Prefix IP Addres Extractor via: https://codeload.github.com/MichaelJorky/Prefix-dan-Subnet-IP-Address-Extractor/zip/refs/heads/main
2. Untuk prefix length yang diijinkan: /9, /10, /11, /12, /13, /14, /15, /16, /17, /18, /19, /20, /21, /22, /23, /24, /25, /26, /27, /28, /29, /30, /31, dan /32.

   Contoh Prefix: 192.168.1.0/9, 192.168.1.0/10, 192.168.1.0/11, 192.168.1.0/12, 192.168.1.0/13, 192.168.1.0/14, 192.168.1.0/15, 192.168.1.0/16, 192.168.1.0/17, 192.168.1.0/18, 192.168.1.0/19, 192.168.1.0/20, 192.168.1.0/21, 192.168.1.0/22, 192.168.1.0/23, 192.168.1.0/24, 192.168.1.0/25, 192.168.1.0/26, 192.168.1.0/27, 192.168.1.0/28, 192.168.1.0/29, 192.168.1.0/30, 192.168.1.0/31, dan 192.168.1.0/32

4. Contoh kalkulasinya jika menggunakan: 192.168.1.0/24

   Address:   192.168.1.0<br/>
   Netmask:   255.255.255.0 = 24<br/>
   Wildcard:  0.0.0.255<br/>
   Network:   192.168.1.0/24<br/>
   Broadcast: 192.168.1.255<br/>
   HostMin:   192.168.1.1<br/>
   HostMax:   192.168.1.254<br/>
   Hosts/Net: 254<br/>

5. Buka aplikasi Prefix IP Address Extractornya lalu paste misalkan 192.168.1.0/24 pada bagian IP/Netmask lalu klik "Extract". maka output log akan menghasilkan file 192.168.1.0_24.txt
