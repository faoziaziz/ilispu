# Hello Gengs

Ini merupakan kumpulan kode gabut sewaktu saya mengerjakan buku pemrograman
dariMIT. Gak usah banyak bacot langsung ajah eksekusi, soalnya dari buku 
***Structure and Interpretation of Computer Programs*** FYI gengs buku ini di
pake oleh MIT sebagai salah satu mata kuliah wajib yang dia pake untuk
menjelaskan komputer itu bekerja. Jadi gengs mungkin MIT sudah terlalu optimis
pada mahasiswanya bahwa mereka jago banget matematika dan fisika, makanya mereka
mencoba secara pedagogis memilih bahasa LISP sebagai dasar pemrograman untuk
melatih otot otak mereka agar terbiasa dengan bahasa komputer. Alasan mereka
tidak memilih bahasa pemrograman kayak java dan C misal. Karena mereka yakin
gengs bahwa LISP adalah bahasa terbaik untuk bisa memahami komputer. Oke gengs 
gak usah banyak bacot langsung masuk ke tutorial pertama.

ada requirementnya gengs. Mempelajari ini pertama kamu harus install scheme.
Mengapa scheme? karena itu lebih mudah ketimbang langsung menggunakan LISP. 

ole jalankan scheme interpreternya. (jadi ada dua mode scheme disini mode
INterpreter dan mode editor gengs. Ane pake emacs biar sekalian naikin skill ane
dengan emacs dan vi karena ane pake doom mode)

dari halaman 34 exercise 1.1 kamu bisa baca sendiri dengan lihat di referensi 1.

no 1. 

``` scheme
10
=> 10

(+ 5 3 4)
=> 12

(- 9 1)
=> 8

(/ 6 2)
=> 3

(+ (* 2 4) (- 4 6))
=> 6

(define a 3)
=> a = 3
(define b (+ a 1))
=> b = 4
(+ a b (* a b))
=> 19

(= a b)
=> false 

(if (and (> b a) (< b (* a b))) b a)
=> 


(cond ((= a 4) 6)((= b 4) (+ 6 7 a)) (else 25))


(+ 2 (if (> b a) b a))


(* (cond ((> a b) a) ((< a b) b)))

```
what happend in the next cond 




## Referensi

1. Abelson, Harold. 1994. Structure and Interpretation of computer programs.
   McGraw-Hill : Boston.
# ilispu
