## API MACHINE LEARNING-PlanTani

## Cara menginstal API ini
1. Clone repositori API ini
2. Instal semua requirment yang diperlukan (didalam requirements.txt)
```
pip install -r requirments.txt
```
3. Menjalankan API ini
```
// dalam mode debug atau developmnt 
python3 app.py

// dalam mode produksi 
gunicorn server:app
```
## Cara menggunakan/consume API ini 
Cukup akses rute API yang tersedia,
- Menggunakan curl
```
// POST gambar untuk prediksi item
curl -X POST -F "file="@sesuaikan dengan file yang tersedia di lokal" "link.api.com/predict"
```
- Menggunakan folder test/ yang sudah tersedia
```
 // POST gambar untuk prediksi item
 ```
 1. masukkan setiap gambar tanaman yang ingin di predik ke folder test/ tersebut
 2. Ubah link curl dibawah sesuai kebutuhan
 // Contoh:
 url="link.api.com//"
curl -X POST -F "file="@sesuaikan dengan file yang tersedia di lokal" $url"/predict"


