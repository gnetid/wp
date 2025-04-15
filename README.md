# webportal
Fitur admin <br>
1. OTP bisa ON/OFF <br>
2. Edit SSID<br>
3. Edit Password<br>
4. Edit No pelanggan<br>
5. Otp fonnte  wablas dan MPWA<br>
6. Support SSID 2.4g dan 5g<br>
7. Data redaman<br>
8. Reboot<br>
9. Data user terkoneksi<br>
10. Refresh / summon <br>
Semua pengaturan bisa di dasboard admin<br>

Fitur pelanggan<br>
1. Ganti SSID 2.4g dan 5g<br>
2. Ganti password 2.4g 5g
3. Ganti Nomer Pelanggan<br>
4. Data user  konek<br>
5. Reboot ONU<br>
6. Refresh ONU<br>


# INSTALL
```
apt install git curl -y
```
```
git clone https://github.com/alijayanet/webportal
```
```
cd webportal
```
CATATAN <br>
edit file env example sesuai dengan server anda <br>

PORT=4000 // port webportal<br>

GenieACS Configuration<br>
GENIEACS_URL=http://192.168.8.xxx:7557 // url GenieACS API<br>
GENIEACS_USERNAME=admin // username GenieACS<br>
GENIEACS_PASSWORD=admin // password GenieACS<br>

Admin Configuration<br>
ADMIN_USERNAME=admin // username admin<br>
ADMIN_PASSWORD=admin // password admin<br>

lalu di rename menjadi .env <br>

```
npm install
```
```
node app.js
```
untuk membuka aplikasi admin <br>
http://192.168.8.xx:4000/admin <br>
untuk pelanggan <br>
http://192.168.8.xx:4000 <br>

demo

https://portal.gantiwifi.online  // nopel 081321960111

🤝 Kontribusi
Kontribusi selalu diterima! Silakan buat pull request atau laporkan issue jika menemukan bug.

https://wa.me/6281947215703

atau link group telegram

https://t.me/alijayaNetAcs

SILAHKAN YANG INGIN BERBAGI UANG KOPI

![Image](https://github.com/user-attachments/assets/724e5ac2-626e-4f2d-bd1f-1265b70b544f)
