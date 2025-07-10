# Day2_ElectricityRegression
Pada Hari kedua ini saya belajar mengenai metode forecasting dengan Data Simulasi Stabilitas Jaringan Listrik
Tujuan hari ini adalah komparasi model dan belajar mendalami metode mana yang lebih baik
dan tentu saja sekalian memperdalam menggunakan pytorch

Pada step pertama kita melihat dulu fitur-fitur tersebut dan ternyata semua bersifat kontinu dan tidak ada missing value untuk semua fitur

Step Kedua melakukan sedikit EDA seperti mengecekan distribusi dan boxplot. Hasil yang didapatkan bahwa semua fitur tidak ada outlier ataupun anomali terdistribusi dengan cukup
pada bagian pengecekan kolerasi terdapat insight fitur P dari 1 -4 memiliki korelasi yang cukup negatif kuat 

Step ketiga melakukan pemodelan, disini fitur yang digunakan semua fitur terkecuali 'stabf' karena fitur tersebut merupakan klasifikasi pada target dan pada kali ini kita mempelajari regresi untuk fitur 'stab'
Masih pada step yang sama kita melakukan banyak pemodelan untuk mengecek base model mana yang lebih bagus

Step keempat Belajar menggunakan pytorch dan menggabungkan optuna didalamnya untuk hasil yang optimal

Kedepannya: Mempelajari lagi pytorch dikarenakan hasil pada optuna dan dirunning ulang berbeda/ belajar konsistensi model untuk deeplearning
