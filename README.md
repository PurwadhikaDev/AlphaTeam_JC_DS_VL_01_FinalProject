![Banner](https://github.com/PurwadhikaDev/AlphaTeam_JC_DS_VL_01_FinalProject/blob/main/image/cover.png)

# AlphaTeam_JC_DS_VL_01_FinalProject

Final project job connector data science yang disusun oleh Al Fath Terry (alfathrubik@gmail.com) dan Syifa Salsabila (syifas09@gmail.com)

## Table of content
* [Problem Statement](#Problem-Statement)
    * [Problem Machine Learning](#Problem-Machine-Learning)
    * [Problem Analytic](#Problem-Analytic)
* [Data Understanding](#data-understanding)
* [Modeling](#modeling)

## Problem Statement

### Problem Machine Learning
Memprediksi harga mobil bekas, agar pelaku bisnis dan calon pembeli dapat meminimalkan overpricing maupun underpricing ketika melakukan jual beli di Exchange and Mart

### Problem Analytic
Mencari brand mobil mana yang mengalami depresiasi value terbesar dan terkecil. Pelaku bisnis jual beli mobil bekas biasanya akan menjual mobil yang paling laris, mobil yang paling laris salah satu cirinya ditandai dengan harga mobil yang relatif stabil (depresiasinya rendah).
Depresiasi mobil adalah selisih harga mobil saat anda membeli dan menjualnya.

## Data Understanding

### Deskripsi Data
Sumber data: https://www.kaggle.com/adityadesai13/used-car-dataset-ford-and-mercedes?select=audi.csv

Data ini merupakan data daftar mobil bekas hasil dari scraping web Exchange and Mart. Exchange and Mart merupakan perusahaan jual beli otomotif yang beroperasi secara online. Tidak hanya mobil saja, perusahaan ini juga melakukan jual beli motor. Namun di dataset kali ini, fokus datanya terbatas pada segmen mobil saja dengan 9 produsen mobil (Audi, BMW, Ford, Hyundai, Mercedes, Skoda, Toyota, Vauxhall, VW).

### Metadata
* manufacturer : perusahaan pembuat mobil
* model : Kategori model mobil.
* year : Tahun registrasi mobil didaftarkan secara resmi di UK (bukan tahun mobil dibuat). Bisa saja mobil tertentu sudah diproduksi setahun sebelum diregistrasikan di UK.
* totalMileage : Keseluruhan jarak tempuh mobil.
* transmission : Tipe gearbox.
* fuelType : Tipe bahan bakar yang digunakan.
* fuelConsump(Mpg) : Mile per galon.
* tax : Pajak mobil.
* engineSize : besar mesin dalam Liter (kalikan 100 untuk merubahnya dalam bentuk CC).
* totalCO2(Pounds) : total keseluruhan co2 yang dihasilkan oleh mobil
* co2Pounds/Mile : besar co2 yang dihasilkan mobil per milesnya (dalam satuan Pounds)
* price : Harga yang ditawarkan (bukan diharga berapa mobil terjual) dalam bentuk £ (Poundsterling).

## Modeling
Model yang digunakan menggunakan algoritma Random Forest, sehingga dalam penggunaan model machine learning dapat menjawab ke 'black-box'an model sehingga dengan visualisasi yang berupa feature importance, global summary, dan local summary yang bisa menjelaskan decision process model machine learning yang dibuat.
