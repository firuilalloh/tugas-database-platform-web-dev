# Soal Database 

Silakan downbload database disini:
https://github.com/triyasmkom/mysql-dasar-docker/blob/main/classicmodels.sql

atau 

https://www.mysqltutorial.org/wp-content/uploads/2018/03/mysqlsampledatabase.zip


## 1. Silakan Tuliskan Query dengan menampilkan data seperti berikut ini:
- Ambil dari tabel customers 
- Filter berdasarkan kolom city yang bernama 'Auckland'

| customerName               | contactFirstName | contactLastName | creditLimit | city     |
|----------------------------|------------------|-----------------|-------------|----------|
| Down Under Souveniers, Inc | Mike             | Graham          | 88000.00    | Auckland |
| GiftsForHim.com            | Wales            | MacKinlay       | 77700.00    | Auckland |
| Kelly's Gift Shop          | Tony             | Snowden         | 110000.00   | Auckland |



## 2. Silakan Tuliskan Query dengan menampilkan data seperti berikut ini:
- Ambil dari tabel customers
- Kemudian hitung tiap-tiap city

| city              | COUNT(city)  |
|-------------------|--------------|
| Aachen            | 1            |
| Allentown         | 1            |
| Amsterdam         | 1            |
| Auckland          | 3            |
| Bantul            | 1            |
| Barcelona         | 1            |
| Bergamo           | 1            |
| Bergen            | 1            |
| Berlin            | 1            |
| Bern              | 1            |
| Boston            | 2            |
| Brandenburg       | 1            |
| Brickhaven        | 3            |
| Bridgewater       | 1            |
| Brisbane          | 1            |
| Bruxelles         | 1            |
| Bräcke            | 1            |
| Burbank           | 1            |
| Burlingame        | 1            |
| Cambridge         | 2            |
| Central Hong Kong | 1            |
| Charleroi         | 1            |
| Chatswood         | 1            |
| Cork              | 1            |
| Cowes             | 1            |
| Cunewalde         | 1            |
| Dublin            | 1            |
| Espoo             | 1            |
| Frankfurt         | 2            |
| Fribourg          | 1            |
| Genève            | 1            |
| Glen Waverly      | 1            |
| Glendale          | 2            |
| Graz              | 1            |
| Hatfield          | 1            |
| Helsinki          | 1            |
| Herzlia           | 1            |
| Kita-ku           | 1            |
| Kobenhavn         | 1            |
| Köln              | 1            |
| Las Vegas         | 1            |
| Leipzig           | 1            |
| Lille             | 1            |
| Lisboa            | 2            |
| Liverpool         | 1            |
| London            | 2            |
| Los Angeles       | 1            |
| Luleå             | 1            |
| Lyon              | 1            |
| Madrid            | 5            |
| Makati City       | 1            |
| Manchester        | 1            |
| Mannheim          | 1            |
| Marseille         | 1            |
| Melbourne         | 1            |
| Milan             | 1            |
| Minato-ku         | 1            |
| Montréal          | 1            |
| Munich            | 1            |
| München           | 1            |
| Münster           | 1            |
| Nantes            | 2            |
| Nashua            | 1            |
| New Bedford       | 2            |
| New Haven         | 2            |
| Newark            | 1            |
| North Sydney      | 1            |
| NYC               | 5            |
| Oslo              | 1            |
| Oulu              | 1            |
| Paris             | 3            |
| Pasadena          | 1            |
| Philadelphia      | 2            |
| Reggio Emilia     | 1            |
| Reims             | 1            |
| Saint Petersburg  | 1            |
| Salzburg          | 1            |
| San Diego         | 1            |
| San Francisco     | 2            |
| San Jose          | 1            |
| San Rafael        | 1            |
| Sevilla           | 1            |
| Singapore         | 3            |
| Sleman            | 4            |
| South Brisbane    | 1            |
| Stavern           | 1            |
| Strasbourg        | 1            |
| Stuttgart         | 1            |
| Torino            | 1            |
| Toulouse          | 1            |
| Tsawassen         | 1            |
| Vancouver         | 1            |
| Versailles        | 1            |
| Warszawa          | 1            |
| Wellington        | 1            |
| White Plains      | 1            |
| Århus             | 1            |



## 3. Silakan Tuliskan Query dengan menampilkan data seperti berikut ini:
- Ambilkan dari tabel customers dan employees
- Filter yang memiliki email kosong

