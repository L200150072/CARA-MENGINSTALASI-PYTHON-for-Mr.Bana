# CARA-MENGINSTALASI-PYTHON-for-Mr.Bana

Cara install Python pada windows 7 dan Pengaturan Environment Variables.
Install Python windows 7
1. Download dulu python terbaru.
http://python.org/download/

2. Install (run/double klik seperti biasa).
-Ketika keluar opsi pemilihan path installer biarkan terinstall pada root C. "C:\Python34"
selanjutnya ikuti proses install sampai selesai

3. Setelah selesai test dulu apakah sudah berjalan dengan baik atau belum,
buka cmd/Command Prompt dan ketik "python"  tanpa tanda petik
biasanya python belum dikenali (not recognized) karena path nya tidak ketemu/dikenali oleh windows.

Pengaturan Environment Variables.
-Masuk ke system pada Control Panel
Control Panel\System and Security\System
-Kemudian klik   "Advanced system settings"
-Lanjut klik "Environment Variables" maka akan muncul lagi pop up "Environment Variables"
-Pada bagian System variables, scroll sampai ketemu Path. (Path adalah nama Variable)
-Seleksi/klik Path dan kemudian klik Edit
-Maka akan muncul lagi pop up "Edit System variable"
sebelum mengedit Variable value bikin dulu backup untuk mencegah hal2 yang diluar dugaan ,buka notepad copas semua Variable value.
-Pada bagian paling kanan/ujung "Variable value"
tambahkan path  ";C:\Python34\"  tanpa tanda petik
dan klik OK pada jendela Edit System variable.
klik OK pada jendela Environment Variables.
klik OK pada jendela System Properties.
dan close Control Panel


-Lanjut Buka lagi : cmd/Command Prompt dan ketik lagi "python" tanpa tanda petik
-Lanjut coba ketik "import this" <<< tanpa tanda petik
 
Maka PC kamu sudah siap untuk python pada windows 7.

