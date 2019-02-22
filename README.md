# Pr-cakru-11-uro

:next_track_button: :next_track_button: :next_track_button: :next_track_button: :next_track_button: 

Anggota         | NIM
------------ | -------------
Jack Dhamma Wijaya | 16918166  
Alya Mizani        | 16518181 
Vincent Fernaldy   | 16918230
Winnie Zhuang      | 16518020



# Deskripsi Game :
```
1. Game terdiri atas 2 orang pemain
2. Waktu untuk 1 turn game adalah 100 ms
3. Setiap pemain saling mengakuisisi zona yang ada dengan menggunakan POD
4. Setiap pemain akan mendapatkan platinum dalam waktu tertentu dan sesuai dengan total platinum per zone yang ditempati oleh POD masing" pemain
5. POD ditukarkan secara otomatis apabila platinum sudah mencukupi 20 yang merupakan syarat untuk mendapatkan POD baru
6. Game dimulai dengan 10 PODs dan 0 platinum
```





1. Menggunakan array of array untuk menyimpan data posisi zone yang saling berhubungan agar POD dapat berpindah . 
   Apabila zone 1 berhubungan dengan zone 2 dan zone 5 maka pada array indeks 1 terdapat array dengan isi 2 dan 5






# Strategi :

- POD akan bergerak dengan memprioritaskan zona yang dapat memberikan platinum terbesar

`-Opening :`
  
 :one: Apabila POD tidak melihat musuh , maka strategi yang diterapkan adalah menyebar. Strateginya adalah 8 POD masing-masing      menguasai zona berbeda secara menyebar , selainkan 2 pod lain akan bergerak mengikuti satu sama lain untuk menguasai daerah yang berada dekat dengan musuh sambil menyerang musuh secara bersama-sama apabila POD mendeteksi musuh yang datang .
 
 :two: Apabila POD melihat musuh , maka strategi berubah menjadi menyerang . 6 pod menyerang musuh dan disaat bersamaan 4 pod lain tetap berfokus untuk menguasai zona yang jauh dari musuh . 6 POD yang menyerang musuh akan mengincar POD lawan yang posisinya paling dekat dengan zona 
 
 
`-Middle game :`
   1. Apabila zona sendiri sudah banyak yang dikuasai lawan maka semua POD akan berfokus untuk terlebih dahulu menyerang musuh secara bersama -sama agar daerah yang telah dikuasai tidak jatuh ke tangan musuh 
   2. Apabila musuh telah terdesak maka POD yang sedang bertahan difokuskan secara menyeluruh untuk menyerang musuh agar musuh lebih cepat kehilangan zona mereka 
   3. Apabila terdapat musuh yang mengikuti arah gerak POD kepunyaan sendiri yang sedang menguasai zona lain maka POD kita akan fokus untuk menyerang POD tersebut terlebih dahulu agar gerakan POD tidak terasa sia-sia
   4. Apabila zona milik sendiri diserang oleh musuh secara bersamaan dan kemungkinan menguasai kembali zona tersebut adalah kecil, maka POD akan fokus untuk menguasai area lain serta area lawan agar tidak menyia-nyiakan POD yang ada 



# Objektif : 
 
 - Syarat Menang :
    - Menguasai zone terbanyak setelah 250 turns
 - Syarat Kalah :
    - Gagal menguasai zone terbanyak setelah 250 turns




