# Backup Snapshot Simulation
# Linux Snapshot Backup Simulation

Simulasi sistem backup otomatis menggunakan `rsnapshot` di Linux. Menggunakan `cron` untuk menjadwalkan backup dan `rsync` untuk efisiensi penyimpanan.

## Fitur
- Backup harian, mingguan, bulanan
- Snapshot berbasis hardlink
- Log sistem otomatis
- Restore data mudah

## Cara Instalasi
1. Install rsnapshot: `sudo apt install rsnapshot`
2. Edit konfigurasi di `rsnapshot.conf`
3. Tambahkan cron job (lihat `cron/crontab-backup.txt`)
4. Jalankan backup manual: `bash scripts/backup-now.sh`

## Author
Septian Tri Mahendra