| customerName                   | contactFirstName | contactLastName | creditLimit | email |
|--------------------------------|------------------|-----------------|-------------|-------|
| Havel & Zbyszek Co             | Zbyszek          | Piestrzeniewicz | 0.00        | null  |
| Porto Imports Co.              | Isabel           | de Castro       | 0.00        | null  |
| Asian Shopping Network, Co     | Brydey           | Walker          | 0.00        | null  |
| Natürlich Autos                | Horst            | Kloss           | 0.00        | null  |
| ANG Resellers                  | Alejandra        | Camino          | 0.00        | null  |
| Messner Shopping Network       | Renate           | Messner         | 0.00        | null  |
| Franken Gifts, Co              | Peter            | Franken         | 0.00        | null  |
| BG&E Collectables              | Ed               | Harrison        | 0.00        | null  |
| Schuyler Imports               | Bradley          | Schuyler        | 0.00        | null  |
| Der Hund Imports               | Mel              | Andersen        | 0.00        | null  |
| Cramer Spezialitäten, Ltd      | Philip           | Cramer          | 0.00        | null  |
| Asian Treasures, Inc.          | Patricia         | McKenna         | 0.00        | null  |
| SAR Distributors, Co           | Armand           | Kuger           | 0.00        | null  |
| Kommission Auto                | Karin            | Josephs         | 0.00        | null  |
| Lisboa Souveniers, Inc         | Lino             | Rodriguez       | 0.00        | null  |
| Stuttgart Collectable Exchange | Rita             | Müller          | 0.00        | null  |
| Feuer Online Stores, Inc       | Alexander        | Feuer           | 0.00        | null  |
| Warburg Exchange               | Sven             | Ottlieb         | 0.00        | null  |
| Anton Designs, Ltd.            | Carmen           | Anton           | 0.00        | null  |
| Mit Vergnügen & Co.            | Hanna            | Moos            | 0.00        | null  |
| Kremlin Collectables, Co.      | Alexander        | Semenov         | 0.00        | null  |
| Raanan Stores, Inc             | Raanan           | Altagar,G M     | 0.00        | null  |
| Yamaha                         | Dani             | Kurniawan       | null        | null  |
| Honda                          | Santika          | Putri           | null        | null  |
| Suzuki                         | Yudha            | Pratama         | null        | null  |
| Astra Daihatsu                 | Andika           | Putra           | null        | null  |


## 4. Silakan tampilkan data seperti ini:
- Ambil data dari tabel customers, employees, dan offices
- Filter berdasarkan credit limit lebih dari 10000 dan kurang dari 50000

| customerName                   | contactFirstName | contactLastName | creditLimit | email                           | postalCode |
|--------------------------------|------------------|-----------------|-------------|---------------------------------|------------|
| Atelier graphique              | Carine           | Schmitt         | 21000.00    | ghernande@classicmodelcars.com  | 75017      |
| Cambridge Collectables Co.     | Jerry            | Tseng           | 43400.00    | jfirrelli@classicmodelcars.com  | 02107      |
| Auto-Moto Classics Inc.        | Leslie           | Taylor          | 23000.00    | spatterson@classicmodelcars.com | 02107      |
| Boards & Toys Co.              | Mary             | Young           | 11000.00    | lthompson@classicmodelcars.com  | 94080      |
| Québec Home Shopping Network   | Jean             | Fresnière       | 48700.00    | ftseng@classicmodelcars.com     | 10022      |
| Tekni Collectables Inc.        | William          | Brown           | 43000.00    | gvanauf@classicmodelcars.com    | 10022      |
| Gifts4AllAges.com              | Juri             | Yoshido         | 41900.00    | spatterson@classicmodelcars.com | 02107      |
| Royale Belge                   | Pascale          | Cartrain        | 23500.00    | pcastillo@classicmodelcars.com  | 75017      |
| Gift Ideas Corp.               | Dan              | Lewis           | 49700.00    | gvanauf@classicmodelcars.com    | 10022      |
| Mini Auto Werke                | Roland           | Mendel          | 45300.00    | pcastillo@classicmodelcars.com  | 75017      |
| Microscale Inc.                | Yu               | Choi            | 39800.00    | ftseng@classicmodelcars.com     | 10022      |
| Frau da Collezione             | Franco           | Ricotti         | 34800.00    | pcastillo@classicmodelcars.com  | 75017      |
| Double Decker Gift Stores, Ltd | Thomas           | Smith           | 43300.00    | lbott@classicmodelcars.com      | EC2N 1HN   |



## 5. Tuliskan Query untuk menghitung orderan tiap tahun dari tabel orders:

| YEAR | TotalOrder |
|------|------------|
| 2003 | 111        |
| 2004 | 151        |
| 2005 | 64         |



## 6.  Hitunglah summary dari tabel orders, dengan tampilan seperti berikut ini:

| year | Shipped | Disputed | In Process | On Hold | Cancelled | Resolved | Total Order |
|------|---------|----------|------------|---------|-----------|----------|-------------|
| 2003 | 108     | 0        | 0          | 0       | 2         | 1        | 111         |
| 2004 | 145     | 0        | 0          | 1       | 4         | 1        | 151         |
| 2005 | 50      | 3        | 6          | 3       | 0         | 2        | 64          |



