1. membuat sebuah folder kosong dengan **namamu sendiri**.
    ```bash
    mkdir faiz
    cd .\faiz\
    ```
    <br>

2. membuat sebuah file di dalam folder tersebut dengan nama `README.md`, isi file tersebut dengan kalimat<br>`"Halo perkenalkan aku halaman utama"`. 
    ```bash
    echo "Halo perkenalkan aku halaman utama." > README.md
    ```
    <br>

3. **inisialisasi** folder tersebut dengan Git, kemudian simpan perubahan menggunakan `commit` dengan pesan<br>`"First commit"`. 
    ```bash
    git init .
    git commit -m "First Commit"
    ```
    <br>

4. Ganti teks sebelumnya dengan `"Hello world"`. 
    ```bash
    notepad .\README.md
    ```
    >**delete teks lalu ubah dengan "Hello world".**
    <br>

5. Tampilkan isi teks tersebut pada command line menggunakan command `cat`. 
    ```bash
    cat .\README.md
    ```
    ![catting](https://user-images.githubusercontent.com/67363618/175885098-9fd23826-ef8f-4eb0-b6dd-fe34465b402e.jpg)
    <br>

6. Ternyata kamu tidak ingin perubahan tersebut, dan ingin kembali ke perubahan seperti commit yang terakhir. Lakukan teknik git backtracking untuk mengembalikan ke perubahan commit yang terakhir. 
    ```bash
    git checkout HEAD .\README.md
    ```
    <br>

7. buat `branch` baru dengan nama `cv`, hal ini berguna agar histori kita tidak tercampur. 
    ```bash
    git branch cv
    ```
    <br>

8. pindah `branch` ke dalam `cv`, kemudian buat file dengan nama `cv.txt` dan isi file tersebut dengan kalimat:<br>`"Ini adalah file CV"`. 
    ```bash
    git checkout cv
    echo "Ini adalah file CV" > cv.txt
    ```
    <br>

9. kemudian simpan perubahan menggunakan `commit` dengan pesan<br>`"Initial CV"`. 
    ```bash
    git add .\cv.txt
    git commit -m "Initial CV"
    ```
    <br>

10. tambahkan **3 perusahaan** yang akan kamu lamar, dan setiap menuliskan 1 nama perusahaan kamu harus melakukan dokumentasi dan menyimpan perubahan menggunakan `commit`.
    ```bash
    notepad .\cv.txt
    git add .\cv.txt
    git commit -m "Perusahaan 1"
    
    notepad .\cv.txt
    git add .\cv.txt
    git commit -m "Perusahaan 2"
    
    notepad .\cv.txt
    git add .\cv.txt
    git commit -m "Perusahaan 3"
    ```
<br>

11. kembali ke `branch master`.
    ```bash
    git checkout master
    ```
    <br>

12. ubah file `README.md` menjadi.
    ```
    Halo perkenalkan aku halaman utama

    Ini adalah update pertama pada branch master
    ```
    jangan lupa untuk menyimpan perubahan menggunakan `commit` dengan pesan<br>`"update master pertama"`.
    ```bash
    notepad README.md
    ```
    >tambahkan text "Ini adalah update pertama pada branch master"
    ```bash
    git add .\README.md
    git commit -m "update master pertama"
    ```
    <br>

13. gabungkan branch `cv` ke dalam branch `master` menggunakan perintah `git merge`.
    ```bash
    git merge cv
    ```
    <br>

14. unggah Git Repository project tersebut tersebut ke dalam GitHub.
    ```bash
    git remote add origin  <insert url>
    git remote -v
    git push origin main
    ```

