# fail2ban-ssh-ipv4

Iseng mengumpulkan IP yang diblokir Fail2Ban maupun yang terobservasi melakukan percobaan autentikasi SSH terhadap server selama kerja praktik. Diperkaya dengan VirusTotal, AbuseIPDB, GreyNoise, dan Shodan sebelum dipublish. Silakan dipakai untuk SIEM, firewall, korelasi log anda atau sekadar dilihat dan yaudah sih.

## Note

### Blocked

IP diblokir karena mencapai ambang batas Fail2Ban akibat percobaan autentikasi SSH yang gagal.

### Observed

IP terdeteksi melakukan percobaan autentikasi SSH namun belum mencapai kriteria pemblokiran Fail2Ban.
