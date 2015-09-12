## Analisis Data Hujan Bulanan##

PENDAHULUAN
===========
Curah hujan merupakan peubah iklim penting pembentuk ekosistem di wilayah tropis. Pada kondisi curah hujan tahunan yang rendah, tipe ekosistem savana sering dijumpai, sedangkan pada wilayah yang menerima curah hujan tahunan tinggi dan cukup merata sepanjang tahun akan menyebabkan pembentukan ekosistem lahan basah. Fakta tersebut banyak dijumpai di Indonesia, dengan penyebaran ekosistem savana di wilayah Nusa Tenggara Timur dan keberadaaan lahan basah di sekitar ekuator Kalimantan dan Sumatra yang memiliki curah hujan lebih dari 2500 mm/tahun. Sehingga pengetahuan dan pemahaman terhadap variabilitas iklim akan bermanfaat untuk kesejahteraan manusia.

Pada kesempatan ini, akan didemonstrasikan penggunaan R language untuk membantu meningkatkan pemahaman kita terhadap data curah hujan di tropis basah. Pertama, mungkin kita akan tertarik untuk mengetahui nilai maksimum, minimum dari data curah hujan bulanan atau lebih mudah kita sebut sebagai nilai statistik deskriptif dari suatu data hujan bulanan. Selanjutnya, keragaman data dapat disajikan secara lebih menarik melalui visualisasi dengan `boxplot` ataupun `density plot`. Terakhir, yaitu penyajian time-series data curah hujan bulanan. 

Data curah hujan yang digunakan yaitu data curah hujan bulanan Pontianak untuk periode pengamatan tahun 1950-2012. Format data berupa data tabular bertipe .xlsx (Ms. Excel). Untuk mengolah data .xlsx diperlukan *package* `readxl`. 

