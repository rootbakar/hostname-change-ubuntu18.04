# hostname-change-ubuntu18.04

### Menggunakan `sysctl`

1. **Edit File `/etc/sysctl.conf`**:
   Buka file `/etc/sysctl.conf` dengan editor teks:
   ```bash
   sudo nano /etc/sysctl.conf
   ```

2. **Tambahkan Konfigurasi Hostname**:
   Tambahkan baris berikut di akhir file:
   ```plaintext
   kernel.hostname = nama_baru_anda
   ```

3. **Terapkan Konfigurasi `sysctl`**:
   Terapkan perubahan konfigurasi dengan menjalankan perintah:
   ```bash
   sudo sysctl -p
   ```

4. **Reboot Sistem**:
   Reboot sistem agar perubahan berlaku:
   ```bash
   sudo reboot
   ```
