# DataTables Plugins Bahasa Indonesia
```bash
DataTables Versi 1.10.18
```
## Unduh Plugin
### Copy Link Repository
![copy link repository](https://user-images.githubusercontent.com/29445299/73582487-01a19e00-44c0-11ea-9836-e0b41531933b.png)

### Tentukan Lokasi Direktori
Direktori ini nantinya akan kita gunakan untuk menaruh **Clone Repository**, lalu klik kanan, pilih **Git Bash Here** 

![copy link repository](https://user-images.githubusercontent.com/29445299/73582926-0b2c0580-44c2-11ea-897c-0db3107076bf.png)

### Mulai Clone Repository
Gunakan Perintah
```bash
$ git clone <link repository>
```
Perintah diatas digunakan untuk mengunduh code repository.

![copy link repository](https://user-images.githubusercontent.com/29445299/73583214-8346fb00-44c3-11ea-8e5f-652ea7091681.png)

Tekan **Enter**, tunggu hingga proses berhasil seperti contoh tampilan berikut.
![copy link repository](https://user-images.githubusercontent.com/29445299/73583403-8a223d80-44c4-11ea-99ef-4ed6140530d2.png)

Yups, Plugin berhasil diunduh. 
**Jangan lupa letakkan di folder project kalian ya ^^**

### BONUS
#### Script Merubah Bahasa DataTables
```bash
var table = $('#dataTable');
table.DataTable({
    language: {
        "url": "PATH/i18n/Indonesian.lang"
    }
});
```
atau bisa langsung cek dokumentasi nya di https://datatables.net/reference/option/language