## 7. Buatlah function dalam mysql untuk melakukan konversi mata uang, dari tabel payments
- Tuliskan function dan query untuk menggambil datanya

| customerNumber | checkNumber | paymentDate | amount ($) | amount (Rp)      |
|----------------|-------------|-------------|------------|------------------|
| 141            | AU364101    | 2003-07-19  | 36251.03   | 543765450        |
| 141            | DB583216    | 2004-11-01  | 36140.38   | 542105700        |
| 141            | DL460618    | 2005-05-19  | 46895.48   | 703432200        |
| 141            | HJ32686     | 2004-01-30  | 59830.55   | 897458250        |
| 141            | ID10962     | 2004-12-31  | 116208.40  | 1743126000       |
| 141            | IN446258    | 2005-03-25  | 65071.26   | 976068900        |
| 141            | JE105477    | 2005-03-18  | 120166.58  | 1802498700       |
| 141            | JN355280    | 2003-10-26  | 49539.37   | 743090550        |
| 141            | JN722010    | 2003-02-25  | 40206.20   | 603093000        |
| 141            | KT52578     | 2003-12-09  | 63843.55   | 957653250        |
| 141            | MC46946     | 2004-07-09  | 35420.74   | 531311099.99999994 |
| 141            | MF629602    | 2004-08-16  | 20009.53   | 300142950        |
| 141            | NU627706    | 2004-05-17  | 26155.91   | 392338650        |





## 8. Buatlah Prosedur dengan menampilkan data tabel product berdasarkan productLine seperti berikut ini:

| productName                           | productVendor             | productLine | quantityInStock | buyPrice |
|---------------------------------------|---------------------------|-------------|-----------------|----------|
| 1969 Harley Davidson Ultimate Chopper | Min Lin Diecast           | Motorcycles | 7933            | 48.81    |
| 1996 Moto Guzzi 1100i                 | Highway 66 Mini Classics  | Motorcycles | 6625            | 68.99    |
| 2003 Harley-Davidson Eagle Drag Bike  | Red Start Diecast         | Motorcycles | 5582            | 91.02    |
| 2002 Suzuki XREO                      | Unimax Art Galleries      | Motorcycles | 9997            | 66.27    |
| 1936 Harley Davidson El Knucklehead   | Welly Diecast Productions | Motorcycles | 4357            | 24.23    |
| 1957 Vespa GS150                      | Studio M Art Models       | Motorcycles | 7689            | 32.95    |
| 1997 BMW R 1100 S                     | Autoart Studio Design     | Motorcycles | 7003            | 60.86    |
| 1960 BSA Gold Star DBD34              | Highway 66 Mini Classics  | Motorcycles | 15              | 37.32    |
| 1982 Ducati 900 Monster               | Highway 66 Mini Classics  | Motorcycles | 6840            | 47.10    |
| 1997 BMW F650 ST                      | Exoto Designs             | Motorcycles | 178             | 66.92    |
| 1982 Ducati 996 R                     | Gearbox Collectibles      | Motorcycles | 9241            | 24.14    |
| 1974 Ducati 350 Mk3 Desmo             | Second Gear Diecast       | Motorcycles | 3341            | 56.13    |
| 2002 Yamaha YZR M1                    | Autoart Studio Design     | Motorcycles | 600             | 34.17    |



## 9. Buatlah Query untuk membuat tabel mahasiswa yang berelasi dengan tabel buku_perpustakaan, relasi keduanya ada many to many:

Tabel Mahasiswa

| Atribut   | Type                                 |
|-----------|--------------------------------------|
| id        | Integer, primary key, auto increment | 
| email     | Varchar not null                     | 
| firstName | Varchar not null                     | 
| lastName  | Varchar not null                     | 
| password  | Varchar not null                     | 
| createdAt | timestamp, default on created        | 
| updatedAt | timestamp, default on updated        |


Tabel Buku

| Atribut   | Type                                 |
|-----------|--------------------------------------|
| id        | Integer, primary key, auto increment |
| judul     | Varchar                              | 
| pengarang | Varchar                              | 
| tahun     | Varchar                              | 
| penerbit  | Varchar                              | 
| createdAt | timestamp, default on created        | 
| updatedAt | timestamp, default on updated        |


Tabel Mahasiswa-Buku (Tabel penghubung)


| Atribut     | Type    |
|-------------|---------|
| bukuId      | Integer | 
| mahasiswaId | Integer |



## 10. Dari soal nomor 9, Tuliskan query sesuai ketentuan berikut ini: 

- Pada tabel mahasiswa coba tambahkan constraint pada kolom email menjadi uniq
- Tambahkan juga kolom isValidated (type data boolean dengan default false) dan posisinya setelah kolom password pada tabel mahasiswa
- Insert 1 data pada tabel-tabel soal no 9
- Insert 5 data pada tabel-tabel soal no 9 secara bersamaan


