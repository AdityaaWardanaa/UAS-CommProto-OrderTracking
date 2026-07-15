# UAS Communication Protocols - Task & Order Tracking System

Repositori ini berisi seluruh dokumentasi, *source code* (JSON export), dan *evidence* untuk Ujian Akhir Semester mata kuliah Communication Protocols.

## Identitas Mahasiswa
* **Nama:** Aditya Wardana
* **NIM:** 25120500001
* **Program Studi:** Sains Data (Kelas Profesional)
* **Universitas:** Universitas Cakrawala
* **Dosen Pengampu:** Bapak Haikal Shiddiq

## Deskripsi Proyek
Proyek ini mengimplementasikan sistem *Task/Order Tracking* (Pemesanan Percetakan) menggunakan arsitektur REST API, diorkestrasi secara dinamis menggunakan **n8n** (berjalan dalam *container* Docker), dan diuji menggunakan **Postman Desktop**. Lalu lintas data disadap dan dianalisis menggunakan **Wireshark** pada antarmuka *loopback* untuk membuktikan integritas *payload* JSON pada *port* 8088.

## Struktur Repositori
* 📁 `/docs` : Berisi [Laporan Utama UAS (PDF)](./docs/25120500001_AdityaWardana_CommProto_UAS.pdf) dan Slide Presentasi.
* 📁 `/evidence` : Berisi tangkapan layar observabilitas n8n, pengujian Postman, dan packet sniffing Wireshark (Skenario 200, 201, 400, dan 404).
* 📁 `/source` : Berisi ekspor [*workflow* n8n](./source/25120500001_AdityaWardana_CommProto_UAS_workflown8n.json), *Postman Collection*, dan rekaman mentah Wireshark (`.pcapng`) untuk keperluan forensik digital.

## Tautan Video Presentasi
🎥 [Tonton Demonstrasi Proyek di YouTube](https://youtu.be/0NUGug2JsgE)
