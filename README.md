# restapi-lara
adalah back-end dari aplikasi biodata simple yang dibangun menggunakan framework laravel, menggunakan basisdata MySql.
Untuk menjalankan, anda harus memiliki aplikasi postman terlebih dahulu, dan sudah melakukan konfigurasi database bernama restapi-lara

### api route beserta fungsinya
- (get) http:localhost/api/all = untuk melihat index daftar
- (get) http:localhost/api/biodata/{id} = untuk melakukan get data berdasarkan id
- (post) http:localhost/api/biodata/ = untuk melakukan posting data disertai json
- (delete) http:localhost/api/biodata/{id} untuk melakukan hapus data berdasarkan id
