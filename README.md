# NoSQL-using-PyMongo
NoSQL Project to make new collcetion using PyMongo
<br>
<br>
<br>
**LANGKAH 1** <br>
Membuat collection baru dengan nama `clean_movies_afifah` yang sama persis dengan `movies` collection pada database `sample_mflix` dengan memakai collection `movies_intial` (projecting_queries pymongo)
<br>
<br>
**LANGKAH 2** <br>
Validasi collection yang telah dibuat dengan parameter sbb :
- Semua document dan banyak document pada `clean_movies` dan `movie` sama
- Semua fields pada `clean_movies` ada pada `movie`
- Semua value pada `clean_movies` sama dengan semua value pada `movies` dengan urutan yang sama
<br>
<br>
**KESIMPULAN**<br>
Practice 1 mengenai NoSQL pada PyMongo dalam membuat collection baru ini menunjukkan bahwa collection baru yang terbentuk (`clean_movies_afifah`) memiliki jumlah yang berbeda jika dibandingkan dengan collection target (`movies`). Namun dapat dipastikan tidak terdapat values yang berulang. Dan dikarenakan tidak terdapat `num_mflix_comments` dan `tomatos` ada collection `movies_initial`, sedangkan kedua keys tersebut ada pada `movies`, maka pada `clean_movies_afifah` kedua keys tersebut tidak memiliki values. Namun unjuk jumlah keys pada `clean_movies_afifah` sudah sama persis dengan `movies`.
