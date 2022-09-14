# Module 1
## Init project

1. Create a folder for your project
2. Initialize Git repository in this folder(in terminal)
    ```
    git init
    ``` 
3. Create `index.html` file.
4. Put the HTML page skeleton in `index.html` and Save the fikle
    ```html
    <!DOCTYPE html>
    <html lang="en">

    <head>
        <title>Document</title>
    </head>

    <body>
    </body>

    </html>
    ```
5. Set title to the page
    ```html
    <title>Your Name</title>
    ```
6. Add heading `<h1>` to your page
    ```html
    <h1>Welcome To the World of WEB Development :)</h1>
    ```
7. Add your changes to stage (in terminal)
    ```
    git add .
    ```
8. Commit your staged change
    ```
    git commit -m "initial commit"
    ```
9. Create new repository at [Github](https://github.com)
    ![init github](./Module-1-images/init%20github%20repo.png)
10. Add your Github repository as origin for project
    ```
    git remote add origin <remote repository URL>
    ```
    Replace `<remote repository URL>` with your new repository URL
     ![init github](./Module-1-images/init%20github%20repo%202.png)
11. Push changes to Github
    ```
    git push -u origin
    ```

### [Next - Excercise](./Module-1-1.md)