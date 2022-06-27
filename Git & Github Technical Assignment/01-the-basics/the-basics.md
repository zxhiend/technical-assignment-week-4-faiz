## [Answers of 01-the-basics](https://github.com/impactbyte/full-stack-web-assignments/blob/master/04-Git-and-Github/01-the-basics/README.md)
>by zxhiend/faiz
<br>

1. Create a folder called `git-basic`. 
    ```bash
    mkdir git-basic
    ```
    <br>
  
2. `cd` into the `git-basic` folder. 
    ```bash
    cd .\git-basic\
    ```
    <br>
    
3. Create a file called `first.txt`. 
   ```bash
   touch first.txt
   ```
   <br>
   
4. Initialize an empty git repository.
   ```bash
   git init
   ```
   <br>
   
5. Add `first.txt` to the staging area. 
   ```bash
   git add .\first.txt
   ```
   <br>
   
6. Commit with the message "adding first.txt".
   ```bash
   git commit -m "adding first.txt"
   ```
   <br>

7. Check out your commit with `git log`. 
   ```bash
   git log
   ```
   ![Screenshot 2022-06-26 194054](https://user-images.githubusercontent.com/67363618/175814680-c8e70909-5031-49a6-bf4f-b19f5d2664b9.jpg)

   <br>

8. Create another file called `second.txt`. 
   ```bash
   touch second.txt
   ```
   <br>
   
9. Add `second.txt` to the staging area. 
   ```bash
   git add .\second.txt
   ```
   <br>


10. Commit with the message "adding second.txt". 
    ```bash
    git commit -m "adding second txt"
     ```
11. Remove the `first.txt` file.
    ```bash
    rm .\first.txt
    ```
   <br>
   
12. Add this change to the staging area. 
    ```bash
    git rm first.txt
    ```
   <br>

13. Commit with the message "removing first.txt".
    ```bash
    git commit -m "removing first.txt"
    ```
   <br>

14. Check out your commits using `git log`.
    ```bash
    git log
    ```
    ![Screenshot 2022-06-26 195233](https://user-images.githubusercontent.com/67363618/175815091-c5e8a550-a2a9-4f41-a766-0fffb08e87b2.jpg)
