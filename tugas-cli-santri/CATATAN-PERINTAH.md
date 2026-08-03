yazid@YZD MINGW64 ~
$ pwd
/c/Users/yazid

yazid@YZD MINGW64 ~
$ ls
'54+waI7ij60='/
AppData/
'Application Data'@
Contacts/
Cookies@
D5W2/
Documents/
Downloads/
Favorites/
'Formulir Pendaftaran (Test)'/
Links/
'Local Settings'@
Music/
'My Documents'@
NTUSER.DAT
NTUSER.DAT{20d170fb-ef87-11ee-9dfe-58e4ebe8bd63}.TM.blf
NTUSER.DAT{20d170fb-ef87-11ee-9dfe-58e4ebe8bd63}.TMContainer00000000000000000001.regtrans-ms
NTUSER.DAT{20d170fb-ef87-11ee-9dfe-58e4ebe8bd63}.TMContainer00000000000000000002.regtrans-ms
NetHood@
OneDrive/
PrintHood@
Recent@
'Saved Games'/
Searches/
SendTo@
'Start Menu'@
Templates@
Videos/
inl-int-ex/
'list test'/
ntuser.dat.LOG1
ntuser.dat.LOG2
ntuser.ini
'test seo'/

yazid@YZD MINGW64 ~
$ cd Documents

yazid@YZD MINGW64 ~/Documents
$ ls
'My Music'@ 'My Pictures'@ 'My Videos'@

yazid@YZD MINGW64 ~/Documents
$ ???
bash: ???: command not found

yazid@YZD MINGW64 ~/Documents
$ mkdir tugas-cli-santri

yazid@YZD MINGW64 ~/Documents
$ cd tugas-cli-santri/

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$ code .

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$ mkdir css js images

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$ touch index.html

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$ cd css

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri/css
$ touch style.css reset.css

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri/css
$ cd ..

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$ touch js/script.js

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$ touch catatan-lama.txt

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$ mv catatan-lama.txt catatan.txt

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$ cp index.html about.html

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$ ls -la
total 8
drwxr-xr-x 1 yazid 197121 0 Aug 3 13:51 ./
drwxr-xr-x 1 yazid 197121 0 Aug 3 13:42 ../
-rw-r--r-- 1 yazid 197121 0 Aug 3 13:51 about.html
-rw-r--r-- 1 yazid 197121 0 Aug 3 13:47 catatan.txt
drwxr-xr-x 1 yazid 197121 0 Aug 3 13:44 css/
drwxr-xr-x 1 yazid 197121 0 Aug 3 13:43 images/
-rw-r--r-- 1 yazid 197121 0 Aug 3 13:44 index.html
drwxr-xr-x 1 yazid 197121 0 Aug 3 13:46 js/

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$ cat catatan.txt

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$ touch CATATAN-PERINTAH.md

yazid@YZD MINGW64 ~/Documents/tugas-cli-santri
$

---

pwd: untuk checkpoint/ mengetahui tempat kita berada

ls: Mengetahui Direktori yang tersedia (kebetulan karena itu, jadi ketauan jika Dokumen tidak terbaca)

mkdir: membuat folder

touch: membuat file dan sejenisnya

cd: change directory/ berpindah tempat

---

[Absolute: Universal/bisa di panggil dimana saja, Contoh kasus (memangil file style.css dengan cara [cat "Home"~/Documents/tugas-cli-santri/css/style.css])

Relative: Memanggil dengan cara singkat, kelemahan nya hanya bisa di pakai secara lokal, contoh penggunaan ada pada langkah pembuatan script.js]

[~:Home
.:file tersembunyi
..:Kembali/mundur ke file luar/sebelumnya]

[menghapus folder berserta isi nya]
