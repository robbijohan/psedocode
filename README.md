# psedocode
hukum newton
algoritma
menghitung resultan gaya pada sebuah mobil yang memiliki massa benda 600 kg dan ketika didorong oleh tiga orang percepatannya adalah 2 m/s2
pseudocode
STORE "massa" EQUAL TO 600
STORE "percepatan benda" EQUAL TO 2
SET "resultan gaya" EQUAL TO "massa" TIMES "percepatan benda"
    DISPLAY "resultan gaya"

algoritma
Jika tahun habis di bagi 4 dan tidak habis di bagi 100, atau
Jika tahun habis di bagi 4, habis di bagi 100 dan habis di bagi 400
pseudocode
STORE "year" WITH ANY VALUE
IF "year" MOD WITH 4 EQUAL TO 0 AND "year" MOD WITH 100 EQUAL TO 1 THEN
    DISPLAY "tahun kabisat"
ELSE IF "year" MOD WITH 4 EQUAL TO 0 AND "year" MOD WITH 100 EQUAL TO 0 AND "year" MOD WITH 400 EQUAL TO O THEN
    DISPLAY "tahun kabisat"
ELSE
    DISPLAY "tidak tahun kabisat"

algoritma
 Pakaian yang akan dicuci oleh Foxie sebanyak 20 dan akan dimasukkan ke mesin cuci. Mesin cuci akan dinyalakan jika semua pakaian Foxie sudah masuk ke mesin cuci
pseudocode
STORE "pakaian" VALUE 1
STORE "maxPakaian" VALUE 20
WHILE "pakaian" LOWER TO 20 "maxPakaian" THEN
    DISPLAY "mesin cuci tidak menyala"
END WHILE
    DISPLAY "mesin cuci menyala"

algoritma
Seorang guru akan memeriksa kuku siswa-siswinya yang sebanyak 40 orang dengan cara berkeliling kelas. Jika guru menemukan siswa/siswi yang memiliki kuku yang panjang maka guru akan menghukum siswa/siswi tersebut, jika tidak guru akan memuji siswa/siswi tersebut
pseudocode
STORE "siswa" VALUE 1
STORE "semua siswa" VALUE 40
STORE "kuku siswa" VALUE "panjang" OR "PENDEK"
WHILE "siswa" LOWER TO 40
IF "kuku siswa" EQUAL TO "panjang" THEN
    DISPLAY "guru marah"
ADD "siswa" VALUE 1
ELSE IF "kuku siswa" EQUAL TO "pendek" THEN
    DISPLAY "guru memuji"
ADD "siswa" VALUE 1
END WHILE