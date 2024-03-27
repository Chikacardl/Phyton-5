# Membersihkan data ('marketing_data.csv')
Prinsip yang di pakai adalah Basic OOP, Inheritance, Polymorphism


# Soal No 1 
Saya membuat class yaitu MarketingDataETL yang memiliki 3 metode, yaitu:
1. Extract
2. Transform
   - Pada transform saya mengubah format tanggal, dan membershikan nilai NULL
3. Data Store
   - Membuat data store dengan data yang sudah di tranform kemudian dimasukan kedalam ('transformed_marketing_data.csv')
     jadi didalam file ('transformed_marketing_data.csv') berisi data yang sudah di ubah dan di bersihkan.


# Soal No 2
- Saya membuat class TargetedMarketing ETL yang mewarisi dari Class MarketingDataETL
- Lalu, saya menambahkan Metode Segment_customers dengan rata-rata jumlah yang di habiskan
- Kemudian hasil tersebut di masukan kedalam ('new_file_category.csv')
