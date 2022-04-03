# Berea-Open-Source-Day

1. Fork the repository 
2. Clone your forked version of the repo. It will have your username in the place of `<YOUR_USERNAME>`. 
  
   * `git clone https://github.com/<YOUR_USERNAME>/Berea-Open-Source-Day.git`

3. Change path to the project folder

    * `cd Berea-Open-Source-Day`

4. Create a new branch 

    * `git checkout -b <BRANCH_NAME>`
    * Example:
      * `git checkout -b adding-name`

5. Open up the `contributors.md` file and write your name. 

7. To see the change you just made, run the following command 
    * `git status`

8. Add your changes 
    * To add the changes files separately, you do 
      * `git add <FILE_NAME>`
    * To add all the changed files, you can do 
      * `git add *`

8. Commit your changes 
    * `git commit -m "<COMMIT_MESSAGE>" `
    * Example 
      * `git commit -m "added my name to the contributors file"`

9. Push your changes 
    * `git push origin <BRANCH-NAME>`
    * Example (Note this is the branch we created in step 4): 
      * `git push origin adding-name` 

10. Go to your repository on Github and refresh it. You will see a “Compare and pull request” button. Click on that button to start making your pull request.
