## Answers of 01-the-basics
>by zxhiend/faiz

1. Create a folder called `git-basic`. **mkdir git-basic**

2. `cd` into the `git-basic` folder. **cd .\git-basic\\**

3. Create a file called `first.txt`. **ni first.txt**

4. Initialize an empty git repository. **git init**

5. Add `first.txt` to the staging area. **git add .\first.txt**

6. Commit with the message "adding first.txt". **git commit -m "adding first.txt"**

7. Check out your commit with `git log`. **git log** 

![Screenshot 2022-06-26 194054](https://user-images.githubusercontent.com/67363618/175814680-c8e70909-5031-49a6-bf4f-b19f5d2664b9.jpg)

8. Create another file called `second.txt`. **ni second.txt**

9. Add `second.txt` to the staging area. **git add .\second.txt**

10. Commit with the message "adding second.txt". **git commit -m "adding second txt"**

11. Remove the `first.txt` file. **rm .\first.txt**

12. Add this change to the staging area. **git rm first.txt**

13. Commit with the message "removing first.txt". **git commit -m "removing first.txt"**

14. Check out your commits using `git log`. **git log**

![Screenshot 2022-06-26 195233](https://user-images.githubusercontent.com/67363618/175815091-c5e8a550-a2a9-4f41-a766-0fffb08e87b2.jpg)
