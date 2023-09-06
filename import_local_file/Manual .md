# STEP 1 

YOU HAVE TO INSTALL GIT BASH FOR IMPORT/EXPORT , PUSH/PULL AND THE GITHUB REPOSITORY 

# STEP 2 

AFTER INSTALLING AND CONFIGRAUTION . MOVE TO YOUR FOLDER WHERE YOU WANT TO EXPORT/IMPORT YOUR FILE/FOLDER PLACED

# STEP3

RIGHT CLICK ON THE FOLDER AND YOU CAN SEE "OPEN BASH HERE"

# STEP 4

To export and import files to a GitHub repository, you can follow these steps:

Exporting Files from a GitHub Repository:

# Create a repository in the Github account through web browser (if not created)

1 Open your web browser and navigate to the GitHub repository you want to export files from.

2. Click on the "Code" button, which is usually located near the top-right corner of the repository page.

3. In the dropdown menu, select the "Download ZIP" option. This will download a compressed ZIP file containing all the files and folders from the repository.

4. Extract the contents of the ZIP file to a location on your local machine. You now have the exported files from the GitHub repository.

# Importing Files to a GitHub Repository:

1. Create a new repository on GitHub, or navigate to an existing repository where you want to import the files.

2. Open your command line or terminal and navigate to the directory where the files you want to import are located.

3. Initialize a new Git repository in this directory by running the following command:

   ```
   git init
   ```

4. Add the files to the Git repository by running the following command:

   ```
   git add .
   ```

   This command adds all the files in the current directory to the Git repository.

5. Commit the changes by running the following command:

   ```
   git commit -m "Initial commit"
   ```

   Replace "Initial commit" with an appropriate commit message describing the changes you're importing.

6. Connect your local repository to the remote GitHub repository by running the following command:

   ```
   git remote add origin <repository-url>
   ```

   Replace `<repository-url>` with the URL of your GitHub repository. For example:

   ```
   git remote add origin https://github.com/your-username/your-repository.git
   ```

7. Push the changes to the remote repository by running the following command:

   ```
   git push -u origin master
   ```

   This command pushes the changes from your local repository to the remote repository on GitHub.

After executing these steps, the files will be imported to your GitHub repository. You can verify this by visiting the repository on GitHub and checking if the files are present.

Please note that you need appropriate permissions to push changes to a GitHub repository. If you encounter any errors during the process, ensure that you have the necessary access rights.
