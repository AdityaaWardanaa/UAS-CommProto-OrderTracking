# UAS Communication Protocols - Task & Order Tracking System

Repositori ini berisi seluruh dokumentasi, source code (JSON export), dan evidence untuk Ujian Akhir Semester mata kuliah Communication Protocols.

## Identitas Mahasiswa
* **Nama:** Aditya Wardana
* **Program Studi:** Sains Data
* **Universitas:** Universitas Cakrawala

## Deskripsi Proyek
Proyek ini mengimplementasikan sistem *Task/Order Tracking* (Pemesanan Percetakan) menggunakan arsitektur REST API, diorkestrasi menggunakan **n8n** (berjalan dalam *container* Docker), dan diuji menggunakan **Postman Desktop**. 

Lalu lintas data disadap dan dianalisis menggunakan **Wireshark** untuk membuktikan integritas *payload* JSON pada *port* 8088.

## Struktur Repositori
* `/evidence`: Berisi tangkapan layar observabilitas n8n, pengujian Postman, dan packet sniffing Wireshark (Skenario 200, 201, 400, dan 404).
* `/source`: Berisi *file* ekspor *workflow* n8n dan Postman Collection untuk keperluan audit kode.
* `/docs`: Berisi Laporan Arsitektur (PDF) dan Slide Presentasi.

## Tautan Video Presentasi
https://youtu.be/0NUGug2JsgE
