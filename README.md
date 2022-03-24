# CRUD MySQLi Procedural PHP
Simpel crud dengan mysqli procedural php

## Instalasi
Buatlah database dengan nama `disty_crud_php_mysqli`, kemudian buka sql dan pastekan kode dibawah ini.
```sql
CREATE TABLE `users` (
  `id` int(11) NOT NULL,
  `name` varchar(191) NOT NULL,
  `email` varchar(191) NOT NULL,
  `password` varchar(191) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
```
Atau Import Database `disty_crud_php_mysqli.sql`

## Configurasi
Sesuaikan koneksi ke database pada file `connect.php` di folder `config`

