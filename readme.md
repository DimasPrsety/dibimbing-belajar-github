# Project: dibimbing-belajar-github

1. Buatlah satu repository Github dengan nama dibimbing-belajar-github
![alt text](<Step 1 - Buat repo github.png>)

2. Clone repository tersebut ke local laptop/working directory yang sudah kita siapkan
![alt text](<Step 2 - clone repo.png>)
git clone https://github.com/DimasPrsety/dibimbing-belajar-github.git

3. Buatlah satu file python yang berisi tentang function untuk read file csv berikut file csv.
![alt text](<Step 3 - Buat py.png>)

4. Membuat branch dengan format feature/<nama_branch>. <nama_branch> bisa diisi bebas
![alt text](<Step 4 - Buat feature:py_read_username.png>)
git checkout -b feature/py_read_username


5. Commit new file ke feature/<nama_branch>, lalu push ke repository
![alt text](<Step 5 - Commit file.png>)
git status
git add .
git commit -m "Input python script"
![alt text](<Step 5 - Push repo.png>)
git push origin feature/py_read_username

6. Lalu, buatlah Pull Request di Github untuk merge ke branch master/main
![alt text](<Step 6 - Buat main utk pull request.png>)
![alt text](<Step 6 - Pull repo.png>)
git checkout -b main
<!-- nambahin satu line di python dan main branch biar bisa pull request -->
git status
git add . 
git commit -m "bedain dikit dari branch"
![alt text](<Step 6 - Push main to git repo.png>)
git push origin main

7. Yang terakhir lakukan Pull remote master/main branch ke local master/main branch
![alt text](<Step 7 - Pull local main.png>)
<!-- pull request -->
git pull origin main

8. Silahkan screenshoot setiap stepnya
<!-- adding readme.md file -->


