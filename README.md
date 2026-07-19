# fail2ban-ssh-ipv4
Iseng mengumpulkan IP yang diblokir Fail2Ban maupun yang terobservasi melakukan percobaan autentikasi SSH terhadap server selama kerja praktik. Diperkaya dengan VirusTotal, AbuseIPDB, GreyNoise, dan Shodan sebelum dipublish. Silakan dipakai untuk SIEM, firewall, korelasi log anda atau sekadar dilihat dan yaudah sih.

# note
a. blocked
IP diblokir karena mencapai ambang batas Fail2Ban akibat percobaan autentikasi SSH yang gagal.

b. observed
Ip terdeteksi melakukan percobaan autentikasi ssh namun belum mencapai kriteria pemblokiran Fail2ban
