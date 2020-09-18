# restapi-lara
adalah back-end dari aplikasi biodata simple yang dibangun menggunakan framework laravel, menggunakan basisdata MySql.
Untuk menjalankan, anda harus memiliki aplikasi postman terlebih dahulu, dan sudah melakukan konfigurasi database bernama restapi-lara

### api route beserta fungsinya
- (get) http:localhost/api/all = untuk melihat index daftar
- (get) http:localhost/api/biodata/{id} = untuk melakukan get data berdasarkan id
- (post) http:localhost/api/biodata/ = untuk melakukan posting data disertai json
- (delete) http:localhost/api/biodata/{id} untuk melakukan hapus data berdasarkan id

##### jika dirasa terlalu berat menggunakan laravel pada mini project ini (overkill),
Maka untuk kedepannya akan dibuat seuah rest api menggunakan microframework bernama Lumen

### Update!
Sebuah rest-api baru dengan framework Lumen telah dibuat!
Dibuat bersama frontend dari ReactJs. [link Repo](https://github.com/ArdaBilly1/restapi-lumen)
